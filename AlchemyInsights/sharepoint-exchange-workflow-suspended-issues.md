---
title: Introducción a SharePoint Online
ms.author: pebaum
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 7ae05f21-eb16-4d71-9e19-4f097eb100d2
ms.openlocfilehash: 4c0220dd2535a1ef41aeef99e2bfc3fe28bac03a
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/04/2019
ms.locfileid: "36751689"
---
# <a name="workflows-in-sharepoint"></a>Flujos de trabajo de SharePoint

Si los flujos de trabajo de SharePoint no envían correos electrónicos, es posible que su organización haya encontrado los límites del remitente de Exchange Online.

El mensaje de error "el flujo de trabajo está suspendido" puede producirse si tiene uno de los siguientes elementos:

- Tiene un flujo de trabajo en SharePoint Online que usa el tipo de plataforma de flujo de trabajo de SharePoint 2010 o SharePoint 2013.

- El flujo de trabajo está configurado para enviar un mensaje de correo electrónico personalizado a más de 200 usuarios a la vez, más de 10.000 destinatarios por día o más de 30 mensajes por minuto.

Cuando ejecuta el flujo de trabajo, el mensaje de correo electrónico no se envía y observa el mensaje de error, el estado interno se establece en suspendido o no se puede enviar a un destinatario.

Para más información, consulte el [artículo](https://docs.microsoft.com/sharepoint/support/workflows/configured-workflow-fails-running)siguiente.

