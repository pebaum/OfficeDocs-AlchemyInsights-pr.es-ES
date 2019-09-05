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
# <a name="sharepoint-online-throttling"></a><span data-ttu-id="43ca8-102">Limitación de SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="43ca8-102">SharePoint Online Throttling</span></span>

<span data-ttu-id="43ca8-103">Es posible que los usuarios reciban un error de un servidor de 503 al intentar navegar a sitios de SharePoint o de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="43ca8-103">Users may receive a 503 server is busy error when attempting to navigate to SharePoint or OneDrive sites.</span></span> 

<span data-ttu-id="43ca8-104">Este error puede deberse a una limitación en el servicio de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="43ca8-104">This error can be caused by throttling within the SharePoint service.</span></span> <span data-ttu-id="43ca8-105">SharePoint Online utiliza limitación para mantener un rendimiento óptimo y la confiabilidad del servicio SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="43ca8-105">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="43ca8-106">La limitación se llama el número de acciones de usuario o simultáneos (por secuencia de comandos o código) para evitar el uso excesivo de los recursos.</span><span class="sxs-lookup"><span data-stu-id="43ca8-106">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> <span data-ttu-id="43ca8-107">Si limita a obtener, 99% de tiempo es debido a código personalizado.</span><span class="sxs-lookup"><span data-stu-id="43ca8-107">If you do get throttled, 99% of the time it is because of custom code.</span></span>

<span data-ttu-id="43ca8-108">Para obtener más información sobre la limitación de peticiones, consulte [limitar o bloqueado en SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span><span class="sxs-lookup"><span data-stu-id="43ca8-108">For more information on throttling see, [Avoid getting throttled or blocked in SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span></span>

<span data-ttu-id="43ca8-109">Si cree que este error no está relacionado con la limitación, puede comprobar si hay mantenimiento activo en su espacio empresarial desplazándose al [centro de mensajes](https://portal.office.com/adminportal/home#/MessageCenter).</span><span class="sxs-lookup"><span data-stu-id="43ca8-109">If you believe this error is unrelated to throttling, you can check if there is active maintenance occurring on your tenant by navigating to the [Message center](https://portal.office.com/adminportal/home#/MessageCenter).</span></span>

 <span data-ttu-id="43ca8-110">Por último, asegúrese de visitar la página de [Estado del servicio](https://portal.office.com/adminportal/home#/servicehealth) para comprobar si hay algún asesor o incidente que pueda producirse.</span><span class="sxs-lookup"><span data-stu-id="43ca8-110">Finally, ensure you visit the [Service Health](https://portal.office.com/adminportal/home#/servicehealth) page to check for any advisories/incidents that may be occurring.</span></span>

