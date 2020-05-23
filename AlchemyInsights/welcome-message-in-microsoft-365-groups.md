---
title: Mensaje de bienvenida en grupos de Microsoft 365
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
- "5685"
ms.openlocfilehash: d82931ae6978a09e674b00640d1dd413bcce7cfd
ms.sourcegitcommit: b196100759b29aecd62b693a2bfedbbd25a697c6
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2020
ms.locfileid: "44320474"
---
# <a name="welcome-message-in-microsoft-365-groups"></a><span data-ttu-id="c6006-102">Mensaje de bienvenida en grupos de Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="c6006-102">Welcome message in Microsoft 365 Groups</span></span>

<span data-ttu-id="c6006-103">Los nuevos usuarios que se unan al grupo de Microsoft 365 recibirán un correo electrónico de bienvenida si la propiedad "UnifiedGroupWelcomeMessageEnabled" está establecida en True.</span><span class="sxs-lookup"><span data-stu-id="c6006-103">New users joining Microsoft 365 group will receive welcome email if the "UnifiedGroupWelcomeMessageEnabled" property is True.</span></span>

<span data-ttu-id="c6006-104">Si desea deshabilitar el mensaje de bienvenida, use el siguiente comando de [EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps):</span><span class="sxs-lookup"><span data-stu-id="c6006-104">In case you want to disable the welcome message, use the following [EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps) command:</span></span>

`
Set-UnifiedGroup <groupname> -UnifiedGroupWelcomeMessageEnabled:$False
`
