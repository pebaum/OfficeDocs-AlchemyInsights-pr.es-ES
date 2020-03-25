---
title: Regla DLP para el número de cuenta bancaria de Estados Unidos no funciona
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1287"
- "3200001"
ms.assetid: 80b40145-8376-4c3a-8d22-6efb9f9cb271
ms.openlocfilehash: 0b5c1fb175275028c56e47080708520fe115fb38
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932567"
---
# <a name="dlp-issues-with-us-bank-account-numbers"></a><span data-ttu-id="b938b-102">Problemas de DLP con números de cuentas bancarias de Estados Unidos</span><span class="sxs-lookup"><span data-stu-id="b938b-102">DLP issues with US bank account numbers</span></span>

<span data-ttu-id="b938b-103">**Importante**: muchos clientes de SharePoint Online y OneDrive ejecutan aplicaciones críticas para la empresa en el servicio que se ejecutan en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="b938b-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="b938b-104">Estas incluyen la migración de contenido, la prevención de pérdida de datos (DLP) y soluciones de copia de seguridad.</span><span class="sxs-lookup"><span data-stu-id="b938b-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="b938b-105">En estos tiempos sin precedente, aplicamos las medidas necesarias para garantizar que los servicios de SharePoint Online y OneDrive permanezcan altamente disponibles y confiables para los usuarios que dependen del servicio más que nunca en escenarios de trabajo remoto.</span><span class="sxs-lookup"><span data-stu-id="b938b-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="b938b-106">Para apoyar este objetivo, hemos implementado límites más estrictos para las aplicaciones en segundo plano (como la migración, DLP y las soluciones de copia de seguridad) durante las horas de la semana laboral.</span><span class="sxs-lookup"><span data-stu-id="b938b-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="b938b-107">Se anticipa que estas aplicaciones obtengan un rendimiento muy limitado durante estas horas.</span><span class="sxs-lookup"><span data-stu-id="b938b-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="b938b-108">Sin embargo, durante las horas de la noche y del fin de semana de la región, el servicio estará listo para procesar un volumen mucho más elevado de solicitudes de aplicaciones en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="b938b-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="b938b-109">**Problemas de DLP con números de cuentas bancarias de Estados Unidos**</span><span class="sxs-lookup"><span data-stu-id="b938b-109">**DLP issues with US bank account numbers**</span></span>

<span data-ttu-id="b938b-110">¿Tiene problemas con la **prevención de pérdida de datos (DLP)** que no funciona para contenido que contiene un **número de cuenta bancaria de Estados Unidos** al usar un tipo de información confidencial de DLP en O365?</span><span class="sxs-lookup"><span data-stu-id="b938b-110">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US Bank Account Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="b938b-111">Si es así, asegúrese de que el contenido contiene la información necesaria para lo que la Directiva de DLP está buscando cuando se evalúa.</span><span class="sxs-lookup"><span data-stu-id="b938b-111">If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span>
  
<span data-ttu-id="b938b-112">Por ejemplo, para una directiva de **número de cuenta bancaria de Estados Unidos** configurada con un nivel de confianza del 85%, se evalúa lo siguiente y debe detectarse para que la regla desencadene:</span><span class="sxs-lookup"><span data-stu-id="b938b-112">For example, for a **US Bank Account Number** policy configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="b938b-113">**[Formato:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 dígitos</span><span class="sxs-lookup"><span data-stu-id="b938b-113">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 digits</span></span>

- <span data-ttu-id="b938b-114">**[Patrón:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 dígitos consecutivos.</span><span class="sxs-lookup"><span data-stu-id="b938b-114">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 consecutive digits.</span></span>

- <span data-ttu-id="b938b-115">**[Suma de comprobación:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, no hay ninguna suma de comprobación</span><span class="sxs-lookup"><span data-stu-id="b938b-115">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span>

- <span data-ttu-id="b938b-116">**[Definición:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** Una directiva DLP está 75% segura de que se detecta este tipo de información confidencial si, en una proximidad de 300 caracteres:</span><span class="sxs-lookup"><span data-stu-id="b938b-116">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="b938b-117">La expresión regular Regex_usa_bank_account_number encuentra contenido que coincide con el patrón.</span><span class="sxs-lookup"><span data-stu-id="b938b-117">The regular expression Regex_usa_bank_account_number finds content that matches the pattern</span></span>

  - <span data-ttu-id="b938b-118">Se encuentra una palabra clave de Keyword_usa_Bank_Account.</span><span class="sxs-lookup"><span data-stu-id="b938b-118">A keyword from Keyword_usa_Bank_Account is found.</span></span>

    <span data-ttu-id="b938b-119">Por ejemplo, el siguiente ejemplo se activaría para la Directiva de **número de cuenta bancaria estadounidense** : comprobando la cuenta 78344011</span><span class="sxs-lookup"><span data-stu-id="b938b-119">For example, the following sample would trigger for the **US Bank Account Number** policy: Checking Account 78344011</span></span>

<span data-ttu-id="b938b-120">Para obtener más información sobre lo que se necesita para que se detecte un **número de cuenta bancaria de Estados Unidos** en el contenido, consulte la siguiente sección de este artículo: [Qué buscan los tipos de información confidencial en su número de cuenta bancaria](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span><span class="sxs-lookup"><span data-stu-id="b938b-120">For more information on what is required for a **US Bank Account Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US Bank Account Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span></span>
  
<span data-ttu-id="b938b-121">Con un tipo de información confidencial integrado diferente, vea el siguiente artículo para obtener información sobre lo que se necesita para otros tipos: [Qué buscan los tipos de información confidencial](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="b938b-121">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  