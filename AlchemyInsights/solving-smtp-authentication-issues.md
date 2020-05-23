---
title: Solucionar problemas de autenticación SMTP
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3000003"
- "5652"
ms.openlocfilehash: 814c49e8e65966a0c9f927b1f7bfb03d3dc3d637
ms.sourcegitcommit: 0e43e19448705f151846e9e9e1e0f47e12938fdf
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 05/15/2020
ms.locfileid: "44264562"
---
# <a name="solving-smtp-authentication-issues"></a><span data-ttu-id="63e49-102">Solucionar problemas de autenticación SMTP</span><span class="sxs-lookup"><span data-stu-id="63e49-102">Solving SMTP authentication issues</span></span>

<span data-ttu-id="63e49-103">Si recibe los errores 5.7.57 o 5.7.3 al intentar enviar correo electrónico SMTP y autenticarse mediante un cliente o aplicación, puede comprobar algunas cosas:</span><span class="sxs-lookup"><span data-stu-id="63e49-103">If you are getting errors 5.7.57 or 5.7.3 when trying to send SMTP email and authenticate with a client or application, there are a few things you should check:</span></span>

- <span data-ttu-id="63e49-104">Es posible que el envío SMTP autenticado esté deshabilitado en su espacio empresarial o en el buzón que está intentando usar (compruebe ambas configuraciones).</span><span class="sxs-lookup"><span data-stu-id="63e49-104">Authenticated SMTP submission might be disabled in your tenant, or on the mailbox that you are trying to use (check both settings).</span></span> <span data-ttu-id="63e49-105">Para obtener más información, consulte [Habilitar o deshabilitar el envío SMTP de cliente autenticado](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/authenticated-client-smtp-submission).</span><span class="sxs-lookup"><span data-stu-id="63e49-105">To read more, see [Enable or disable authenticated client SMTP submission](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/authenticated-client-smtp-submission).</span></span>

- <span data-ttu-id="63e49-106">Compruebe si los [valores predeterminados de seguridad de Azure](https://docs.microsoft.com/azure/active-directory/fundamentals/concept-fundamentals-security-defaults) están habilitados para su espacio empresarial. Si están habilitados, se producirá un error de autenticación SMTP con autenticación básica (también conocido como heredado; este usará el nombre de usuario y la contraseña).</span><span class="sxs-lookup"><span data-stu-id="63e49-106">Check whether [Azure Security Defaults](https://docs.microsoft.com/azure/active-directory/fundamentals/concept-fundamentals-security-defaults) are enabled for your tenant; if enabled, SMTP authentication using basic authentication (also known as legacy; this will use username and password) will fail.</span></span>
