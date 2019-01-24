---
title: Supervisión de acceso condicional
ms.author: pebaum
author: pebaum
ms.date: 8/1/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: dcb86c54-769e-4832-9f88-bc45f1e5f36c
ms.openlocfilehash: 06307b57475e8828e6d4e5e01625d5100576f12b
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29490661"
---
# <a name="monitoring-conditional-access"></a>Supervisión de acceso condicional

Usuarios con acceso condicional recibirá un correo electrónico de notificación si no cumplen los requisitos de acceso de la organización. Para resolver, se recomienda una o varias de las siguientes soluciones:
  
- Si se supone que el dispositivo se inscriben, avisar al usuario ir a la aplicación de Portal de empresa y compruebe que aparece en el Portal de la compañía. Si no es así, el usuario debe inscribirse el dispositivo.
    
- En el portal de Azure, vaya a **Intune \> cumplimiento de dispositivo**. Haga clic en **cumplimiento de dispositivo**de **Monitor** . Ver el informe de cumplimiento de normas de dispositivos para comprobar que el dispositivo del usuario está marcado como compatible. 
    
- En el portal de Azure, vaya a **Intune \> cumplimiento de dispositivo**. En **Administrar**, haga clic en **directivas**. En la lista de directivas de cumplimiento, compruebe que tiene asignado un perfil de dispositivo del usuario. Si no se ha asignado ningún perfil, Intune no podrá comprobar el estado de cumplimiento del dispositivo. 
    
- Editar la asignación de acceso condicional del usuario.
    
1. En el portal de Azure, vaya a **Intune \> acceso condicional \> directivas**
    
2. Seleccione una directiva de la lista
    
3. Haga clic en **usuarios y grupos**
    
4. Para dirigir una directiva determinada en una persona, agregarlos a la lista de **inclusión** . Para asegurarse de que una persona se omite en la directiva, agregarlos a la lista de **exclusión** . 
    
Más información: [cómo controlar el acceso condicional dispositivos](https://docs.microsoft.com/en-us/intune/conditional-access-exchange-monitor)
  

