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
ms.openlocfilehash: cb1b50792b07a1b3b69607bf2f6824141a15922f
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "32408125"
---
# <a name="consistencyguid--sourceanchor-behavior"></a><span data-ttu-id="b8929-102">Comportamiento de ConsistencyGuid/sourceAnchor</span><span class="sxs-lookup"><span data-stu-id="b8929-102">ConsistencyGuid / sourceAnchor behavior</span></span>

<span data-ttu-id="b8929-103">Azure AD Connect (versión 1.1.524.0 y After) ahora facilita el uso de msDS-ConsistencyGuid como atributo sourceAnchor.</span><span class="sxs-lookup"><span data-stu-id="b8929-103">Azure AD Connect (version 1.1.524.0 and after) now facilitates the use of msDS-ConsistencyGuid as sourceAnchor attribute.</span></span> <span data-ttu-id="b8929-104">Cuando se usa esta característica, Azure AD Connect configura automáticamente las reglas de sincronización para:</span><span class="sxs-lookup"><span data-stu-id="b8929-104">When using this feature, Azure AD Connect automatically configures the synchronization rules to:</span></span>
  
- <span data-ttu-id="b8929-105">Use msDS-ConsistencyGuid como atributo sourceAnchor para objetos de usuario.</span><span class="sxs-lookup"><span data-stu-id="b8929-105">Use msDS-ConsistencyGuid as the sourceAnchor attribute for User objects.</span></span> <span data-ttu-id="b8929-106">ObjectGUID se usa para otros tipos de objeto.</span><span class="sxs-lookup"><span data-stu-id="b8929-106">ObjectGUID is used for other object types.</span></span>
    
- <span data-ttu-id="b8929-107">Para un objeto de usuario de AD local dado cuyo atributo msDS-ConsistencyGuid no está rellenado, Azure AD Connect vuelve a escribir el valor de objectGUID en el atributo msDS-ConsistencyGuid de Active Directory local.</span><span class="sxs-lookup"><span data-stu-id="b8929-107">For any given on-premises AD User object whose msDS-ConsistencyGuid attribute isn't populated, Azure AD Connect writes its objectGUID value back to the msDS-ConsistencyGuid attribute in on-premises Active Directory.</span></span> <span data-ttu-id="b8929-108">Una vez que se haya rellenado el atributo msDS-ConsistencyGuid, Azure AD Connect exportará el objeto a Azure AD.</span><span class="sxs-lookup"><span data-stu-id="b8929-108">After the msDS-ConsistencyGuid attribute is populated, Azure AD Connect then exports the object to Azure AD.</span></span>
    
 <span data-ttu-id="b8929-109">**Nota:** Una vez que un objeto de AD local se importa a Azure AD Connect (es decir, se importa en el espacio de conector de AD y se proyecta en el metaverso), no puede cambiar su valor de sourceAnchor ya.</span><span class="sxs-lookup"><span data-stu-id="b8929-109">**Note:** Once an on-premises AD object is imported into Azure AD Connect (that is, imported into the AD Connector Space and projected into the Metaverse), you cannot change its sourceAnchor value anymore.</span></span> <span data-ttu-id="b8929-110">Para especificar el valor sourceAnchor para un objeto AD local determinado, configure su atributo msDS-ConsistencyGuid antes de importarlo a Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="b8929-110">To specify the sourceAnchor value for a given on-premises AD object, configure its msDS-ConsistencyGuid attribute before it is imported into Azure AD Connect.</span></span> 
  
<span data-ttu-id="b8929-111">Para obtener más información sobre SourceAnchor y ConsistencyGuid, consulte lo siguiente: [Azure ad Connect: conceptos de diseño](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span><span class="sxs-lookup"><span data-stu-id="b8929-111">For more information on SourceAnchor and ConsistencyGuid, refer to the following: [Azure AD Connect: Design concepts](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span></span>
  

