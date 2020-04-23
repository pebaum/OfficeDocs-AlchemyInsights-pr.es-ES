---
title: 646 cómo configurar los
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "646"
- "1300023"
ms.assetid: 599698ac-6709-477a-a66f-169b3165064e
ms.openlocfilehash: 713cda26e55f07f0438cb9ebe5aa9da86c4ebb3a
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43722580"
---
# <a name="configure-sync-features"></a><span data-ttu-id="c47d9-102">Configurar las características de sincronización</span><span class="sxs-lookup"><span data-stu-id="c47d9-102">Configure sync features</span></span>

<span data-ttu-id="c47d9-103">Azure AD Connect incluye varias características que están habilitadas de forma predeterminada o que puede habilitar más adelante.</span><span class="sxs-lookup"><span data-stu-id="c47d9-103">Azure AD Connect includes several features that are enabled by default, or that you can enable later.</span></span> <span data-ttu-id="c47d9-104">Algunas características requieren una configuración adicional en entornos específicos.</span><span class="sxs-lookup"><span data-stu-id="c47d9-104">Some features require additional configuration in specific environments.</span></span>

- <span data-ttu-id="c47d9-105">Límites de [filtrado](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) los objetos se sincronizan con Azure ad.</span><span class="sxs-lookup"><span data-stu-id="c47d9-105">[Filtering](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-configure-filtering) limits the objects are synchronized to Azure AD.</span></span> <span data-ttu-id="c47d9-106">De forma predeterminada, todos los usuarios, contactos, grupos y cuentas de equipo de Windows 10 están sincronizados.</span><span class="sxs-lookup"><span data-stu-id="c47d9-106">By default, all users, contacts, groups, and Windows 10 computer accounts are synchronized.</span></span> <span data-ttu-id="c47d9-107">Puede incluir o excluir objetos basados en dominios, unidades organizativas u otros atributos.</span><span class="sxs-lookup"><span data-stu-id="c47d9-107">You can include or exclude objects based on domains, OUs, or other attributes.</span></span>

- <span data-ttu-id="c47d9-108">La [sincronización de hash de contraseña](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) sincroniza el hash de contraseña de Active Directory local con Azure ad.</span><span class="sxs-lookup"><span data-stu-id="c47d9-108">[Password hash synchronization](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-implement-password-hash-synchronization) synchronizes the password hash from the on-premises Active Directory to Azure AD.</span></span> <span data-ttu-id="c47d9-109">Esto permite la administración de contraseñas en una ubicación, pero usa la misma contraseña en entornos locales y en la nube.</span><span class="sxs-lookup"><span data-stu-id="c47d9-109">This allows password management in one location, but use of the same password in both on-premises and cloud environments.</span></span> <span data-ttu-id="c47d9-110">Como Active Directory es el origen de autoridad, puede usar sus propias directivas de contraseñas.</span><span class="sxs-lookup"><span data-stu-id="c47d9-110">Because Active Directory is the authoritative source, you can use your own password policies.</span></span>

- <span data-ttu-id="c47d9-111">El [restablecimiento de contraseña de autoservicio (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) permite a los usuarios restablecer sus propias contraseñas en la nube y, al mismo tiempo, aplicar la Directiva de contraseña local.</span><span class="sxs-lookup"><span data-stu-id="c47d9-111">[Self-service password reset (SSPR)](https://docs.microsoft.com/azure/active-directory/authentication/quickstart-sspr) allows users to reset their own passwords in the cloud while still applying your on-premises password policy.</span></span>

- <span data-ttu-id="c47d9-112">La [reescritura de dispositivo](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) permite que los dispositivos registrados de Azure ad se vuelvan a escribir en Active Directory local, de modo que se puedan usar para el acceso condicional.</span><span class="sxs-lookup"><span data-stu-id="c47d9-112">[Device writeback](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-device-writeback) allows registered devices in Azure AD to be written back to the on-premises Active Directory so they can be used for conditional access.</span></span>

- <span data-ttu-id="c47d9-113">[Impedir eliminaciones accidentales](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) está habilitada de forma predeterminada para ayudar a evitar que se eliminen objetos simultáneamente (más de 500 objetos por sincronización).</span><span class="sxs-lookup"><span data-stu-id="c47d9-113">[Prevent accidental deletes](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-feature-prevent-accidental-deletes) is enabled by default to help prevent too many simultaneous object deletions (more than 500 objects per synchronization).</span></span> <span data-ttu-id="c47d9-114">Puede cambiar esta configuración para satisfacer las necesidades de su organización.</span><span class="sxs-lookup"><span data-stu-id="c47d9-114">You can change this setting to meet the needs of your organization.</span></span>

- <span data-ttu-id="c47d9-115">La [actualización automática](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) está habilitada de forma predeterminada para las instalaciones Express y ayuda a garantizar que la versión de Azure ad Connect siempre esté actualizada.</span><span class="sxs-lookup"><span data-stu-id="c47d9-115">[Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade) is enabled by default for express installations and helps ensure your version of Azure AD Connect is always current.</span></span>
