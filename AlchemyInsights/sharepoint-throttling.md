---
title: Limitación de SharePoint Online
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.openlocfilehash: 9af4f09d50992c04a1f3d5a164093049a3ec3517
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931459"
---
# <a name="sharepoint-online-throttling"></a><span data-ttu-id="63e42-102">Limitación de SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="63e42-102">SharePoint Online throttling</span></span>

<span data-ttu-id="63e42-103">**Importante**: muchos clientes de SharePoint Online y OneDrive ejecutan aplicaciones críticas para la empresa en el servicio que se ejecutan en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="63e42-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="63e42-104">Estas incluyen la migración de contenido, la prevención de pérdida de datos (DLP) y soluciones de copia de seguridad.</span><span class="sxs-lookup"><span data-stu-id="63e42-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="63e42-105">En estos tiempos sin precedente, aplicamos las medidas necesarias para garantizar que los servicios de SharePoint Online y OneDrive permanezcan altamente disponibles y confiables para los usuarios que dependen del servicio más que nunca en escenarios de trabajo remoto.</span><span class="sxs-lookup"><span data-stu-id="63e42-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="63e42-106">Para apoyar este objetivo, hemos implementado límites más estrictos para las aplicaciones en segundo plano (como la migración, DLP y las soluciones de copia de seguridad) durante las horas de la semana laboral.</span><span class="sxs-lookup"><span data-stu-id="63e42-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="63e42-107">Se anticipa que estas aplicaciones obtengan un rendimiento muy limitado durante estas horas.</span><span class="sxs-lookup"><span data-stu-id="63e42-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="63e42-108">Sin embargo, durante las horas de la noche y del fin de semana de la región, el servicio estará listo para procesar un volumen mucho más elevado de solicitudes de aplicaciones en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="63e42-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="63e42-109">**Limitación de SharePoint Online**</span><span class="sxs-lookup"><span data-stu-id="63e42-109">**SharePoint Online throttling**</span></span>

<span data-ttu-id="63e42-110">SharePoint Online utiliza limitación para mantener un rendimiento óptimo y la confiabilidad del servicio SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="63e42-110">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="63e42-111">La limitación se llama el número de acciones de usuario o simultáneos (por secuencia de comandos o código) para evitar el uso excesivo de los recursos.</span><span class="sxs-lookup"><span data-stu-id="63e42-111">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> <span data-ttu-id="63e42-112">Para obtener más información, vea los siguientes vínculos.</span><span class="sxs-lookup"><span data-stu-id="63e42-112">For more information, please visit the links below.</span></span>

- [<span data-ttu-id="63e42-113">Evitar las limitaciones o los bloqueos en SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="63e42-113">Avoid getting throttled or blocked in SharePoint Online</span></span>](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online)

- [<span data-ttu-id="63e42-114">Migración de datos y limitación de SPO</span><span class="sxs-lookup"><span data-stu-id="63e42-114">Data Migration and SPO Throttling </span></span>](https://blogs.technet.microsoft.com/sposupport/2017/08/12/data-migration-and-spo-service-throttling/)

- [<span data-ttu-id="63e42-115">Velocidad de migración de SharePoint Online y OneDrive</span><span class="sxs-lookup"><span data-stu-id="63e42-115">SharePoint Online and OneDrive Migration Speed</span></span>](https://docs.microsoft.com/sharepointmigration/sharepoint-online-and-onedrive-migration-speed)

 - [<span data-ttu-id="63e42-116">Controlar la limitación de SharePoint Online con retroceso exponencial</span><span class="sxs-lookup"><span data-stu-id="63e42-116">Handle SharePoint Online throttling by using exponential back off</span></span>](https://docs.microsoft.com/sharepoint/dev/solution-guidance/handle-sharepoint-online-throttling-by-using-exponential-back-off)

- [<span data-ttu-id="63e42-117">Planeamiento de capacidad y pruebas de carga en SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="63e42-117">Capacity planning and load testing SharePoint Online</span></span>](https://docs.microsoft.com/office365/enterprise/capacity-planning-and-load-testing-sharepoint-online)

