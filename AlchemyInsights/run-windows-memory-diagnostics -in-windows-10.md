---
title: Ejecutar el Diagnóstico de memoria de Windows en Windows 10
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002959"
- "5661"
ms.openlocfilehash: 3fedc52d02f1f70743429d0313eda0361306c3f3
ms.sourcegitcommit: 18b080c2a5d741af01ec589158effc35ea7cf449
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 05/19/2020
ms.locfileid: "44289807"
---
# <a name="run-windows-memory-diagnostics-in-windows-10"></a>Ejecutar el Diagnóstico de memoria de Windows en Windows 10

Si Windows o las aplicaciones de su PC se bloquean, dejan de funcionar o actúan de forma inestable, es posible que tenga un problema con la memoria de su PC (RAM). Puede ejecutar el Diagnóstico de memoria de Windows para comprobar si hay problemas con la memoria RAM de su PC.

En el cuadro de búsqueda de la barra de tareas, escriba **Diagnóstico de memoria** y seleccione **Diagnóstico de Memoria de Windows**. 

Para ejecutar el diagnóstico, es necesario reiniciar el equipo. Puede reiniciar inmediatamente (si lo hace, guarde primero su trabajo y cierre los mensajes de correo y documentos abiertos) o programar el diagnóstico para que se ejecute automáticamente la próxima vez que se reinicie el equipo:

![Diagnóstico de Memoria de Windows](media/windows-memory-diagnostic.png)

Tras reiniciar, la **herramienta Diagnóstico de Memoria de Windows** se ejecutará automáticamente. El estado y el progreso se mostrarán a medida que se ejecuta el diagnóstico. Si lo desea, puede cancelar el diagnóstico pulsando la tecla **ESC** en el teclado.

Cuando finalice el diagnóstico, Windows se iniciará normalmente.
Nada más iniciarse, cuando aparezca el escritorio, verá una notificación (situada junto al icono del **Centro de actividades** de la barra de tareas) que le indicará si se encontraron errores de memoria. Por ejemplo:

Este es el icono del Centro de actividades: ![Icono del Centro de actividades](media/action-center-icon.png) 

Y una notificación de muestra: ![No hay errores de memoria](media/no-memory-errors.png)

Si no llegó a ver la notificación, seleccione el icono del **Centro de actividades** en la barra de tareas para mostrar el **Centro de actividades**. Allí, verá una lista desplegable con todas las notificaciones.

Para revisar información detallada, escriba **evento** en el cuadro de búsqueda de la barra de tareas y, a continuación, seleccione **Visor de eventos**. En el panel izquierdo del **Visor de eventos**, vaya a **Registros de Windows >** Sistema. En el panel derecho, desplácese por la lista sin perder de vista la columna **Origen**, hasta que vea eventos cuyo valor de Origen sea **MemoryDiagnostics-Results**. Si marca uno de esos eventos, verá la información del resultado en el cuadro de la pestaña **General** situado debajo de la lista.
