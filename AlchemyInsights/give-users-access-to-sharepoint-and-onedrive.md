---
title: Dar acceso a los usuarios a SharePoint y OneDrive
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 11/14/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: eead51d6d16206de19bca213d6df72dbb6b66c8b
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/15/2019
ms.locfileid: "40051946"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a><span data-ttu-id="99187-102">Dar acceso a los usuarios a SharePoint y OneDrive</span><span class="sxs-lookup"><span data-stu-id="99187-102">Give users access to SharePoint and OneDrive</span></span>

> [!NOTE]
> <span data-ttu-id="99187-103">Si un sitio de OneDrive o SharePoint no está disponible para varios usuarios que anteriormente tenían acceso, es posible que haya un problema de servicio temporal.</span><span class="sxs-lookup"><span data-stu-id="99187-103">If a OneDrive or SharePoint site is not available to multiple users who previously had access, there may be a temporary service issue.</span></span> [<span data-ttu-id="99187-104">Comprobar el panel de estado del servicio</span><span class="sxs-lookup"><span data-stu-id="99187-104">Check the service health dashboard</span></span>](https://portal.office.com/adminportal/home#/servicehealth)
  
<span data-ttu-id="99187-105">Si quiere que los usuarios de su organización puedan iniciar sesión y usar SharePoint y OneDrive, necesita agregar cuentas para ellos y asegurarse de que tienen una licencia que les da acceso a SharePoint y OneDrive.</span><span class="sxs-lookup"><span data-stu-id="99187-105">If you want people in your organization to be able to sign in and use SharePoint and OneDrive, you need to add accounts for them and make sure they have a license that gives them access to SharePoint and OneDrive.</span></span> <span data-ttu-id="99187-106">La forma más sencilla de agregar usuarios es en el centro de administración de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="99187-106">The easiest way to add users is in the Microsoft 365 admin center.</span></span>
  
1. <span data-ttu-id="99187-107">Vaya a la [Página usuarios activos en el centro de administración de Microsoft 365](https://portal.office.com/adminportal/home#/users)y, a continuación, haga clic en **Agregar un usuario**.</span><span class="sxs-lookup"><span data-stu-id="99187-107">Go to the [Active users page in the Microsoft 365 admin center](https://portal.office.com/adminportal/home#/users), and then click **Add a user**.</span></span>
    
2. <span data-ttu-id="99187-108">Rellene la información del usuario y asegúrese de que en licencias de **productos**, se ha asignado una licencia y se ha seleccionado **SharePoint Online** .</span><span class="sxs-lookup"><span data-stu-id="99187-108">Fill in the information for the user, and make sure that under **Product licenses**, a license is assigned and **SharePoint Online** is selected.</span></span> 
    
<span data-ttu-id="99187-109">Tenga en cuenta que, si permite el uso compartido externo en su organización, los usuarios pueden compartir contenido de SharePoint y OneDrive con personas de fuera de la organización.</span><span class="sxs-lookup"><span data-stu-id="99187-109">Note that if you allow external sharing in your organization, users can share SharePoint and OneDrive content with people outside the organization.</span></span> <span data-ttu-id="99187-110">No es necesario conceder estas licencias a los usuarios externos.</span><span class="sxs-lookup"><span data-stu-id="99187-110">You don't need to give these external users licenses.</span></span> <span data-ttu-id="99187-111">Tampoco necesita agregar cuentas para ellos, a menos que el uso compartido esté establecido en "solo usuarios externos existentes".</span><span class="sxs-lookup"><span data-stu-id="99187-111">You also don't need to add accounts for them, unless sharing is set to "Only existing external users."</span></span> <span data-ttu-id="99187-112">En ese caso, si los usuarios no están en el directorio de su organización, debe agregarlos como usuarios invitados en el centro de administración de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="99187-112">In that case, if the people aren't in your organization's directory, you need to add them as guest users in the Azure AD admin center.</span></span>
  

