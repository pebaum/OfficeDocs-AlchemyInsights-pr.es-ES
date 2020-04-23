---
title: 1336 la carpeta RecoverableItems está llena
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1336"
- "3700003"
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: fb10b792981040bdcf4661b8aff30733c2438212
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43720269"
---
# <a name="the-recoverable-items-folder-is-full"></a>La carpeta elementos recuperables está llena

Para los buzones de correo de Exchange Online, el límite de almacenamiento predeterminado para la carpeta elementos recuperables es de 30 GB. El límite de almacenamiento de la carpeta elementos recuperables aumenta automáticamente a 100 GB si el buzón se coloca en retención por juicio, suspensión de eDiscovery o se asigna a una directiva de retención.

Cuando la carpeta elementos recuperables alcanza el límite de almacenamiento, la funcionalidad de buzón de correo se ve afectada de las siguientes maneras:

- El usuario no puede eliminar elementos del buzón.

- El asistente para carpetas administradas no puede eliminar elementos basados en la etiqueta de retención o en la configuración de carpetas administradas.

- Para los buzones que tienen habilitada la recuperación de un único elemento o que están en espera, el proceso de protección de página de copia en escritura no puede mantener versiones de los elementos editados por el usuario.

- Para los buzones que tienen habilitado el registro de auditoría de buzones de correo, las entradas del registro de auditoría de buzones no se pueden guardar en la subcarpeta auditorías de la carpeta elementos recuperables.

Para los buzones que no están en suspensión, los administradores pueden `Search-Mailbox -SearchDumpsterOnly -DeleteContent` usar el comando en Exchange Online PowerShell para eliminar elementos de la carpeta elementos recuperables. Para obtener más información, vea los siguientes temas:

- [Búsqueda y eliminación de mensajes](https://docs.microsoft.com/office365/securitycompliance/search-for-and-delete-messagesadmin-help)

- [Search-Mailbox](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)

Para los buzones que están en retención, los administradores deben quitar la retención antes de que puedan eliminar elementos de la carpeta elementos recuperables. Para obtener más información, vea [eliminar elementos de la carpeta elementos recuperables de buzones basados en la nube en retención](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).

Para ayudar a evitar que la carpeta elementos recuperables se llene, los administradores pueden aumentar el límite de almacenamiento de la carpeta elementos recuperables para los buzones de correo en retención y configurar una directiva de retención de buzones que mueva los elementos de la carpeta elementos recuperables al buzón de archivo del usuario. Consulte [aumentar la cuota de elementos recuperables para los buzones de correo en retención](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).
