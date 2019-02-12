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
# <a name="configure-sync-features"></a>Configurar las características de sincronización

Conectar de Azure AD incluye varias características que están habilitadas de forma predeterminada, o puede habilitar posteriormente. Algunas características requieren una configuración adicional en entornos específicos.
  
- Límites de [filtrado de](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) los objetos se sincronizan en Azure AD. De forma predeterminada, todos los usuarios, contactos, grupos y 10 de Windows se sincronizan las cuentas de equipo. Puede incluir o excluir objetos basados en dominios, unidades organizativas u otros atributos. 
    
- [Sincronización de hash de contraseña](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) sincroniza el hash de contraseña de Active Directory local a Azure AD. Esto permite la administración de contraseñas en una ubicación, pero el uso de la misma contraseña en ambos local y entornos de nube. Dado que Active Directory es el origen de autoridad, puede usar sus propias directivas de contraseña. 
    
- [Restablecimiento de contraseñas de autoservicio (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) permite a los usuarios restablecer sus propias contraseñas en la nube mientras se sigue aplicando la directiva de contraseñas local. 
    
- [Reescritura de dispositivo](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) permite que los dispositivos registrados en Azure AD para se escribe en Active Directory local para que se puedan utilizar para el acceso condicional. 
    
- [Evitar eliminaciones accidental elimina](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) está habilitado de forma predeterminada para ayudar a evitar que demasiados eliminaciones de objetos simultáneos (más de 500 objetos por sincronización). Puede cambiar esta configuración para satisfacer las necesidades de su organización. 
    
- [Actualización automática](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) está habilitada de forma predeterminada para las instalaciones de express y ayuda a garantiza que su versión de Azure Connect AD siempre es actual. 
    

