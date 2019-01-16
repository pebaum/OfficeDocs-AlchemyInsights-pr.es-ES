---
title: ¿Conversión de buzón de usuario en un buzón compartido?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ROBOTS: NOINDEX, NOFOLLOW
description: ''
ms.openlocfilehash: 22ad1b3fb818b40bcd77974031735f931e986968
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28314355"
---
<span data-ttu-id="dea07-p101">Sólo se puede convertir un buzón de usuario a un buzón compartido si el usuario tiene una licencia de Exchange. Después se convierte el buzón de correo, continuará aparezca en la lista de usuarios activos debido a que esa lista incluye los buzones compartidos. Sin embargo, el buzón convertido también aparecerá en la lista de buzones compartidos.</span><span class="sxs-lookup"><span data-stu-id="dea07-p101">You can only convert a user mailbox to a shared mailbox if the user has an Exchange license. After the mailbox is converted, it will continue to show up in the active users list because that list includes shared mailboxes. However, the converted mailbox will also show up in the shared mailbox list.</span></span> 
  
<span data-ttu-id="dea07-p102">Si se intenta convertir un buzón de correo en la consola de administración de Exchange y se produce un error en la conversión, borre la memoria caché del explorador y las cookies y vuelva a intentarlo. Si aún no funciona, pruebe a convertir el buzón de correo en el Shell de administración de Exchange, ejecute el comando siguiente:</span><span class="sxs-lookup"><span data-stu-id="dea07-p102">If you try to convert a mailbox in the Exchange Admin Console and the conversion fails, clear your browser cache and cookies and try again. If it still isn't working, try converting the mailbox in the Exchange Management Shell by running the following command:</span></span>
  
```
Set-Mailbox -Type Shared
```

<span data-ttu-id="dea07-107">Obtener más información de conversión de buzón de correo está disponible en la [conversión de un buzón de usuario a un buzón compartido](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba).</span><span class="sxs-lookup"><span data-stu-id="dea07-107">More mailbox conversion information is available in [Convert a user mailbox to a shared mailbox](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba).</span></span>
  
