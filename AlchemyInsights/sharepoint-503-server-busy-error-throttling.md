---
title: Limitación de SharePoint Online
ms.author: kirks
author: Techwriter40
ms.date: 9/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.openlocfilehash: b157ce22962ac1616d6e9b3a5475edaec7fed9f7
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/07/2019
ms.locfileid: "34761275"
---
# <a name="sharepoint-online-throttling"></a>Limitación de SharePoint Online

Es posible que los usuarios reciban un error de un servidor de 503 al intentar navegar a sitios de SharePoint o de OneDrive. 

Este error puede deberse a una limitación en el servicio de SharePoint. SharePoint Online utiliza limitación para mantener un rendimiento óptimo y la confiabilidad del servicio SharePoint Online. La limitación se llama el número de acciones de usuario o simultáneos (por secuencia de comandos o código) para evitar el uso excesivo de los recursos. Si limita a obtener, 99% de tiempo es debido a código personalizado.

Para obtener más información sobre la limitación de peticiones, consulte [limitar o bloqueado en SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).

Si cree que este error no está relacionado con la limitación, puede comprobar si hay mantenimiento activo en su espacio empresarial desplazándose al [centro de mensajes](https://portal.office.com/adminportal/home#/MessageCenter).

 Por último, asegúrese de visitar la página de [Estado del servicio](https://portal.office.com/adminportal/home#/servicehealth) para comprobar si hay algún asesor o incidente que pueda producirse.
