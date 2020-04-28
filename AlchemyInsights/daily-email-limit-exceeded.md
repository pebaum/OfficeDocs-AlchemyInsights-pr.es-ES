---
title: Se superó el límite diario de correo electrónico. El flujo de trabajo está suspendido.
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1227"
ms.openlocfilehash: 5a510f1137c7c49cd1de3d3fd2a470759e37ba1e
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/27/2020
ms.locfileid: "43908721"
---
# <a name="daily-email-limit-exceeded-workflow-is-suspended"></a><span data-ttu-id="4aa20-103">Se superó el límite diario de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="4aa20-103">Daily email Limit Exceeded.</span></span> <span data-ttu-id="4aa20-104">El flujo de trabajo está suspendido.</span><span class="sxs-lookup"><span data-stu-id="4aa20-104">Workflow is suspended.</span></span>

<span data-ttu-id="4aa20-105">Este error puede recibirse en las siguientes situaciones:</span><span class="sxs-lookup"><span data-stu-id="4aa20-105">This error may be received in the following scenarios:</span></span>

- <span data-ttu-id="4aa20-106">Tiene un flujo de trabajo en SharePoint Online que usa el tipo de plataforma de flujo de trabajo de SharePoint 2010 o SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="4aa20-106">You have a workflow in SharePoint Online that's using the SharePoint 2010 or SharePoint 2013 workflow platform type.</span></span>
- <span data-ttu-id="4aa20-107">El flujo de trabajo está configurado para enviar un mensaje de correo electrónico personalizado a más de 200 usuarios a la vez, más de 10.000 destinatarios por día o más de 30 mensajes por minuto.</span><span class="sxs-lookup"><span data-stu-id="4aa20-107">The workflow is configured to send a custom email message to more than 200 users at a time, more than 10,000 recipients per day, or more than 30 messages per minute.</span></span>
- <span data-ttu-id="4aa20-108">Cuando ejecuta el flujo de trabajo, el mensaje de correo electrónico no se envía y observa el comportamiento siguiente:</span><span class="sxs-lookup"><span data-stu-id="4aa20-108">When you run the workflow, the email message isn't sent, and you notice the following behavior:</span></span>
    - <span data-ttu-id="4aa20-109">Para un flujo de trabajo que usa el tipo de plataforma 2013 de SharePoint, vaya a la página de **Estado del flujo de trabajo** .</span><span class="sxs-lookup"><span data-stu-id="4aa20-109">For a workflow using the SharePoint 2013 platform type, you browse to the **Workflow Status** page.</span></span> <span data-ttu-id="4aa20-110">En la página estado del flujo de trabajo, el **estado interno** se establece en **iniciado**y el globo de información muestra **no se puede enviar a un destinatario**.</span><span class="sxs-lookup"><span data-stu-id="4aa20-110">On the Workflow Status page, the **Internal Status** is set to **Started**, and the information balloon displays **Unable to send to a recipient**.</span></span>

<span data-ttu-id="4aa20-111">Para solucionar este problema, configure el flujo de trabajo para que envíe mensajes de correo electrónico sin superar los [límites del remitente de Exchange Online](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#recipientlimits).</span><span class="sxs-lookup"><span data-stu-id="4aa20-111">To work around this issue, configure your workflow to send email messages without exceeding the [Exchange Online sender limits](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#recipientlimits).</span></span> <span data-ttu-id="4aa20-112">Por ejemplo, use una pausa en el flujo de trabajo, envíe el correo electrónico a un grupo de Microsoft 365, a un grupo de distribución o a un grupo de seguridad habilitado para correo, o envíe el mensaje a menos de 200 destinatarios a la vez.</span><span class="sxs-lookup"><span data-stu-id="4aa20-112">For example, use a pause in the workflow, send the email to an Microsoft 365 group, a distribution group or mail enabled security group, or send the message to fewer than 200 recipients at a time.</span></span>


<span data-ttu-id="4aa20-113">Para obtener más información, vea el siguiente [artículo](https://support.microsoft.com/help/3150442/daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or).</span><span class="sxs-lookup"><span data-stu-id="4aa20-113">For more information, see the following [article](https://support.microsoft.com/help/3150442/daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or).</span></span>

## <a name="related-topics"></a><span data-ttu-id="4aa20-114">Temas relacionados</span><span class="sxs-lookup"><span data-stu-id="4aa20-114">Related topics</span></span>
- [<span data-ttu-id="4aa20-115">Crear flujo</span><span class="sxs-lookup"><span data-stu-id="4aa20-115">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="4aa20-116">Flujo y SharePoint</span><span class="sxs-lookup"><span data-stu-id="4aa20-116">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 