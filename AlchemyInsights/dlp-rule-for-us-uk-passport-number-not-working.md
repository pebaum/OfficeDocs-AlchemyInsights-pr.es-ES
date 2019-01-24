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
¿Tiene problemas con la **Prevención de pérdida de datos (DLP)** no funciona para que contiene contenido un **US / número de pasaporte del Reino Unido** cuando se utiliza un tipo de información confidencial de DLP en Office 365? Si es así, asegúrese de que el contenido contiene la información necesaria para lo que la directiva de DLP está buscando cuando se evalúa. 
  
Por ejemplo, para un **US / número de pasaporte del Reino Unido** directiva configurada con un nivel de confianza de un 75%, el siguiente se evalúan y deben detectarse para que desencadenan la regla 
  
- **[Formato:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Nueve dígitos 
    
- **[Patrón:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Nueve dígitos consecutivos 
    
- **[Suma de comprobación:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, no hay ninguna suma de comprobación 
    
- **[Definición:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** Una directiva de DLP está seguro de que ha detectado este tipo de información confidencial al 75% if, dentro de una proximidad de 300 caracteres: 
    
  - La función Func_usa_uk_passport encuentra contenido que coincide con el patrón.
    
  - Se encuentra una palabra clave de Keyword_passport.
    
    Por ejemplo, podría desencadenar en el siguiente ejemplo para el **US / número de pasaporte del Reino Unido** directiva: número de Estados Unidos Passport 123456789 
    
Para obtener más información sobre lo que se requiere para un US / número de pasaporte Reino Unido para que detecte para su contenido, vea la siguiente sección de este artículo: [aspecto de lo que el confidencial tipos de información para los Estados Unidos o Reino Unido Passport número](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)
  
Uso de un tipo de información confidencial integrada diferente, vea el siguiente artículo para obtener información en lo que se requiere para otros tipos de: [Buscar qué el confidencial tipos de información](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  

