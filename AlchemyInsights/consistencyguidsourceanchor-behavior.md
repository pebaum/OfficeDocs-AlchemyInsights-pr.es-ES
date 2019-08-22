---
title: Comportamiento de ConsistencyGuid/sourceAnchor
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 6a44f797-acc7-4cbe-aa5a-47e2581fabf5
ms.openlocfilehash: f0ff94a8e46f1fb4e0ac8653c51f8f651e29498b
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36517012"
---
# <a name="consistencyguid--sourceanchor-behavior"></a>Comportamiento de ConsistencyGuid/sourceAnchor

Azure AD Connect (versión 1.1.524.0 y After) ahora facilita el uso de msDS-ConsistencyGuid como atributo sourceAnchor. Cuando se usa esta característica, Azure AD Connect configura automáticamente las reglas de sincronización para:
  
- Use msDS-ConsistencyGuid como atributo sourceAnchor para objetos de usuario. ObjectGUID se usa para otros tipos de objeto.
    
- Para un objeto de usuario de AD local dado cuyo atributo msDS-ConsistencyGuid no está rellenado, Azure AD Connect vuelve a escribir el valor de objectGUID en el atributo msDS-ConsistencyGuid de Active Directory local. Una vez que se haya rellenado el atributo msDS-ConsistencyGuid, Azure AD Connect exportará el objeto a Azure AD.
    
 **Nota:** Una vez que un objeto de AD local se importa a Azure AD Connect (es decir, se importa en el espacio de conector de AD y se proyecta en el metaverso), no puede cambiar su valor de sourceAnchor ya. Para especificar el valor sourceAnchor para un objeto AD local determinado, configure su atributo msDS-ConsistencyGuid antes de importarlo a Azure AD Connect. 
  
Para obtener más información sobre SourceAnchor y ConsistencyGuid, consulte lo siguiente: [Azure ad Connect: conceptos de diseño](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)
  

