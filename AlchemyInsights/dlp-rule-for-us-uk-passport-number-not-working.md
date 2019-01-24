---
title: Reglas de DLP para Estados Unidos / número de pasaporte del Reino Unido no funciona
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: fc178b8b-943b-4346-a2bd-a75c6af6f80f
ms.openlocfilehash: 716d1030d93ce006c36d7925fb132e974ae8feb4
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29491200"
---
<span data-ttu-id="68fd2-p101">¿Tiene problemas con la **Prevención de pérdida de datos (DLP)** no funciona para que contiene contenido un **US / número de pasaporte del Reino Unido** cuando se utiliza un tipo de información confidencial de DLP en Office 365? Si es así, asegúrese de que el contenido contiene la información necesaria para lo que la directiva de DLP está buscando cuando se evalúa.</span><span class="sxs-lookup"><span data-stu-id="68fd2-p101">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US/UK Passport Number** when using a DLP sensitive information type in O365? If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span> 
  
<span data-ttu-id="68fd2-104">Por ejemplo, para un **US / número de pasaporte del Reino Unido** directiva configurada con un nivel de confianza de un 75%, el siguiente se evalúan y deben detectarse para que desencadenan la regla</span><span class="sxs-lookup"><span data-stu-id="68fd2-104">For example, for a **US/UK Passport Number** policy configured with a confidence level of 75%, the following are evaluated and must be detected for the rule to trigger</span></span> 
  
- <span data-ttu-id="68fd2-105">**[Formato:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Nueve dígitos</span><span class="sxs-lookup"><span data-stu-id="68fd2-105">**[Format:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Nine digits</span></span> 
    
- <span data-ttu-id="68fd2-106">**[Patrón:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Nueve dígitos consecutivos</span><span class="sxs-lookup"><span data-stu-id="68fd2-106">**[Pattern:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Nine consecutive digits</span></span> 
    
- <span data-ttu-id="68fd2-107">**[Suma de comprobación:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, no hay ninguna suma de comprobación</span><span class="sxs-lookup"><span data-stu-id="68fd2-107">**[Checksum:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span> 
    
- <span data-ttu-id="68fd2-108">**[Definición:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** Una directiva de DLP está seguro de que ha detectado este tipo de información confidencial al 75% if, dentro de una proximidad de 300 caracteres:</span><span class="sxs-lookup"><span data-stu-id="68fd2-108">**[Definition:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span> 
    
  - <span data-ttu-id="68fd2-109">La función Func_usa_uk_passport encuentra contenido que coincide con el patrón.</span><span class="sxs-lookup"><span data-stu-id="68fd2-109">The function Func_usa_uk_passport finds content that matches the pattern.</span></span>
    
  - <span data-ttu-id="68fd2-110">Se encuentra una palabra clave de Keyword_passport.</span><span class="sxs-lookup"><span data-stu-id="68fd2-110">A keyword from Keyword_passport is found.</span></span>
    
    <span data-ttu-id="68fd2-111">Por ejemplo, podría desencadenar en el siguiente ejemplo para el **US / número de pasaporte del Reino Unido** directiva: número de Estados Unidos Passport 123456789</span><span class="sxs-lookup"><span data-stu-id="68fd2-111">For example, the following sample would trigger for the **US/UK Passport Number** policy: U.S. Passport number 123456789</span></span> 
    
<span data-ttu-id="68fd2-112">Para obtener más información sobre lo que se requiere para un US / número de pasaporte Reino Unido para que detecte para su contenido, vea la siguiente sección de este artículo: [aspecto de lo que el confidencial tipos de información para los Estados Unidos o Reino Unido Passport número](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)</span><span class="sxs-lookup"><span data-stu-id="68fd2-112">For more information on what is required for a US/UK Passport Number to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US/UK Passport Number](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)</span></span>
  
<span data-ttu-id="68fd2-113">Uso de un tipo de información confidencial integrada diferente, vea el siguiente artículo para obtener información en lo que se requiere para otros tipos de: [Buscar qué el confidencial tipos de información](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="68fd2-113">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  

