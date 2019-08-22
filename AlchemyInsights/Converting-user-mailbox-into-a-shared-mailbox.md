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
# <a name="convert-a-user-mail-box-into-a-shared-mailbox"></a>Convertir un cuadro de correo de usuario en un buzón compartido

Solo puede convertir un buzón de usuario en un buzón compartido si el usuario tiene una licencia de Exchange. Una vez convertido el buzón, se seguirá mostrando en la lista usuarios activos porque esa lista incluye buzones compartidos. Sin embargo, el buzón convertido también se mostrará en la lista de buzones compartidos. 
  
Si intenta convertir un buzón en la consola de administración de Exchange y se produce un error en la conversión, borre la memoria caché del explorador y las cookies y vuelva a intentarlo. Si sigue sin funcionar, pruebe a convertir el buzón de correo en el shell de administración de Exchange ejecutando el siguiente comando:
  
```
Set-Mailbox -Type Shared
```

Hay más información sobre la conversión de buzones de correo en [convertir un buzón de usuario en un buzón compartido](https://docs.microsoft.com/office365/admin/email/convert-user-mailbox-to-shared-mailbox).
  
