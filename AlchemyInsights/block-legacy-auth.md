---
title: BlockLegacyAuth
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3154"
- "9001194"
ms.openlocfilehash: e7bff5f9fcf6f2f2c77e93c2f27f585f2cc18bea
ms.sourcegitcommit: 98231a228ecb2bf14ec3b96d4dd4ccf2507617a3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/01/2020
ms.locfileid: "43079277"
---
# <a name="blocking-legacy-authentication"></a><span data-ttu-id="33ba1-102">Bloqueo de la autenticación heredada</span><span class="sxs-lookup"><span data-stu-id="33ba1-102">Blocking legacy authentication</span></span>

<span data-ttu-id="33ba1-103">La autenticación heredada es un término que hace referencia a una solicitud de autenticación realizada por:</span><span class="sxs-lookup"><span data-stu-id="33ba1-103">Legacy authentication is a term that refers to an authentication request made by:</span></span>

- <span data-ttu-id="33ba1-104">Clientes de Office antiguos que no usan la autenticación moderna (por ejemplo, Office 2010 Client).</span><span class="sxs-lookup"><span data-stu-id="33ba1-104">Older Office clients that do not use modern authentication (for example, Office 2010 client).</span></span>

- <span data-ttu-id="33ba1-105">Cualquier cliente que use protocolos de correo heredados, como IMAP/SMTP/POP3.</span><span class="sxs-lookup"><span data-stu-id="33ba1-105">Any client that uses legacy mail protocols such as IMAP/SMTP/POP3.</span></span>

<span data-ttu-id="33ba1-106">Para obtener más información sobre el bloqueo de la autenticación heredada y la habilitación de la autenticación moderna, consulte [blocking Legacy Authentication](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-conditional-access-block-legacy-authentication).</span><span class="sxs-lookup"><span data-stu-id="33ba1-106">For more information on blocking legacy authentication and enabling modern authentication, refer to [Blocking legacy authentication](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-conditional-access-block-legacy-authentication).</span></span>

<span data-ttu-id="33ba1-107">Los valores predeterminados de seguridad en Azure Active Directory (Azure AD) hacen que sea más fácil ser seguro y ayudar a proteger su organización.</span><span class="sxs-lookup"><span data-stu-id="33ba1-107">Security defaults in Azure Active Directory (Azure AD) make it easier to be secure and help protect your organization.</span></span> <span data-ttu-id="33ba1-108">Los valores predeterminados de seguridad contienen configuraciones de seguridad preconfiguradas para ataques comunes.</span><span class="sxs-lookup"><span data-stu-id="33ba1-108">Security defaults contain preconfigured security settings for common attacks.</span></span>
<span data-ttu-id="33ba1-109">Para obtener más información acerca de los valores predeterminados de seguridad, consulte [¿Qué son los valores predeterminados de seguridad?](https://docs.microsoft.com/azure/active-directory/fundamentals/concept-fundamentals-security-defaults).</span><span class="sxs-lookup"><span data-stu-id="33ba1-109">For more information about security defaults, refer to [What are security defaults?](https://docs.microsoft.com/azure/active-directory/fundamentals/concept-fundamentals-security-defaults).</span></span> 

<span data-ttu-id="33ba1-110">**Nota**: Si el inquilino se creó el 22 de octubre de 2019, es posible que esté experimentando el nuevo comportamiento seguro de forma predeterminada y que ya tenga habilitada la seguridad predeterminada en su espacio empresarial.</span><span class="sxs-lookup"><span data-stu-id="33ba1-110">**Note**:  If your tenant was created on or after October 22nd, 2019, it's possible you are experiencing the new secure-by-default behavior and already have security defaults enabled in your tenant.</span></span>  <span data-ttu-id="33ba1-111">En un esfuerzo por proteger a todos los usuarios, los valores predeterminados de seguridad se implementan en todos los nuevos inquilinos creados.</span><span class="sxs-lookup"><span data-stu-id="33ba1-111">In an effort to protect all of our users, security defaults is being rolled out to all new tenants created.</span></span>
