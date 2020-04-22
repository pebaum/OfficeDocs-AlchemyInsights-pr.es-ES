---
title: Retirada de herramientas de eDiscovery heredadas
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001487"
- "3523"
ms.openlocfilehash: 262cca0feee17d1f929a5a94a4dd6c1ec317f6ec
ms.sourcegitcommit: 6bf1d945b4fd6a1fe37d00c5ea99adea7eef9910
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/21/2020
ms.locfileid: "43650585"
---
# <a name="retirement-of-legacy-ediscovery-tools"></a>Retirada de herramientas de eDiscovery heredadas

Como resultado de la nueva y mejorada funcionalidad de eDiscovery en el centro de cumplimiento de Microsoft 365, las siguientes herramientas y commandlets de eDiscovery heredadas se retirarán en los próximos meses:

- [Exhibición](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery) de documentos electrónicos local y [conservaciones locales](https://docs.microsoft.com/exchange/security-and-compliance/create-or-remove-in-place-holds) en el centro de administración de Exchange.

- Los cmdlets de PowerShell de Exchange online que admiten la exhibición de documentos electrónicos local y las suspensiones locales. (Estos cmdlets se identifican colectivamente como cmdlets *-MailboxSearch). Esto incluye los siguientes cmdlets:

    - [New-MailboxSearch](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/new-mailboxsearch)
    - [Start-MailboxSearch](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/start-mailboxsearch)
    - [Stop-MailboxSearch](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/stop-mailboxsearch)
    - [Set-MailboxSearch](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/set-mailboxsearch)

- El cmdlet [Search-Mailbox](https://docs.microsoft.com/powershell/module/exchange/mailboxes/search-mailbox?view=exchange-ps) en Exchange Online PowerShell.
- Las siguientes operaciones en la API de servicios web Exchange:
    - [GetSearchableMailboxes](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getsearchablemailboxes-operation)
    - [SetHoldOnMailboxes](https://docs.microsoft.com/exchange/client-developer/web-service-reference/setholdonmailboxes-operation)
    - [GetHoldOnMailboxes](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getholdonmailboxes-operation)

- [EDiscovery avanzado v 1.0](https://docs.microsoft.com/microsoft-365/compliance/office-365-advanced-ediscovery)

**Escala de tiempo para la jubilación**:
- 1 de abril de 2020: no podrá crear nuevas búsquedas y suspensiones, pero puede seguir ejecutando, editando y eliminando las búsquedas existentes bajo su propio riesgo. El soporte técnico de Microsoft ya no admitirá las retenciones de exhibición de documentos electrónicos local & en el EAC.

- 1 de julio de 2020: el & de la exhibición de documentos electrónicos local contiene funcionalidad en el EAC se colocará en modo de solo lectura. Esto significa que solo podrá quitar búsquedas y suspensiones existentes.

**Para obtener más información, vea**:

 - [Migrar las búsquedas y suspensiones de eDiscovery heredado al centro de cumplimiento de Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/migrate-legacy-ediscovery-searches-and-holds)
 - [Retirada de herramientas heredadas de eDiscovery](https://docs.microsoft.com/microsoft-365/compliance/legacy-ediscovery-retirement)
 - [Preguntas más frecuentes sobre la exhibición de documentos electrónicos local y las suspensiones locales](https://docs.microsoft.com/microsoft-365/compliance/legacy-ediscovery-retirement#faqs-about-in-place-ediscovery-and-in-place-holds)



