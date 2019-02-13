---
title: Reglas de DLP para nosotros número de cuenta bancaria no funciona
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
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29916433"
---
¿Tiene problemas con la **Prevención de pérdida de datos (DLP)** no funciona para el contenido que contiene un **Número de cuenta bancaria de Estados Unidos** cuando se utiliza un tipo de información confidencial de DLP en Office 365? Si es así, asegúrese de que el contenido contiene la información necesaria para lo que la directiva de DLP está buscando cuando se evalúa. 
  
Por ejemplo, para una directiva de **Número de cuenta bancaria de Estados Unidos** configurada con un nivel de confianza de 85%, el siguiente se evalúa y debe detectarse para que desencadenan la regla: 
  
- **[Formato:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 dígitos 
    
- **[Patrón:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** dígitos consecutivos de 8-17. 
    
- **[Suma de comprobación:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, no hay ninguna suma de comprobación 
    
- **[Definición:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** Una directiva de DLP está seguro de que ha detectado este tipo de información confidencial al 75% if, dentro de una proximidad de 300 caracteres: 
    
  - La expresión regular Regex_usa_bank_account_number busca contenido que coincide con el patrón
    
  - Se encuentra una palabra clave de Keyword_usa_Bank_Account.
    
    Por ejemplo, podría desencadenar en el siguiente ejemplo para la directiva de **Número de cuenta bancaria de Estados Unidos** : cuenta corriente 78344011 
    
Para obtener más información sobre lo que se requiere para un **Número de cuenta bancaria de Estados Unidos** para que detecte para su contenido, vea la siguiente sección de este artículo: [¿Qué el confidencial tipos de información busque el número de cuenta bancaria de Estados Unidos](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)
  
Uso de un tipo de información confidencial integrada diferente, vea el siguiente artículo para obtener información en lo que se requiere para otros tipos de: [Buscar qué el confidencial tipos de información](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  

