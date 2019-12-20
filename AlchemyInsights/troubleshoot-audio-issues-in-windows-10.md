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
ms.openlocfilehash: 46b23f97c2e682258224dc95e7a76b1201991828
ms.sourcegitcommit: 802537a54ef8bde1bdd758ee9a60b6c19d37d6e1
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/19/2019
ms.locfileid: "40796395"
---
# <a name="troubleshooting-audio-problems-in-windows-10"></a>Solución de problemas de audio en Windows 10

**Ejecutar el solucionador de problemas de audio**

Es posible que el solucionador de problemas de audio pueda corregir los problemas de audio automáticamente: 

1. Seleccione **Inicio**, escriba **solución de problemas**y, a continuación, seleccione **solución de problemas** en la lista de resultados. 
2. Seleccionar **reproducir audio** > **ejecute el solucionador de problemas**.

**Comprobar los cables, el volumen, los altavoces y los auriculares**

- Comprueba las conexiones de altavoces y auriculares para ver si hay cables sueltos y asegúrate de que estén conectados a la clavija correcta.
- Compruebe los niveles de energía y volumen e intente subir todos los controles de volumen.
- Algunos altavoces y aplicaciones tienen sus propios controles de volumen y es posible que debas comprobar todos ellos para asegurarse de que se encuentran en los niveles correctos.
- Intente conectarse usando un puerto USB diferente.
- **Nota:** Recuerde que es posible que los altavoces no funcionen cuando los auriculares estén conectados.

**Comprobar el administrador de dispositivos**

Para asegurarse de que los controladores están actualizados:

- Seleccione **Inicio**, escriba **Administrador de dispositivos**y, a continuación, seleccione **Administrador de dispositivos** en la lista de resultados.

2. En **dispositivos de sonido, vídeo y juegos**, seleccione la tarjeta de sonido, ábrala, seleccione la pestaña **controlador** y haga clic en **Actualizar controlador**. 

**Nota:** Si Windows no encuentra un nuevo controlador, busca uno en el sitio web del fabricante del dispositivo y sigue sus instrucciones.

**Reinstalar el controlador**

Si no puede actualizar mediante el administrador de dispositivos o encontrar un nuevo controlador en el sitio web del fabricante, pruebe estos pasos: 

1. En el administrador de dispositivos, haga clic con el botón derecho (o mantenga presionado) el controlador de audio y seleccione **desinstalar**. Reinicia el dispositivo y Windows intentará reinstalar el controlador.

2. Si no funciona la reinstalación del controlador, prueba a usar el controlador de audio genérico que se incluye con Windows. En el administrador de dispositivos, haga clic con el botón derecho (o mantenga presionado) el controlador de audio > **actualizar el software** > **de controlador buscar en el equipo para el software** > de controlador**permitirme elegir de una lista de controladores de dispositivo en mi PC**, seleccione **dispositivo de audio de alta definición**, seleccione **siguiente**y siga las instrucciones para instalarlo.

**Establecer el dispositivo predeterminado**

Si te conectas a un dispositivo de audio mediante USB o HDMI, es posible que tengas que establecer ese dispositivo como predeterminado: 

1. Seleccione **Inicio**, escriba **sonido**y, a continuación, seleccione **sonido** o **cambiar sonidos del sistema** de la lista de resultados.

2. En la pestaña **reproducción** , seleccione un dispositivo, seleccione **establecer como predeterminado**y, después, haga clic en **Aceptar**.

