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
# <a name="change-email-address-of-an-microsoft-365-group"></a><span data-ttu-id="164d0-102">Cambiar la dirección de correo electrónico de un grupo de Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="164d0-102">Change email address of an Microsoft 365 group</span></span>

<span data-ttu-id="164d0-103">Para cambiar la dirección de correo electrónico de un grupo de Microsoft 365, use el Centro de administración.</span><span class="sxs-lookup"><span data-stu-id="164d0-103">You can change the email address of an Microsoft 365 group by using the admin center.</span></span> <span data-ttu-id="164d0-104">Solo tiene que seleccionar el grupo y, luego, seleccionar @editar dirección de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="164d0-104">Just select the group and select @edit email address.</span></span>

<span data-ttu-id="164d0-105">También puede usar el siguiente comando de PowerShell EXO para cambiar la dirección SMTP principal de un grupo de Microsoft 365:</span><span class="sxs-lookup"><span data-stu-id="164d0-105">You can also use following the EXO PowerShell command to change the primary SMTP address of an Microsoft 365 group:</span></span>

<span data-ttu-id="164d0-106">Set-UnifiedGroup <Group Name>-PrimarySmtpAddress <new SMTP Address></span><span class="sxs-lookup"><span data-stu-id="164d0-106">Set-UnifiedGroup <Group Name> -PrimarySmtpAddress <new SMTP Address></span></span>

<span data-ttu-id="164d0-107">Ejemplo:</span><span class="sxs-lookup"><span data-stu-id="164d0-107">Example:</span></span>

```
    Set-UnifiedGroup Marketing -PrimarySmtpAddress marketing@contoso.com
```
