---
title: No funciona el uso compartido con usuarios externos
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 5/18/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: 69e290e5a13f40ad045086791189a7d0af88240b
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "32369515"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a><span data-ttu-id="3522c-102">Solucionar problemas de uso compartido de contenido de SharePoint con usuarios externos</span><span class="sxs-lookup"><span data-stu-id="3522c-102">Fix problems sharing SharePoint content with external users</span></span>

<span data-ttu-id="3522c-103">Asegúrese de que el uso compartido externo está activado para su organización:</span><span class="sxs-lookup"><span data-stu-id="3522c-103">Make sure external sharing is turned on for your organization:</span></span>
  
1. <span data-ttu-id="3522c-104">Vaya a la [página &amp; complementos de servicios en el centro de administración de Microsoft 365](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns)y haga clic en **sitios**.</span><span class="sxs-lookup"><span data-stu-id="3522c-104">Go to the [Services &amp; add-ins page in the Microsoft 365 admin center](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), and click **Sites**.</span></span>
    
2. <span data-ttu-id="3522c-105">Asegúrese de que la configuración esté activada como "ON".</span><span class="sxs-lookup"><span data-stu-id="3522c-105">Make sure the setting is turned to "On."</span></span> <span data-ttu-id="3522c-106">Si se selecciona "solo usuarios externos existentes", asegúrese de que el usuario externo aparece en el centro de administración de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="3522c-106">If "Only existing external users" is selected, make sure the external user is listed in the Microsoft 365 admin center.</span></span>
    
<span data-ttu-id="3522c-107">Asegúrese de que el uso compartido externo esté activado para el sitio.</span><span class="sxs-lookup"><span data-stu-id="3522c-107">Make sure external sharing it turned on for the site.</span></span> <span data-ttu-id="3522c-108">Para una colección de sitios clásica:</span><span class="sxs-lookup"><span data-stu-id="3522c-108">For a classic site collection:</span></span>
  
1. <span data-ttu-id="3522c-109">En el panel izquierdo del nuevo centro de administración de SharePoint, haga clic en **sitios**.</span><span class="sxs-lookup"><span data-stu-id="3522c-109">In the new SharePoint admin center, in the left pane, click **sites**.</span></span>
    
2. <span data-ttu-id="3522c-110">Seleccione el sitio o los sitios y, en la cinta de opciones, haga clic en **compartir**.</span><span class="sxs-lookup"><span data-stu-id="3522c-110">Select the site or sites, and on the ribbon, click **Sharing**.</span></span>
    
<span data-ttu-id="3522c-111">Para un sitio de grupo que pertenece a un grupo de Office 365 o a un sitio de comunicación:</span><span class="sxs-lookup"><span data-stu-id="3522c-111">For a team site that belongs to an Office 365 group, or a communication site:</span></span>
  
- <span data-ttu-id="3522c-112">Estos nuevos tipos de sitio tienen la misma configuración de uso compartido que la configuración de toda la organización, a menos que la configuración de toda la organización permita compartir archivos mediante vínculos que no requieran el inicio de sesión.</span><span class="sxs-lookup"><span data-stu-id="3522c-112">These new site types have the same sharing setting as your organization-wide setting, unless the organization-wide setting allows sharing files using links that don't require sign-in.</span></span> <span data-ttu-id="3522c-113">En este caso, los sitios permiten el uso compartido con usuarios externos nuevos y existentes que inician sesión.</span><span class="sxs-lookup"><span data-stu-id="3522c-113">In this case, the sites allow sharing with new and existing external users who sign in.</span></span> <span data-ttu-id="3522c-114">Para cambiar la configuración de sitios específicos, use el nuevo centro de administración de SharePoint o PowerShell.</span><span class="sxs-lookup"><span data-stu-id="3522c-114">To change the setting for specific sites, use the new SharePoint admin center or PowerShell.</span></span> <span data-ttu-id="3522c-115">Obtener [más información](https://go.microsoft.com/fwlink/?linkid=871863).</span><span class="sxs-lookup"><span data-stu-id="3522c-115">[Learn more](https://go.microsoft.com/fwlink/?linkid=871863).</span></span>
    
> [!NOTE]
> <span data-ttu-id="3522c-116">La configuración de uso compartido externo de cualquier sitio puede ser más restrictiva que la configuración de toda la organización, pero no más permisiva que la configuración de toda la organización.</span><span class="sxs-lookup"><span data-stu-id="3522c-116">The external sharing setting for any site can be more restrictive than your organization-wide setting, but not more permissive than the organization-wide setting.</span></span> 
  

