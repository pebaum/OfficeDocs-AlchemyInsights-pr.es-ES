---
title: ¿Va a convertir el buzón de usuario en un buzón compartido?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ROBOTS: NOINDEX, NOFOLLOW
description: ''
ms.openlocfilehash: 4da54121763fd33aa111f3bb3c26963cd271dc51
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "32374340"
---
<span data-ttu-id="581f4-102">Solo puede convertir un buzón de usuario en un buzón compartido si el usuario tiene una licencia de Exchange.</span><span class="sxs-lookup"><span data-stu-id="581f4-102">You can only convert a user mailbox to a shared mailbox if the user has an Exchange license.</span></span> <span data-ttu-id="581f4-103">Una vez convertido el buzón, se seguirá mostrando en la lista usuarios activos porque esa lista incluye buzones compartidos.</span><span class="sxs-lookup"><span data-stu-id="581f4-103">After the mailbox is converted, it will continue to show up in the active users list because that list includes shared mailboxes.</span></span> <span data-ttu-id="581f4-104">Sin embargo, el buzón convertido también se mostrará en la lista de buzones compartidos.</span><span class="sxs-lookup"><span data-stu-id="581f4-104">However, the converted mailbox will also show up in the shared mailbox list.</span></span> 
  
<span data-ttu-id="581f4-105">Si intenta convertir un buzón en la consola de administración de Exchange y se produce un error en la conversión, borre la memoria caché del explorador y las cookies y vuelva a intentarlo.</span><span class="sxs-lookup"><span data-stu-id="581f4-105">If you try to convert a mailbox in the Exchange Admin Console and the conversion fails, clear your browser cache and cookies and try again.</span></span> <span data-ttu-id="581f4-106">Si sigue sin funcionar, pruebe a convertir el buzón de correo en el shell de administración de Exchange ejecutando el siguiente comando:</span><span class="sxs-lookup"><span data-stu-id="581f4-106">If it still isn't working, try converting the mailbox in the Exchange Management Shell by running the following command:</span></span>
  
```
Set-Mailbox -Type Shared
```

<span data-ttu-id="581f4-107">Hay más información sobre la conversión de buzones de correo en [convertir un buzón de usuario en un buzón compartido](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba).</span><span class="sxs-lookup"><span data-stu-id="581f4-107">More mailbox conversion information is available in [Convert a user mailbox to a shared mailbox](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba).</span></span>
  
