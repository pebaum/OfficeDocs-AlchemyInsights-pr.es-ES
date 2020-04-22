---
title: Solucionar problemas de mensajes de acceso denegado
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 82e11458529b8a49e583b1a6963a51e2a466bfd6
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43758534"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a><span data-ttu-id="8795f-102">Solucionar problemas de mensajes de acceso denegado en el centro de administración de SharePoint/OneDrive</span><span class="sxs-lookup"><span data-stu-id="8795f-102">Troubleshoot Access Denied messages in Sharepoint/OneDrive Admin Center</span></span>

<span data-ttu-id="8795f-103">Si recibe un mensaje de acceso denegado al intentar ir a un centro de administración de SharePoint o OneDrive, asegúrese de [asignar una licencia al usuario](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span><span class="sxs-lookup"><span data-stu-id="8795f-103">If you are receiving an access denied message when attempting to browse to a Sharepoint/OneDrive Admin Center, please make sure that you [assign a license to the user](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span></span> <span data-ttu-id="8795f-104">Si el usuario tiene una licencia, también debe asegurarse de que tiene [asignado un rol de administrador](https://docs.microsoft.com/office365/admin/add-users/about-admin-roles?view=o365-worldwide) que puede tener acceso a los centros de administración.</span><span class="sxs-lookup"><span data-stu-id="8795f-104">If the user has a license, you should also make sure they are [assigned an administrator role](https://docs.microsoft.com/office365/admin/add-users/about-admin-roles?view=o365-worldwide) that can access the admin centers.</span></span>

<span data-ttu-id="8795f-105">Este problema también puede producirse cuando se elimina un usuario y se vuelve a crear con el mismo nombre principal de usuario (UPN).</span><span class="sxs-lookup"><span data-stu-id="8795f-105">This issue can also occur when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="8795f-106">La nueva cuenta se crea con un valor de PUID (identificador único de pasaporte) diferente.</span><span class="sxs-lookup"><span data-stu-id="8795f-106">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="8795f-107">Cuando el usuario intenta tener acceso a una colección de sitios o a su OneDrive, el usuario tiene un PUID incorrecto.</span><span class="sxs-lookup"><span data-stu-id="8795f-107">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="8795f-108">Un segundo escenario implica la sincronización de directorios con una unidad organizativa (OU) de Active Directory.</span><span class="sxs-lookup"><span data-stu-id="8795f-108">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="8795f-109">Si los usuarios ya han iniciado sesión en SharePoint y, a continuación, se mueven a otra unidad organizativa y se resincronizan con SharePoint, pueden experimentar este problema.</span><span class="sxs-lookup"><span data-stu-id="8795f-109">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

<span data-ttu-id="8795f-110">Para resolver este problema, restaure el UPN original con los pasos del artículo [restaurar un usuario en Microsoft 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="8795f-110">To resolve this issue, you should restore the original UPN with the steps in the article, [Restore a user in Microsoft 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span></span>

<span data-ttu-id="8795f-111">Nota: Si un centro de administración de OneDrive o SharePoint no está disponible para varios usuarios que anteriormente tenían acceso, es posible que haya un problema de servicio temporal.</span><span class="sxs-lookup"><span data-stu-id="8795f-111">Note: If a OneDrive or SharePoint Admin center is not available to multiple users who previously had access, there may be a temporary service issue.</span></span>  <span data-ttu-id="8795f-112">[Compruebe el panel de estado del servicio](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="8795f-112">[Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>


