---
title: No se está enviando correo electrónico de flujo de trabajo
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 7/25/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1586"
ms.openlocfilehash: 783bf0a5721aa5db7088432c71e06cac6dc90513
ms.sourcegitcommit: 407f6c1e82f1a0be5cf53301fbf03cd25dcbf0ee
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/02/2019
ms.locfileid: "36059620"
---
# <a name="workflow-email-is-not-being-sent"></a><span data-ttu-id="cd220-102">No se está enviando correo electrónico de flujo de trabajo</span><span class="sxs-lookup"><span data-stu-id="cd220-102">Workflow email is not being sent</span></span>

1. <span data-ttu-id="cd220-103">El correo electrónico de los flujos de trabajo no se envía a todos los usuarios o solo a usuarios específicos, o Ve el error **no se puede enviar el mensaje de correo electrónico. Asegúrese de que el correo electrónico tiene un destinatario válido**.</span><span class="sxs-lookup"><span data-stu-id="cd220-103">Email from workflows are not sent to all users or only specific users, or you see the error **The e-mail message cannot be sent. Make sure the e-mail has a valid recipient**.</span></span>

<span data-ttu-id="cd220-104">Compruebe si el usuario existe en el grupo de permisos **todos los usuarios** (lista de información del usuario) para esa colección de sitios.</span><span class="sxs-lookup"><span data-stu-id="cd220-104">Check if the user exist in the **All People** permissions group (user information list) for that site collection.</span></span>  <span data-ttu-id="cd220-105">¿Dirección URL directa de<tenant>ejemplo:<sitename>https://. SharePoint.com/sites//_layouts/15/People.aspx? MembershipGroupId = 0</span><span class="sxs-lookup"><span data-stu-id="cd220-105">Sample direct URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx?MembershipGroupId=0</span></span>

- <span data-ttu-id="cd220-106">Si el usuario no existe, asegúrese de que el usuario haya iniciado sesión en la página.</span><span class="sxs-lookup"><span data-stu-id="cd220-106">If the user does not exist, make sure the user is signed into the page.</span></span> 
- <span data-ttu-id="cd220-107">Si es un usuario externo, asegúrese de que su invitación se ha aceptado.</span><span class="sxs-lookup"><span data-stu-id="cd220-107">If it is an external user, make sure that their invitation has been accepted.</span></span>
- <span data-ttu-id="cd220-108">Si el usuario existe en el grupo permisos, asegúrese de que la dirección de correo electrónico es correcta.</span><span class="sxs-lookup"><span data-stu-id="cd220-108">If the user does exist in the permissions group, make sure the email address is correct.</span></span>
- <span data-ttu-id="cd220-109">Si no se establece aquí la dirección de correo electrónico de los usuarios, cree una alerta de ejemplo para ese usuario que fuerce la sincronización de esa cuenta de usuario de los perfiles de usuario de SharePoint con esta colección de sitios.</span><span class="sxs-lookup"><span data-stu-id="cd220-109">If the users email address is not set here, then create a sample alert for that user which forces the sync of that user account from User Profiles of SharePoint to this site collection.</span></span>
 
2. <span data-ttu-id="cd220-110">El correo electrónico de flujos de trabajo se envía a los administradores de la colección de sitios, pero no a otros usuarios, y ve el error \*\*http prohibido a <spam> <spam>. \*\* <spam> <spam></span><span class="sxs-lookup"><span data-stu-id="cd220-110">Email from Workflows are sent to the site collection administrators but not to other users and see the error **HTTP Forbidden to <spam><spam>https://URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**<spam><spam>.</span></span>
 

<span data-ttu-id="cd220-111">Consulte [acceso denegado cuando se envía un correo electrónico a grupos](https://docs.microsoft.com/sharepoint/support/server-admin/access-denied-when-send-an-email-to-groups).</span><span class="sxs-lookup"><span data-stu-id="cd220-111">See [Access Denied when sent email to groups](https://docs.microsoft.com/sharepoint/support/server-admin/access-denied-when-send-an-email-to-groups).</span></span>

<span data-ttu-id="cd220-112">Compruebe también que la característica de colección de sitios del **modo de bloqueo de permisos de usuario de acceso limitado** no está activa.</span><span class="sxs-lookup"><span data-stu-id="cd220-112">Also, verify that the **Limited-access user permission lockdown mode** site collection feature is not active.</span></span>

## <a name="related-topics"></a><span data-ttu-id="cd220-113">Temas relacionados</span><span class="sxs-lookup"><span data-stu-id="cd220-113">Related topics</span></span>
- [<span data-ttu-id="cd220-114">Crear flujo</span><span class="sxs-lookup"><span data-stu-id="cd220-114">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="cd220-115">Flujo y SharePoint</span><span class="sxs-lookup"><span data-stu-id="cd220-115">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


