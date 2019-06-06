---
title: Introducción a SharePoint Online
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 7ae05f21-eb16-4d71-9e19-4f097eb100d2
ms.openlocfilehash: a44b2c7b26895e09c24df772f1ada9a2e3483747
ms.sourcegitcommit: 241e21b6da226563bf70bdb1f5bad3d91c38cd2c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/05/2019
ms.locfileid: "34735999"
---
# <a name="workflows-in-sharepoint"></a><span data-ttu-id="a9d5c-102">Flujos de trabajo de SharePoint</span><span class="sxs-lookup"><span data-stu-id="a9d5c-102">Workflows in SharePoint</span></span>

<span data-ttu-id="a9d5c-103">Si los flujos de trabajo de SharePoint no envían correos electrónicos, es posible que su organización haya encontrado los límites del remitente de Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="a9d5c-103">If SharePoint workflows are not sending emails, your organization may have encountered the Exchange Online sender limits.</span></span>

<span data-ttu-id="a9d5c-104">El mensaje de error "el flujo de trabajo está suspendido" puede producirse si tiene uno de los siguientes elementos:</span><span class="sxs-lookup"><span data-stu-id="a9d5c-104">'Workflow is Suspended' error message may occur if you have one of the following items:</span></span>

- <span data-ttu-id="a9d5c-105">Tiene un flujo de trabajo en SharePoint Online que usa el tipo de plataforma de flujo de trabajo de SharePoint 2010 o SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="a9d5c-105">You have a workflow in SharePoint Online that's using the SharePoint 2010 or SharePoint 2013 workflow platform type.</span></span>

- <span data-ttu-id="a9d5c-106">El flujo de trabajo está configurado para enviar un mensaje de correo electrónico personalizado a más de 200 usuarios a la vez, más de 10.000 destinatarios por día o más de 30 mensajes por minuto.</span><span class="sxs-lookup"><span data-stu-id="a9d5c-106">The workflow is configured to send a custom email message to more than 200 users at a time, more than 10,000 recipients per day, or more than 30 messages per minute.</span></span>

<span data-ttu-id="a9d5c-107">Cuando ejecuta el flujo de trabajo, el mensaje de correo electrónico no se envía y observa el mensaje de error, el estado interno se establece en suspendido o no se puede enviar a un destinatario.</span><span class="sxs-lookup"><span data-stu-id="a9d5c-107">When you run the workflow, the email message isn't sent, and you notice the error message, Internal Status is set to Suspended or Unable to send to a recipient is displayed.</span></span>

<span data-ttu-id="a9d5c-108">Para más información, consulte el [artículo](https://support.office.com/en-us/article/-daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or-unable-to-send-to-a-recipient-error-in-a-sharepoint-online-workflow-89d02169-5fa6-4259-affc-73edb6ca9fb6?ui=en-US&amp;rs=en-US&amp;ad=US)siguiente.</span><span class="sxs-lookup"><span data-stu-id="a9d5c-108">For more information, please refer to the following [article](https://support.office.com/en-us/article/-daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or-unable-to-send-to-a-recipient-error-in-a-sharepoint-online-workflow-89d02169-5fa6-4259-affc-73edb6ca9fb6?ui=en-US&amp;rs=en-US&amp;ad=US).</span></span>

