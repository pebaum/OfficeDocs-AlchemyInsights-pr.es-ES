---
title: Las directivas de retención del centro de administración de Exchange no funcionan
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "308"
- "3100007"
ms.assetid: a48fd5fd-4af7-4d5f-b617-b0f9334ccaa7
ms.openlocfilehash: 9f4a175239bc20aaf489615da63ef35002030a70
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/28/2019
ms.locfileid: "35369682"
---
# <a name="retention-policies-in-exchange-admin-center"></a><span data-ttu-id="42d89-102">Directivas de retención en el centro de administración de Exchange</span><span class="sxs-lookup"><span data-stu-id="42d89-102">Retention Policies in Exchange Admin Center</span></span>

 <span data-ttu-id="42d89-103">**Problema:** Las directivas de retención recién creadas o actualizadas en el centro de administración de Exchange no se aplican a los buzones o los elementos no se mueven al buzón de archivo o se eliminan.</span><span class="sxs-lookup"><span data-stu-id="42d89-103">**Issue:** Newly created or updated retention policies in the Exchange Admin Center are not applying to mailboxes or items are not moved to the archive mailbox or deleted.</span></span> 
  
 <span data-ttu-id="42d89-104">**Causas principales:**</span><span class="sxs-lookup"><span data-stu-id="42d89-104">**Root Causes:**</span></span>
  
- <span data-ttu-id="42d89-105">Esto puede deberse a que el **Asistente para carpeta administrada** no ha procesado el buzón del usuario.</span><span class="sxs-lookup"><span data-stu-id="42d89-105">This may be because the **Managed Folder Assistant** has not processed the user's mailbox.</span></span> <span data-ttu-id="42d89-106">El Asistente para carpeta administrada intenta procesar todos los buzones de correo de la organización basada en la nube una vez cada siete días.</span><span class="sxs-lookup"><span data-stu-id="42d89-106">The Managed Folder Assistant tries to process every mailbox in your cloud-based organization once every seven days.</span></span> <span data-ttu-id="42d89-107">Si cambia una etiqueta de retención o aplica una directiva de retención diferente a un buzón, puede esperar hasta que la carpeta administrada Ayude a procesar el buzón o puede ejecutar el cmdlet Start-ManagedFolderAssistant para iniciar el Asistente para carpeta administrada para procesar un determinado bandeja.</span><span class="sxs-lookup"><span data-stu-id="42d89-107">If you change a retention tag or apply a different retention policy to a mailbox, you can wait until the Managed Folder Assist processes the mailbox, or you can run the Start-ManagedFolderAssistant cmdlet to start the Managed Folder Assistant to process a specific mailbox.</span></span> <span data-ttu-id="42d89-108">La ejecución de este cmdlet es útil para probar o solucionar problemas de configuración de una directiva de retención o de una etiqueta de retención.</span><span class="sxs-lookup"><span data-stu-id="42d89-108">Running this cmdlet is useful for testing or troubleshooting a retention policy or retention tag settings.</span></span> <span data-ttu-id="42d89-109">Para obtener más información, visite [ejecutar el Asistente para carpeta administrada](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).</span><span class="sxs-lookup"><span data-stu-id="42d89-109">For more information, visit [Run the Managed Folder Assistant](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).</span></span>
    
  - <span data-ttu-id="42d89-110">**Solución:** Ejecute el siguiente comando para iniciar el Asistente para carpeta administrada para un buzón específico:</span><span class="sxs-lookup"><span data-stu-id="42d89-110">**Solution:** Run the following command to start the Managed Folder Assistant for a specific mailbox:</span></span>
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

- <span data-ttu-id="42d89-111">Esto también puede ocurrir si **RetentionHold** se ha **habilitado** en el buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="42d89-111">This may also be occur if **RetentionHold** has been **enabled** on the mailbox.</span></span> <span data-ttu-id="42d89-112">Si el buzón se ha colocado en un RetentionHold, la Directiva de retención en el buzón no se procesará durante este período.</span><span class="sxs-lookup"><span data-stu-id="42d89-112">If the mailbox has been placed on a RetentionHold, the retention policy on the mailbox will not be processed during that time.</span></span> <span data-ttu-id="42d89-113">Para obtener más información sobre la configuración de RetentionHold, vea: conservación de la retención de buzones de [correo](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).</span><span class="sxs-lookup"><span data-stu-id="42d89-113">For more informaton on the RetentionHold setting see: [Mailbox Retention Hold](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).</span></span>
    
    <span data-ttu-id="42d89-114">**Soluciones**</span><span class="sxs-lookup"><span data-stu-id="42d89-114">**Solution:**</span></span>
    
  - <span data-ttu-id="42d89-115">Compruebe el estado de la opción RetentionHold en el buzón específico en el [PowerShell Exo](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):</span><span class="sxs-lookup"><span data-stu-id="42d89-115">Check the status of the RetentionHold setting on the specific mailbox in [EXO powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):</span></span>
    
  ```
  Get-Mailbox -Identity <name of the mailbox> |fl *retentionHold*
  ```

  - <span data-ttu-id="42d89-116">Ejecute el siguiente comando para **deshabilitar** RetentionHold en un buzón específico:</span><span class="sxs-lookup"><span data-stu-id="42d89-116">Run the following command to **disable** RetentionHold on a specific mailbox:</span></span>
    
  ```
  Set-Mailbox -RetentionHoldEnabled $false
  ```

  - <span data-ttu-id="42d89-117">Ahora, vuelva a ejecutar el Asistente para carpeta administrada:</span><span class="sxs-lookup"><span data-stu-id="42d89-117">Now, re-run the Managed folder Assistant:</span></span>
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

 <span data-ttu-id="42d89-118">**Nota:** Si un buzón tiene menos de 10 MB, el Asistente para carpeta administrada no procesará automáticamente el buzón.</span><span class="sxs-lookup"><span data-stu-id="42d89-118">**Note:** If a mailbox is smaller than 10 MB, the Managed Folder Assistant will not automatically process the mailbox.</span></span>
  