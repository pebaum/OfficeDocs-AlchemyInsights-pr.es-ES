---
title: ConsistencyGuid / sourceAnchor comportamiento
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 6a44f797-acc7-4cbe-aa5a-47e2581fabf5
ms.openlocfilehash: 80516ed9e15040475a8b65a1af98a1b561704d49
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29498535"
---
# <a name="consistencyguid--sourceanchor-behavior"></a>ConsistencyGuid / sourceAnchor comportamiento

Conectar de Azure AD (versión 1.1.524.0 y posterior) ahora facilita el uso de msDS-ConsistencyGuid como atributo de sourceAnchor. Cuando se usa esta característica, Azure Connect AD configura automáticamente las reglas de sincronización para:
  
- Usar msDS-ConsistencyGuid como el atributo sourceAnchor para objetos de usuario. GUID de objeto se usa para otros tipos de objeto.
    
- Para cualquier dado local AD usuario objeto cuyo atributo msDS-ConsistencyGuid no está llenas, Azure escrituras AD conectar hacer una copia de su valor de GUID de objeto para el atributo msDS-ConsistencyGuid en Active Directory local. Después de que se rellena el atributo msDS-ConsistencyGuid, Azure Connect de AD, a continuación, exporta el objeto a Azure AD.
    
 **Nota:** Una vez un local de objeto de AD se importan a Azure Connect AD (es decir, importar en el espacio de conector de AD y proyectan en Metaverse), no se puede cambiar su valor sourceAnchor ya. Para especificar el valor de sourceAnchor para un dado local AD de objetos, configure el atributo msDS-ConsistencyGuid antes de que se importa en Azure Connect de AD. 
  
Para obtener más información en SourceAnchor y ConsistencyGuid, hacer referencia a los siguientes elementos: [Azure Connect AD: conceptos de diseño](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect-design-concepts)
  

