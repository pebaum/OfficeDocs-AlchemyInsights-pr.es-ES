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
# <a name="retention-policies-in-exchange-admin-center"></a>Directivas de retención en el centro de administración de Exchange

 **Problema:** Recién creado o las directivas de retención actualizado en el centro de administración de Exchange no se aplican a buzones de correo o no se mueven al buzón de archivo o se eliminan elementos. 
  
 **Causas raíz:**
  
- Esto puede ser debido a que el **Asistente para carpeta administrada** no procesó el buzón del usuario. El Asistente para carpeta administrada intenta procesar cada buzón de correo en su organización basada en la nube una vez cada siete días. Si cambia una etiqueta de retención o aplicar una directiva de retención diferente a un buzón de correo, puede esperar hasta que la carpeta administrada Assist procesa el buzón de correo, o bien puede ejecutar el cmdlet Start-ManagedFolderAssistant para iniciar el Asistente para carpeta administrada para procesar una determinada buzón de correo. Si ejecuta este cmdlet es útil para realizar pruebas o solucionar problemas de una directiva de retención o la configuración de la etiqueta de retención. Para obtener más información, visite [ejecutar el Asistente para carpeta administrada](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).
    
  - **Solución:** Ejecute el siguiente comando para iniciar el Asistente para carpeta administrada para un buzón específico: 
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

- Esto también se puede ocurrir si **RetentionHold** se ha **habilitado** en el buzón de correo. Si el buzón de correo se ha colocado en un RetentionHold, no se procesará la directiva de retención en el buzón de correo durante ese tiempo. Para obtener más información sobre la opción RetentionHold, consulte: [Suspensión de retención de buzón de correo](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).
    
    **Solución:**
    
  - Compruebe el estado de la configuración de RetentionHold en el buzón de correo específico en [EXO powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):
    
  ```
  Get-Mailbox -Identity <name of the mailbox> |fl *retentionHold*
  ```

  - Ejecute el siguiente comando para **Deshabilitar** RetentionHold en un buzón específico: 
    
  ```
  Set-Mailbox -RetentionHoldEnabled $false
  ```

  - Ahora, vuelva a ejecutar el Ayudante de carpeta administrada:
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

 **Nota:** Si un buzón de correo es menor que 10 MB, el Asistente para carpeta administrada no procesará automáticamente el buzón de correo. 
  

