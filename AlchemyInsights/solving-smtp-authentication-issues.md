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
# <a name="solving-smtp-authentication-issues"></a>Solucionar problemas de autenticación SMTP

Si recibe los errores 5.7.57 o 5.7.3 al intentar enviar correo electrónico SMTP y autenticarse mediante un cliente o aplicación, puede comprobar algunas cosas:

- Es posible que el envío SMTP autenticado esté deshabilitado en su espacio empresarial o en el buzón que está intentando usar (compruebe ambas configuraciones). Para obtener más información, consulte [Habilitar o deshabilitar el envío SMTP de cliente autenticado](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/authenticated-client-smtp-submission).

- Compruebe si los [valores predeterminados de seguridad de Azure](https://docs.microsoft.com/azure/active-directory/fundamentals/concept-fundamentals-security-defaults) están habilitados para su espacio empresarial. Si están habilitados, se producirá un error de autenticación SMTP con autenticación básica (también conocido como heredado; este usará el nombre de usuario y la contraseña).
