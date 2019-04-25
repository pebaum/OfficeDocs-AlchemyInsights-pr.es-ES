---
title: La regla DLP para el número de tarjeta de crédito no funciona
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: e1d60c493a27efb7f724d57051e21fad5bd0242f
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "32404542"
---
<span data-ttu-id="35b07-102">¿Tiene problemas con la **prevención de pérdida de datos (DLP)** que no funciona para contenido que contiene un **número de tarjeta de crédito** al usar un tipo de información confidencial de DLP en O365?</span><span class="sxs-lookup"><span data-stu-id="35b07-102">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Credit Card Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="35b07-103">Si es así, asegúrese de que el contenido contiene la información necesaria para desencadenar la Directiva DLP cuando se evalúe.</span><span class="sxs-lookup"><span data-stu-id="35b07-103">If so, make sure your content contains the needed information to trigger the the DLP policy when it is evaluated.</span></span> <span data-ttu-id="35b07-104">Por ejemplo, para una **Directiva de tarjeta de crédito** configurada con un nivel de confianza del 85%, se evalúa lo siguiente y debe detectarse para que la regla desencadene:</span><span class="sxs-lookup"><span data-stu-id="35b07-104">For example, for a **Credit Card policy** configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span> 
  
- <span data-ttu-id="35b07-105">**[Formato:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 dígitos que pueden ser formateados o sin formato (dddddddddddddddd) y deben pasar la prueba Luhn.</span><span class="sxs-lookup"><span data-stu-id="35b07-105">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 digits which can be formatted or unformatted (dddddddddddddddd) and must pass the Luhn test.</span></span> 
    
- <span data-ttu-id="35b07-106">**[Patrón:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Patrón muy complejo y robusto que detecta las tarjetas de todas las principales marcas en todo el mundo, incluidas Visa, MasterCard, Tarjeta Discover, JCB, American Express, tarjetas regalo y tarjetas de comensal.</span><span class="sxs-lookup"><span data-stu-id="35b07-106">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Very complex and robust pattern that detects cards from all major brands worldwide, including Visa, MasterCard, Discover Card, JCB, American Express, gift cards, and diner cards.</span></span> 
    
- <span data-ttu-id="35b07-107">**[Suma de comprobación:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Sí, la suma de comprobación Luhn</span><span class="sxs-lookup"><span data-stu-id="35b07-107">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Yes, the Luhn checksum</span></span> 
    
- <span data-ttu-id="35b07-108">**[Definición:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** Una directiva DLP está 85% segura de que se detecta este tipo de información confidencial si, en una proximidad de 300 caracteres:</span><span class="sxs-lookup"><span data-stu-id="35b07-108">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span> 
    
  - <span data-ttu-id="35b07-109">La función Func_credit_card encuentra contenido que coincide con el patrón.</span><span class="sxs-lookup"><span data-stu-id="35b07-109">The function Func_credit_card finds content that matches the pattern.</span></span>
    
  - <span data-ttu-id="35b07-110">Una de las siguientes opciones es verdadera:</span><span class="sxs-lookup"><span data-stu-id="35b07-110">One of the following is true:</span></span> 
    
  - <span data-ttu-id="35b07-111">Se encuentra una palabra clave de Keyword_cc_verification.</span><span class="sxs-lookup"><span data-stu-id="35b07-111">A keyword from Keyword_cc_verification is found.</span></span>
    
  - <span data-ttu-id="35b07-112">Se encuentra una palabra clave de Keyword_cc_name</span><span class="sxs-lookup"><span data-stu-id="35b07-112">A keyword from Keyword_cc_name is found</span></span>
    
  - <span data-ttu-id="35b07-113">La función Func_expiration_date encuentra una fecha en el formato de fecha correcto.</span><span class="sxs-lookup"><span data-stu-id="35b07-113">The function Func_expiration_date finds a date in the right date format.</span></span>
    
  - <span data-ttu-id="35b07-114">La suma de comprobación pasa</span><span class="sxs-lookup"><span data-stu-id="35b07-114">The checksum passes</span></span>
    
    <span data-ttu-id="35b07-115">Por ejemplo, el siguiente ejemplo se activaría para una directiva de número de tarjeta de crédito DLP:</span><span class="sxs-lookup"><span data-stu-id="35b07-115">For example, the following sample would trigger for a DLP Credit Card Number Policy:</span></span>
    
  - <span data-ttu-id="35b07-116">Visa: 4485 3647 3952 7352</span><span class="sxs-lookup"><span data-stu-id="35b07-116">Visa: 4485 3647 3952 7352</span></span> 
    
  - <span data-ttu-id="35b07-117">Expira: 2/2009</span><span class="sxs-lookup"><span data-stu-id="35b07-117">Expires: 2/2009</span></span>
    
<span data-ttu-id="35b07-118">Para obtener más información sobre lo que se necesita para que se detecte un **número de tarjeta de crédito** para el contenido, vea la siguiente sección de este artículo: [¿qué aspecto tienen los tipos de información confidencial para la tarjeta de crédito #](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span><span class="sxs-lookup"><span data-stu-id="35b07-118">For more information on what is required for a **Credit Card Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for Credit Card#](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span></span>
  
<span data-ttu-id="35b07-119">Con un tipo de información confidencial integrado diferente, vea el siguiente artículo para obtener información sobre lo que se necesita para otros tipos: [Qué buscan los tipos de información confidencial](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="35b07-119">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  

