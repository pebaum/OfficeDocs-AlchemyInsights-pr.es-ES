---
title: Iniciar sesión en Windows 10 sin usar una contraseña
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001690"
- "3766"
ms.openlocfilehash: 1f325eb7afb1e88457296e8187f8ba6dff2ebfe0
ms.sourcegitcommit: 00e4266575438f55bdc18db05ed54aafcb75a3c9
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/11/2020
ms.locfileid: "42588297"
---
# <a name="sign-in-to-windows-10-without-using-a-password"></a>Iniciar sesión en Windows 10 sin usar una contraseña

Para evitar tener que escribir una contraseña durante el inicio de Windows, le recomendamos que use una de las opciones de inicio de sesión seguro de Windows Hello, como un PIN, un reconocimiento facial o una huella digital, si está disponible. Si realmente quiere deshabilitar el inicio de sesión seguro, consulte las instrucciones "iniciar sesión automáticamente en Windows 10" a continuación.

**Proteger las alternativas de Windows Hello a la contraseña de la cuenta**

Vaya a **configuración > cuentas > opciones de inicio de sesión** (o haga clic [aquí](ms-settings:signinoptions?activationSource=GetHelp)). Se mostrarán las opciones de inicio de sesión disponibles. Por ejemplo:

![Opciones de inicio de sesión.](media/sign-in-options.png)

Haga clic o pulse en una de las opciones para configurarla. La siguiente vez que inicie o desbloquee Windows, podrá usar la nueva opción en lugar de una contraseña. 

**Inicio de sesión automático en Windows 10**

**Nota**: el inicio de sesión automático es conveniente, pero introduce un riesgo de seguridad, especialmente si el equipo es accesible para varias personas. 

1. Haga clic o pulse en el botón **Inicio** de la barra de tareas.

2. Escriba **netplwiz** y presione la tecla entrar para abrir la ventana cuentas de usuario.

3. En **cuentas de usuario**, haga clic en la cuenta en la que desea iniciar sesión automáticamente cuando se inicie Windows.

4. Desactive la casilla "los usuarios deben escribir un nombre de usuario y una contraseña para usar el equipo".

    ![Los usuarios deben escribir una opción de nombre de usuario y contraseña.](media/users-must-enter-username.png)

5. Haga clic en **Aceptar**. Se le pedirá que escriba y confirme la contraseña de la cuenta que ha seleccionado. Haga clic en **Aceptar** para finalizar. La próxima vez que se inicie Windows 10, se iniciará sesión automáticamente en la cuenta seleccionada.
