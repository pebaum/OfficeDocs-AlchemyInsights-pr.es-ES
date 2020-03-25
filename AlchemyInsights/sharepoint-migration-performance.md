---
title: Rendimiento de la migración de SharePoint
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 686e8f18-b871-4dd2-864f-8562947ab583
ms.collection: Adm_O365
ms.custom:
- "5300030"
- "2700"
ms.openlocfilehash: 812444589d5a5bf766bbc6f466077d4ca829d79f
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932405"
---
# <a name="sharepoint-migration-performance"></a><span data-ttu-id="928de-102">Rendimiento de la migración de SharePoint</span><span class="sxs-lookup"><span data-stu-id="928de-102">SharePoint migration performance</span></span>

<span data-ttu-id="928de-103">**Importante**: muchos de los clientes de SharePoint Online y OneDrive ejecutan aplicaciones esenciales para la empresa en el servicio que ejecutan en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="928de-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="928de-104">Estas incluyen la migración de contenido, la prevención de pérdida de datos (DLP) y soluciones de copia de seguridad.</span><span class="sxs-lookup"><span data-stu-id="928de-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="928de-105">En estos tiempos sin precedente, aplicamos las medidas necesarias para garantizar que los servicios de SharePoint Online y OneDrive permanezcan altamente disponibles y confiables para los usuarios que dependen del servicio más que nunca en escenarios de trabajo remoto.</span><span class="sxs-lookup"><span data-stu-id="928de-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="928de-106">Para apoyar este objetivo, hemos implementado límites más estrictos para las aplicaciones en segundo plano (como la migración, DLP y las soluciones de copia de seguridad) durante las horas de la semana laboral.</span><span class="sxs-lookup"><span data-stu-id="928de-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="928de-107">Se anticipa que estas aplicaciones obtengan un rendimiento muy limitado durante estas horas.</span><span class="sxs-lookup"><span data-stu-id="928de-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="928de-108">Sin embargo, durante las horas de la noche y del fin de semana de la región, el servicio estará listo para procesar un volumen mucho más elevado de solicitudes de aplicaciones en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="928de-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="928de-109">**Rendimiento de la migración**</span><span class="sxs-lookup"><span data-stu-id="928de-109">**Migration performance**</span></span>

<span data-ttu-id="928de-p103">El rendimiento de la migración puede verse afectado por la infraestructura de red, el tamaño de archivo, el tiempo de migración y la limitación. La comprensión de esto le ayudará a planear y maximizar la eficacia de la migración.</span><span class="sxs-lookup"><span data-stu-id="928de-p103">Migration performance can be impacted by network infrastructure, file size, migration time, and throttling. Understanding these will help you plan and maximize the efficiency of your migration.</span></span>

<span data-ttu-id="928de-112">Para obtener más información, visite los vínculos siguientes.</span><span class="sxs-lookup"><span data-stu-id="928de-112">For more information, please visit the links below.</span></span>

- [<span data-ttu-id="928de-113">Velocidad de migración de SharePoint Online y ODB</span><span class="sxs-lookup"><span data-stu-id="928de-113">Sharepoint Online and ODB Migration Speed</span></span>](https://docs.microsoft.com/sharepointmigration/sharepoint-online-and-onedrive-migration-speed)

- [<span data-ttu-id="928de-114">Evitar las limitaciones o los bloqueos en SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="928de-114">Avoid getting throttled or blocked in SharePoint Online</span></span>](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online)

- [<span data-ttu-id="928de-115">Descargar e instalar la Herramienta de migración de SharePoint</span><span class="sxs-lookup"><span data-stu-id="928de-115">Download and install the SharePoint Migration Tool</span></span>](https://docs.microsoft.com/sharepointmigration/introducing-the-sharepoint-migration-tool)
