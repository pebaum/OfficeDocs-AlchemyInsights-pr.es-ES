---
title: Uso compartido con usuarios externos no funciona
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 5/18/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: 305b3891e6c83e27b5c55c13757640e6e9d51a81
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28314093"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a><span data-ttu-id="e8139-102">Solucionar problemas de uso compartido de contenido de SharePoint con usuarios externos</span><span class="sxs-lookup"><span data-stu-id="e8139-102">Fix problems sharing SharePoint content with external users</span></span>

<span data-ttu-id="e8139-103">Asegúrese de que está activado el uso compartido externo para su organización:</span><span class="sxs-lookup"><span data-stu-id="e8139-103">Make sure external sharing is turned on for your organization:</span></span>
  
1. <span data-ttu-id="e8139-104">Vaya a la [servicios &amp; página de complementos en el centro de administración de Office 365](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns)y haga clic en **sitios**.</span><span class="sxs-lookup"><span data-stu-id="e8139-104">Go to the [Services &amp; add-ins page in the Office 365 admin center](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), and click **Sites**.</span></span>
    
2. <span data-ttu-id="e8139-p101">Asegúrese de que está activada la opción "Activado". Si se selecciona "Solo existente los usuarios externos", asegúrese de que el usuario externo aparece en el centro de administración de Office 365.</span><span class="sxs-lookup"><span data-stu-id="e8139-p101">Make sure the setting is turned to "On." If "Only existing external users" is selected, make sure the external user is listed in the Office 365 admin center.</span></span>
    
<span data-ttu-id="e8139-p102">Asegúrese de que externo compartirla activado para el sitio. Para una colección de sitios clásico:</span><span class="sxs-lookup"><span data-stu-id="e8139-p102">Make sure external sharing it turned on for the site. For a classic site collection:</span></span>
  
1. <span data-ttu-id="e8139-109">En el centro de administración de SharePoint clásico, en el panel izquierdo, haga clic en **las colecciones de sitios**.</span><span class="sxs-lookup"><span data-stu-id="e8139-109">In the classic SharePoint admin center, in the left pane, click **site collections**.</span></span>
    
2. <span data-ttu-id="e8139-110">Seleccione el sitio o los sitios y, en la cinta de opciones, haga clic en **Compartir**.</span><span class="sxs-lookup"><span data-stu-id="e8139-110">Select the site or sites, and on the ribbon, click **Sharing**.</span></span>
    
<span data-ttu-id="e8139-111">Para un sitio de grupo que pertenece a un grupo de Office 365, o un sitio de comunicación:</span><span class="sxs-lookup"><span data-stu-id="e8139-111">For a team site that belongs to an Office 365 group, or a communication site:</span></span>
  
- <span data-ttu-id="e8139-p103">Estos nuevos tipos de sitios tienen la misma configuración uso compartido como la configuración de toda la organización, a menos que la configuración de toda la organización permite el uso compartido de archivos con vínculos que no requieren inicio de sesión. En este caso, los sitios de permiten el uso compartido con usuarios externos nuevos y existentes que inician sesión en. Para cambiar la configuración para sitios específicos, use el nuevo centro de administración de SharePoint (vista previa) o PowerShell. [Más información](https://go.microsoft.com/fwlink/?linkid=871863).</span><span class="sxs-lookup"><span data-stu-id="e8139-p103">These new site types have the same sharing setting as your organization-wide setting, unless the organization-wide setting allows sharing files using links that don't require sign-in. In this case, the sites allow sharing with new and existing external users who sign in. To change the setting for specific sites, use the new SharePoint admin center (preview) or PowerShell. [Learn more](https://go.microsoft.com/fwlink/?linkid=871863).</span></span>
    
> [!NOTE]
> <span data-ttu-id="e8139-116">La opción de uso compartido externo para cualquier sitio puede ser más restrictivo que la configuración de toda la organización, pero no más permisivo que el valor de toda la organización.</span><span class="sxs-lookup"><span data-stu-id="e8139-116">The external sharing setting for any site can be more restrictive than your organization-wide setting, but not more permissive than the organization-wide setting.</span></span> 
  

