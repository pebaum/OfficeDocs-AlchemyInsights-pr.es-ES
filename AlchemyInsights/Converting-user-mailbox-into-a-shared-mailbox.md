---
title: ¿Conversión de buzón de usuario en un buzón compartido?
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
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29906749"
---
Sólo se puede convertir un buzón de usuario a un buzón compartido si el usuario tiene una licencia de Exchange. Después se convierte el buzón de correo, continuará aparezca en la lista de usuarios activos debido a que esa lista incluye los buzones compartidos. Sin embargo, el buzón convertido también aparecerá en la lista de buzones compartidos. 
  
Si se intenta convertir un buzón de correo en la consola de administración de Exchange y se produce un error en la conversión, borre la memoria caché del explorador y las cookies y vuelva a intentarlo. Si aún no funciona, pruebe a convertir el buzón de correo en el Shell de administración de Exchange, ejecute el comando siguiente:
  
```
Set-Mailbox -Type Shared
```

Obtener más información de conversión de buzón de correo está disponible en la [conversión de un buzón de usuario a un buzón compartido](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba).
  
