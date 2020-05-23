---
title: Cambiar la dirección de correo electrónico de un grupo de Microsoft 365
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "4704"
ms.openlocfilehash: 0a07e6279f533a4c26a4e90c10651421a5df8860
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/27/2020
ms.locfileid: "44282471"
---
# <a name="change-email-address-of-an-microsoft-365-group"></a>Cambiar la dirección de correo electrónico de un grupo de Microsoft 365

Para cambiar la dirección de correo electrónico de un grupo de Microsoft 365, use el Centro de administración. Solo tiene que seleccionar el grupo y, luego, seleccionar @editar dirección de correo electrónico.

También puede usar el siguiente comando de PowerShell EXO para cambiar la dirección SMTP principal de un grupo de Microsoft 365:

Set-UnifiedGroup <Group Name>-PrimarySmtpAddress <new SMTP Address>

Ejemplo:

```
    Set-UnifiedGroup Marketing -PrimarySmtpAddress marketing@contoso.com
```
