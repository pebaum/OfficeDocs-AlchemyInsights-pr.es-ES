---
title: Regla DLP para el número de cuenta bancaria de Estados Unidos no funciona
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1287"
- "3200001"
ms.assetid: 80b40145-8376-4c3a-8d22-6efb9f9cb271
ms.openlocfilehash: 0a32708b5ac8d95ec6777ada2d151a15f90d65bf
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36529899"
---
# <a name="dlp-issues-with-us-bank-account-numbers"></a>Problemas de DLP con números de cuentas bancarias de Estados Unidos

¿Tiene problemas con la **prevención de pérdida de datos (DLP)** que no funciona para contenido que contiene un **número de cuenta bancaria de Estados Unidos** al usar un tipo de información confidencial de DLP en O365? Si es así, asegúrese de que el contenido contiene la información necesaria para lo que la Directiva de DLP está buscando cuando se evalúa.
  
Por ejemplo, para una directiva de **número de cuenta bancaria de Estados Unidos** configurada con un nivel de confianza del 85%, se evalúa lo siguiente y debe detectarse para que la regla desencadene:
  
- **[Formato:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 dígitos

- **[Patrón:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 dígitos consecutivos.

- **[Suma de comprobación:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, no hay ninguna suma de comprobación

- **[Definición:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** Una directiva DLP está 75% segura de que se detecta este tipo de información confidencial si, en una proximidad de 300 caracteres:

  - La expresión regular Regex_usa_bank_account_number encuentra contenido que coincide con el patrón

  - Se encuentra una palabra clave de Keyword_usa_Bank_Account.

    Por ejemplo, el siguiente ejemplo se activaría para la Directiva de **número de cuenta bancaria estadounidense** : comprobando la cuenta 78344011

Para obtener más información sobre lo que se necesita para que se detecte un **número de cuenta bancaria de Estados Unidos** en el contenido, consulte la siguiente sección de este artículo: [Qué buscan los tipos de información confidencial en su número de cuenta bancaria](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)
  
Con un tipo de información confidencial integrado diferente, vea el siguiente artículo para obtener información sobre lo que se necesita para otros tipos: [Qué buscan los tipos de información confidencial](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  