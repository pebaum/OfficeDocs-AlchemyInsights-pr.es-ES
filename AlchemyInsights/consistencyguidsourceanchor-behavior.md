---
title: Comportamiento de ConsistencyGuid/sourceAnchor
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 6a44f797-acc7-4cbe-aa5a-47e2581fabf5
ms.openlocfilehash: 8527e7c2404742a999041f85ed12d78c48cc0d8c
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43705750"
---
# <a name="consistencyguid--sourceanchor-behavior"></a>Comportamiento de ConsistencyGuid/sourceAnchor

Azure AD Connect (versión 1.1.524.0 y After) ahora facilita el uso de msDS-ConsistencyGuid como atributo sourceAnchor. Cuando se usa esta característica, Azure AD Connect configura automáticamente las reglas de sincronización para:
  
- Use msDS-ConsistencyGuid como atributo sourceAnchor para objetos de usuario. ObjectGUID se usa para otros tipos de objeto.
    
- Para un objeto de usuario de AD local dado cuyo atributo msDS-ConsistencyGuid no está rellenado, Azure AD Connect vuelve a escribir el valor de objectGUID en el atributo msDS-ConsistencyGuid de Active Directory local. Una vez que se haya rellenado el atributo msDS-ConsistencyGuid, Azure AD Connect exportará el objeto a Azure AD.
    
 **Nota:** Una vez que un objeto de AD local se importa a Azure AD Connect (es decir, se importa en el espacio de conector de AD y se proyecta en el metaverso), no puede cambiar su valor de sourceAnchor ya. Para especificar el valor sourceAnchor para un objeto AD local determinado, configure su atributo msDS-ConsistencyGuid antes de importarlo a Azure AD Connect. 
  
Para obtener más información sobre SourceAnchor y ConsistencyGuid, consulte lo siguiente: [Azure ad Connect: conceptos de diseño](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)
  

