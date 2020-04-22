---
title: Habilitar la auditoría de buzones de correo
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: ae11d6be0789a5662d202b85268480a3d42922c4
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43703588"
---
# <a name="enable-mailbox-auditing"></a><span data-ttu-id="638e0-102">Habilitar la auditoría de buzones de correo</span><span class="sxs-lookup"><span data-stu-id="638e0-102">Enable mailbox auditing</span></span>

<span data-ttu-id="638e0-103">Para habilitar la auditoría de buzones de correo para un solo usuario o para toda una organización, los siguientes cmdlets deben ejecutarse desde el shell de alimentación remota:</span><span class="sxs-lookup"><span data-stu-id="638e0-103">To enable Mailbox Auditing for either a single user or an entire organization the following cmdlets must be run from Remote Power Shell:</span></span>
  
 <span data-ttu-id="638e0-104">**Usuario único**</span><span class="sxs-lookup"><span data-stu-id="638e0-104">**Single User**</span></span>
  
<span data-ttu-id="638e0-105">Set-Mailbox-Identity "Jane Dow"-AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="638e0-105">Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true</span></span>
  
 <span data-ttu-id="638e0-106">**Organización**</span><span class="sxs-lookup"><span data-stu-id="638e0-106">**Organization**</span></span>
  
<span data-ttu-id="638e0-107">Get-Mailbox-Resultsize-Filter {RecipientTypeDetails-EQ "UserMailbox"} | Set-Mailbox-AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="638e0-107">Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span></span>
  
[<span data-ttu-id="638e0-108">Más información</span><span class="sxs-lookup"><span data-stu-id="638e0-108">Learn more</span></span>](https://docs.microsoft.com/office365/securitycompliance/enable-mailbox-auditing)
  

