---
title: La regla DLP para el número de tarjeta de crédito no funciona
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1270"
- "3200001"
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: 80ff41b3e746f95278ccbf0df19eebb61f7f9ee0
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43704218"
---
# <a name="dlp-issues-with-credit-card-numbers"></a>Problemas de DLP con números de tarjeta de crédito

**Importante**: durante estos tiempos, se siguen pasos para asegurarse de que los servicios de SharePoint Online y OneDrive estén altamente disponibles. Para obtener más información, visite [Ajustes temporales de características de SharePoint Online](https://aka.ms/ODSPAdjustments).

**Problemas de DLP con números de tarjeta de crédito**

¿Tiene problemas con la **prevención de pérdida de datos (DLP)** que no funciona para contenido que contiene un **número de tarjeta de crédito** al usar un tipo de información confidencial de DLP en O365? Si es así, asegúrese de que el contenido contiene la información necesaria para desencadenar la Directiva DLP cuando se evalúe. Por ejemplo, para una **Directiva de tarjeta de crédito** configurada con un nivel de confianza del 85%, se evalúa lo siguiente y debe detectarse para que la regla desencadene:
  
- **[Formato:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 dígitos que pueden ser formateados o sin formato (dddddddddddddddd) y deben pasar la prueba Luhn.

- **[Patrón:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Patrón muy complejo y robusto que detecta las tarjetas de todas las principales marcas en todo el mundo, incluidas Visa, MasterCard, Tarjeta Discover, JCB, American Express, tarjetas regalo y tarjetas de comensal.

- **[Suma de comprobación:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Sí, la suma de comprobación Luhn

- **[Definición:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** Una directiva DLP está 85% segura de que se detecta este tipo de información confidencial si, en una proximidad de 300 caracteres:

  - La función Func_credit_card encuentra contenido que coincide con el patrón.

  - Una de las siguientes opciones es verdadera:

  - Se encuentra una palabra clave de Keyword_cc_verification.

  - Se encuentra una palabra clave de Keyword_cc_name

  - La función Func_expiration_date encuentra una fecha en el formato de fecha correcto.

  - La suma de comprobación pasa

    Por ejemplo, el siguiente ejemplo se activaría para una directiva de número de tarjeta de crédito DLP:

  - Visa: 4485 3647 3952 7352
  
  - Expira: 2/2009

Para obtener más información sobre lo que se necesita para que se detecte un **número de tarjeta de crédito** para el contenido, vea la siguiente sección de este artículo: [¿qué aspecto tienen los tipos de información confidencial para la tarjeta de crédito #](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)
  
Con un tipo de información confidencial integrado diferente, vea el siguiente artículo para obtener información sobre lo que se necesita para otros tipos: [Qué buscan los tipos de información confidencial](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  