---
title: 929 reglas de la bandeja de entrada a reglas de deflectTransport
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 6/15/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "929"
- "1800021"
ms.assetid: 9733ef4e-db8d-4345-a072-c251480875a1
ms.openlocfilehash: 6cf996e6d0a2698a5ce2bb57251de7c61d248d2a
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/28/2019
ms.locfileid: "35382682"
---
# <a name="mail-flow-rules-also-known-as-transport-rules"></a><span data-ttu-id="2f2ce-102">Reglas de flujo de correo (también conocidas como reglas de transporte)</span><span class="sxs-lookup"><span data-stu-id="2f2ce-102">Mail flow rules (also known as transport rules)</span></span>

- <span data-ttu-id="2f2ce-103">Información general sobre las reglas de flujo de correo: [reglas de flujo de correo (reglas de transporte) en Exchange Online](https://technet.microsoft.com/library/jj919238.aspx)</span><span class="sxs-lookup"><span data-stu-id="2f2ce-103">General overview of mail flow rules: [Mail flow rules (transport rules) in Exchange Online](https://technet.microsoft.com/library/jj919238.aspx)</span></span>

- <span data-ttu-id="2f2ce-104">Configuración de reglas de flujo [de correo: procedimientos de reglas de flujo de correo en Exchange Online](https://technet.microsoft.com/library/dn600436.aspx)</span><span class="sxs-lookup"><span data-stu-id="2f2ce-104">Setup mail flow rules: [Mail flow rule procedures in Exchange Online](https://technet.microsoft.com/library/dn600436.aspx)</span></span>

- <span data-ttu-id="2f2ce-105">Crear, modificar y eliminar reglas de flujo de correo: [administrar reglas de flujo de correo](https://technet.microsoft.com/library/jj657505.aspx)</span><span class="sxs-lookup"><span data-stu-id="2f2ce-105">Create, modify, and delete mail flow rules: [Manage mail flow rules](https://technet.microsoft.com/library/jj657505.aspx)</span></span>

<span data-ttu-id="2f2ce-106">También puede administrar reglas de flujo de correo en Exchange Online PowerShell.</span><span class="sxs-lookup"><span data-stu-id="2f2ce-106">You can also manage mail flow rules in Exchange Online PowerShell.</span></span> <span data-ttu-id="2f2ce-107">Para obtener más información, [consulte Get-transportrule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportrule) (View), [New-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/new-transportrule) (Create), [Remove-Transportrule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/remove-transportrule) (Delete), [set-transportrule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/set-transportrule) (Modify Existing), Disable [-transportrule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/disable-transportrule) (Disable Existing) y [Enable-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/enable-transportrule) (habilite Existing).</span><span class="sxs-lookup"><span data-stu-id="2f2ce-107">For more information, see [Get-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportrule) (view), [New-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/new-transportrule) (create), [Remove-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/remove-transportrule) (delete), [Set-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/set-transportrule) (modify existing), [Disable-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/disable-transportrule) (disable existing), and [Enable-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/enable-transportrule) (enable existing).</span></span>

<span data-ttu-id="2f2ce-108">Cmdlets de reglas de flujo de correo adicionales: [Get-TransportRuleAction](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportruleaction) (lista de acciones disponibles), [Get-TransportRulePredicate](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportrulepredicate) (lista de condiciones y excepciones disponibles), [Export-TransportRuleCollection](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/export-transportrulecollection) (reglas de exportación) y [ Import-TransportRuleCollection](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/import-transportrulecollection) (reglas de importación).</span><span class="sxs-lookup"><span data-stu-id="2f2ce-108">Additional mail flow rule cmdlets: [Get-TransportRuleAction](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportruleaction) (list available actions), [Get-TransportRulePredicate](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportrulepredicate) (list available conditions and exceptions), [Export-TransportRuleCollection](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/export-transportrulecollection) (export rules), and [Import-TransportRuleCollection](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/import-transportrulecollection) (import rules).</span></span>
