---
title: Creación de un sitio de SharePoint
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.collection: Adm_O365
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "5200004"
- "1386"
- "2303"
ms.assetid: e62b9f80-b017-42dc-9464-f4e32c19d6c9
ms.openlocfilehash: 2611c3ed9cfe78c82c9b123ea26b6fe8f951b458
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/15/2019
ms.locfileid: "40049894"
---
# <a name="create-a-sharepoint-site"></a><span data-ttu-id="1c2e7-102">Creación de un sitio de SharePoint</span><span class="sxs-lookup"><span data-stu-id="1c2e7-102">Create a SharePoint site</span></span>

<span data-ttu-id="1c2e7-103">Puede ver lo siguiente para obtener información sobre la creación de sitios de SharePoint:</span><span class="sxs-lookup"><span data-stu-id="1c2e7-103">You can see the following for information about SharePoint site creation:</span></span>
- <span data-ttu-id="1c2e7-104">[Administrar sitios en el nuevo centro de administración de SharePoint](https://docs.microsoft.com/sharepoint/manage-site-creation): Obtenga información sobre las opciones de creación de sitios, incluido cómo crear un sitio clásico o un sitio de teams que no incluya un grupo de Office 365.</span><span class="sxs-lookup"><span data-stu-id="1c2e7-104">[Manage sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/manage-site-creation): Learn about site creation options, including how to create a classic site or a teams site that doesn't include an Office 365 group.</span></span>
- <span data-ttu-id="1c2e7-105">[Cree un sitio de grupo en SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d): Aprenda a crear un sitio de grupo.</span><span class="sxs-lookup"><span data-stu-id="1c2e7-105">[Create a team site in SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d): Learn how to create a team site.</span></span>
- <span data-ttu-id="1c2e7-106">[Cree un sitio de comunicación en SharePoint Online](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb): Aprenda a crear un sitio de comunicaciones.</span><span class="sxs-lookup"><span data-stu-id="1c2e7-106">[Create a communication site in SharePoint Online](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb): Learn how to create a communications site.</span></span>
- <span data-ttu-id="1c2e7-107">[Administrar sitios en el nuevo centro de administración de SharePoint](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site): Aprenda a crear un sitio clásico o un sitio de grupo que no incluya un grupo de Office 365.</span><span class="sxs-lookup"><span data-stu-id="1c2e7-107">[Manage sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site):  Learn how to create a classic site or a team site that doesn't include an Office 365 group.</span></span>


  
<span data-ttu-id="1c2e7-108">**Abrevia**</span><span class="sxs-lookup"><span data-stu-id="1c2e7-108">**Tips:**</span></span>
- <span data-ttu-id="1c2e7-109">No se puede crear un sitio con la misma dirección URL de un sitio existente.</span><span class="sxs-lookup"><span data-stu-id="1c2e7-109">You cannot create a site with the same URL of an existing site.</span></span> <span data-ttu-id="1c2e7-110">Si ha eliminado un sitio y desea volver a usar la dirección URL, es posible que el sitio eliminado siga existiendo en **sitios eliminados**.</span><span class="sxs-lookup"><span data-stu-id="1c2e7-110">If you deleted a site and are wishing to re-use the URL, it's possible the deleted site still exists under **Deleted sites**.</span></span> <span data-ttu-id="1c2e7-111">Para administrar sitios eliminados, consulte [eliminar un sitio](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site).</span><span class="sxs-lookup"><span data-stu-id="1c2e7-111">To manage deleted sites see, [Delete a Site](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site).</span></span> <span data-ttu-id="1c2e7-112">Para quitar por completo un sitio con PowerShell, consulte el ejemplo del cmdlet [Remove-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) .</span><span class="sxs-lookup"><span data-stu-id="1c2e7-112">To completely remove a site with Powershell, see the [Remove-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) cmdlet example.</span></span>
- <span data-ttu-id="1c2e7-113">Es posible que algunos usuarios no puedan crear un sitio.</span><span class="sxs-lookup"><span data-stu-id="1c2e7-113">Some users may not be able to create a site.</span></span> <span data-ttu-id="1c2e7-114">Consulte [administrar la creación de sitios en SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation).</span><span class="sxs-lookup"><span data-stu-id="1c2e7-114">See [Manage site creation in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation).</span></span>
- <span data-ttu-id="1c2e7-115">Es posible que el sitio aparezca bloqueado en la **creación** de más tiempo del esperado.</span><span class="sxs-lookup"><span data-stu-id="1c2e7-115">It's possible the site appears stuck at **Creating** longer than expected.</span></span> <span data-ttu-id="1c2e7-116">Si ha pasado más de 24 horas desde que vio por primera vez este problema, registre un vale de soporte técnico.</span><span class="sxs-lookup"><span data-stu-id="1c2e7-116">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="1c2e7-117">En muchos casos, ya estamos trabajando en una solución.</span><span class="sxs-lookup"><span data-stu-id="1c2e7-117">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="1c2e7-118">Por lo menos, danos 24 horas para completar una soluci? a.</span><span class="sxs-lookup"><span data-stu-id="1c2e7-118">Please give us at least 24 hours to complete a solution.</span></span>
- <span data-ttu-id="1c2e7-119">Si necesita crear un nuevo sitio de grupo que no incluya un grupo de Office 365,</span><span class="sxs-lookup"><span data-stu-id="1c2e7-119">If you need to create a new team site that doesn't include an Office 365 group,</span></span> 


