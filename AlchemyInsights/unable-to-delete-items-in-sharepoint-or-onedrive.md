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
# <a name="unable-to-delete-items"></a><span data-ttu-id="9e061-102">No se pueden eliminar los elementos</span><span class="sxs-lookup"><span data-stu-id="9e061-102">Unable to delete items</span></span>

<span data-ttu-id="9e061-103">Las directivas de retención pueden causar esto, tiene que deshabilitar o excluir la retención respectiva que está causando este problema.</span><span class="sxs-lookup"><span data-stu-id="9e061-103">Retention policies can cause this, you need to either disable or exclude respective hold that's causing this issue.</span></span> <span data-ttu-id="9e061-104">Una vez quitada la retención o la Directiva de retención, el cambio puede tardar hasta 24 horas en surtir efecto.</span><span class="sxs-lookup"><span data-stu-id="9e061-104">After a retention policy or hold is removed, it may take up to 24 hours for the change to take effect.</span></span> <span data-ttu-id="9e061-105">Asegúrese de que no hay ninguna configuración de [Directiva de retención](https://docs.microsoft.com/office365/securitycompliance/retention-policies) en el elemento.</span><span class="sxs-lookup"><span data-stu-id="9e061-105">Ensure that there is not a [retention policy](https://docs.microsoft.com/office365/securitycompliance/retention-policies) setup on the item.</span></span>

<span data-ttu-id="9e061-106">Es posible que el sitio haya superado el límite de almacenamiento, aumente la [cuota del sitio](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) y elimine el elemento.</span><span class="sxs-lookup"><span data-stu-id="9e061-106">The site might have exceeded storage limit, increase the [site quota](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) and delete the item.</span></span>

<span data-ttu-id="9e061-107">Asegúrese de que otro usuario no ha [desprotegido](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) el elemento.</span><span class="sxs-lookup"><span data-stu-id="9e061-107">Ensure the item is not [checked out](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) to another user.</span></span>

<span data-ttu-id="9e061-108">Por último, los administradores pueden usar [patrones y prácticas de SharePoint](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PNP), que contiene una biblioteca de comandos de PowerShell que le permiten realizar acciones de administración complejas, como forzar la eliminación de elementos stubborn.</span><span class="sxs-lookup"><span data-stu-id="9e061-108">Finally, administrators can use [SharePoint Patterns and Practices](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) which contains a library of PowerShell commands that allow you to perform complex management actions such as force deleting stubborn items.</span></span>
- [<span data-ttu-id="9e061-109">Quitar archivo PNP</span><span class="sxs-lookup"><span data-stu-id="9e061-109">Remove PNP File</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [<span data-ttu-id="9e061-110">Quitar la carpeta PNP</span><span class="sxs-lookup"><span data-stu-id="9e061-110">Remove PNP Folder</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [<span data-ttu-id="9e061-111">Quitar elemento de lista PNP</span><span class="sxs-lookup"><span data-stu-id="9e061-111">Remove PNP List Item</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [<span data-ttu-id="9e061-112">Quitar lista PNP</span><span class="sxs-lookup"><span data-stu-id="9e061-112">Remove PNP List</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [<span data-ttu-id="9e061-113">Quitar campo PNP (columna)</span><span class="sxs-lookup"><span data-stu-id="9e061-113">Remove PNP Field (Column)</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)