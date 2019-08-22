---
title: Error AttributeValueMustBeUnique
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: bf8ac830-6f0c-4616-827d-987616700e59
ms.openlocfilehash: 5ac56fa78c66cf3b246bc0cc01f040e27310d629
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36527064"
---
# <a name="error-attributevaluemustbeunique"></a>Error: AttributeValueMustBeUnique

La causa más común del error AttributeValueMustBeUnique son dos objetos con diferentes SourceAnchor (immutableId) que tienen el mismo valor para los atributos ProxyAddresses y UserPrincipalName. Para corregir el error AttributeValueMustBeUnique:
  
1. Identifique el valor de atributo proxyAddresses, userPrincipalName u otro atributo duplicado que está causando el error. Identifique también qué dos (o más) objetos participan en el conflicto. El informe generado por Azure AD Connect Health for Sync puede ayudarle a identificar los dos objetos.
    
2. Identifique qué objeto debe seguir teniendo el valor duplicado y qué objeto no debería.
    
3. Quite el valor duplicado del objeto que no debe tener ese valor. Tenga en cuenta que debe realizar el cambio en el directorio desde el que se origina el objeto. En algunos casos, es posible que deba eliminar uno de los objetos en conflicto.
    
4. Si realizó el cambio en el anuncio local, deje que Azure AD Connect sincronice el cambio para que se corrija el error.
    

