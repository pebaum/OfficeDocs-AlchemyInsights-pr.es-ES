---
title: No se puede iniciar sesión en Teams por el error autologon.microsoftazuread-sso.com:443
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 686e8f18-b871-4dd2-864f-8562947ab583
ms.collection: Adm_O365
ms.custom:
- "9001686"
- "3750"
ms.openlocfilehash: 77049153939989d1c63789adfec0b494d047a6e4
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932288"
---
# <a name="unable-to-log-into-teams-due-to-error-autologonmicrosoftazuread-sso-dot-com443"></a>No se puede iniciar sesión en Teams por el error autologon.microsoftazuread-sso dot com:443

Si el SSO de conexión directa está habilitado como la autenticación de O365, quizás tenga que agregar la dirección URL "autologon.microsoftazuread-sso.com" a los sitios de intranet.  Si se ha agregado anteriormente a Sitios de confianza y usa SSO de conexión directa, se debe quitar de Sitios de confianza.

Consulte la [Lista de comprobación de solución de problemas de SSO de conexión directa](https://docs.microsoft.com/azure/active-directory/hybrid/tshoot-connect-sso#troubleshooting-checklist).

Siga estos pasos para agregar una dirección URL a la lista de sitios de la intranet:

1. Para abrir Internet Explorer, haga clic en el botón **Inicio**. En el cuadro de búsqueda, escriba Internet Explorer y, a continuación, en la lista de resultados, haga clic en **Internet Explorer**.
2. Haga clic en **Herramientas** y, luego, en **Opciones de Internet**.
3. Haga clic en la pestaña **Seguridad**.
4. Ahora, haga clic en **Sitios de Intranet local**, después, haga clic en el botón **sitios** y, luego, en el botón**Avanzado**.
5. Escriba la dirección URL del sitio web y haga clic en **Agregar**.
6. Cuando haya terminado, haga clic en **Cerrar.**

Para obtener más información, vea [Documentación sobre cómo implementar SSO de conexión directa para O365](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-sso-quick-start) (incluye el proceso basado en directivas para agregar una dirección URL a los sitios de intranet en el Paso 3).
