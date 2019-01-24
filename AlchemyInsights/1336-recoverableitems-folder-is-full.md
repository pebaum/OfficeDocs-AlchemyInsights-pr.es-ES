---
title: Carpeta de RecoverableItems 1336 está llena
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: ee96abfa179c36ebaf43dbd327d4608b849395d3
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29491112"
---
# <a name="the-recoverable-items-folder-is-full"></a>La carpeta elementos recuperables está llena

Para buzones de Exchange Online en Office 365, el límite de almacenamiento predeterminada para la carpeta elementos recuperables es de 30 GB. El límite de almacenamiento de la carpeta elementos recuperables se incrementa automáticamente a 100 GB si el buzón de correo se pondrá en suspensión por litigio, exhibición de documentos electrónicos, o que esté asignada a una directiva de retención de Office 365.
  
Cuando la carpeta elementos recuperables alcanza el límite de almacenamiento, la funcionalidad de buzón de correo se ve afectada de las siguientes maneras:
  
- El usuario no puede eliminar elementos del buzón de correo.
    
- El asistente para carpetas administradas no puede eliminar elementos basados en la etiqueta de retención o en la configuración de carpetas administradas.
    
- Para los buzones de correo que tienen la recuperación de elemento único habilitada o se colocan en espera, el proceso de protección de la página de copia en escritura no puede mantener las versiones de los elementos modificadas por el usuario.
    
- Para los buzones que tienen el buzón habilitado el registro de auditoría, no hay entradas de registro de auditoría de buzón pueden guardarse en la subcarpeta de auditorías en la carpeta elementos recuperables.
    
Para los buzones que no están en espera, los administradores pueden utilizar el `Search-Mailbox -SearchDumpsterOnly -DeleteContent` comando en Exchange Online PowerShell para eliminar elementos de la carpeta elementos recuperables. Para obtener más información, vea los temas siguientes: 
  
- [Búsqueda y eliminación de mensajes](https://docs.microsoft.com/office365/securitycompliance/search-for-and-delete-messagesadmin-help)
    
- [Search-Mailbox](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)
    
Para los buzones de correo que están en espera, los administradores tienen que quitar la suspensión antes de que los elementos eliminados de la carpeta elementos recuperables. Para obtener más información, vea [Eliminar elementos en la carpeta de buzones de correo basados en la nube en retención de elementos recuperables](https://docs.microsoft.com/en-us/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).
  
Para ayudar a evitar que la carpeta elementos recuperables completa, los administradores pueden aumentar el límite de almacenamiento de los elementos recuperables de carpeta para los buzones de correo en suspensión y configurar una directiva de retención de buzón de correo que mueve los elementos de la carpeta elementos recuperables para el archivo del usuario buzón de correo. Vea [aumentar la cuota de buzones de correo en suspensión de elementos recuperables](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).
  

