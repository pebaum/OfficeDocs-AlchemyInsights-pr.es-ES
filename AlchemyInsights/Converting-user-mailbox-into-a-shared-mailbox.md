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
ms.openlocfilehash: ab34b8939b95b29bedb797f640dd744bc783adef
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36496452"
---
# <a name="convert-a-user-mail-box-into-a-shared-mailbox"></a><span data-ttu-id="5ffd2-102">Convertir un cuadro de correo de usuario en un buzón compartido</span><span class="sxs-lookup"><span data-stu-id="5ffd2-102">Convert a user mail box into a shared mailbox</span></span>

<span data-ttu-id="5ffd2-103">Solo puede convertir un buzón de usuario en un buzón compartido si el usuario tiene una licencia de Exchange.</span><span class="sxs-lookup"><span data-stu-id="5ffd2-103">You can only convert a user mailbox to a shared mailbox if the user has an Exchange license.</span></span> <span data-ttu-id="5ffd2-104">Una vez convertido el buzón, se seguirá mostrando en la lista usuarios activos porque esa lista incluye buzones compartidos.</span><span class="sxs-lookup"><span data-stu-id="5ffd2-104">After the mailbox is converted, it will continue to show up in the active users list because that list includes shared mailboxes.</span></span> <span data-ttu-id="5ffd2-105">Sin embargo, el buzón convertido también se mostrará en la lista de buzones compartidos.</span><span class="sxs-lookup"><span data-stu-id="5ffd2-105">However, the converted mailbox will also show up in the shared mailbox list.</span></span> 
  
<span data-ttu-id="5ffd2-106">Si intenta convertir un buzón en la consola de administración de Exchange y se produce un error en la conversión, borre la memoria caché del explorador y las cookies y vuelva a intentarlo.</span><span class="sxs-lookup"><span data-stu-id="5ffd2-106">If you try to convert a mailbox in the Exchange Admin Console and the conversion fails, clear your browser cache and cookies and try again.</span></span> <span data-ttu-id="5ffd2-107">Si sigue sin funcionar, pruebe a convertir el buzón de correo en el shell de administración de Exchange ejecutando el siguiente comando:</span><span class="sxs-lookup"><span data-stu-id="5ffd2-107">If it still isn't working, try converting the mailbox in the Exchange Management Shell by running the following command:</span></span>
  
```
Set-Mailbox -Type Shared
```

<span data-ttu-id="5ffd2-108">Hay más información sobre la conversión de buzones de correo en [convertir un buzón de usuario en un buzón compartido](https://docs.microsoft.com/office365/admin/email/convert-user-mailbox-to-shared-mailbox).</span><span class="sxs-lookup"><span data-stu-id="5ffd2-108">More mailbox conversion information is available in [Convert a user mailbox to a shared mailbox](https://docs.microsoft.com/office365/admin/email/convert-user-mailbox-to-shared-mailbox).</span></span>
  
