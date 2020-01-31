---
title: No se pueden eliminar elementos en SharePoint o OneDrive
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1851"
- "2377"
- "9000255"
ms.assetid: ''
ms.openlocfilehash: abfcb91c6040aeed759d697ca63546ccea8ede97
ms.sourcegitcommit: c5e800313a6f211386a384716e5fa18e7fcc8c1c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/28/2020
ms.locfileid: "41571288"
---
# <a name="unable-to-delete-items"></a>No se pueden eliminar los elementos

Las directivas de retención pueden causar esto, tiene que deshabilitar o excluir la retención respectiva que está causando este problema. Una vez quitada la retención o la Directiva de retención, el cambio puede tardar hasta 24 horas en surtir efecto. Asegúrese de que no hay ninguna configuración de [Directiva de retención](https://docs.microsoft.com/office365/securitycompliance/retention-policies) en el elemento.

Es posible que el sitio haya superado el límite de almacenamiento, aumente la [cuota del sitio](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) y elimine el elemento.

Asegúrese de que otro usuario no ha [desprotegido](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) el elemento.

Por último, los administradores pueden usar [patrones y prácticas de SharePoint](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PNP), que contiene una biblioteca de comandos de PowerShell que le permiten realizar acciones de administración complejas, como forzar la eliminación de elementos stubborn.
- [Quitar archivo PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [Quitar la carpeta PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [Quitar elemento de lista PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [Quitar lista PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [Quitar campo PNP (columna)](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)