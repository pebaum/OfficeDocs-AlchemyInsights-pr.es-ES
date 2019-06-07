---
title: Mover mensajes de correo electrónico al buzón de archivo
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: fb5745b60d42e1f7d7bb9b7a336a51b62c2ff92a
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/07/2019
ms.locfileid: "34762382"
---
# <a name="move-email-to-the-archive-mailbox"></a>Mover el correo electrónico al buzón de archivo
 
1. Confirme que se ha habilitado un **buzón de archivo** . Si no es así, siga los pasos de [este artículo](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) para habilitar el buzón de archivo.

2. Para archivar mensajes automáticamente en el buzón de archivo, se debe establecer una etiqueta de retención con la acción **mover a archivo** para que se **aplique automáticamente a toda la etiqueta del buzón (predeterminado)**. Siga los pasos que se describen aquí para crear la etiqueta: archivar la [etiqueta predeterminada](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Foffice365%2Fsecuritycompliance%2Fset-up-an-archive-and-deletion-policy-for-mailboxes%23create-a-custom-archive-default-policy-tag&data=04%7C01%7Cstephow%40microsoft.com%7C89934e16dbd84ebdef6708d6b319b348%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C636893320296576506%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C-1&sdata=UibWi%2BtrO3ITZ6iF%2FtKQj5JyxzEb9Mu9frBJPT6FNFI%3D&reserved=0).
    
3. A continuación, agregue la etiqueta de **archivo** a la Directiva de retención. En el centro de administración de Exchange, seleccione **directivas de retención** > agregue la **etiqueta mover a archivo** a la Directiva > **Guardar**. 
    
4. Ahora [asigne la Directiva de retención](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) al buzón de correo del usuario específico. La misma directiva se aplicará al buzón **principal** y al buzón de **archivo** . 
    
Puede que sea necesario forzar la ejecución del Asistente para carpeta administrada (MFA) y aplicar la nueva configuración al buzón de correo del usuario. Ejecute el comando siguiente mientras [está conectado a Exo PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) para iniciar el Asistente para carpeta administrada para un buzón específico: 
  
```
Start-ManagedFolderAssistant -Identity <name of the mailbox>
```

Para obtener más información sobre cómo configurar una directiva de archivo, consulte [configurar una directiva de archivo y eliminación para](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users)los buzones.
  

