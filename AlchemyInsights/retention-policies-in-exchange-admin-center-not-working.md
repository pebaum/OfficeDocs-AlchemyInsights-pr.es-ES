---
title: Directivas de retención en el centro de administración de Exchange no funciona
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: a48fd5fd-4af7-4d5f-b617-b0f9334ccaa7
ms.openlocfilehash: 73e8db432afccb73b872ec7a3ce84c25f1ba7f25
ms.sourcegitcommit: ca06ef831226d629de3057a0df85e017b80f3356
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/08/2019
ms.locfileid: "29786787"
---
# <a name="retention-policies-in-exchange-admin-center"></a><span data-ttu-id="636ac-102">Directivas de retención en el centro de administración de Exchange</span><span class="sxs-lookup"><span data-stu-id="636ac-102">Retention Policies in Exchange Admin Center</span></span>

 <span data-ttu-id="636ac-103">**Problema:** Recién creado o las directivas de retención actualizado en el centro de administración de Exchange no se aplican a buzones de correo o no se mueven al buzón de archivo o se eliminan elementos.</span><span class="sxs-lookup"><span data-stu-id="636ac-103">**Issue:** Newly created or updated retention policies in the Exchange Admin Center are not applying to mailboxes or items are not moved to the archive mailbox or deleted.</span></span> 
  
 <span data-ttu-id="636ac-104">**Causas raíz:**</span><span class="sxs-lookup"><span data-stu-id="636ac-104">**Root Causes:**</span></span>
  
- <span data-ttu-id="636ac-p101">Esto puede ser debido a que el **Asistente para carpeta administrada** no procesó el buzón del usuario. El Asistente para carpeta administrada intenta procesar cada buzón de correo en su organización basada en la nube una vez cada siete días. Si cambia una etiqueta de retención o aplicar una directiva de retención diferente a un buzón de correo, puede esperar hasta que la carpeta administrada Assist procesa el buzón de correo, o bien puede ejecutar el cmdlet Start-ManagedFolderAssistant para iniciar el Asistente para carpeta administrada para procesar una determinada buzón de correo. Si ejecuta este cmdlet es útil para realizar pruebas o solucionar problemas de una directiva de retención o la configuración de la etiqueta de retención. Para obtener más información, visite [ejecutar el Asistente para carpeta administrada](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).</span><span class="sxs-lookup"><span data-stu-id="636ac-p101">This may be because the **Managed Folder Assistant** has not processed the user's mailbox. The Managed Folder Assistant tries to process every mailbox in your cloud-based organization once every seven days. If you change a retention tag or apply a different retention policy to a mailbox, you can wait until the Managed Folder Assist processes the mailbox, or you can run the Start-ManagedFolderAssistant cmdlet to start the Managed Folder Assistant to process a specific mailbox. Running this cmdlet is useful for testing or troubleshooting a retention policy or retention tag settings. For more information, visit [Run the Managed Folder Assistant](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).</span></span>
    
  - <span data-ttu-id="636ac-110">**Solución:** Ejecute el siguiente comando para iniciar el Asistente para carpeta administrada para un buzón específico:</span><span class="sxs-lookup"><span data-stu-id="636ac-110">**Solution:** Run the following command to start the Managed Folder Assistant for a specific mailbox:</span></span> 
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

- <span data-ttu-id="636ac-p102">Esto también se puede ocurrir si **RetentionHold** se ha **habilitado** en el buzón de correo. Si el buzón de correo se ha colocado en un RetentionHold, no se procesará la directiva de retención en el buzón de correo durante ese tiempo. Para obtener más información sobre la opción RetentionHold, consulte: [Suspensión de retención de buzón de correo](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).</span><span class="sxs-lookup"><span data-stu-id="636ac-p102">This may also be occur if **RetentionHold** has been **enabled** on the mailbox. If the mailbox has been placed on a RetentionHold, the retention policy on the mailbox will not be processed during that time. For more informaton on the RetentionHold setting see: [Mailbox Retention Hold](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).</span></span>
    
    <span data-ttu-id="636ac-114">**Solución:**</span><span class="sxs-lookup"><span data-stu-id="636ac-114">**Solution:**</span></span>
    
  - <span data-ttu-id="636ac-115">Compruebe el estado de la configuración de RetentionHold en el buzón de correo específico en [EXO powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):</span><span class="sxs-lookup"><span data-stu-id="636ac-115">Check the status of the RetentionHold setting on the specific mailbox in [EXO powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):</span></span>
    
  ```
  Get-Mailbox -Identity <name of the mailbox> |fl *retentionHold*
  ```

  - <span data-ttu-id="636ac-116">Ejecute el siguiente comando para **Deshabilitar** RetentionHold en un buzón específico:</span><span class="sxs-lookup"><span data-stu-id="636ac-116">Run the following command to **disable** RetentionHold on a specific mailbox:</span></span> 
    
  ```
  Set-Mailbox -RetentionHoldEnabled $false
  ```

  - <span data-ttu-id="636ac-117">Ahora, vuelva a ejecutar el Ayudante de carpeta administrada:</span><span class="sxs-lookup"><span data-stu-id="636ac-117">Now, re-run the Managed folder Assistant:</span></span>
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

 <span data-ttu-id="636ac-118">**Nota:** Si un buzón de correo es menor que 10 MB, el Asistente para carpeta administrada no procesará automáticamente el buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="636ac-118">**Note:** If a mailbox is smaller than 10 MB, the Managed Folder Assistant will not automatically process the mailbox.</span></span> 
  

