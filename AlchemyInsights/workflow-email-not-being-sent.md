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
ms.openlocfilehash: 261fe1b1bc815dd4ad568051cfefad1e214b957e
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36530907"
---
# <a name="workflow-email-is-not-being-sent-for-a-sharepoint-list-or-library"></a><span data-ttu-id="cb464-102">El correo electrónico de flujo de trabajo no se envía a una lista o biblioteca de SharePoint</span><span class="sxs-lookup"><span data-stu-id="cb464-102">Workflow email is not being sent for a SharePoint list or library</span></span>

1. <span data-ttu-id="cb464-103">El correo electrónico de los flujos de trabajo no se envía a todos los usuarios o solo a usuarios específicos, o Ve el error **no se puede enviar el mensaje de correo electrónico. Asegúrese de que el correo electrónico tiene un destinatario válido**.</span><span class="sxs-lookup"><span data-stu-id="cb464-103">Email from workflows are not sent to all users or only specific users, or you see the error **The e-mail message cannot be sent. Make sure the e-mail has a valid recipient**.</span></span>

    <span data-ttu-id="cb464-104">Compruebe si el usuario existe en el grupo de permisos **todos los usuarios** (lista de información del usuario) para esa colección de sitios.</span><span class="sxs-lookup"><span data-stu-id="cb464-104">Check if the user exist in the **All People** permissions group (user information list) for that site collection.</span></span>  <span data-ttu-id="cb464-105">¿Dirección URL directa de<tenant>ejemplo:<sitename>https://. SharePoint.com/sites//_layouts/15/People.aspx? MembershipGroupId = 0</span><span class="sxs-lookup"><span data-stu-id="cb464-105">Sample direct URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx?MembershipGroupId=0</span></span>

    - <span data-ttu-id="cb464-106">Si el usuario no existe, asegúrese de que el usuario haya iniciado sesión en la página.</span><span class="sxs-lookup"><span data-stu-id="cb464-106">If the user does not exist, make sure the user is signed into the page.</span></span> 
    - <span data-ttu-id="cb464-107">Si es un usuario externo, asegúrese de que su invitación se ha aceptado.</span><span class="sxs-lookup"><span data-stu-id="cb464-107">If it is an external user, make sure that their invitation has been accepted.</span></span>
    - <span data-ttu-id="cb464-108">Si el usuario existe en el grupo permisos, asegúrese de que la dirección de correo electrónico es correcta.</span><span class="sxs-lookup"><span data-stu-id="cb464-108">If the user does exist in the permissions group, make sure the email address is correct.</span></span>
    - <span data-ttu-id="cb464-109">Si no se establece aquí la dirección de correo electrónico de los usuarios, cree una alerta de ejemplo para ese usuario que fuerce la sincronización de esa cuenta de usuario de los perfiles de usuario de SharePoint con esta colección de sitios.</span><span class="sxs-lookup"><span data-stu-id="cb464-109">If the users email address is not set here, then create a sample alert for that user which forces the sync of that user account from User Profiles of SharePoint to this site collection.</span></span>
 
2. <span data-ttu-id="cb464-110">El correo electrónico de los flujos de trabajo se envía a los administradores de la colección de sitios, pero no a otros usuarios, y ve el error **http prohibido a <span>https:</span>//URL/_vti_bin/Client.XVC.SP.Utilities.Utility.sendEmail**.</span><span class="sxs-lookup"><span data-stu-id="cb464-110">Email from workflows are sent to the site collection administrators but not to other users and see the error **HTTP Forbidden to <span>https:</span>//URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**.</span></span>
 

    <span data-ttu-id="cb464-111">Vea [acceso denegado cuando se envía un correo electrónico a un grupo de SharePoint](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).</span><span class="sxs-lookup"><span data-stu-id="cb464-111">See [Access Denied when you send an email to a SharePoint group](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).</span></span>

    <span data-ttu-id="cb464-112">Compruebe también que la característica de colección de sitios del **modo de bloqueo de permisos de usuario de acceso limitado** no está activa.</span><span class="sxs-lookup"><span data-stu-id="cb464-112">Also, verify that the **Limited-access user permission lockdown mode** site collection feature is not active.</span></span>


## <a name="related-topics"></a><span data-ttu-id="cb464-113">Temas relacionados</span><span class="sxs-lookup"><span data-stu-id="cb464-113">Related topics</span></span>
<span data-ttu-id="cb464-114">¿Desea probar Microsoft Flow en SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="cb464-114">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="cb464-115">Crear flujo</span><span class="sxs-lookup"><span data-stu-id="cb464-115">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="cb464-116">Flujo y SharePoint</span><span class="sxs-lookup"><span data-stu-id="cb464-116">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


