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
# <a name="daily-email-limit-exceeded-workflow-is-suspended"></a>Se superó el límite diario de correo electrónico. El flujo de trabajo está suspendido.

Este error puede recibirse en las siguientes situaciones:

- Tiene un flujo de trabajo en SharePoint Online que usa el tipo de plataforma de flujo de trabajo de SharePoint 2010 o SharePoint 2013.
- El flujo de trabajo está configurado para enviar un mensaje de correo electrónico personalizado a más de 200 usuarios a la vez, más de 10.000 destinatarios por día o más de 30 mensajes por minuto.
- Cuando ejecuta el flujo de trabajo, el mensaje de correo electrónico no se envía y observa el comportamiento siguiente:
    - Para un flujo de trabajo que usa el tipo de plataforma 2013 de SharePoint, vaya a la página de **Estado del flujo de trabajo** . En la página estado del flujo de trabajo, el **estado interno** se establece en **iniciado**y el globo de información muestra **no se puede enviar a un destinatario**.

Para solucionar este problema, configure el flujo de trabajo para que envíe mensajes de correo electrónico sin superar los [límites del remitente de Exchange Online](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#recipientlimits). Por ejemplo, use una pausa en el flujo de trabajo, envíe el correo electrónico a un grupo de Microsoft 365, a un grupo de distribución o a un grupo de seguridad habilitado para correo, o envíe el mensaje a menos de 200 destinatarios a la vez.


Para obtener más información, vea el siguiente [artículo](https://support.microsoft.com/help/3150442/daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or).

## <a name="related-topics"></a>Temas relacionados
- [Crear flujo](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [Flujo y SharePoint](https://flow.microsoft.com/blog/sharepoint-and-flow/) 