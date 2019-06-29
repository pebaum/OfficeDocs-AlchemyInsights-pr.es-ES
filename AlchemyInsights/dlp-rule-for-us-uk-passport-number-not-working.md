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
ms.openlocfilehash: 0567e9521507bcc192b187d0e5a8a0658332ff99
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/28/2019
ms.locfileid: "35389558"
---
# <a name="problems-with-dlp---usuk-passport-numbers"></a>Problemas con números de pasaporte de DLP-US/UK

¿Tiene problemas con la **prevención de pérdida de datos (DLP)** que no funciona para contenido que contiene un **número de pasaporte de Estados Unidos** al usar un tipo de información confidencial de DLP en O365? Si es así, asegúrese de que el contenido contiene la información necesaria para lo que la Directiva de DLP está buscando cuando se evalúa.
  
Por ejemplo, para una directiva de **número de pasaporte de Estados Unidos** configurada con un nivel de confianza del 75%, se evalúa lo siguiente y debe detectarse para que la regla desencadene
  
- **[Formato:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Nueve dígitos

- **[Patrón:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Nueve dígitos consecutivos

- **[Suma de comprobación:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, no hay ninguna suma de comprobación

- **[Definición:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** Una directiva DLP está 75% segura de que se detecta este tipo de información confidencial si, en una proximidad de 300 caracteres:

  - La función Func_usa_uk_passport encuentra contenido que coincide con el patrón.

  - Se encuentra una palabra clave de Keyword_passport.

    Por ejemplo, el siguiente ejemplo se activaría para la Directiva de **número de pasaporte de Estados Unidos** : número de pasaporte de estados Unidos 123456789

Para obtener más información sobre lo que se necesita para que se detecte un número de Passport de US/UK para el contenido, consulte la siguiente sección de este artículo: [Qué buscan los tipos de información confidencial para el número de pasaporte de Estados Unidos/Reino Unido](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)
  
Con un tipo de información confidencial integrado diferente, vea el siguiente artículo para obtener información sobre lo que se necesita para otros tipos: [Qué buscan los tipos de información confidencial](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  