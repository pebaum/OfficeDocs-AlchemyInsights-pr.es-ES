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
ms.openlocfilehash: 9a8d72a01ed35794fcab370b48bbb189663d3396
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/04/2019
ms.locfileid: "34718763"
---
# <a name="workflows-in-sharepoint"></a>Flujos de trabajo de SharePoint

<p>Si los flujos de trabajo de SharePoint no envían correos electrónicos, es posible que su organización haya encontrado los límites del remitente de Exchange Online.&nbsp;</p> <p>El mensaje de error "el flujo de trabajo está suspendido" puede producirse si tiene uno de los siguientes elementos:</p> <ul> <li>Tiene un flujo de trabajo en SharePoint Online que usa el tipo de plataforma de flujo de trabajo de SharePoint 2010 o SharePoint 2013.</li> <li>El flujo de trabajo está configurado para enviar un mensaje de correo electrónico personalizado a más de 200 usuarios a la vez, más de 10.000 destinatarios por día o más de 30 mensajes por minuto.</li> <li>Cuando ejecuta el flujo de trabajo, el mensaje de correo electrónico no se envía y observa el mensaje de error, el <strong>estado interno se establece en suspendido</strong> o <strong>no se puede enviar a un destinatario</strong> .</li> </ul> <p>Para más información, consulte el <a href="https://support.office.com/en-us/article/-daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or-unable-to-send-to-a-recipient-error-in-a-sharepoint-online-workflow-89d02169-5fa6-4259-affc-73edb6ca9fb6?ui=en-US&amp;rs=en-US&amp;ad=US">artículo</a>siguiente.</p>

