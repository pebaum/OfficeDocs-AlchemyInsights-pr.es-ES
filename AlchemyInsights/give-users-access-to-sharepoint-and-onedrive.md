---
title: Dar acceso a los usuarios a SharePoint y OneDrive
ms.author: kaarins
author: kaarins
manager: scotv
ms.date: 11/14/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: d29764266f44aee5f8f8e2c93ad67b2a33c6f417
ms.sourcegitcommit: c003a5db7edc3a44fb5b31b46cd45f12b62d172a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/22/2019
ms.locfileid: "30209754"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a><span data-ttu-id="b3731-102">Dar acceso a los usuarios a SharePoint y OneDrive</span><span class="sxs-lookup"><span data-stu-id="b3731-102">Give users access to SharePoint and OneDrive</span></span>

> [!NOTE]
> <span data-ttu-id="b3731-p101">Si un sitio de OneDrive o SharePoint no está disponible para varios usuarios que anteriormente tenían acceso, es posible que haya un problema de servicio temporal. [Comprobar el panel de estado del servicio](https://portal.office.com/adminportal/home#/servicehealth)</span><span class="sxs-lookup"><span data-stu-id="b3731-p101">If a OneDrive or SharePoint site is not available to multiple users who previously had access, there may be a temporary service issue. [Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth)</span></span>
  
<span data-ttu-id="b3731-p102">Si quiere que los usuarios de su organización puedan iniciar sesión y usar SharePoint y OneDrive, necesita agregar cuentas para ellos y asegurarse de que tienen una licencia que les da acceso a SharePoint y OneDrive. La forma más sencilla de agregar usuarios es en el centro de administración de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="b3731-p102">If you want people in your organization to be able to sign in and use SharePoint and OneDrive, you need to add accounts for them and make sure they have a license that gives them access to SharePoint and OneDrive. The easiest way to add users is in the Microsoft 365 admin center.</span></span>
  
1. <span data-ttu-id="b3731-107">Vaya a la [Página usuarios activos en el centro de administración de Microsoft 365](https://portal.office.com/adminportal/home#/users)y, a continuación, haga clic en **Agregar un usuario**.</span><span class="sxs-lookup"><span data-stu-id="b3731-107">Go to the [Active users page in the Microsoft 365 admin center](https://portal.office.com/adminportal/home#/users), and then click **Add a user**.</span></span>
    
2. <span data-ttu-id="b3731-108">ReLlene la información del usuario y asegúrese de que en licencias de **productos**, se ha asignado una licencia y se ha seleccionado **SharePoint Online** .</span><span class="sxs-lookup"><span data-stu-id="b3731-108">Fill in the information for the user, and make sure that under **Product licenses**, a license is assigned and **SharePoint Online** is selected.</span></span> 
    
<span data-ttu-id="b3731-p103">Tenga en cuenta que, si permite el uso compartido externo en su organización, los usuarios pueden compartir contenido de SharePoint y OneDrive con personas de fuera de la organización. No es necesario conceder estas licencias a los usuarios externos. Tampoco necesita agregar cuentas para ellos, a menos que el uso compartido esté establecido en "solo usuarios externos existentes". En ese caso, si los usuarios no están en el directorio de su organización, debe agregarlos como usuarios invitados en el centro de administración de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="b3731-p103">Note that if you allow external sharing in your organization, users can share SharePoint and OneDrive content with people outside the organization. You don't need to give these external users licenses. You also don't need to add accounts for them, unless sharing is set to "Only existing external users." In that case, if the people aren't in your organization's directory, you need to add them as guest users in the Azure AD admin center.</span></span>
  

