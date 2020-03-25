---
title: Es posible que DLP necesite un tipo personalizado
ms.author: pebaum
author: pebaum
manager: laurawi
ms.date: ''
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1647"
- "3200001"
ms.assetid: ''
ms.openlocfilehash: 890bba57bc36c034c507e6124cd6593ef4d92af8
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932675"
---
# <a name="dlp-might-need-a-custom-type"></a><span data-ttu-id="c4cdf-102">Es posible que DLP necesite un tipo personalizado</span><span class="sxs-lookup"><span data-stu-id="c4cdf-102">DLP might need a custom type</span></span>

<span data-ttu-id="c4cdf-103">**Importante**: muchos clientes de SharePoint Online y OneDrive ejecutan aplicaciones críticas para la empresa en el servicio que se ejecutan en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="c4cdf-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="c4cdf-104">Estas incluyen la migración de contenido, la prevención de pérdida de datos (DLP) y soluciones de copia de seguridad.</span><span class="sxs-lookup"><span data-stu-id="c4cdf-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="c4cdf-105">En estos tiempos sin precedente, aplicamos las medidas necesarias para garantizar que los servicios de SharePoint Online y OneDrive permanezcan altamente disponibles y confiables para los usuarios que dependen del servicio más que nunca en escenarios de trabajo remoto.</span><span class="sxs-lookup"><span data-stu-id="c4cdf-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="c4cdf-106">Para apoyar este objetivo, hemos implementado límites más estrictos para las aplicaciones en segundo plano (como la migración, DLP y las soluciones de copia de seguridad) durante las horas de la semana laboral.</span><span class="sxs-lookup"><span data-stu-id="c4cdf-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="c4cdf-107">Se anticipa que estas aplicaciones obtengan un rendimiento muy limitado durante estas horas.</span><span class="sxs-lookup"><span data-stu-id="c4cdf-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="c4cdf-108">Sin embargo, durante las horas de la noche y del fin de semana de la región, el servicio estará listo para procesar un volumen mucho más elevado de solicitudes de aplicaciones en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="c4cdf-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="c4cdf-109">**Es posible que DLP requiera un tipo de información personalizada**</span><span class="sxs-lookup"><span data-stu-id="c4cdf-109">**DLP may require a custom information type**</span></span>

<span data-ttu-id="c4cdf-110">Con una directiva de prevención de pérdida de datos (DLP), puede identificar y proteger los datos confidenciales de su organización.</span><span class="sxs-lookup"><span data-stu-id="c4cdf-110">With a data loss prevention (DLP) policy, you can identify and protect sensitive data in your organization.</span></span> <span data-ttu-id="c4cdf-111">En algunos escenarios, es posible que necesite crear su propio tipo **personalizado** de información confidencial para proteger los datos de su organización.</span><span class="sxs-lookup"><span data-stu-id="c4cdf-111">In some scenarios, you might need to create your own **custom** sensitive information type to protect your organization's data.</span></span>

<span data-ttu-id="c4cdf-112">Por ejemplo, es posible que su organización necesite identificar y proteger los identificadores de los empleados u otros datos en algún formato específico de su organización. Si es así, consulte los artículos siguientes para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="c4cdf-112">For example, your organization might need to identify and protect employee IDs or other data in some format specific to your org. If so, see the following articles for more information.</span></span>
  
 <span data-ttu-id="c4cdf-113">**Personalizar un tipo de información confidencial integrado**</span><span class="sxs-lookup"><span data-stu-id="c4cdf-113">**Customize a built-in sensitive information type**</span></span>
  
<span data-ttu-id="c4cdf-114">Si un tipo de información confidencial incorporado satisface sus necesidades con solo unos cuantos ajustes, puede [personalizar un tipo de información confidencial integrada](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="c4cdf-114">If a built-in sensitive information type would meet your needs with just a few tweaks, you can [customize a built-in sensitive information type](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type).</span></span> <span data-ttu-id="c4cdf-115">Por ejemplo, puede Agregar o quitar palabras clave, o bien agregar o quitar evidencias auxiliares, como una fecha o una dirección.</span><span class="sxs-lookup"><span data-stu-id="c4cdf-115">For example, you can add or remove keywords, or add or remove supporting evidence such as a date or address.</span></span>
  
 <span data-ttu-id="c4cdf-116">**Crear un tipo personalizado de información confidencial**</span><span class="sxs-lookup"><span data-stu-id="c4cdf-116">**Create a custom sensitive information type**</span></span>
  
<span data-ttu-id="c4cdf-117">Pero si necesita identificar y proteger por completo un tipo diferente de información confidencial, puede [crear un tipo personalizado de información confidencial](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) en la interfaz de usuario del centro de seguridad & cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="c4cdf-117">But if you need to identify and protect a different type of sensitive information altogether, you can [create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) in the UI of the Security & Compliance Center.</span></span>
  
<span data-ttu-id="c4cdf-118">**Crear un tipo personalizado de información confidencial en PowerShell del Centro de seguridad y cumplimientol**</span><span class="sxs-lookup"><span data-stu-id="c4cdf-118">**Create a custom sensitive information type in Security & Compliance Center PowerShell**</span></span>

<span data-ttu-id="c4cdf-119">Por último, si la interfaz de usuario no proporciona todas las opciones que necesita, puede [crear un tipo personalizado de información confidencial en el PowerShell del centro de cumplimiento de & de seguridad](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span><span class="sxs-lookup"><span data-stu-id="c4cdf-119">Finally, if the UI doesn't provide all the options you need, you can [create a custom sensitive information type in Security & Compliance Center PowerShell](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span></span> <span data-ttu-id="c4cdf-120">Al comenzar con un archivo XML, puede usar todas las opciones disponibles.</span><span class="sxs-lookup"><span data-stu-id="c4cdf-120">By starting with an XML file, you can use every option available.</span></span>
