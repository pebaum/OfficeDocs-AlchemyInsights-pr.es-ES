---
title: Solucionar problemas de mensajes de acceso denegado
ms.author: kirks
author: Techwriter40
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 5958ad06ca905f713b5f56aa5c536e95a485f01c
ms.sourcegitcommit: 241e21b6da226563bf70bdb1f5bad3d91c38cd2c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/05/2019
ms.locfileid: "34735754"
---
# <a name="troubleshoot-access-denied-messages"></a><span data-ttu-id="5ba09-102">Solucionar problemas de mensajes de acceso denegado</span><span class="sxs-lookup"><span data-stu-id="5ba09-102">Troubleshoot Access Denied messages</span></span>

<span data-ttu-id="5ba09-103">Si recibe un mensaje de acceso denegado al intentar examinar un sitio de SharePoint Online, vea los artículos siguientes.</span><span class="sxs-lookup"><span data-stu-id="5ba09-103">If you are receiving an access denied message when attempting to browse a Sharepoint Online site, please see the below articles.</span></span>

## <a name="add-and-license-the-user"></a><span data-ttu-id="5ba09-104">Agregar y conceder una licencia al usuario</span><span class="sxs-lookup"><span data-stu-id="5ba09-104">Add and License the user</span></span>

<span data-ttu-id="5ba09-105">Asegúrese de [asignar licencias a usuarios en Office 365 para empresas](https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span><span class="sxs-lookup"><span data-stu-id="5ba09-105">Ensure that you [Assign licenses to users in Office 365 for business](https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span></span>

<span data-ttu-id="5ba09-106">Asignar permisos</span><span class="sxs-lookup"><span data-stu-id="5ba09-106">Assign Permissions</span></span>

<span data-ttu-id="5ba09-107">Si al usuario se le ha asignado una licencia de SharePoint y sigue recibiendo un mensaje de acceso denegado, asegúrese de que tiene [asignado el nivel de permisos adecuado](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels).</span><span class="sxs-lookup"><span data-stu-id="5ba09-107">If the user has been assigned a Sharepoint license and is still receiving an access denied message, please ensure they have the [appropriate permission level assigned](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels).</span></span>

<span data-ttu-id="5ba09-108">Considerar el uso de la característica de solicitud de acceso</span><span class="sxs-lookup"><span data-stu-id="5ba09-108">Consider using the access request feature</span></span>

<span data-ttu-id="5ba09-109">La característica de [solicitud de acceso](https://support.office.com/en-us/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) permite que las personas soliciten acceso al contenido que actualmente no tiene permiso para ver.</span><span class="sxs-lookup"><span data-stu-id="5ba09-109">The [access request](https://support.office.com/en-us/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) feature allows people to request access to content that they do not currently have permission to see.</span></span> 

<span data-ttu-id="5ba09-110">Permitir el script personalizado puede provocar problemas de denegación de acceso</span><span class="sxs-lookup"><span data-stu-id="5ba09-110">Allow custom script may cause access denied issues</span></span>

<span data-ttu-id="5ba09-111">Hay algunos escenarios en los que la característica "permitir secuencias de comandos personalizadas" puede presentar un acceso denegado.</span><span class="sxs-lookup"><span data-stu-id="5ba09-111">There are certain scenarios where the "Allow custom script" feature may be presenting an access denied.</span></span> <span data-ttu-id="5ba09-112">Para obtener una lista de características afectadas, consideraciones de seguridad y la posibilidad de deshabilitar la característica.</span><span class="sxs-lookup"><span data-stu-id="5ba09-112">For a list of features affected, security considerations and the ability to disable the feature.</span></span> <span data-ttu-id="5ba09-113">Visite, [permita o impida el scripts personalizados](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script) .</span><span class="sxs-lookup"><span data-stu-id="5ba09-113">Please visit , [Allow or prevent custom script](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script)</span></span>

<span data-ttu-id="5ba09-114">Nota: Si un sitio de OneDrive o SharePoint no está disponible para varios usuarios que anteriormente tenían acceso, es posible que haya un problema de servicio temporal.</span><span class="sxs-lookup"><span data-stu-id="5ba09-114">Note: If a OneDrive or SharePoint site is not available to multiple users who previously had access, there may be a temporary service issue.</span></span> <span data-ttu-id="5ba09-115">[Compruebe el panel de estado del servicio](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="5ba09-115">[Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>


  

