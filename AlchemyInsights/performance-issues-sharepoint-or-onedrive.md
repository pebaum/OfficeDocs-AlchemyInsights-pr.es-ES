---
title: 'Problemas de rendimiento: SharePoint o OneDrive'
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1133"
- "2397"
- "2418"
- "5200018"
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.openlocfilehash: aecbf4043c6456ece73f7deed6b068040f0691a2
ms.sourcegitcommit: 0fb89d8106fe409ab1b78e50f5357ffc2252f7c7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/17/2019
ms.locfileid: "40068436"
---
# <a name="sharepoint-or-onedrive-slow-inaccessible-or-unavailable-for-multiple-users"></a>SharePoint o OneDrive es lento, inaccesible o no disponible para varios usuarios

SharePoint o OneDrive puede ser lento, inaccesible o no disponible, o puede mostrar los errores servicio no disponible o 503, por varios motivos:
  
- Si el sitio de SharePoint o de OneDrive es lento o se retrasa para varios usuarios, es posible que haya un problema de servicio temporal en el que los usuarios experimenten retrasos intermitentes o errores de navegación al obtener acceso a sitios de SharePoint o contenido de OneDrive. Compruebe el [Panel de estado del servicio](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) para ver si su organización se ve afectada.
  
- Es posible que los usuarios reciban un error de un *servidor de 503* al intentar navegar a sitios de SharePoint o de OneDrive. Este error puede deberse a una limitación en el servicio de SharePoint. SharePoint Online utiliza limitación para mantener un rendimiento óptimo y la confiabilidad del servicio SharePoint Online. La limitación se llama el número de acciones de usuario o simultáneos (por secuencia de comandos o código) para evitar el uso excesivo de los recursos. Para obtener más información sobre la limitación de peticiones, consulte [limitar o bloqueado en SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).

- Si experimenta un rendimiento lento con un sitio o página de SharePoint **clásico** o **moderno** , use la [herramienta de diagnóstico de páginas](https://aka.ms/perftool) para analizar las páginas.
  
- Si sigue experimentando un rendimiento lento general, revise los recursos que se encuentra en la parte inferior de este artículo: [Introducción al ajuste del rendimiento de SharePoint Online](https://go.microsoft.com/fwlink/?linkid=2024334) .
  