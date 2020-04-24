---
title: Registro duplicado de dispositivo en el portal
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001495"
- "4386"
ms.openlocfilehash: 277afc59705e6040f0f9ae0c8cad965bd7d3ef65
ms.sourcegitcommit: 89ae9e8b36d1980f89f07b016fff0ec48f96b620
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2020
ms.locfileid: "43790174"
---
# <a name="duplicate-device-record-in-the-portal"></a>Registro duplicado de dispositivo en el portal

Es posible que vea dos registros de un mismo dispositivo en el portal si el dispositivo no ha informado correctamente del estado de administración conjunta en el sitio de Configuration Manager. Para comprobar el estado de administración conjunta de un dispositivo, revise la columna **Administrado conjuntamente** del dispositivo en la consola de Configuration Manager. Si la columna no está visible, puede agregarla haciendo clic con el botón derecho en cualquiera de los encabezados de columna y seleccionándola en la lista.

El valor de administración conjunta tiene que ser **Sí**. Si el valor es **No**, abra el applet de cliente de Configuration Manager en el dispositivo cliente y compruebe la propiedad **Administración conjunta** en la pestaña General.

- Si el valor es **Habilitado**, existen problemas con la comunicación del cliente con el punto de administración. Revise **CcmMessaging.log** en el dispositivo para investigar posibles problemas de conectividad.

- Si el valor es **Deshabilitado** y el dispositivo está inscrito en Intune, revise **CoManagementHandler.log** en el dispositivo para asegurarse de que el dispositivo ha recibido la Directiva de administración conjunta.
