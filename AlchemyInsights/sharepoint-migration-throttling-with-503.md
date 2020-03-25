---
title: Limitación de la migración de SharePoint con 503 errores
ms.author: pebaum
author: pebaum
ms.date: 8/8/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: ''
ms.custom:
- "9000136"
- "2541"
ms.openlocfilehash: 7e12c74d33e3cee7c626ad899a4e7f2f0a409bca
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931675"
---
# <a name="sharepoint-migration-throttling-with-503-errors"></a><span data-ttu-id="74016-102">Limitación de la migración de SharePoint con 503 errores</span><span class="sxs-lookup"><span data-stu-id="74016-102">SharePoint migration throttling with 503 errors</span></span>

<span data-ttu-id="74016-103">**Importante**: muchos clientes de SharePoint Online y OneDrive ejecutan aplicaciones críticas para la empresa en el servicio que se ejecutan en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="74016-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="74016-104">Estas incluyen la migración de contenido, la prevención de pérdida de datos (DLP) y soluciones de copia de seguridad.</span><span class="sxs-lookup"><span data-stu-id="74016-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="74016-105">En estos tiempos sin precedente, aplicamos las medidas necesarias para garantizar que los servicios de SharePoint Online y OneDrive permanezcan altamente disponibles y confiables para los usuarios que dependen del servicio más que nunca en escenarios de trabajo remoto.</span><span class="sxs-lookup"><span data-stu-id="74016-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="74016-106">Para apoyar este objetivo, hemos implementado límites más estrictos para las aplicaciones en segundo plano (como la migración, DLP y las soluciones de copia de seguridad) durante las horas de la semana laboral.</span><span class="sxs-lookup"><span data-stu-id="74016-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="74016-107">Se anticipa que estas aplicaciones obtengan un rendimiento muy limitado durante estas horas.</span><span class="sxs-lookup"><span data-stu-id="74016-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="74016-108">Sin embargo, durante las horas de la noche y del fin de semana de la región, el servicio estará listo para procesar un volumen mucho más elevado de solicitudes de aplicaciones en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="74016-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="74016-109">**503 errores al migrar a SharePoint Online**</span><span class="sxs-lookup"><span data-stu-id="74016-109">**503 errors when migrating to SharePoint Online**</span></span>

<span data-ttu-id="74016-110">Parece que está migrando a SharePoint Online y recibiendo errores de 503.</span><span class="sxs-lookup"><span data-stu-id="74016-110">It appears you are migrating to SharePoint Online and receiving 503 errors.</span></span> <span data-ttu-id="74016-111">Siga los pasos que se indican a continuación para que podamos ayudarle tan pronto como sea posible.</span><span class="sxs-lookup"><span data-stu-id="74016-111">Please follow the steps below so we may assist you as soon as possible.</span></span> 

1. <span data-ttu-id="74016-112">Haga clic en **contactar con soporte técnico**y, a continuación, en **nueva solicitud de servicio**.</span><span class="sxs-lookup"><span data-stu-id="74016-112">Click **Contact Support**, and then **New Service Request**.</span></span>
2. <span data-ttu-id="74016-113">Para el título y la descripción, escriba **limitar la migración de SharePoint con 503**.</span><span class="sxs-lookup"><span data-stu-id="74016-113">For the title and description, type **SharePoint Migration Throttling with 503**.</span></span>
3. <span data-ttu-id="74016-114">Una vez enviado el vale, actualícelo con la siguiente información:</span><span class="sxs-lookup"><span data-stu-id="74016-114">Once the ticket has been submitted, please update it with the following information:</span></span>
    - <span data-ttu-id="74016-115">La parte izquierda de la migración (por ejemplo, cuántos TBs?).</span><span class="sxs-lookup"><span data-stu-id="74016-115">How much left of migration (for example, how many TBs?).</span></span>
    - <span data-ttu-id="74016-116">Fecha de inicio y finalización de la migración.</span><span class="sxs-lookup"><span data-stu-id="74016-116">Migration start and end date.</span></span>
    - <span data-ttu-id="74016-117">Describir el lugar desde el que se va a migrar el contenido de, como SharePoint Server, cuadro, GDrive, recursos compartidos de archivos, etc.</span><span class="sxs-lookup"><span data-stu-id="74016-117">Describe where you are migrating your content from, such as SharePoint Server, Box, GDrive, File shares, etc..</span></span>
    - <span data-ttu-id="74016-118">Estimación del número de errores de limitación de peticiones (por ejemplo, la aceleración x por hora?) y el momento en que se produjo el límite.</span><span class="sxs-lookup"><span data-stu-id="74016-118">Estimate the number of throttling errors (for example, x throttle per hour?) and when did the throttling happen.</span></span>
    - <span data-ttu-id="74016-119">Qué herramienta de migración está usando (por ejemplo, SPMT o ShareGate).</span><span class="sxs-lookup"><span data-stu-id="74016-119">Which migration tool you are using (for example, SPMT or ShareGate).</span></span>


