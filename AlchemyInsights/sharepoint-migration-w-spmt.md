---
title: Migración de SharePoint con SPMT
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 9/18/19
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5300030"
- "2594"
ms.openlocfilehash: e7719d1fc6dda0d5bd340775219401dade2933fe
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931567"
---
# <a name="sharepoint-migration-with-spmt"></a><span data-ttu-id="81094-102">Migración de SharePoint con SPMT</span><span class="sxs-lookup"><span data-stu-id="81094-102">SharePoint Migration with SPMT</span></span>

<span data-ttu-id="81094-103">**Importante**: muchos clientes de SharePoint Online y OneDrive ejecutan aplicaciones críticas para la empresa en el servicio que se ejecutan en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="81094-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="81094-104">Estas incluyen la migración de contenido, la prevención de pérdida de datos (DLP) y soluciones de copia de seguridad.</span><span class="sxs-lookup"><span data-stu-id="81094-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="81094-105">En estos tiempos sin precedente, aplicamos las medidas necesarias para garantizar que los servicios de SharePoint Online y OneDrive permanezcan altamente disponibles y confiables para los usuarios que dependen del servicio más que nunca en escenarios de trabajo remoto.</span><span class="sxs-lookup"><span data-stu-id="81094-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="81094-106">Para apoyar este objetivo, hemos implementado límites más estrictos para las aplicaciones en segundo plano (como la migración, DLP y las soluciones de copia de seguridad) durante las horas de la semana laboral.</span><span class="sxs-lookup"><span data-stu-id="81094-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="81094-107">Se anticipa que estas aplicaciones obtengan un rendimiento muy limitado durante estas horas.</span><span class="sxs-lookup"><span data-stu-id="81094-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="81094-108">Sin embargo, durante las horas de la noche y del fin de semana de la región, el servicio estará listo para procesar un volumen mucho más elevado de solicitudes de aplicaciones en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="81094-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="81094-109">**Herramienta de migración de SharePoint**</span><span class="sxs-lookup"><span data-stu-id="81094-109">**SharePoint Migration Tool**</span></span>

<span data-ttu-id="81094-110">Diseñada para usarse en migraciones que van desde el conjunto más pequeño de archivos a una migración empresarial a gran escala, la herramienta de migración de SharePoint le permitirá transferir la información a la nube y aprovechar las ventajas de la colaboración, inteligencia y soluciones de seguridad con Office 365.</span><span class="sxs-lookup"><span data-stu-id="81094-110">Designed to be used for migrations ranging from the smallest set of files to a large scale enterprise migration, the SharePoint Migration Tool will allow you to transfer your information to the cloud and take advantage of the newest collaboration, intelligence, and security solutions with Office 365.</span></span>

- [<span data-ttu-id="81094-111">Descargar e instalar la Herramienta de migración de SharePoint</span><span class="sxs-lookup"><span data-stu-id="81094-111">Download and install the SharePoint Migration Tool</span></span>](https://docs.microsoft.com/sharepointmigration/introducing-the-sharepoint-migration-tool)
- [<span data-ttu-id="81094-112">Solución de problemas y errores comunes de SPMT</span><span class="sxs-lookup"><span data-stu-id="81094-112">Troubleshooting common SPMT issues and errors</span></span>](https://docs.microsoft.com/sharepointmigration/troubleshooting-common-spmt-issues)
- [<span data-ttu-id="81094-113">Solucionar problemas de instalación de SPMT</span><span class="sxs-lookup"><span data-stu-id="81094-113">Troubleshooting SPMT installation issues</span></span>](https://docs.microsoft.com/sharepointmigration/spmt-install-issues#troubleshooting-spmt-installation-issues)
