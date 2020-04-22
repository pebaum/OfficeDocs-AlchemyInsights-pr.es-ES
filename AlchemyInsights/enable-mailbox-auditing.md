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
# <a name="enable-mailbox-auditing"></a>Habilitar la auditoría de buzones de correo

Para habilitar la auditoría de buzones de correo para un solo usuario o para toda una organización, los siguientes cmdlets deben ejecutarse desde el shell de alimentación remota:
  
 **Usuario único**
  
Set-Mailbox-Identity "Jane Dow"-AuditEnabled $true
  
 **Organización**
  
Get-Mailbox-Resultsize-Filter {RecipientTypeDetails-EQ "UserMailbox"} | Set-Mailbox-AuditEnabled $true
  
[Más información](https://docs.microsoft.com/office365/securitycompliance/enable-mailbox-auditing)
  

