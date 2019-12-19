---
title: Solución de problemas del monitor existente
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3454"
- "9001450"
ms.openlocfilehash: d90baddd01bdf8508bd6289509c8399b8241887a
ms.sourcegitcommit: 42463e8d8869f36225a27388d83d37629c6b149e
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/18/2019
ms.locfileid: "40738585"
---
# <a name="troubleshoot-an-existing-monitor"></a>Solucionar problemas de un monitor existente

Pruebe estas soluciones para solucionar problemas de un monitor. 

**Actualizar la pantalla del monitor:**

Presione las siguientes teclas al mismo tiempo: tecla Windows + Ctrl + Mayús + B. Esto actualizará la comunicación con el controlador de gráficos. Los monitores parpadearán momentáneamente y regresarán después de unos segundos.

**Solución de problemas de hardware de monitor:**

1. Desconecta el cable que conecta el equipo con el monitor y vuelve a conectarlo.
2. Desconecte los dispositivos que no sean esenciales de su PC (como adaptadores o muelles).

**Si ha instalado recientemente una actualización en su PC, puede revertir el controlador de pantalla:**

1. Seleccione **Inicio**, escriba **Administrador de dispositivos**y seleccione el **Administrador de dispositivos** en los resultados.
2. Expanda la sección **adaptadores de pantalla** , haga clic con el botón secundario en el adaptador de pantalla mezclar seleccione **propiedades**.
3. Vaya a la ficha **controlador** y seleccione **volver al controlador posterior**. <br>
Nota: Si esta opción no está disponible o está atenuada, seleccione **no** en las siguientes opciones para ir al paso siguiente.
4. Es posible que tengas que reiniciar el equipo para que estos cambios surtan efecto.

**Desinstale y vuelva a instalar el controlador de pantalla:**

1. Seleccione **Inicio**, escriba **Administrador de dispositivos**y seleccione el **Administrador de dispositivos** en los resultados.
2. Expanda la sección **adaptadores de pantalla** , haga clic con el botón secundario en el adaptador de pantalla, mezclar seleccione **desinstalar dispositivo**. 
3. Seleccione el cuadro situado junto a **eliminar el software de controlador para este dispositivo** y seleccione **desinstalar**.<br>
Nota: es posible que se le pida que reinicie el equipo en esta fase. Asegúrese de anotar las demás instrucciones antes de reiniciar.
4. Vuelva a abrir el administrador de dispositivos.
5. Expanda la sección **adaptadores de pantalla** , haga clic con el botón secundario en el adaptador de pantalla y seleccione **Actualizar controlador**.
6. Seleccione **Buscar software de controlador de actualización automáticamente** y siga las instrucciones de instalación.