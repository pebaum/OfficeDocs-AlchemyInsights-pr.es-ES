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
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/04/2019
ms.locfileid: "36748593"
---
# <a name="unable-to-delete-items"></a><span data-ttu-id="d276e-102">No se pueden eliminar los elementos</span><span class="sxs-lookup"><span data-stu-id="d276e-102">Unable to delete items</span></span>

<span data-ttu-id="d276e-103">¿Tiene problemas para eliminar elementos de SharePoint?</span><span class="sxs-lookup"><span data-stu-id="d276e-103">Having issues deleting SharePoint items?</span></span>

- <span data-ttu-id="d276e-104">Asegúrese siempre de tener los [permisos adecuados](https://docs.microsoft.com/sharepoint/default-sharepoint-groups) para eliminar el elemento o de que un [Administrador de colección de sitios](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) intente quitar el elemento.</span><span class="sxs-lookup"><span data-stu-id="d276e-104">Always make sure you have the [appropriate permissions](https://docs.microsoft.com/sharepoint/default-sharepoint-groups) to delete the item or have a [site collection administrator](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) attempt remove the item.</span></span>

- <span data-ttu-id="d276e-105">Asegúrese de que no hay ninguna configuración de [Directiva de retención](https://docs.microsoft.com/office365/securitycompliance/retention-policies) en el elemento.</span><span class="sxs-lookup"><span data-stu-id="d276e-105">Ensure that there is not a [retention policy](https://docs.microsoft.com/office365/securitycompliance/retention-policies) setup on the item.</span></span>

- <span data-ttu-id="d276e-106">Asegúrese de que otro usuario no ha [desprotegido](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) el elemento.</span><span class="sxs-lookup"><span data-stu-id="d276e-106">Ensure the item is not [checked out](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) to another user.</span></span>

- <span data-ttu-id="d276e-107">Por último, los administradores pueden usar [patrones y prácticas de SharePoint](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PNP), que contiene una biblioteca de comandos de PowerShell que le permiten realizar acciones de administración complejas, como forzar la eliminación de elementos stubborn.</span><span class="sxs-lookup"><span data-stu-id="d276e-107">Finally, administrators can use [SharePoint Patterns and Practices](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) which contains a library of PowerShell commands that allow you to perform complex management actions such as force deleting stubborn items.</span></span>
- [<span data-ttu-id="d276e-108">Quitar archivo PNP</span><span class="sxs-lookup"><span data-stu-id="d276e-108">Remove PNP File</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [<span data-ttu-id="d276e-109">Quitar la carpeta PNP</span><span class="sxs-lookup"><span data-stu-id="d276e-109">Remove PNP Folder</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [<span data-ttu-id="d276e-110">Quitar elemento de lista PNP</span><span class="sxs-lookup"><span data-stu-id="d276e-110">Remove PNP List Item</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [<span data-ttu-id="d276e-111">Quitar lista PNP</span><span class="sxs-lookup"><span data-stu-id="d276e-111">Remove PNP List</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [<span data-ttu-id="d276e-112">Quitar campo PNP (columna)</span><span class="sxs-lookup"><span data-stu-id="d276e-112">Remove PNP Field (Column)</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)