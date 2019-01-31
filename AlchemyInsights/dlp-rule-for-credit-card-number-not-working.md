---
title: Reglas de DLP para el número de tarjeta de crédito no funciona
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: 4b8897c5cc8286bc4bd49860658a5a94ad17380d
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/30/2019
ms.locfileid: "29657484"
---
¿Tiene problemas con la **Prevención de pérdida de datos (DLP)** no funciona para el contenido que contiene un **Número de tarjeta de crédito** cuando se utiliza un tipo de información confidencial de DLP en Office 365? Si es así, asegúrese de que el contenido contiene la información necesaria para desencadenar la cuando se evalúa la directiva de DLP. Por ejemplo, para una **tarjeta de crédito directiva** configurada con un nivel de confianza de 85%, el siguiente se evalúa y debe detectarse para que desencadenan la regla: 
  
- **[Formato:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 dígitos que se pueden dar formato o sin formato (dddddddddddddddd) y debe pasar la prueba Luhn. 
    
- **[Patrón:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Trama muy compleja y eficaz que detecta las tarjetas de todas las marcas principales en todo el mundo, incluidas Visa, Mastercard, tarjeta de descubrir, JCB, American Express, tarjetas de regalo y comensal tarjetas. 
    
- **[Suma de comprobación:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Sí, la suma de comprobación Luhn 
    
- **[Definición:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** Una directiva de DLP es 85% seguro de que ha detectado este tipo de información confidencial if, dentro de una proximidad de 300 caracteres: 
    
  - La función Func_credit_card encuentra contenido que coincide con el patrón.
    
  - Una de las siguientes opciones es verdadera: 
    
  - Se encuentra una palabra clave de Keyword_cc_verification.
    
  - Se encuentra una palabra clave de Keyword_cc_name
    
  - La función Func_expiration_date encuentra una fecha en el formato de fecha correcto.
    
  - Pasa de la suma de comprobación
    
    Por ejemplo, en el ejemplo siguiente sería desencadenar para una directiva de número de tarjeta de crédito de DLP:
    
  - Visa: 4485 3647 3952 7352 
    
  - Caduca: 2/2009
    
Para obtener más información sobre lo que se requiere para un **Número de tarjeta de crédito** a ser detectados para su contenido, vea la siguiente sección de este artículo: [¿Qué el confidencial tipos de información busque tarjeta de crédito #](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)
  
Uso de un tipo de información confidencial integrada diferente, vea el siguiente artículo para obtener información en lo que se requiere para otros tipos de: [Buscar qué el confidencial tipos de información](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  

