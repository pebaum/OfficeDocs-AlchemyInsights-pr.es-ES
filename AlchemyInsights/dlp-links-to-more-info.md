---
title: Más información sobre los problemas de DLP
ms.author: pebaum
author: pebaum
manager: laurawi
ms.audience: admin
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2447"
- "3200001"
ms.openlocfilehash: 6525cee0555f1ae67b7d4e32445b9a1537d4a804
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932711"
---
# <a name="information-about-dlp-issues"></a><span data-ttu-id="8044f-102">Información sobre problemas de DLP</span><span class="sxs-lookup"><span data-stu-id="8044f-102">Information about DLP issues</span></span>

<span data-ttu-id="8044f-103">**Importante**: muchos clientes de SharePoint Online y OneDrive ejecutan aplicaciones críticas para la empresa en el servicio que se ejecutan en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="8044f-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="8044f-104">Estas incluyen la migración de contenido, la prevención de pérdida de datos (DLP) y soluciones de copia de seguridad.</span><span class="sxs-lookup"><span data-stu-id="8044f-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="8044f-105">En estos tiempos sin precedente, aplicamos las medidas necesarias para garantizar que los servicios de SharePoint Online y OneDrive permanezcan altamente disponibles y confiables para los usuarios que dependen del servicio más que nunca en escenarios de trabajo remoto.</span><span class="sxs-lookup"><span data-stu-id="8044f-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="8044f-106">Para apoyar este objetivo, hemos implementado límites más estrictos para las aplicaciones en segundo plano (como la migración, DLP y las soluciones de copia de seguridad) durante las horas de la semana laboral.</span><span class="sxs-lookup"><span data-stu-id="8044f-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="8044f-107">Se anticipa que estas aplicaciones obtengan un rendimiento muy limitado durante estas horas.</span><span class="sxs-lookup"><span data-stu-id="8044f-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="8044f-108">Sin embargo, durante las horas de la noche y del fin de semana de la región, el servicio estará listo para procesar un volumen mucho más elevado de solicitudes de aplicaciones en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="8044f-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="8044f-109">**Información sobre la Directiva de DLP**</span><span class="sxs-lookup"><span data-stu-id="8044f-109">**Information on DLP policy**</span></span>

<span data-ttu-id="8044f-110">Con una directiva DLP, puede identificar, supervisar y proteger automáticamente la información confidencial en Office 365.</span><span class="sxs-lookup"><span data-stu-id="8044f-110">With a DLP policy, you can identify, monitor, and automatically protect sensitive information across Office 365.</span></span>

<span data-ttu-id="8044f-111">Para obtener más información, visite estos vínculos:</span><span class="sxs-lookup"><span data-stu-id="8044f-111">Please visit these links for more information:</span></span>

- [<span data-ttu-id="8044f-112">Información general sobre la prevención de pérdida de datos</span><span class="sxs-lookup"><span data-stu-id="8044f-112">Overview of data loss prevention</span></span>](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)
- [<span data-ttu-id="8044f-113">Información que buscan los tipos de información confidencial</span><span class="sxs-lookup"><span data-stu-id="8044f-113">What the sensitive information types look for</span></span>](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
- [<span data-ttu-id="8044f-114">Crear un tipo de información confidencial personalizado</span><span class="sxs-lookup"><span data-stu-id="8044f-114">Create a custom sensitive information type</span></span>](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type)
- [<span data-ttu-id="8044f-115">Enviar notificaciones de correo electrónico y Mostrar sugerencias de directivas</span><span class="sxs-lookup"><span data-stu-id="8044f-115">Send email notifications and show policy tips</span></span>](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips)
- [<span data-ttu-id="8044f-116">Proteger archivos de SharePoint Online con DLP y etiquetas de retención</span><span class="sxs-lookup"><span data-stu-id="8044f-116">Protect SharePoint Online files with retention labels and DLP</span></span>](https://docs.microsoft.com/office365/securitycompliance/protect-sharepoint-online-files-with-office-365-labels-and-dlp)
- [<span data-ttu-id="8044f-117">DLP y Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="8044f-117">DLP and Microsoft Teams</span></span>](https://docs.microsoft.com/office365/securitycompliance/dlp-microsoft-teams)

<span data-ttu-id="8044f-118">Para probar los datos con un tipo de información confidencial integrado o personalizado, use la opción **tipo de prueba** en **clasificaciones** > de**información confidencial**.</span><span class="sxs-lookup"><span data-stu-id="8044f-118">To test your data with a built-in or custom sensitive information type, use the **Test type** option under **Classifications** > **Sensitive info types**.</span></span> <span data-ttu-id="8044f-119">Para obtener más información, vea [probar tipos personalizados de información confidencial](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span><span class="sxs-lookup"><span data-stu-id="8044f-119">For more information, see [Test custom sensitive information types](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span></span>