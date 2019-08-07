---
title: Problemas con MFA
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.custom:
- "2417"
- "9000557"
ms.openlocfilehash: 2e79040c249b7825b964a19c51bcc42e5a6afb3f
ms.sourcegitcommit: 514ced512d0d7fff485b6fbf236cd27d6b4166e0
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/26/2019
ms.locfileid: "35250182"
---
# <a name="issues-with-mfa"></a><span data-ttu-id="ce594-102">Problemas con MFA</span><span class="sxs-lookup"><span data-stu-id="ce594-102">Issues with MFA</span></span>
<span data-ttu-id="ce594-103">Hay un par de cosas para comprobar si los usuarios no pueden iniciar sesión mediante la autenticación multifactor (MFA).</span><span class="sxs-lookup"><span data-stu-id="ce594-103">There are a couple of things to check if users cannot login using multi-factor authentication (MFA)</span></span>

1. <span data-ttu-id="ce594-104">Es posible que el usuario afectado esté bloqueado en el portal de Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="ce594-104">The affected user may be blocked in Azure Active Directory Portal.</span></span> <span data-ttu-id="ce594-105">Si ese es el caso, los intentos de autenticación para ese usuario específico se denegarán automáticamente.</span><span class="sxs-lookup"><span data-stu-id="ce594-105">If that is the case, Authentication attempts for that specific user will be automatically denied.</span></span> [<span data-ttu-id="ce594-106">Siga los pasos de este artículo para desbloquearlos.</span><span class="sxs-lookup"><span data-stu-id="ce594-106">Please follow the steps in this article to unblock them.</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#block-and-unblock-users)

2. <span data-ttu-id="ce594-107">Si el proceso de desbloqueo del usuario no es de ayuda o el usuario no está bloqueado, puede intentar restablecer la MFA para el usuario y se volverá a pasar por el proceso de inscripción.</span><span class="sxs-lookup"><span data-stu-id="ce594-107">If unblocking the user didn't help or the user is not blocked you can try to reset MFA for the user and they will go through the enroll process again.</span></span> [<span data-ttu-id="ce594-108">Siga los pasos descritos en este artículo.</span><span class="sxs-lookup"><span data-stu-id="ce594-108">Please follow the steps in this article.</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-userdevicesettings#require-users-to-provide-contact-methods-again)

<span data-ttu-id="ce594-109">Si esta es la primera vez que habilita la MFA y los usuarios no pueden iniciar sesión en clientes que no sean exploradores como Outlook, Skype, etc., quizá ADAL (biblioteca de autenticación de Active Directory) no está habilitado en su suscripción de O365.</span><span class="sxs-lookup"><span data-stu-id="ce594-109">If this is the first time you enabled MFA and your users are unable to login to non-browsers clients such as Outlook, Skype, etc, perhaps ADAL (Active Directory Authentication Library) is not enabled on your O365 subscription.</span></span> <span data-ttu-id="ce594-110">En este caso, deberá conectarse a Exchange Online PowerShell y ejecutar este cmdlet:  *set-OrganizationConfig-OAuth2ClientProfileEnabled: $true*</span><span class="sxs-lookup"><span data-stu-id="ce594-110">In this case you will need to connect to Exchange Online Powershell and run this cmdlet:  *Set-OrganizationConfig -OAuth2ClientProfileEnabled:$true*</span></span>