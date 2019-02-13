---
title: Reglas de DLP para SSN no funciona
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ac265ee6-c946-476e-9bf0-0ea0e8adc98a
ms.openlocfilehash: d2d21fb5546d36990d69b76e3ceb72ce2edf3d80
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29933497"
---
¿Tiene problemas con la **Prevención de pérdida de datos (DLP)** no funciona para el contenido que contiene un **Número de seguridad Social (SSN)** cuando se utiliza un tipo de información confidencial en Office 365? Si es así, asegúrese de que el contenido contiene la información necesaria para lo que está buscando la directiva de DLP. 
  
Por ejemplo, para una directiva de SSN configurada con un nivel de confianza de 85%, el siguiente se evalúa y debe detectarse para que desencadenan la regla:
  
- **[Formato:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-80)** 9 dígitos, que pueden estar en un patrón con o sin formato 
    
- **[Patrón:](https://msconnect.microsoft.com/https:/docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** Cuatro funciones buscan números de seguridad social en cuatro patrones diferentes: 
    
  - Func_ssn busca SSN con formato seguro anteriores a 2011 y formateados con guiones o espacios (ddd-dd-dddd O ddd dd dddd)
    
  - Func_unformatted_ssn busca SSN con formato seguro anteriores a 2011 y formateados de manera no específica como nueve dígitos consecutivos (ddddddddd)
    
  - Func_randomized_formatted_ssn busca SSN posteriores a 2011 y formateados con guiones o espacios (ddd-dd-dddd O ddd dd dddd)
    
  - Func_randomized_unformatted_ssn busca SSN posteriores a 2011 y formateados de manera no específica como nueve dígitos consecutivos (ddddddddd)
    
- **[Suma de comprobación:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-79)** No, no hay ninguna suma de comprobación 
    
- **[Definición:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-80)** Una directiva de DLP es 85% seguro de que ha detectado este tipo de información confidencial if, dentro de una proximidad de 300 caracteres: 
    
  - La [función Func_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80) busca contenido que coincide con el patrón. 
    
  - Se ha encontrado una palabra clave de [Keyword_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#keyword_ssn) . Incluye ejemplos de palabras clave: *Seguridad Social, la seguridad Social #, seguridad social, SSN* . Por ejemplo, podría desencadenar en el siguiente ejemplo para la directiva de DLP SSN: **SSN: 489-36-8350**
    
Para obtener más información sobre lo que se requiere para números de seguridad social que se detecte su contenido, vea la siguiente sección de este artículo: [¿Qué el confidencial tipos de información buscar números de seguridad social](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-social-security-number-ssn)
  
Uso de un tipo de información confidencial integrada diferente, vea el siguiente artículo para obtener información en lo que se requiere para otros tipos de: [Buscar qué el confidencial tipos de información](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  

