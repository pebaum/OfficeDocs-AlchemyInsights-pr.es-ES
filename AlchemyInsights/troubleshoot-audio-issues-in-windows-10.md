---
title: Solucionar problemas de audio en Windows 10
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3476"
- "9001463"
ms.openlocfilehash: f51fd233db5ae068e719f1cf3bc94a0dac82444f
ms.sourcegitcommit: d87a6ac6ee77375d1d750100359b4dc7b2871691
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/25/2020
ms.locfileid: "42265033"
---
# <a name="troubleshooting-audio-issues-in-windows-10"></a>Solución de problemas de audio en Windows 10

**Ejecutar el solucionador de problemas de audio**

1.  Abra la [configuración para solucionar problemas](ms-settings:troubleshoot).

2.  Seleccionar **reproducir audio** > **ejecute el solucionador de problemas**.

**Establecer el dispositivo predeterminado**

Si te conectas a un dispositivo de audio mediante USB o HDMI, es posible que tengas que establecer ese dispositivo como predeterminado:

1. Abra el**sonido**de **Inicio** > y, a continuación, seleccione **sonido** o cambie los **sonidos del sistema** de la lista de resultados.

2.  En la pestaña **reproducción** , seleccione un dispositivo, seleccione **establecer como predeterminado**y, después, haga clic en **Aceptar**.

**Comprobar los cables, el volumen, los altavoces y los auriculares**

1. Comprueba las conexiones de altavoces y auriculares para ver si hay cables sueltos y asegúrate de que estén conectados a la clavija correcta.

2. Compruebe los niveles de capacidad y volumen e intente subir todos los controles de volumen.

3. Algunos altavoces y aplicaciones tienen sus propios controles de volumen; es posible que tenga que comprobar todos los niveles para asegurarse de que se encuentran en los niveles correctos.

4. Intente conectarse usando un puerto USB diferente.

**Nota**: Recuerde que es posible que los altavoces no funcionen cuando los auriculares estén enchufados.

**Comprobar el administrador de dispositivos**

Para asegurarse de que los controladores están actualizados:

1. Seleccione **Inicio**, escriba **Administrador de dispositivos**y, a continuación, seleccione **Administrador de dispositivos** en la lista de resultados.

2. En **dispositivos de sonido, vídeo y juegos**, seleccione la tarjeta de sonido, ábrala, seleccione la pestaña **controlador** y haga clic en **Actualizar controlador**.

**Nota**: Si Windows no encuentra un nuevo controlador, busca uno en el sitio web del fabricante del dispositivo y sigue sus instrucciones.

**Reinstalar el controlador**

Si no puede actualizar mediante el administrador de dispositivos o encontrar un nuevo controlador en el sitio web del fabricante, pruebe estos pasos:

1. En el administrador de dispositivos, haga clic con el botón derecho (o mantenga presionado) el controlador de audio y seleccione **desinstalar**. Reinicia el dispositivo y Windows intentará reinstalar el controlador.

2. Si no funciona la reinstalación del controlador, prueba a usar el controlador de audio genérico que se incluye con Windows. En el administrador de dispositivos, haga clic con el botón derecho (o mantenga presionado) el controlador de audio > **actualizar el software** > **de controlador buscar en el equipo para el software** > de controlador**permitirme elegir de una lista de controladores de dispositivo en mi PC**, seleccione **dispositivo de audio de alta definición**, seleccione **siguiente**y siga las instrucciones para instalarlo.
