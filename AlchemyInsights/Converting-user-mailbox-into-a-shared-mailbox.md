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
Sólo se puede convertir un buzón de usuario a un buzón compartido si el usuario tiene una licencia de Exchange. Después se convierte el buzón de correo, continuará aparezca en la lista de usuarios activos debido a que esa lista incluye los buzones compartidos. Sin embargo, el buzón convertido también aparecerá en la lista de buzones compartidos. 
  
Si se intenta convertir un buzón de correo en la consola de administración de Exchange y se produce un error en la conversión, borre la memoria caché del explorador y las cookies y vuelva a intentarlo. Si aún no funciona, pruebe a convertir el buzón de correo en el Shell de administración de Exchange, ejecute el comando siguiente:
  
```
Set-Mailbox -Type Shared
```

Obtener más información de conversión de buzón de correo está disponible en la [conversión de un buzón de usuario a un buzón compartido](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba).
  
