---
title: ConsistencyGuid / sourceAnchor comportamiento
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 6a44f797-acc7-4cbe-aa5a-47e2581fabf5
ms.openlocfilehash: e1ffa9cf2b59570cb6ea3517efad7a55fd9489a8
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29927695"
---
# <a name="consistencyguid--sourceanchor-behavior"></a><span data-ttu-id="9dbfc-102">ConsistencyGuid / sourceAnchor comportamiento</span><span class="sxs-lookup"><span data-stu-id="9dbfc-102">ConsistencyGuid / sourceAnchor behavior</span></span>

<span data-ttu-id="9dbfc-p101">Conectar de Azure AD (versión 1.1.524.0 y posterior) ahora facilita el uso de msDS-ConsistencyGuid como atributo de sourceAnchor. Cuando se usa esta característica, Azure Connect AD configura automáticamente las reglas de sincronización para:</span><span class="sxs-lookup"><span data-stu-id="9dbfc-p101">Azure AD Connect (version 1.1.524.0 and after) now facilitates the use of msDS-ConsistencyGuid as sourceAnchor attribute. When using this feature, Azure AD Connect automatically configures the synchronization rules to:</span></span>
  
- <span data-ttu-id="9dbfc-p102">Usar msDS-ConsistencyGuid como el atributo sourceAnchor para objetos de usuario. GUID de objeto se usa para otros tipos de objeto.</span><span class="sxs-lookup"><span data-stu-id="9dbfc-p102">Use msDS-ConsistencyGuid as the sourceAnchor attribute for User objects. ObjectGUID is used for other object types.</span></span>
    
- <span data-ttu-id="9dbfc-p103">Para cualquier dado local AD usuario objeto cuyo atributo msDS-ConsistencyGuid no está llenas, Azure escrituras AD conectar hacer una copia de su valor de GUID de objeto para el atributo msDS-ConsistencyGuid en Active Directory local. Después de que se rellena el atributo msDS-ConsistencyGuid, Azure Connect de AD, a continuación, exporta el objeto a Azure AD.</span><span class="sxs-lookup"><span data-stu-id="9dbfc-p103">For any given on-premises AD User object whose msDS-ConsistencyGuid attribute isn't populated, Azure AD Connect writes its objectGUID value back to the msDS-ConsistencyGuid attribute in on-premises Active Directory. After the msDS-ConsistencyGuid attribute is populated, Azure AD Connect then exports the object to Azure AD.</span></span>
    
 <span data-ttu-id="9dbfc-p104">**Nota:** Una vez un local de objeto de AD se importan a Azure Connect AD (es decir, importar en el espacio de conector de AD y proyectan en Metaverse), no se puede cambiar su valor sourceAnchor ya. Para especificar el valor de sourceAnchor para un dado local AD de objetos, configure el atributo msDS-ConsistencyGuid antes de que se importa en Azure Connect de AD.</span><span class="sxs-lookup"><span data-stu-id="9dbfc-p104">**Note:** Once an on-premises AD object is imported into Azure AD Connect (that is, imported into the AD Connector Space and projected into the Metaverse), you cannot change its sourceAnchor value anymore. To specify the sourceAnchor value for a given on-premises AD object, configure its msDS-ConsistencyGuid attribute before it is imported into Azure AD Connect.</span></span> 
  
<span data-ttu-id="9dbfc-111">Para obtener más información en SourceAnchor y ConsistencyGuid, hacer referencia a los siguientes elementos: [Azure Connect AD: conceptos de diseño](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span><span class="sxs-lookup"><span data-stu-id="9dbfc-111">For more information on SourceAnchor and ConsistencyGuid, refer to the following: [Azure AD Connect: Design concepts](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span></span>
  

