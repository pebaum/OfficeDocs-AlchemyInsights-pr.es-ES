---
title: Eliminar permanentemente un sitio de SharePoint
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.custom: ''
ms.assetid:
- "5200006"
- "4391"
ms.openlocfilehash: 263317339d965d173a5a038fa006e0ce6f8476cc
ms.sourcegitcommit: da04e79b6072321caa16a6ceea6eb5f15de22394
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 03/25/2020
ms.locfileid: "42955236"
---
# <a name="permanently-delete-a-site-in-sharepoint"></a><span data-ttu-id="3f884-102">Eliminar permanentemente un sitio de SharePoint</span><span class="sxs-lookup"><span data-stu-id="3f884-102">Permanently delete a site in SharePoint</span></span>

<span data-ttu-id="3f884-103">Para volver a usar una dirección URL de un sitio eliminado (para volver a crear un sitio) o para eliminar permanentemente un sitio porque ya no está en uso, puede usar **Eliminar permanentemente** del nuevo Centro de administración de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="3f884-103">To reuse a URL from a deleted site (to recreate a site), or to permanently delete a site because it's no longer in use, you can use **Permanently Delete** from the New SharePoint Admin Center.</span></span> 

1. <span data-ttu-id="3f884-104">Vaya a la página [Sitios eliminados del nuevo Centro de administración de SharePoint](https://admin.microsoft.com/sharepoint?page=recycleBin&modern=true) e inicie sesión con una cuenta que tenga permisos de administrador para su organización.</span><span class="sxs-lookup"><span data-stu-id="3f884-104">Go to the [Deleted sites page of the new SharePoint admin center](https://admin.microsoft.com/sharepoint?page=recycleBin&modern=true) and sign in with an account that has admin permissions for your organization.</span></span> 

2. <span data-ttu-id="3f884-105">En la columna de la izquierda, seleccione un sitio.</span><span class="sxs-lookup"><span data-stu-id="3f884-105">In the left column, select a site.</span></span> 

3. <span data-ttu-id="3f884-106">Haga clic en **Eliminar permanentemente**</span><span class="sxs-lookup"><span data-stu-id="3f884-106">Click **Permanently Delete**.</span></span> 

<span data-ttu-id="3f884-107">**Tenga en cuenta**: los sitios conectados a un grupo no se pueden eliminar permanentemente desde el nuevo Centro de administración de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="3f884-107">**Note**: Group-connected sites cannot be permanently deleted from the New SharePoint Admin Center.</span></span> <span data-ttu-id="3f884-108">Se debe usar [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-spodeletedsite) en su lugar.</span><span class="sxs-lookup"><span data-stu-id="3f884-108">[Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-spodeletedsite) will need to be used instead.</span></span>  

<span data-ttu-id="3f884-109">Para obtener más información, vea [Eliminar de forma permanente un sitio](https://docs.microsoft.com/sharepoint/delete-site-collection#permanently-delete-a-site).</span><span class="sxs-lookup"><span data-stu-id="3f884-109">For more info, see [Permanently delete a site](https://docs.microsoft.com/sharepoint/delete-site-collection#permanently-delete-a-site).</span></span> 
