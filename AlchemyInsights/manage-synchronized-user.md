---
title: Administrar usuarios sincronizados
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000609"
- "2444"
ms.openlocfilehash: a943c59d67c512e6326856dacd0053db121f6aa3
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36542034"
---
# <a name="unable-to-set-primary-email-address-or-change-user-attributes"></a>No se puede establecer la dirección de correo electrónico principal ni cambiar los atributos de usuario

Si la sincronización de directorios está habilitada para su entorno, algunos atributos de usuario o de objeto no se pueden cambiar mediante el centro de administración 365 de Microsoft.

Para administrar por completo los usuarios sincronizados y todos sus atributos, use la consola de administración de usuarios y grupos de Active Directory (AdsiEdit. msc) local.  

Como alternativa, puede cambiar usuarios individuales o atributos para los usuarios sincronizados mediante PowerShell, como se muestra en estos ejemplos comunes: 
- Set-MsolUser-UserPrincipalName user@yourdomain.onmicrosoft.com-AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com
- Set-MsolUser-UserPrincipalName "user@yourdomain.onmicrosoft.com"-DisplayName "usuario de prueba"-LastName "User"-title "Manager"-Department "HR"
- Remove-MsolUser-UserPrincipalName "user@yourdomain.onmicrosoft.com