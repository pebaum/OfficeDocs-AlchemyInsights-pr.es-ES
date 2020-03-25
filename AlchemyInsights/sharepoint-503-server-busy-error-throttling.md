---
title: Limitación de SharePoint Online
ms.author: pebaum
author: pebaum
ms.date: 9/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.custom:
- "9000149"
- "1662"
- "3491"
ms.openlocfilehash: 59104ef96c95de4e4bc7744825245bdafba97d7c
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931243"
---
# <a name="sharepoint-online-throttling"></a><span data-ttu-id="e075e-102">Limitación de SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="e075e-102">SharePoint Online Throttling</span></span>

<span data-ttu-id="e075e-103">**Importante**: muchos clientes de SharePoint Online y OneDrive ejecutan aplicaciones críticas para la empresa en el servicio que se ejecutan en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="e075e-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="e075e-104">Estas incluyen la migración de contenido, la prevención de pérdida de datos (DLP) y soluciones de copia de seguridad.</span><span class="sxs-lookup"><span data-stu-id="e075e-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="e075e-105">En estos tiempos sin precedente, aplicamos las medidas necesarias para garantizar que los servicios de SharePoint Online y OneDrive permanezcan altamente disponibles y confiables para los usuarios que dependen del servicio más que nunca en escenarios de trabajo remoto.</span><span class="sxs-lookup"><span data-stu-id="e075e-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="e075e-106">Para apoyar este objetivo, hemos implementado límites más estrictos para las aplicaciones en segundo plano (como la migración, DLP y las soluciones de copia de seguridad) durante las horas de la semana laboral.</span><span class="sxs-lookup"><span data-stu-id="e075e-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="e075e-107">Se anticipa que estas aplicaciones obtengan un rendimiento muy limitado durante estas horas.</span><span class="sxs-lookup"><span data-stu-id="e075e-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="e075e-108">Sin embargo, durante las horas de la noche y del fin de semana de la región, el servicio estará listo para procesar un volumen mucho más elevado de solicitudes de aplicaciones en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="e075e-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="e075e-109">**503 el servidor está ocupado error**</span><span class="sxs-lookup"><span data-stu-id="e075e-109">**503 server is busy error**</span></span>

<span data-ttu-id="e075e-110">Es posible que los usuarios reciban un error de un servidor de 503 al intentar navegar a sitios de SharePoint o de OneDrive.</span><span class="sxs-lookup"><span data-stu-id="e075e-110">Users may receive a 503 server is busy error when attempting to navigate to SharePoint or OneDrive sites.</span></span> 

<span data-ttu-id="e075e-111">Este error puede deberse a una limitación en el servicio de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="e075e-111">This error can be caused by throttling within the SharePoint service.</span></span> <span data-ttu-id="e075e-112">SharePoint Online utiliza limitación para mantener un rendimiento óptimo y la confiabilidad del servicio SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="e075e-112">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="e075e-113">La limitación se llama el número de acciones de usuario o simultáneos (por secuencia de comandos o código) para evitar el uso excesivo de los recursos.</span><span class="sxs-lookup"><span data-stu-id="e075e-113">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> 

<span data-ttu-id="e075e-114">Para obtener más información sobre la limitación de peticiones, consulte [limitar o bloqueado en SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span><span class="sxs-lookup"><span data-stu-id="e075e-114">For more information on throttling see, [Avoid getting throttled or blocked in SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span></span>

<span data-ttu-id="e075e-115">Si cree que este error no está relacionado con la limitación, puede comprobar si hay mantenimiento activo en su espacio empresarial desplazándose al [centro de mensajes](https://portal.office.com/adminportal/home#/MessageCenter).</span><span class="sxs-lookup"><span data-stu-id="e075e-115">If you believe this error is unrelated to throttling, you can check if there is active maintenance occurring on your tenant by navigating to the [Message center](https://portal.office.com/adminportal/home#/MessageCenter).</span></span>

 <span data-ttu-id="e075e-116">Por último, asegúrese de visitar la página de [Estado del servicio](https://portal.office.com/adminportal/home#/servicehealth) para comprobar si hay algún asesor o incidente que pueda producirse.</span><span class="sxs-lookup"><span data-stu-id="e075e-116">Finally, ensure you visit the [Service Health](https://portal.office.com/adminportal/home#/servicehealth) page to check for any advisories/incidents that may be occurring.</span></span>

