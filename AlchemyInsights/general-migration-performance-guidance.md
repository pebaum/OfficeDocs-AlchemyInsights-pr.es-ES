---
title: Instrucciones de rendimiento de la migración general
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
- "3179"
ms.openlocfilehash: 10a0069c41d2e5128b2592425d815364a83b730f
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932495"
---
# <a name="general-migration-performance-guidance"></a><span data-ttu-id="1c695-102">Instrucciones de rendimiento de la migración general</span><span class="sxs-lookup"><span data-stu-id="1c695-102">General migration performance guidance</span></span>

<span data-ttu-id="1c695-103">**Importante**: muchos de los clientes de SharePoint Online y OneDrive ejecutan aplicaciones esenciales para la empresa en el servicio que ejecutan en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="1c695-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="1c695-104">Estas incluyen la migración de contenido, la prevención de pérdida de datos (DLP) y soluciones de copia de seguridad.</span><span class="sxs-lookup"><span data-stu-id="1c695-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="1c695-105">En estos tiempos sin precedente, aplicamos las medidas necesarias para garantizar que los servicios de SharePoint Online y OneDrive permanezcan altamente disponibles y confiables para los usuarios que dependen del servicio más que nunca en escenarios de trabajo remoto.</span><span class="sxs-lookup"><span data-stu-id="1c695-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="1c695-106">Para apoyar este objetivo, hemos implementado límites más estrictos para las aplicaciones en segundo plano (como la migración, DLP y las soluciones de copia de seguridad) durante las horas de la semana laboral.</span><span class="sxs-lookup"><span data-stu-id="1c695-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="1c695-107">Se anticipa que estas aplicaciones obtengan un rendimiento muy limitado durante estas horas.</span><span class="sxs-lookup"><span data-stu-id="1c695-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="1c695-108">Sin embargo, durante las horas de la noche y del fin de semana de la región, el servicio estará listo para procesar un volumen mucho más elevado de solicitudes de aplicaciones en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="1c695-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="1c695-109">**Instrucciones de rendimiento de la migración**</span><span class="sxs-lookup"><span data-stu-id="1c695-109">**Migration performance guidance**</span></span>

<span data-ttu-id="1c695-p103">El rendimiento de la migración puede verse afectado por la infraestructura de red, el tamaño de archivo, el tiempo de migración y la limitación. La comprensión de esto le ayudará a planear y maximizar la eficacia de la migración.</span><span class="sxs-lookup"><span data-stu-id="1c695-p103">Migration performance can be impacted by network infrastructure, file size, migration time, and throttling. Understanding these will help you plan and maximize the efficiency of your migration.</span></span>

- [<span data-ttu-id="1c695-112">Instrucciones de rendimiento de la migración general</span><span class="sxs-lookup"><span data-stu-id="1c695-112">General migration performance guidance</span></span>](https://docs.microsoft.com/sharepointmigration/sharepoint-online-and-onedrive-migration-speed)
