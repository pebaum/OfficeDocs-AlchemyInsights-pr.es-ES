---
title: Micro retrasos o limitación en Exchange Online PowerShell
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3500011"
- "5106"
ms.openlocfilehash: 7ab4e7f18b7b8edf08098af8fe9674f66b1b81f4
ms.sourcegitcommit: fbaa2ce2cfb4d56d8c4cf2fa2d95489bdfcb7ff0
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/30/2020
ms.locfileid: "43948030"
---
# <a name="micro-delays-or-throttling-in-exchange-online-powershell"></a>Micro retrasos o limitación en Exchange Online PowerShell

Es posible que vea advertencias de "Micro retraso aplicado" o retrasos cuando ejecuta scripts y cmdlets en Exchange Online. Aquí tiene dos sugerencias relacionadas con esto:

- Es posible que quiera usar el [módulo de PowerShell de Exchange Online v2](https://docs.microsoft.com/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps), que incluye CMDlets basados en la API de REST y son significativamente más eficaces Esta podría ser una buena solución para muchos CMDlets Get- que se usan con frecuencia.
- Si necesita usar CMDlets que aún no están cubiertos en el módulo v2, consulte [Ejecución de cmdlets de PowerShell para un gran número de usuarios en Office 365](https://techcommunity.microsoft.com/t5/exchange-team-blog/updated-running-powershell-cmdlets-for-large-numbers-of-users-in/ba-p/1000628#), que habla sobre cómo sortear la limitación esperada de PowerShell en Exchange Online.
