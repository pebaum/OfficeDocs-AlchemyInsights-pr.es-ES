---
title: Código de error 550 5.7.501 acceso denegado, abuso de correo no deseado detectado
ms.author: chrisda
author: chrisda
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "351"
- "3100015"
ms.assetid: 3105905c-e7a0-42a7-9c5a-61dc56a1d6fc
ms.openlocfilehash: 7be23f02878d12aa08cb4970af6f99539a9cefab
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43703043"
---
# <a name="550-57501-access-denied-spam-abuse-detected"></a>550 5.7.501 acceso denegado, se ha detectado abuso de correo no deseado

Normalmente, este mensaje se produce cuando los usuarios envían mensajes de correo electrónico desde direcciones IP mediante el dominio inicial *. onmicrosoft.com* que está asignado a los nuevos inquilinos en Microsoft 365. La forma más sencilla de solucionar este problema es:

1. [Agregue un dominio a su inquilino](https://docs.microsoft.com//office365/admin/setup/add-domain).

2. [Cambie la dirección de correo electrónico principal de los usuarios](https://docs.microsoft.com//office365/admin/add-users/change-a-user-name-and-email-address) por el nuevo dominio personalizado que acaba de agregar.
