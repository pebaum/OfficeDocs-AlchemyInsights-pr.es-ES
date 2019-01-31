---
title: Reglas de DLP para nosotros número de cuenta bancaria no funciona
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 80b40145-8376-4c3a-8d22-6efb9f9cb271
ms.openlocfilehash: 9fd5d4736c5209f85e235dc6a0846f65f1b5f624
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/30/2019
ms.locfileid: "29657016"
---
<span data-ttu-id="b12e9-p101">¿Tiene problemas con la **Prevención de pérdida de datos (DLP)** no funciona para el contenido que contiene un **Número de cuenta bancaria de Estados Unidos** cuando se utiliza un tipo de información confidencial de DLP en Office 365? Si es así, asegúrese de que el contenido contiene la información necesaria para lo que la directiva de DLP está buscando cuando se evalúa.</span><span class="sxs-lookup"><span data-stu-id="b12e9-p101">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US Bank Account Number** when using a DLP sensitive information type in O365? If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span> 
  
<span data-ttu-id="b12e9-104">Por ejemplo, para una directiva de **Número de cuenta bancaria de Estados Unidos** configurada con un nivel de confianza de 85%, el siguiente se evalúa y debe detectarse para que desencadenan la regla:</span><span class="sxs-lookup"><span data-stu-id="b12e9-104">For example, for a **US Bank Account Number** policy configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span> 
  
- <span data-ttu-id="b12e9-105">**[Formato:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 dígitos</span><span class="sxs-lookup"><span data-stu-id="b12e9-105">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 digits</span></span> 
    
- <span data-ttu-id="b12e9-106">**[Patrón:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** dígitos consecutivos de 8-17.</span><span class="sxs-lookup"><span data-stu-id="b12e9-106">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 consecutive digits.</span></span> 
    
- <span data-ttu-id="b12e9-107">**[Suma de comprobación:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, no hay ninguna suma de comprobación</span><span class="sxs-lookup"><span data-stu-id="b12e9-107">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span> 
    
- <span data-ttu-id="b12e9-108">**[Definición:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** Una directiva de DLP está seguro de que ha detectado este tipo de información confidencial al 75% if, dentro de una proximidad de 300 caracteres:</span><span class="sxs-lookup"><span data-stu-id="b12e9-108">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span> 
    
  - <span data-ttu-id="b12e9-109">La expresión regular Regex_usa_bank_account_number busca contenido que coincide con el patrón</span><span class="sxs-lookup"><span data-stu-id="b12e9-109">The regular expression Regex_usa_bank_account_number finds content that matches the pattern</span></span>
    
  - <span data-ttu-id="b12e9-110">Se encuentra una palabra clave de Keyword_usa_Bank_Account.</span><span class="sxs-lookup"><span data-stu-id="b12e9-110">A keyword from Keyword_usa_Bank_Account is found.</span></span>
    
    <span data-ttu-id="b12e9-111">Por ejemplo, podría desencadenar en el siguiente ejemplo para la directiva de **Número de cuenta bancaria de Estados Unidos** : cuenta corriente 78344011</span><span class="sxs-lookup"><span data-stu-id="b12e9-111">For example, the following sample would trigger for the **US Bank Account Number** policy: Checking Account 78344011</span></span> 
    
<span data-ttu-id="b12e9-112">Para obtener más información sobre lo que se requiere para un **Número de cuenta bancaria de Estados Unidos** para que detecte para su contenido, vea la siguiente sección de este artículo: [¿Qué el confidencial tipos de información busque el número de cuenta bancaria de Estados Unidos](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span><span class="sxs-lookup"><span data-stu-id="b12e9-112">For more information on what is required for a **US Bank Account Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US Bank Account Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span></span>
  
<span data-ttu-id="b12e9-113">Uso de un tipo de información confidencial integrada diferente, vea el siguiente artículo para obtener información en lo que se requiere para otros tipos de: [Buscar qué el confidencial tipos de información](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="b12e9-113">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  

