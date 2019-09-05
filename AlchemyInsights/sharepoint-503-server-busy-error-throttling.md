---
title: Limitación de SharePoint Online
ms.author: pebaum
author: Techwriter40
ms.date: 9/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.openlocfilehash: d9e1400697b1e6435fea78703d2ecadc6733a57f
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/04/2019
ms.locfileid: "36751905"
---
# <a name="sharepoint-online-throttling"></a>Limitación de SharePoint Online

Es posible que los usuarios reciban un error de un servidor de 503 al intentar navegar a sitios de SharePoint o de OneDrive. 

Este error puede deberse a una limitación en el servicio de SharePoint. SharePoint Online utiliza limitación para mantener un rendimiento óptimo y la confiabilidad del servicio SharePoint Online. La limitación se llama el número de acciones de usuario o simultáneos (por secuencia de comandos o código) para evitar el uso excesivo de los recursos. Si limita a obtener, 99% de tiempo es debido a código personalizado.

Para obtener más información sobre la limitación de peticiones, consulte [limitar o bloqueado en SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).

Si cree que este error no está relacionado con la limitación, puede comprobar si hay mantenimiento activo en su espacio empresarial desplazándose al [centro de mensajes](https://portal.office.com/adminportal/home#/MessageCenter).

 Por último, asegúrese de visitar la página de [Estado del servicio](https://portal.office.com/adminportal/home#/servicehealth) para comprobar si hay algún asesor o incidente que pueda producirse.

