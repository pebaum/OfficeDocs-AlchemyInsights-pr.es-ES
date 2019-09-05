---
title: Habilitar la auditoría de buzones de correo
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/5/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 73517f46935a67a4a8a3e4770090ac897fe67979
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/04/2019
ms.locfileid: "36736270"
---
# <a name="enable-mailbox-auditing"></a>Habilitar la auditoría de buzones de correo

Para habilitar la auditoría de buzones de correo para un solo usuario o para toda una organización, los siguientes cmdlets deben ejecutarse desde el shell de alimentación remota:
  
 **Usuario único**
  
Set-Mailbox-Identity "Jane Dow"-AuditEnabled $true
  
 **Organización**
  
Get-Mailbox-Resultsize-Filter {RecipientTypeDetails-EQ "UserMailbox"} | Set-Mailbox-AuditEnabled $true
  
[Más información](https://docs.microsoft.com/office365/securitycompliance/enable-mailbox-auditing)
  

