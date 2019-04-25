---
title: Regla DLP para el número de cuenta bancaria de Estados Unidos no funciona
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 80b40145-8376-4c3a-8d22-6efb9f9cb271
ms.openlocfilehash: 9ebfa6bc09cef9ab7c30bddb4fcb8b6be3ab55a5
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "32404292"
---
<span data-ttu-id="b3260-102">¿Tiene problemas con la **prevención de pérdida de datos (DLP)** que no funciona para contenido que contiene un **número de cuenta bancaria de Estados Unidos** al usar un tipo de información confidencial de DLP en O365?</span><span class="sxs-lookup"><span data-stu-id="b3260-102">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US Bank Account Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="b3260-103">Si es así, asegúrese de que el contenido contiene la información necesaria para lo que la Directiva de DLP está buscando cuando se evalúa.</span><span class="sxs-lookup"><span data-stu-id="b3260-103">If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span> 
  
<span data-ttu-id="b3260-104">Por ejemplo, para una directiva de **número de cuenta bancaria de Estados Unidos** configurada con un nivel de confianza del 85%, se evalúa lo siguiente y debe detectarse para que la regla desencadene:</span><span class="sxs-lookup"><span data-stu-id="b3260-104">For example, for a **US Bank Account Number** policy configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span> 
  
- <span data-ttu-id="b3260-105">**[Formato:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 dígitos</span><span class="sxs-lookup"><span data-stu-id="b3260-105">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 digits</span></span> 
    
- <span data-ttu-id="b3260-106">**[Patrón:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 dígitos consecutivos.</span><span class="sxs-lookup"><span data-stu-id="b3260-106">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 consecutive digits.</span></span> 
    
- <span data-ttu-id="b3260-107">**[Suma de comprobación:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, no hay ninguna suma de comprobación</span><span class="sxs-lookup"><span data-stu-id="b3260-107">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span> 
    
- <span data-ttu-id="b3260-108">**[Definición:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** Una directiva DLP está 75% segura de que se detecta este tipo de información confidencial si, en una proximidad de 300 caracteres:</span><span class="sxs-lookup"><span data-stu-id="b3260-108">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span> 
    
  - <span data-ttu-id="b3260-109">La expresión regular Regex_usa_bank_account_number encuentra contenido que coincide con el patrón</span><span class="sxs-lookup"><span data-stu-id="b3260-109">The regular expression Regex_usa_bank_account_number finds content that matches the pattern</span></span>
    
  - <span data-ttu-id="b3260-110">Se encuentra una palabra clave de Keyword_usa_Bank_Account.</span><span class="sxs-lookup"><span data-stu-id="b3260-110">A keyword from Keyword_usa_Bank_Account is found.</span></span>
    
    <span data-ttu-id="b3260-111">Por ejemplo, el siguiente ejemplo se activaría para la Directiva de **número de cuenta bancaria estadounidense** : comprobaNdo la cuenta 78344011</span><span class="sxs-lookup"><span data-stu-id="b3260-111">For example, the following sample would trigger for the **US Bank Account Number** policy: Checking Account 78344011</span></span> 
    
<span data-ttu-id="b3260-112">Para obtener más información sobre lo que se necesita para que se detecte un **número de cuenta bancaria de Estados Unidos** en el contenido, consulte la siguiente sección de este artículo: [Qué buscan los tipos de información confidencial en su número de cuenta bancaria](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span><span class="sxs-lookup"><span data-stu-id="b3260-112">For more information on what is required for a **US Bank Account Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US Bank Account Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span></span>
  
<span data-ttu-id="b3260-113">Con un tipo de información confidencial integrado diferente, vea el siguiente artículo para obtener información sobre lo que se necesita para otros tipos: [Qué buscan los tipos de información confidencial](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="b3260-113">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  

