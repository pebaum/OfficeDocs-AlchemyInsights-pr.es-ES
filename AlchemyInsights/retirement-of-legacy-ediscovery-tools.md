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
ms.openlocfilehash: c4632b52dde579b7d5b2e6e15f1583300a0bd136
ms.sourcegitcommit: a7c17217c170ead24571421baaf5a14f1525b1a6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/20/2020
ms.locfileid: "42157724"
---
# <a name="retirement-of-legacy-ediscovery-tools"></a><span data-ttu-id="3a8ee-102">Retirada de herramientas de eDiscovery heredadas</span><span class="sxs-lookup"><span data-stu-id="3a8ee-102">Retirement of Legacy eDiscovery Tools</span></span>

<span data-ttu-id="3a8ee-103">Como resultado de la nueva y mejorada funcionalidad de eDiscovery en el centro de cumplimiento de Microsoft 365, las siguientes herramientas y commandlets de eDiscovery heredadas se retirarán en los próximos meses:</span><span class="sxs-lookup"><span data-stu-id="3a8ee-103">As a result of the new and improved eDiscovery functionality in Microsoft 365 Compliance center, the following legacy eDiscovery tools and commandlets will be retired in the coming months:</span></span>

- <span data-ttu-id="3a8ee-104">[Exhibición](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery) de documentos electrónicos local y [conservaciones locales](https://docs.microsoft.com/exchange/security-and-compliance/create-or-remove-in-place-holds) en el centro de administración de Exchange.</span><span class="sxs-lookup"><span data-stu-id="3a8ee-104">[In-Place eDiscovery](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery) and [In-Place Holds](https://docs.microsoft.com/exchange/security-and-compliance/create-or-remove-in-place-holds) in the Exchange admin center.</span></span>

- <span data-ttu-id="3a8ee-105">Los cmdlets de PowerShell de Exchange online que admiten la exhibición de documentos electrónicos local y las suspensiones locales.</span><span class="sxs-lookup"><span data-stu-id="3a8ee-105">The Exchange Online PowerShell cmdlets that support In-Place eDiscovery and In-Place Holds.</span></span> <span data-ttu-id="3a8ee-106">(Estos cmdlets se identifican colectivamente como cmdlets \*-MailboxSearch). Esto incluye los siguientes cmdlets:</span><span class="sxs-lookup"><span data-stu-id="3a8ee-106">(These cmdlets are collectively identified as \*-MailboxSearch cmdlets.) This includes the following cmdlets:</span></span>

    - [<span data-ttu-id="3a8ee-107">New-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="3a8ee-107">New-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/new-mailboxsearch)
    - [<span data-ttu-id="3a8ee-108">Start-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="3a8ee-108">Start-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/start-mailboxsearch)
    - [<span data-ttu-id="3a8ee-109">Stop-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="3a8ee-109">Stop-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/stop-mailboxsearch)
    - [<span data-ttu-id="3a8ee-110">Set-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="3a8ee-110">Set-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/set-mailboxsearch)

- <span data-ttu-id="3a8ee-111">El cmdlet [Search-Mailbox](https://docs.microsoft.com/powershell/module/exchange/mailboxes/search-mailbox?view=exchange-ps) en Exchange Online PowerShell.</span><span class="sxs-lookup"><span data-stu-id="3a8ee-111">The [Search-Mailbox](https://docs.microsoft.com/powershell/module/exchange/mailboxes/search-mailbox?view=exchange-ps) cmdlet in Exchange Online PowerShell.</span></span>
- <span data-ttu-id="3a8ee-112">Las siguientes operaciones en la API de servicios web Exchange:</span><span class="sxs-lookup"><span data-stu-id="3a8ee-112">The following operations in the Exchange Web Services API:</span></span>
    - [<span data-ttu-id="3a8ee-113">GetSearchableMailboxes</span><span class="sxs-lookup"><span data-stu-id="3a8ee-113">GetSearchableMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getsearchablemailboxes-operation)
    - [<span data-ttu-id="3a8ee-114">SetHoldOnMailboxes</span><span class="sxs-lookup"><span data-stu-id="3a8ee-114">SetHoldOnMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/setholdonmailboxes-operation)
    - [<span data-ttu-id="3a8ee-115">GetHoldOnMailboxes</span><span class="sxs-lookup"><span data-stu-id="3a8ee-115">GetHoldOnMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getholdonmailboxes-operation)

- [<span data-ttu-id="3a8ee-116">Office 365 Advanced eDiscovery v 1.0</span><span class="sxs-lookup"><span data-stu-id="3a8ee-116">Office 365 Advanced eDiscovery v1.0</span></span>](https://docs.microsoft.com/en-us/microsoft-365/compliance/office-365-advanced-ediscovery)

<span data-ttu-id="3a8ee-117">**Escala de tiempo para la jubilación**:</span><span class="sxs-lookup"><span data-stu-id="3a8ee-117">**Timeline for retirement**:</span></span>
- <span data-ttu-id="3a8ee-118">1 de abril de 2020: no podrá crear nuevas búsquedas y suspensiones, pero puede seguir ejecutando, editando y eliminando las búsquedas existentes bajo su propio riesgo.</span><span class="sxs-lookup"><span data-stu-id="3a8ee-118">April 1, 2020: You won't be able to create new searches and holds, but you can still run, edit, and delete existing searches at your own risk.</span></span> <span data-ttu-id="3a8ee-119">El soporte técnico de Microsoft ya no admitirá las retenciones de exhibición de documentos electrónicos local & en el EAC.</span><span class="sxs-lookup"><span data-stu-id="3a8ee-119">Microsoft Support will no longer support In-Place eDiscovery & Holds in the EAC.</span></span>

- <span data-ttu-id="3a8ee-120">1 de julio de 2020: el & de la exhibición de documentos electrónicos local contiene funcionalidad en el EAC se colocará en modo de solo lectura.</span><span class="sxs-lookup"><span data-stu-id="3a8ee-120">July 1, 2020: The In-Place eDiscovery & Holds functionality in the EAC will be placed in a read-only mode.</span></span> <span data-ttu-id="3a8ee-121">Esto significa que solo podrá quitar búsquedas y suspensiones existentes.</span><span class="sxs-lookup"><span data-stu-id="3a8ee-121">This means you'll only be able to remove existing searches and holds.</span></span>

<span data-ttu-id="3a8ee-122">**Para obtener más información, vea**:</span><span class="sxs-lookup"><span data-stu-id="3a8ee-122">**For more information, see**:</span></span>

 - [<span data-ttu-id="3a8ee-123">Migrar las búsquedas y suspensiones de eDiscovery heredado al centro de cumplimiento de Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="3a8ee-123">Migrate legacy eDiscovery searches and holds to the Microsoft 365 compliance center</span></span>](https://docs.microsoft.com/en-us/microsoft-365/compliance/migrate-legacy-ediscovery-searches-and-holds)
 - [<span data-ttu-id="3a8ee-124">Retirada de herramientas de eDiscovery heredadas</span><span class="sxs-lookup"><span data-stu-id="3a8ee-124">Retirement of legacy eDiscovery tools</span></span>](https://docs.microsoft.com/en-us/microsoft-365/compliance/legacy-ediscovery-retirement)
 - [<span data-ttu-id="3a8ee-125">Preguntas más frecuentes sobre la exhibición de documentos electrónicos local y las suspensiones locales</span><span class="sxs-lookup"><span data-stu-id="3a8ee-125">FAQs about In-Place eDiscovery and In-Place Holds</span></span>](https://docs.microsoft.com/en-us/microsoft-365/compliance/legacy-ediscovery-retirement#faqs-about-in-place-ediscovery-and-in-place-holds)



