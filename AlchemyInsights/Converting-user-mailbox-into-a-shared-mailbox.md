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
Solo puede convertir un buzón de usuario en un buzón compartido si el usuario tiene una licencia de Exchange. Una vez convertido el buzón, se seguirá mostrando en la lista usuarios activos porque esa lista incluye buzones compartidos. Sin embargo, el buzón convertido también se mostrará en la lista de buzones compartidos. 
  
Si intenta convertir un buzón en la consola de administración de Exchange y se produce un error en la conversión, borre la memoria caché del explorador y las cookies y vuelva a intentarlo. Si sigue sin funcionar, pruebe a convertir el buzón de correo en el shell de administración de Exchange ejecutando el siguiente comando:
  
```
Set-Mailbox -Type Shared
```

Hay más información sobre la conversión de buzones de correo en [convertir un buzón de usuario en un buzón compartido](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba).
  
