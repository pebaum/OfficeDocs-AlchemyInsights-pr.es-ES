---
title: 646 cómo configurar los
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "646"
- "1300023"
ms.assetid: 599698ac-6709-477a-a66f-169b3165064e
ms.openlocfilehash: 0569cb10c1d1dd422709de5d2569e43ee9d75386
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/28/2019
ms.locfileid: "35385389"
---
# <a name="configure-sync-features"></a>Configurar las características de sincronización

Azure AD Connect incluye varias características que están habilitadas de forma predeterminada o que puede habilitar más adelante. Algunas características requieren una configuración adicional en entornos específicos.

- Límites de [filtrado](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) los objetos se sincronizan con Azure ad. De forma predeterminada, todos los usuarios, contactos, grupos y cuentas de equipo de Windows 10 están sincronizados. Puede incluir o excluir objetos basados en dominios, unidades organizativas u otros atributos.

- La [sincronización de hash de contraseña](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) sincroniza el hash de contraseña de Active Directory local con Azure ad. Esto permite la administración de contraseñas en una ubicación, pero usa la misma contraseña en entornos locales y en la nube. Como Active Directory es el origen de autoridad, puede usar sus propias directivas de contraseñas.

- El [restablecimiento de contraseña de autoservicio (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) permite a los usuarios restablecer sus propias contraseñas en la nube y, al mismo tiempo, aplicar la Directiva de contraseña local.

- La reescritura de [dispositivo](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) permite que los dispositivos registrados de Azure ad se vuelvan a escribir en Active Directory local, de modo que se puedan usar para el acceso condicional.

- [Impedir eliminaciones accidentales](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) está habilitada de forma predeterminada para ayudar a evitar que se eliminen objetos simultáneamente (más de 500 objetos por sincronización). Puede cambiar esta configuración para satisfacer las necesidades de su organización.

- La [actualización automática](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) está habilitada de forma predeterminada para las instalaciones Express y ayuda a garantizar que la versión de Azure ad Connect siempre esté actualizada.
