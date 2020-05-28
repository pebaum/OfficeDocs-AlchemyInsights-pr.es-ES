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
ms.openlocfilehash: 84e337a7224fdd3c3ab7ad0f61240692fe007d5a
ms.sourcegitcommit: 82af227ac6d075e748e27c4ce6bdcf56628559cb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/28/2020
ms.locfileid: "44407367"
---
# <a name="unable-to-set-primary-email-address-change-user-attributes-or-removedelete-a-synchronized-user"></a>No se puede establecer la dirección de correo electrónico principal, cambiar los atributos de usuario o quitar o eliminar un usuario sincronizado

Si la sincronización de directorios está habilitada para su entorno, algunos atributos de usuario o de objeto no se pueden cambiar mediante el centro de administración 365 de Microsoft.

Para administrar por completo los usuarios sincronizados y todos sus atributos, use la consola de administración de usuarios y grupos de Active Directory (AdsiEdit. msc) local.  

Como alternativa, puede cambiar usuarios individuales o atributos para los usuarios sincronizados mediante PowerShell, como se muestra en estos ejemplos comunes: 
- `Set-MsolUser -UserPrincipalName user@yourdomain.onmicrosoft.com -AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com`

- `Set-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com" -DisplayName "Test User" -LastName "User" -Title "Manager" -Department "HR"`

- `Remove-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com`
