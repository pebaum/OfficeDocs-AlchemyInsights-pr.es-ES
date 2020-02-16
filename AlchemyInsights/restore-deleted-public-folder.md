---
title: Restaurar una carpeta pública eliminada
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3488"
ms.openlocfilehash: 7b04612daca61650d162c1dde240e25c1b185b04
ms.sourcegitcommit: 8ba12eff67e405f5922ea4cc35155e3036447859
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/15/2020
ms.locfileid: "42063754"
---
# <a name="restore-a-deleted-public-folder"></a><span data-ttu-id="5a267-102">Restaurar una carpeta pública eliminada</span><span class="sxs-lookup"><span data-stu-id="5a267-102">Restore a deleted public folder</span></span>

<span data-ttu-id="5a267-103">**Para restaurar elementos eliminados de una carpeta pública**:</span><span class="sxs-lookup"><span data-stu-id="5a267-103">**To restore deleted items from a public folder**:</span></span>

- <span data-ttu-id="5a267-104">Vea [no puede recuperar los elementos eliminados de una carpeta pública que no es de correo en Outlook 2016](https://aka.ms/pfrec).</span><span class="sxs-lookup"><span data-stu-id="5a267-104">See [You can't recover deleted items from a non-mail public folder in Outlook 2016](https://aka.ms/pfrec).</span></span>
 
<span data-ttu-id="5a267-105">**Para restaurar una carpeta pública eliminada (de cualquier tipo)**:</span><span class="sxs-lookup"><span data-stu-id="5a267-105">**To restore a deleted public folder (of any type)**:</span></span> 

- <span data-ttu-id="5a267-106">Use el siguiente comando de PowerShell EXO:</span><span class="sxs-lookup"><span data-stu-id="5a267-106">Please use following EXO PowerShell command:</span></span>

    <span data-ttu-id="5a267-107">Sintaxis:</span><span class="sxs-lookup"><span data-stu-id="5a267-107">Syntax:</span></span>

    ><span data-ttu-id="5a267-108">$pf = Get-PublicFolder \ NON_IPM_SUBTREE \ DUMPSTER_ROOT-recurse |? {$_. Name-EQ "\<name_of_deleted_public_Folder"}; Set-PublicFolder $pf. Identity-path \<ruta de acceso en la que se va a restaurar la carpeta></span><span class="sxs-lookup"><span data-stu-id="5a267-108">$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse  | ?{$_.Name -eq "\<name_of_deleted_public_Folder"};Set-PublicFolder $pf.identity -Path \<path where the folder will be restored></span></span>

    <span data-ttu-id="5a267-109">Ejemplo: en el siguiente comando se restaurará Subfolder1 y se colocará en \Parent1:</span><span class="sxs-lookup"><span data-stu-id="5a267-109">Example: The following command will restore Subfolder1 and place it under \Parent1:</span></span>

    ><span data-ttu-id="5a267-110">$pf = Get-PublicFolder \ NON_IPM_SUBTREE \ DUMPSTER_ROOT-recurse |? {$_. Name-EQ "Subfolder1"}; Set-PublicFolder $pf. Identity-path \Parent1</span><span class="sxs-lookup"><span data-stu-id="5a267-110">$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse | ?{$_.Name -eq "Subfolder1"};Set-PublicFolder $pf.identity -Path \Parent1</span></span>

<span data-ttu-id="5a267-111">Consulte [restaurar una carpeta pública eliminada](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="5a267-111">See [Restore a deleted public folder](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) for more details.</span></span>
