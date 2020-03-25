---
title: La regla DLP para el número de tarjeta de crédito no funciona
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1270"
- "3200001"
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: 6b28534d072c024a98a9b05f6cb55bfdc3435db6
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932460"
---
# <a name="dlp-issues-with-credit-card-numbers"></a><span data-ttu-id="c9236-102">Problemas de DLP con números de tarjeta de crédito</span><span class="sxs-lookup"><span data-stu-id="c9236-102">DLP issues with credit card numbers</span></span>

<span data-ttu-id="c9236-103">**Importante**: muchos clientes de SharePoint Online y OneDrive ejecutan aplicaciones críticas para la empresa en el servicio que se ejecutan en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="c9236-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="c9236-104">Estas incluyen la migración de contenido, la prevención de pérdida de datos (DLP) y soluciones de copia de seguridad.</span><span class="sxs-lookup"><span data-stu-id="c9236-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="c9236-105">En estos tiempos sin precedente, aplicamos las medidas necesarias para garantizar que los servicios de SharePoint Online y OneDrive permanezcan altamente disponibles y confiables para los usuarios que dependen del servicio más que nunca en escenarios de trabajo remoto.</span><span class="sxs-lookup"><span data-stu-id="c9236-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="c9236-106">Para apoyar este objetivo, hemos implementado límites más estrictos para las aplicaciones en segundo plano (como la migración, DLP y las soluciones de copia de seguridad) durante las horas de la semana laboral.</span><span class="sxs-lookup"><span data-stu-id="c9236-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="c9236-107">Se anticipa que estas aplicaciones obtengan un rendimiento muy limitado durante estas horas.</span><span class="sxs-lookup"><span data-stu-id="c9236-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="c9236-108">Sin embargo, durante las horas de la noche y del fin de semana de la región, el servicio estará listo para procesar un volumen mucho más elevado de solicitudes de aplicaciones en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="c9236-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="c9236-109">**Problemas de DLP con números de tarjeta de crédito**</span><span class="sxs-lookup"><span data-stu-id="c9236-109">**DLP issues with credit card numbers**</span></span>

<span data-ttu-id="c9236-110">¿Tiene problemas con la **prevención de pérdida de datos (DLP)** que no funciona para contenido que contiene un **número de tarjeta de crédito** al usar un tipo de información confidencial de DLP en O365?</span><span class="sxs-lookup"><span data-stu-id="c9236-110">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Credit Card Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="c9236-111">Si es así, asegúrese de que el contenido contiene la información necesaria para desencadenar la Directiva DLP cuando se evalúe.</span><span class="sxs-lookup"><span data-stu-id="c9236-111">If so, make sure your content contains the needed information to trigger the the DLP policy when it is evaluated.</span></span> <span data-ttu-id="c9236-112">Por ejemplo, para una **Directiva de tarjeta de crédito** configurada con un nivel de confianza del 85%, se evalúa lo siguiente y debe detectarse para que la regla desencadene:</span><span class="sxs-lookup"><span data-stu-id="c9236-112">For example, for a **Credit Card policy** configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="c9236-113">**[Formato:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 dígitos que pueden ser formateados o sin formato (dddddddddddddddd) y deben pasar la prueba Luhn.</span><span class="sxs-lookup"><span data-stu-id="c9236-113">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 digits which can be formatted or unformatted (dddddddddddddddd) and must pass the Luhn test.</span></span>

- <span data-ttu-id="c9236-114">**[Patrón:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Patrón muy complejo y robusto que detecta las tarjetas de todas las principales marcas en todo el mundo, incluidas Visa, MasterCard, Tarjeta Discover, JCB, American Express, tarjetas regalo y tarjetas de comensal.</span><span class="sxs-lookup"><span data-stu-id="c9236-114">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Very complex and robust pattern that detects cards from all major brands worldwide, including Visa, MasterCard, Discover Card, JCB, American Express, gift cards, and diner cards.</span></span>

- <span data-ttu-id="c9236-115">**[Suma de comprobación:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Sí, la suma de comprobación Luhn</span><span class="sxs-lookup"><span data-stu-id="c9236-115">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Yes, the Luhn checksum</span></span>

- <span data-ttu-id="c9236-116">**[Definición:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** Una directiva DLP está 85% segura de que se detecta este tipo de información confidencial si, en una proximidad de 300 caracteres:</span><span class="sxs-lookup"><span data-stu-id="c9236-116">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="c9236-117">La función Func_credit_card encuentra contenido que coincide con el patrón.</span><span class="sxs-lookup"><span data-stu-id="c9236-117">The function Func_credit_card finds content that matches the pattern.</span></span>

  - <span data-ttu-id="c9236-118">Una de las siguientes opciones es verdadera:</span><span class="sxs-lookup"><span data-stu-id="c9236-118">One of the following is true:</span></span>

  - <span data-ttu-id="c9236-119">Se encuentra una palabra clave de Keyword_cc_verification.</span><span class="sxs-lookup"><span data-stu-id="c9236-119">A keyword from Keyword_cc_verification is found.</span></span>

  - <span data-ttu-id="c9236-120">Se encuentra una palabra clave de Keyword_cc_name</span><span class="sxs-lookup"><span data-stu-id="c9236-120">A keyword from Keyword_cc_name is found</span></span>

  - <span data-ttu-id="c9236-121">La función Func_expiration_date encuentra una fecha en el formato de fecha correcto.</span><span class="sxs-lookup"><span data-stu-id="c9236-121">The function Func_expiration_date finds a date in the right date format.</span></span>

  - <span data-ttu-id="c9236-122">La suma de comprobación pasa</span><span class="sxs-lookup"><span data-stu-id="c9236-122">The checksum passes</span></span>

    <span data-ttu-id="c9236-123">Por ejemplo, el siguiente ejemplo se activaría para una directiva de número de tarjeta de crédito DLP:</span><span class="sxs-lookup"><span data-stu-id="c9236-123">For example, the following sample would trigger for a DLP Credit Card Number Policy:</span></span>

  - <span data-ttu-id="c9236-124">Visa: 4485 3647 3952 7352</span><span class="sxs-lookup"><span data-stu-id="c9236-124">Visa: 4485 3647 3952 7352</span></span>
  
  - <span data-ttu-id="c9236-125">Expira: 2/2009</span><span class="sxs-lookup"><span data-stu-id="c9236-125">Expires: 2/2009</span></span>

<span data-ttu-id="c9236-126">Para obtener más información sobre lo que se necesita para que se detecte un **número de tarjeta de crédito** para el contenido, vea la siguiente sección de este artículo: [¿qué aspecto tienen los tipos de información confidencial para la tarjeta de crédito #](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span><span class="sxs-lookup"><span data-stu-id="c9236-126">For more information on what is required for a **Credit Card Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for Credit Card#](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span></span>
  
<span data-ttu-id="c9236-127">Con un tipo de información confidencial integrado diferente, vea el siguiente artículo para obtener información sobre lo que se necesita para otros tipos: [Qué buscan los tipos de información confidencial](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="c9236-127">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  