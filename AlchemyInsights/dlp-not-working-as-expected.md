---
title: DLP no funciona como se esperaba
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 1/9/2019
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1241"
- "3200001"
ms.assetid: f6fcf5ad-55a1-4f25-af27-1f7c1ce06409
ms.openlocfilehash: a56e18ddadef3a2f9056978b8542c1dba8f29665
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932639"
---
# <a name="dlp-not-working-as-expected"></a><span data-ttu-id="752d5-102">DLP no funciona como se esperaba</span><span class="sxs-lookup"><span data-stu-id="752d5-102">DLP not working as expected</span></span>

<span data-ttu-id="752d5-103">**Importante**: muchos clientes de SharePoint Online y OneDrive ejecutan aplicaciones críticas para la empresa en el servicio que se ejecutan en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="752d5-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="752d5-104">Estas incluyen la migración de contenido, la prevención de pérdida de datos (DLP) y soluciones de copia de seguridad.</span><span class="sxs-lookup"><span data-stu-id="752d5-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="752d5-105">En estos tiempos sin precedente, aplicamos las medidas necesarias para garantizar que los servicios de SharePoint Online y OneDrive permanezcan altamente disponibles y confiables para los usuarios que dependen del servicio más que nunca en escenarios de trabajo remoto.</span><span class="sxs-lookup"><span data-stu-id="752d5-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="752d5-106">Para apoyar este objetivo, hemos implementado límites más estrictos para las aplicaciones en segundo plano (como la migración, DLP y las soluciones de copia de seguridad) durante las horas de la semana laboral.</span><span class="sxs-lookup"><span data-stu-id="752d5-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="752d5-107">Se anticipa que estas aplicaciones obtengan un rendimiento muy limitado durante estas horas.</span><span class="sxs-lookup"><span data-stu-id="752d5-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="752d5-108">Sin embargo, durante las horas de la noche y del fin de semana de la región, el servicio estará listo para procesar un volumen mucho más elevado de solicitudes de aplicaciones en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="752d5-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

 <span data-ttu-id="752d5-109">**Configuración de DLP**</span><span class="sxs-lookup"><span data-stu-id="752d5-109">**Setting up DLP**</span></span>

<span data-ttu-id="752d5-110">¿Tiene problemas con la **prevención de pérdida de datos (DLP)** en Office 365 que no funciona como se esperaba?</span><span class="sxs-lookup"><span data-stu-id="752d5-110">Are you having problems with **Data Loss Prevention (DLP)** in Office 365 not working as expected?</span></span> <span data-ttu-id="752d5-111">Si es así, asegúrese de que la **Directiva DLP** está correctamente configurada y de que los datos contienen lo que la **Directiva DLP** busca cuando se evalúa.</span><span class="sxs-lookup"><span data-stu-id="752d5-111">If so, make sure that your **DLP policy** is set up correctly, and that your data contains what the **DLP policy** is looking for when it is being evaluated.</span></span>
  
<span data-ttu-id="752d5-112">Las directivas de DLP le permiten identificar y proteger la información confidencial de su organización.</span><span class="sxs-lookup"><span data-stu-id="752d5-112">DLP policies allows you to identify and protect sensitive information in your organization.</span></span> <span data-ttu-id="752d5-113">Para configurar directivas de DLP, use la información que se muestra [aquí](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span><span class="sxs-lookup"><span data-stu-id="752d5-113">To setup DLP policies, use the information [here](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span></span>
  
 <span data-ttu-id="752d5-114">**Qué buscan las directivas de DLP**</span><span class="sxs-lookup"><span data-stu-id="752d5-114">**What DLP policies look for**</span></span>
  
<span data-ttu-id="752d5-115">Al usar los **tipos de información confidencial integrados** en el centro de seguridad y cumplimiento de Office 365, las directivas de DLP buscan patrones y elementos específicos al detectar estos tipos confidenciales.</span><span class="sxs-lookup"><span data-stu-id="752d5-115">When using the **built-in sensitive information types** in Office 365 Security and Compliance center, DLP policies look for specific patterns and elements when detecting these sensitive types.</span></span>
  
- <span data-ttu-id="752d5-116">**Tipos de información confidencial integrados**</span><span class="sxs-lookup"><span data-stu-id="752d5-116">**Built-in Sensitive Information Types**</span></span>

    <span data-ttu-id="752d5-117">Para obtener información sobre los tipos confidenciales integrados y qué busca una directiva DLP cuando se detecta el tipo confidencial, vea: [Qué buscan los tipos de información confidencial](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span><span class="sxs-lookup"><span data-stu-id="752d5-117">For information on the built-in Sensitive types and what a DLP policy looks for when detecting the Sensitive type, see: [What the sensitive information types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span></span>

- <span data-ttu-id="752d5-118">**Tipos personalizados de información confidencial**</span><span class="sxs-lookup"><span data-stu-id="752d5-118">**Custom Sensitive Information Types**</span></span>

    <span data-ttu-id="752d5-119">Si está intentando crear tipos personalizados de información confidencial, use el siguiente artículo para obtener información sobre cómo crear un tipo confidencial personalizado: [crear un tipo personalizado de información confidencial](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="752d5-119">If you are trying to create custom sensitive information types, use the following article for information on how to create a custom sensitive type: [Create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span></span>

<span data-ttu-id="752d5-120">**Probar una directiva DLP**</span><span class="sxs-lookup"><span data-stu-id="752d5-120">**Test a DLP policy**</span></span>

<span data-ttu-id="752d5-121">Para probar los datos con un tipo de información confidencial integrado o personalizado, use la opción **tipo de prueba** en **clasificaciones** > de**información confidencial**.</span><span class="sxs-lookup"><span data-stu-id="752d5-121">To test your data with a built-in or custom sensitive information type, use the **Test type** option under **Classifications** > **Sensitive info types**.</span></span> <span data-ttu-id="752d5-122">Para obtener más información, vea [probar tipos personalizados de información confidencial](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span><span class="sxs-lookup"><span data-stu-id="752d5-122">For more information, see [Test custom sensitive information types](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span></span>

 <span data-ttu-id="752d5-123">**Informes**</span><span class="sxs-lookup"><span data-stu-id="752d5-123">**Reports**</span></span>
  
- <span data-ttu-id="752d5-124">Obtenga información confidencial sobre los datos con [informes de DLP.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span><span class="sxs-lookup"><span data-stu-id="752d5-124">Get sensitive data insights with [DLP Reports.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span></span>

- <span data-ttu-id="752d5-125">Vea los detalles específicos del evento con un [Informe de incidentes](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).</span><span class="sxs-lookup"><span data-stu-id="752d5-125">See specific details of the event with an [Incident Report](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).</span></span>
