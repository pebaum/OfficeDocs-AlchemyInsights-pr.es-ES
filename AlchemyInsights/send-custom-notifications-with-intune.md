---
title: Enviar notificaciones personalizadas con Intune
ms.author: brenduns
author: brenduns
manager: dougeby
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000679"
- "2565"
ms.openlocfilehash: 969649084a2ac536ee1b41f225c3be5415a27c4b
ms.sourcegitcommit: 2572c4e5a981d5f3f556835061c568cfd08b78da
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/27/2019
ms.locfileid: "40886874"
---
# <a name="how-to-send-custom-notifications-to-the-users-of-managed-ios-and-android-devices"></a>Cómo enviar notificaciones personalizadas a los usuarios de dispositivos administrados iOS y Android

Las notificaciones personalizadas para Intune las procesa la aplicación portal de empresa en el dispositivo de un usuario. A continuación, la aplicación crea la notificación de inserción en ese dispositivo.

Los siguientes son requisitos previos de dispositivos para admitir la recepción de notificaciones personalizadas, y para que la aplicación cree la notificación de inserción:

- El dispositivo debe tener instalada la aplicación portal de empresa.  

- El dispositivo debe permitir que la aplicación de portal de empresa envíe notificaciones de inserción. Cuando la aplicación se instale o actualice, se le pedirá al usuario que permita las notificaciones.

- Los dispositivos Android deben tener instalado Google Play Services.

- El dispositivo debe estar inscrito con Intune.

Para obtener más información, incluido cómo enviar un mensaje, consulte la documentación de la [característica](https://docs.microsoft.com/intune/custom-notifications).
