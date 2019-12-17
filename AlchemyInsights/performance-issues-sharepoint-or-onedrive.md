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
# <a name="sharepoint-or-onedrive-slow-inaccessible-or-unavailable-for-multiple-users"></a><span data-ttu-id="e5624-102">SharePoint o OneDrive es lento, inaccesible o no disponible para varios usuarios</span><span class="sxs-lookup"><span data-stu-id="e5624-102">SharePoint or OneDrive slow, inaccessible, or unavailable for multiple users</span></span>

<span data-ttu-id="e5624-103">SharePoint o OneDrive puede ser lento, inaccesible o no disponible, o puede mostrar los errores servicio no disponible o 503, por varios motivos:</span><span class="sxs-lookup"><span data-stu-id="e5624-103">SharePoint or OneDrive may be slow, inaccessible, or unavailable, or may display service unavailable or 503 errors, for several reasons:</span></span>
  
- <span data-ttu-id="e5624-104">Si el sitio de SharePoint o de OneDrive es lento o se retrasa para varios usuarios, es posible que haya un problema de servicio temporal en el que los usuarios experimenten retrasos intermitentes o errores de navegación al obtener acceso a sitios de SharePoint o contenido de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="e5624-104">If your SharePoint or OneDrive site is slow or delayed for multiple users, there may be a temporary service issue where users experience intermittent delays or navigation errors when accessing SharePoint sites or OneDrive content.</span></span> <span data-ttu-id="e5624-105">Compruebe el [Panel de estado del servicio](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) para ver si su organización se ve afectada.</span><span class="sxs-lookup"><span data-stu-id="e5624-105">Check the [Service health dashboard](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) to see if your organization is impacted.</span></span>
  
- <span data-ttu-id="e5624-106">Es posible que los usuarios reciban un error de un *servidor de 503* al intentar navegar a sitios de SharePoint o de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="e5624-106">Users may receive a *503 server is busy* error when attempting to navigate to SharePoint or OneDrive sites.</span></span> <span data-ttu-id="e5624-107">Este error puede deberse a una limitación en el servicio de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="e5624-107">This error can be caused by throttling within the SharePoint service.</span></span> <span data-ttu-id="e5624-108">SharePoint Online utiliza limitación para mantener un rendimiento óptimo y la confiabilidad del servicio SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="e5624-108">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="e5624-109">La limitación se llama el número de acciones de usuario o simultáneos (por secuencia de comandos o código) para evitar el uso excesivo de los recursos.</span><span class="sxs-lookup"><span data-stu-id="e5624-109">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> <span data-ttu-id="e5624-110">Para obtener más información sobre la limitación de peticiones, consulte [limitar o bloqueado en SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span><span class="sxs-lookup"><span data-stu-id="e5624-110">For more information on throttling see, [Avoid getting throttled or blocked in SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span></span>

- <span data-ttu-id="e5624-111">Si experimenta un rendimiento lento con un sitio o página de SharePoint **clásico** o **moderno** , use la [herramienta de diagnóstico de páginas](https://aka.ms/perftool) para analizar las páginas.</span><span class="sxs-lookup"><span data-stu-id="e5624-111">If you experience slow performance with a **classic** or **modern** SharePoint site or page, utilize the [Page Diagnostic tool](https://aka.ms/perftool) to analyze the pages.</span></span>
  
- <span data-ttu-id="e5624-112">Si sigue experimentando un rendimiento lento general, revise los recursos que se encuentra en la parte inferior de este artículo: [Introducción al ajuste del rendimiento de SharePoint Online](https://go.microsoft.com/fwlink/?linkid=2024334) .</span><span class="sxs-lookup"><span data-stu-id="e5624-112">If you still experience general slow performance, please review the resources at the bottom of this article: [Introduction to performance tuning for SharePoint Online](https://go.microsoft.com/fwlink/?linkid=2024334)</span></span>
  