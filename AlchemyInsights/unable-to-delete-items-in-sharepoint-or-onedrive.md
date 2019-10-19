---
title: No se pueden eliminar elementos en SharePoint o OneDrive
ms.author: pebaum
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1851"
- "2377"
- "9000255"
ms.assetid: ''
ms.openlocfilehash: 3cc168846999c6880b95edfaedb2df8cf6e843a6
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2019
ms.locfileid: "36748593"
---
# <a name="unable-to-delete-items"></a>No se pueden eliminar los elementos

¿Tiene problemas para eliminar elementos de SharePoint?

- Asegúrese siempre de tener los [permisos adecuados](https://docs.microsoft.com/sharepoint/default-sharepoint-groups) para eliminar el elemento o de que un [Administrador de colección de sitios](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) intente quitar el elemento.

- Asegúrese de que no hay ninguna configuración de [Directiva de retención](https://docs.microsoft.com/office365/securitycompliance/retention-policies) en el elemento.

- Asegúrese de que otro usuario no ha [desprotegido](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) el elemento.

- Por último, los administradores pueden usar [patrones y prácticas de SharePoint](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PNP), que contiene una biblioteca de comandos de PowerShell que le permiten realizar acciones de administración complejas, como forzar la eliminación de elementos stubborn.
- [Quitar archivo PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [Quitar la carpeta PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [Quitar elemento de lista PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [Quitar lista PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [Quitar campo PNP (columna)](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)