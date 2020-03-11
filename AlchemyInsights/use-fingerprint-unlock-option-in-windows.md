---
title: Usar la opción de desbloqueo de huellas digitales en Windows 10
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001689"
- "3765"
ms.openlocfilehash: 8a5059c722c306ad79811140062cec7f52f31766
ms.sourcegitcommit: 00e4266575438f55bdc18db05ed54aafcb75a3c9
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/11/2020
ms.locfileid: "42588332"
---
# <a name="use-fingerprint-unlock-option-in-windows-10"></a>Usar la opción de desbloqueo de huellas digitales en Windows 10

**Habilitar huella digital de Windows Hello**

Para desbloquear Windows 10 con tu huella digital, debes configurar la huella digital de Windows Hello agregando (permitiendo que Windows aprenda a reconocer), al menos, un dedo. 

1. Vaya a **configuración > cuentas > opciones de inicio de sesión** (o haga clic [aquí](ms-settings:signinoptions?activationSource=GetHelp)). Se mostrarán las opciones de inicio de sesión disponibles. Por ejemplo:

    ![Opciones de inicio de sesión.](media/sign-in-options.png)

2. Haga clic o pulse **huella digital de Windows Hello**y, a continuación, haga clic en **configurar**. En la ventana de configuración de Windows Hello **, haga clic en introducción.** El sensor de huellas digitales se activará y se le pedirá que ponga el dedo en el sensor:

   ![Sensor de huellas digitales.](media/fingerprint-sensor.png)

3. Sigue las instrucciones, que te pedirán que digitalices el dedo repetidamente. Cuando termine, tendrá la opción de agregar otros dedos que quiera usar para el inicio de sesión. La próxima vez que inicie sesión en Windows 10, tendrá la opción de usar su huella dactilar para hacerlo.

**Huella digital de Windows Hello no disponible como opción de inicio de sesión**

Si la huella digital de Windows Hello no se muestra como una opción en **Opciones de inicio de sesión**, significa que Windows no tiene constancia de ningún escáner o lector de huellas digitales conectado a tu PC, o que una directiva del sistema impide su uso (si, por ejemplo, el equipo está administrado por el área de trabajo). Para solucionar problemas: 

1. Seleccione el botón **Inicio** de la barra de tareas y busque **Administrador de dispositivos**.

2. Haga clic o pulse para abrir el **Administrador de dispositivos**.

3. En el administrador de dispositivos, expanda dispositivos biométricos haciendo clic en su cheurón.

   ![Dispositivos biométricos.](media/biometric-devices.png)

4. El escáner de huellas digitales debe aparecer como un dispositivo biométrico, como el explorador de WBDI de Synaptics:

   ![Dispositivos biométricos.](media/biometric-devices-expanded.png)

5. Si no se muestra el escáner de huellas digitales y el escáner está integrado en el equipo, ve al sitio web del fabricante del equipo. En la sección de soporte técnico de su modelo de equipo, busque un controlador de Windows 10 para un escáner que pueda instalar.

6. Si el escáner es independiente del equipo (conectado a través de USB), ve al sitio web del fabricante del escáner para buscar e instalar el software de controlador de dispositivo de Windows 10 para el modelo de escáner que tienes.
