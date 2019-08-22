---
title: Regla DLP para US/UK el número de Passport no funciona
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1319"
- "3200001"
ms.assetid: fc178b8b-943b-4346-a2bd-a75c6af6f80f
ms.openlocfilehash: bc91af8be58d49204f84cd7d22f481348af3c013
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36529936"
---
# <a name="problems-with-dlp---usuk-passport-numbers"></a><span data-ttu-id="1a15a-102">Problemas con números de pasaporte de DLP-US/UK</span><span class="sxs-lookup"><span data-stu-id="1a15a-102">Problems with DLP - US/UK Passport Numbers</span></span>

<span data-ttu-id="1a15a-103">¿Tiene problemas con la **prevención de pérdida de datos (DLP)** que no funciona para contenido que contiene un **número de pasaporte de Estados Unidos** al usar un tipo de información confidencial de DLP en O365?</span><span class="sxs-lookup"><span data-stu-id="1a15a-103">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US/UK Passport Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="1a15a-104">Si es así, asegúrese de que el contenido contiene la información necesaria para lo que la Directiva de DLP está buscando cuando se evalúa.</span><span class="sxs-lookup"><span data-stu-id="1a15a-104">If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span>
  
<span data-ttu-id="1a15a-105">Por ejemplo, para una directiva de **número de pasaporte de Estados Unidos** configurada con un nivel de confianza del 75%, se evalúa lo siguiente y debe detectarse para que la regla desencadene</span><span class="sxs-lookup"><span data-stu-id="1a15a-105">For example, for a **US/UK Passport Number** policy configured with a confidence level of 75%, the following are evaluated and must be detected for the rule to trigger</span></span>
  
- <span data-ttu-id="1a15a-106">**[Formato:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Nueve dígitos</span><span class="sxs-lookup"><span data-stu-id="1a15a-106">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Nine digits</span></span>

- <span data-ttu-id="1a15a-107">**[Patrón:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Nueve dígitos consecutivos</span><span class="sxs-lookup"><span data-stu-id="1a15a-107">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Nine consecutive digits</span></span>

- <span data-ttu-id="1a15a-108">**[Suma de comprobación:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, no hay ninguna suma de comprobación</span><span class="sxs-lookup"><span data-stu-id="1a15a-108">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span>

- <span data-ttu-id="1a15a-109">**[Definición:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** Una directiva DLP está 75% segura de que se detecta este tipo de información confidencial si, en una proximidad de 300 caracteres:</span><span class="sxs-lookup"><span data-stu-id="1a15a-109">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="1a15a-110">La función Func_usa_uk_passport encuentra contenido que coincide con el patrón.</span><span class="sxs-lookup"><span data-stu-id="1a15a-110">The function Func_usa_uk_passport finds content that matches the pattern.</span></span>

  - <span data-ttu-id="1a15a-111">Se encuentra una palabra clave de Keyword_passport.</span><span class="sxs-lookup"><span data-stu-id="1a15a-111">A keyword from Keyword_passport is found.</span></span>

    <span data-ttu-id="1a15a-112">Por ejemplo, el siguiente ejemplo se activaría para la Directiva de **número de pasaporte de Estados Unidos** : número de pasaporte de estados Unidos 123456789</span><span class="sxs-lookup"><span data-stu-id="1a15a-112">For example, the following sample would trigger for the **US/UK Passport Number** policy: U.S. Passport number 123456789</span></span>

<span data-ttu-id="1a15a-113">Para obtener más información sobre lo que se necesita para que se detecte un número de Passport de US/UK para el contenido, consulte la siguiente sección de este artículo: [Qué buscan los tipos de información confidencial para el número de pasaporte de Estados Unidos/Reino Unido](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)</span><span class="sxs-lookup"><span data-stu-id="1a15a-113">For more information on what is required for a US/UK Passport Number to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US/UK Passport Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)</span></span>
  
<span data-ttu-id="1a15a-114">Con un tipo de información confidencial integrado diferente, vea el siguiente artículo para obtener información sobre lo que se necesita para otros tipos: [Qué buscan los tipos de información confidencial](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="1a15a-114">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  