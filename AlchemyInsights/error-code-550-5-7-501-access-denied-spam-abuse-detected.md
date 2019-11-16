---
title: Código de error 550 5.7.501 acceso denegado, abuso de correo no deseado detectado
ms.author: chrisda
author: chrisda
ms.date: 6/28/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "351"
- "3100015"
ms.assetid: 3105905c-e7a0-42a7-9c5a-61dc56a1d6fc
ms.openlocfilehash: 545cab07cc7c49def849be20bb6363da228a5393
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/15/2019
ms.locfileid: "36740158"
---
# <a name="550-57501-access-denied-spam-abuse-detected"></a><span data-ttu-id="125ad-102">550 5.7.501 acceso denegado, se ha detectado abuso de correo no deseado</span><span class="sxs-lookup"><span data-stu-id="125ad-102">550 5.7.501 Access denied, spam abuse detected</span></span>

<span data-ttu-id="125ad-103">Normalmente, este mensaje se produce cuando los usuarios envían mensajes de correo electrónico desde direcciones IP mediante el dominio inicial *. onmicrosoft.com* que está asignado a los nuevos inquilinos en Office 365.</span><span class="sxs-lookup"><span data-stu-id="125ad-103">Typically, this message occurs when users send email messages from IP addresses using the initial *.onmicrosoft.com* domain that's assigned to new tenants in Office 365.</span></span> <span data-ttu-id="125ad-104">La forma más sencilla de solucionar este problema es:</span><span class="sxs-lookup"><span data-stu-id="125ad-104">The easiest way to resolve this problem is to:</span></span>

1. <span data-ttu-id="125ad-105">[Agregue un dominio a su inquilino](https://docs.microsoft.com//office365/admin/setup/add-domain).</span><span class="sxs-lookup"><span data-stu-id="125ad-105">[Add a domain to your tenant](https://docs.microsoft.com//office365/admin/setup/add-domain).</span></span>

2. <span data-ttu-id="125ad-106">[Cambie la dirección de correo electrónico principal de los usuarios](https://docs.microsoft.com//office365/admin/add-users/change-a-user-name-and-email-address) por el nuevo dominio personalizado que acaba de agregar.</span><span class="sxs-lookup"><span data-stu-id="125ad-106">[Change your users' primary email address](https://docs.microsoft.com//office365/admin/add-users/change-a-user-name-and-email-address) to the new custom domain you just added.</span></span>
