---
title: La regla de DLP para SSN no funciona
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1242"
- "3200001"
ms.assetid: ac265ee6-c946-476e-9bf0-0ea0e8adc98a
ms.openlocfilehash: 5af843c2b70b5b2e1aaf82c9f01356546929d840
ms.sourcegitcommit: 6a3748f5c05693ca0c19a829287cb8f30635940c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43788719"
---
# <a name="dlp-issues-with-social-security-numbers"></a><span data-ttu-id="2efec-102">Problemas de DLP con números de la seguridad social</span><span class="sxs-lookup"><span data-stu-id="2efec-102">DLP issues with Social Security Numbers</span></span>

<span data-ttu-id="2efec-103">**Importante**: durante estos tiempos, se siguen pasos para asegurarse de que los servicios de SharePoint Online y OneDrive estén altamente disponibles. Para obtener más información, visite [Ajustes temporales de características de SharePoint Online](https://aka.ms/ODSPAdjustments).</span><span class="sxs-lookup"><span data-stu-id="2efec-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="2efec-104">**Problemas de DLP con SSN**</span><span class="sxs-lookup"><span data-stu-id="2efec-104">**DLP issues with SSNs**</span></span>

<span data-ttu-id="2efec-105">¿Tiene problemas con la **prevención de pérdida de datos (DLP)** que no funciona para contenido que contiene un número de la **seguridad social (SSN)** al usar un tipo de información confidencial en Microsoft 365?</span><span class="sxs-lookup"><span data-stu-id="2efec-105">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Social Security Number (SSN)** when using a sensitive information type in Microsoft 365?</span></span> <span data-ttu-id="2efec-106">Si es así, asegúrese de que el contenido contiene la información necesaria para el aspecto de la Directiva DLP.</span><span class="sxs-lookup"><span data-stu-id="2efec-106">If so, make sure your content contains the needed information for what the DLP policy is looking.</span></span> 
  
<span data-ttu-id="2efec-107">Por ejemplo, para una directiva SSN configurada con un nivel de confianza de 85%, se evalúa lo siguiente y debe detectarse para que la regla desencadene:</span><span class="sxs-lookup"><span data-stu-id="2efec-107">For example, for an SSN policy configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="2efec-108">**[Formato:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-80)** 9 dígitos, que pueden estar en un patrón con o sin formato</span><span class="sxs-lookup"><span data-stu-id="2efec-108">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-80)** 9 digits, which may be in a formatted or unformatted pattern</span></span>

- <span data-ttu-id="2efec-109">**[Patrón:](https://msconnect.microsoft.com/https:/docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** Cuatro funciones buscan SSN en cuatro patrones diferentes:</span><span class="sxs-lookup"><span data-stu-id="2efec-109">**[Pattern:](https://msconnect.microsoft.com/https:/docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** Four functions look for SSNs in four different patterns:</span></span>

  - <span data-ttu-id="2efec-110">Func_ssn busca SSN con formato seguro anteriores a 2011 y formateados con guiones o espacios (ddd-dd-dddd O ddd dd dddd)</span><span class="sxs-lookup"><span data-stu-id="2efec-110">Func_ssn finds SSNs with pre-2011 strong formatting that are formatted with dashes or spaces (ddd-dd-dddd OR ddd dd dddd)</span></span>

  - <span data-ttu-id="2efec-111">Func_unformatted_ssn busca SSN con formato seguro anteriores a 2011 y formateados de manera no específica como nueve dígitos consecutivos (ddddddddd)</span><span class="sxs-lookup"><span data-stu-id="2efec-111">Func_unformatted_ssn finds SSNs with pre-2011 strong formatting that are unformatted as nine consecutive digits (ddddddddd)</span></span>

  - <span data-ttu-id="2efec-112">Func_randomized_formatted_ssn busca SSN posteriores a 2011 y formateados con guiones o espacios (ddd-dd-dddd O ddd dd dddd)</span><span class="sxs-lookup"><span data-stu-id="2efec-112">Func_randomized_formatted_ssn finds post-2011 SSNs that are formatted with dashes or spaces (ddd-dd-dddd OR ddd dd dddd)</span></span>

  - <span data-ttu-id="2efec-113">Func_randomized_unformatted_ssn busca SSN posteriores a 2011 y formateados de manera no específica como nueve dígitos consecutivos (ddddddddd)</span><span class="sxs-lookup"><span data-stu-id="2efec-113">Func_randomized_unformatted_ssn finds post-2011 SSNs that are unformatted as nine consecutive digits (ddddddddd)</span></span>

- <span data-ttu-id="2efec-114">**[Suma de comprobación:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-79)** No, no hay ninguna suma de comprobación</span><span class="sxs-lookup"><span data-stu-id="2efec-114">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-79)** No, there is no Checksum</span></span>

- <span data-ttu-id="2efec-115">**[Definición:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-80)** Una directiva DLP está 85% segura de que se detecta este tipo de información confidencial si, en una proximidad de 300 caracteres:</span><span class="sxs-lookup"><span data-stu-id="2efec-115">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-80)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="2efec-116">La [función Func_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80) encuentra contenido que coincide con el patrón.</span><span class="sxs-lookup"><span data-stu-id="2efec-116">The [function Func_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80) finds content that matches the pattern.</span></span>

  - <span data-ttu-id="2efec-117">Se encuentra una palabra clave de [Keyword_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#keyword_ssn).</span><span class="sxs-lookup"><span data-stu-id="2efec-117">A keyword from [Keyword_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#keyword_ssn) is found.</span></span> <span data-ttu-id="2efec-118">Algunos ejemplos de palabras clave son: *seguridad social, seguridad social #, SOC sec, SSN* .</span><span class="sxs-lookup"><span data-stu-id="2efec-118">Examples of keywords includes:  *Social Security, Social Security#, Soc Sec ,SSN*  .</span></span> <span data-ttu-id="2efec-119">Por ejemplo, el siguiente ejemplo se activaría para la Directiva de SSN de DLP: **SSN: 489-36-8350**</span><span class="sxs-lookup"><span data-stu-id="2efec-119">For example, the following sample would trigger for the DLP SSN policy: **SSN: 489-36-8350**</span></span>
  
<span data-ttu-id="2efec-120">Para obtener más información sobre lo que se necesita para que SSN se detecte en el contenido, vea la siguiente sección de este artículo: [Qué buscan los tipos de información confidencial SSN](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-social-security-number-ssn)</span><span class="sxs-lookup"><span data-stu-id="2efec-120">For more information on what is required for SSNs to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for SSNs](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-social-security-number-ssn)</span></span>
  
<span data-ttu-id="2efec-121">Con un tipo de información confidencial integrado diferente, vea el siguiente artículo para obtener información sobre lo que se necesita para otros tipos: [Qué buscan los tipos de información confidencial](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="2efec-121">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  