---
title: Error AttributeValueMustBeUnique
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: bf8ac830-6f0c-4616-827d-987616700e59
ms.openlocfilehash: 7a97d1a5ff352b55833bd457e3220a56130d7e7e
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29499651"
---
# <a name="error-attributevaluemustbeunique"></a>Error: AttributeValueMustBeUnique

La razón más común para el error AttributeValueMustBeUnique es dos objetos con diferente SourceAnchor (immutableId) tienen el mismo valor para los atributos ProxyAddresses o UserPrincipalName. Para solucionar el error AttributeValueMustBeUnique:
  
1. Identificar el proxyAddresses duplicada, userPrincipalName u otro valor de atributo que está provocando el error. También identificar qué objetos dos (o más) están implicados en el conflicto. El informe generado por Azure AD conectar mantenimiento para sincronización puede ayudarle a identificar los dos objetos.
    
2. Identificar qué objeto debería seguir tienen el valor duplicado y qué objeto no se debe.
    
3. Quitar el valor duplicado del objeto de que no debería tener ese valor. Tenga en cuenta que debe realizar el cambio en el directorio donde el objeto es proceden de un. En algunos casos, debe eliminar uno de los objetos en conflicto.
    
4. Si realizó el cambio en el local AD, permiten a Azure Connect AD sincronizar el cambio del error obtener fijo.
    

