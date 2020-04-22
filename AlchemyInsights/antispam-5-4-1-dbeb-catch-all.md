---
title: Correo no deseado 5.4.1 DBEB catch-all
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001209"
- "3167"
ms.openlocfilehash: ad0f4c691a5e06306dbb408f4d66a4e00609e4d5
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43707928"
---
# <a name="fix-delivery-issues-for-error-code-550-541-relay-access-denied"></a>Corregir problemas de entrega para el código de error 550 5.4.1 acceso de retransmisión denegado

Este problema se produce cuando [se comprueba si una dirección de correo electrónico es válida para evitar que se bouncebacks](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-directory-based-edge-blocking) al entrar en la red de Microsoft. Pruebe a hacer lo siguiente:

1. Determine si el problema es específico de un dominio completo o de una sola dirección de correo electrónico:
    - Dominio completo: a veces, es necesario sincronizar el dominio; Pruebe a [configurar el dominio como interno y, a continuación, de nuevo a autoritario](https://docs.microsoft.com/exchange/mail-flow-best-practices/manage-accepted-domains/manage-accepted-domains).
    - Dirección de correo electrónico única: a veces, la dirección debe sincronizarse; cambiar la dirección del proxy SMTP y, a continuación, cambiarla de nuevo puede resultarle útil.
2. Determine si el problema es específico de un grupo o una carpeta pública. Para algunos tipos de objetos, es posible que los objetos deban crearse manualmente en Azure Active Directory.

Si necesita ayuda adicional, abra una incidencia de soporte técnico y especifique el ámbito del problema (incluido el tipo de objeto al que va a enviar) para que podamos ayudarle mejor.