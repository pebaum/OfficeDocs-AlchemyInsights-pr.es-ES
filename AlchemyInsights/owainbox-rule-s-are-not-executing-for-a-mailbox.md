---
title: 1332 OWA-las reglas de la bandeja de entrada no se ejecutan para un buzón
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 12/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1332"
- "3700002"
ms.assetid: 383d1c77-5e4b-4a69-92d6-c404d890b6b7
ms.openlocfilehash: 901237d4dc7b99695097142c61a4bfef7c09750d
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36555790"
---
# <a name="an-inbox-rule-doesnt-work-as-expected"></a>Una regla de la bandeja de entrada no funciona como se esperaba

Compruebe la siguiente configuración en Outlook en la web:

- Un mensaje puede redirigirse, reenviarse o responderse automáticamente en función de las reglas de la bandeja de entrada sólo una vez. Una regla de redireccionamiento (una regla de bandeja de entrada o una regla de flujo de correo, también denominada regla de transporte) puede Agregar un máximo de diez destinatarios de reenvío a un mensaje. Para obtener más información, vea los límites de las [reglas diario, transporte y bandeja de entrada](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).

- Las reglas de la bandeja de entrada no funcionan en el buzón de registro en diario alternativo. Para obtener más información acerca del buzón de correo de registro en diario alternativo, consulte [buzón de registro en diario alternativo](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).

Para solucionar estos problemas, consulte [KB 2829319](https://support.microsoft.com/kb/2829319).

Si no se aplican los problemas anteriores, ejecute el informe de diagnóstico de reglas de la bandeja de entrada antes de remitir el problema al soporte técnico de Microsoft:

1. Abra el buzón en Outlook en la web y haga clic en <img src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAMAAABhEH5lAAAA51BMVEX6+fj6+fDr+fjK+fj69LRxsuj6+cjY+fi/+fin3ev6+ddMk81HdK5AaatHLn/ntXTrsW5cRmLOk0pAND5KNCl1NCOi3fiGwvjJ3fDBz+F6teFgpdt6stX68c314syTucirtchum8bjz8BQh7/6+b47fbrKtapiian63aFDaaHJuZJiQo36woVabH7ZtHiOQnTHm2wlKmqriWF/cFzVnVTFjlSyeUkrNEmBLkWfaUGsaT67fTrj9Pi19PjO8fiv5vj69OFWm9Pt3aZ1Qo0lNHQ1P2iYTWGOQmHcpV5kRlqvc0mrbERpPzMoEeekAAAAxElEQVQY03WQ5w6CUAyFy3Jv3HsrICoKqLj3fP/nsTcNakjsn9t+bW/OKfyL6iTCc49e/ktuRs2WEhE1U/qgQQfEzGkNyxzVXLdw0ASW+a7BZp3HpJ+cpovUjcv6PYtvSmKj4/SswTMaBgg9FQF5axWysKoson4cGMYCvlEAQDwK7XkZwEVbRBpDPC46ygbAbPl31p4Wvd8nwiRCLnIArJb1ZBD7KFWMkdQLSUVIhowsGaIwzzVHikfVV8lzHPv3OGTfTd4gnRNqGdZ49AAAAABJRU5ErkJggg==' />
 **Configuración** > **ver todas** > **** > **las reglas**de correo de la configuración de Outlook.

2. En la parte inferior de la página, haga clic en **si las reglas no funcionan haga clic aquí para generar un informe de diagnóstico**.
