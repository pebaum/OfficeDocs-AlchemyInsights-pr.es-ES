---
title: 646 cómo configurar AADConnect
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 599698ac-6709-477a-a66f-169b3165064e
ms.openlocfilehash: dd6d6986b23c8adcc98fe713bacf32fb5bf8b4b6
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29915605"
---
# <a name="configure-sync-features"></a><span data-ttu-id="bbc5f-102">Configurar las características de sincronización</span><span class="sxs-lookup"><span data-stu-id="bbc5f-102">Configure sync features</span></span>

<span data-ttu-id="bbc5f-p101">Conectar de Azure AD incluye varias características que están habilitadas de forma predeterminada, o puede habilitar posteriormente. Algunas características requieren una configuración adicional en entornos específicos.</span><span class="sxs-lookup"><span data-stu-id="bbc5f-p101">Azure AD Connect includes several features that are enabled by default, or that you can enable later. Some features require additional configuration in specific environments.</span></span>
  
- <span data-ttu-id="bbc5f-p102">Límites de [filtrado de](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) los objetos se sincronizan en Azure AD. De forma predeterminada, todos los usuarios, contactos, grupos y 10 de Windows se sincronizan las cuentas de equipo. Puede incluir o excluir objetos basados en dominios, unidades organizativas u otros atributos.</span><span class="sxs-lookup"><span data-stu-id="bbc5f-p102">[Filtering](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) limits the objects are synchronized to Azure AD. By default, all users, contacts, groups, and Windows 10 computer accounts are synchronized. You can include or exclude objects based on domains, OUs, or other attributes.</span></span> 
    
- <span data-ttu-id="bbc5f-p103">[Sincronización de hash de contraseña](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) sincroniza el hash de contraseña de Active Directory local a Azure AD. Esto permite la administración de contraseñas en una ubicación, pero el uso de la misma contraseña en ambos local y entornos de nube. Dado que Active Directory es el origen de autoridad, puede usar sus propias directivas de contraseña.</span><span class="sxs-lookup"><span data-stu-id="bbc5f-p103">[Password hash syncronization](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) synchronizes the password hash from the on-premises Active Directory to Azure AD. This allows password management in one location, but use of the same password in both on-premises and cloud environments. Because Active Directory is the authoritative source, you can use your own password policies.</span></span> 
    
- <span data-ttu-id="bbc5f-111">[Restablecimiento de contraseñas de autoservicio (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) permite a los usuarios restablecer sus propias contraseñas en la nube mientras se sigue aplicando la directiva de contraseñas local.</span><span class="sxs-lookup"><span data-stu-id="bbc5f-111">[Self-service password reset (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) allows users to reset their own passwords in the cloud while still applying your on-premises password policy.</span></span> 
    
- <span data-ttu-id="bbc5f-112">[Reescritura de dispositivo](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) permite que los dispositivos registrados en Azure AD para se escribe en Active Directory local para que se puedan utilizar para el acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="bbc5f-112">[Device writeback](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) allows registered devices in Azure AD to be written back to the on-premises Active Directory so they can be used for conditional access.</span></span> 
    
- <span data-ttu-id="bbc5f-p104">[Evitar eliminaciones accidental elimina](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) está habilitado de forma predeterminada para ayudar a evitar que demasiados eliminaciones de objetos simultáneos (más de 500 objetos por sincronización). Puede cambiar esta configuración para satisfacer las necesidades de su organización.</span><span class="sxs-lookup"><span data-stu-id="bbc5f-p104">[Prevent accidental deletes](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) is enabled by default to help prevent too many simultaneous object deletions (more than 500 objects per synchronization). You can change this setting to meet the needs of your organization.</span></span> 
    
- <span data-ttu-id="bbc5f-115">[Actualización automática](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) está habilitada de forma predeterminada para las instalaciones de express y ayuda a garantiza que su versión de Azure Connect AD siempre es actual.</span><span class="sxs-lookup"><span data-stu-id="bbc5f-115">[Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) is enabled by default for express installations and helps ensure your version of Azure AD Connect is always current.</span></span> 
    

