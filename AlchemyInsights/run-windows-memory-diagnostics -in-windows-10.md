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
# <a name="run-windows-memory-diagnostics-in-windows-10"></a><span data-ttu-id="1e511-102">Ejecutar el Diagnóstico de memoria de Windows en Windows 10</span><span class="sxs-lookup"><span data-stu-id="1e511-102">Run Windows Memory Diagnostics in Windows 10</span></span>

<span data-ttu-id="1e511-103">Si Windows o las aplicaciones de su PC se bloquean, dejan de funcionar o actúan de forma inestable, es posible que tenga un problema con la memoria de su PC (RAM).</span><span class="sxs-lookup"><span data-stu-id="1e511-103">If Windows and apps on your PC are crashing, freezing, or acting in an unstable manner, you may have a problem with the PC’s memory (RAM).</span></span> <span data-ttu-id="1e511-104">Puede ejecutar el Diagnóstico de memoria de Windows para comprobar si hay problemas con la memoria RAM de su PC.</span><span class="sxs-lookup"><span data-stu-id="1e511-104">You can run the Windows Memory Diagnostic to check for problems with the PC’s RAM.</span></span>

<span data-ttu-id="1e511-105">En el cuadro de búsqueda de la barra de tareas, escriba **Diagnóstico de memoria** y seleccione **Diagnóstico de Memoria de Windows**.</span><span class="sxs-lookup"><span data-stu-id="1e511-105">In the search box on your taskbar, type **memory diagnostic**, and then select **Windows Memory Diagnostic**.</span></span> 

<span data-ttu-id="1e511-106">Para ejecutar el diagnóstico, es necesario reiniciar el equipo.</span><span class="sxs-lookup"><span data-stu-id="1e511-106">To run the diagnostic, the PC needs to restart.</span></span> <span data-ttu-id="1e511-107">Puede reiniciar inmediatamente (si lo hace, guarde primero su trabajo y cierre los mensajes de correo y documentos abiertos) o programar el diagnóstico para que se ejecute automáticamente la próxima vez que se reinicie el equipo:</span><span class="sxs-lookup"><span data-stu-id="1e511-107">You have the option to restart immediately (please save your work and close open documents and e-mails first), or schedule the diagnostic to run automatically the next time the PC restarts:</span></span>

![Diagnóstico de Memoria de Windows](media/windows-memory-diagnostic.png)

<span data-ttu-id="1e511-109">Tras reiniciar, la **herramienta Diagnóstico de Memoria de Windows** se ejecutará automáticamente.</span><span class="sxs-lookup"><span data-stu-id="1e511-109">When the PC restarts, the **Windows Memory Diagnostics Tool** will run automatically.</span></span> <span data-ttu-id="1e511-110">El estado y el progreso se mostrarán a medida que se ejecuta el diagnóstico. Si lo desea, puede cancelar el diagnóstico pulsando la tecla **ESC** en el teclado.</span><span class="sxs-lookup"><span data-stu-id="1e511-110">Status and progress will be displayed as the diagnostics run, and you have the option of cancelling the diagnostics by hitting the **ESC** key on your keyboard.</span></span>

<span data-ttu-id="1e511-111">Cuando finalice el diagnóstico, Windows se iniciará normalmente.</span><span class="sxs-lookup"><span data-stu-id="1e511-111">When the diagnostics are complete, Windows will start normally.</span></span>
<span data-ttu-id="1e511-112">Nada más iniciarse, cuando aparezca el escritorio, verá una notificación (situada junto al icono del **Centro de actividades** de la barra de tareas) que le indicará si se encontraron errores de memoria.</span><span class="sxs-lookup"><span data-stu-id="1e511-112">Immediately after restart, when the Desktop appears, a notification will appear (next to the **Action Center** icon on the taskbar), to indicate whether any memory errors were found.</span></span> <span data-ttu-id="1e511-113">Por ejemplo:</span><span class="sxs-lookup"><span data-stu-id="1e511-113">For example:</span></span>

<span data-ttu-id="1e511-114">Este es el icono del Centro de actividades:</span><span class="sxs-lookup"><span data-stu-id="1e511-114">Here's the Action Center icon:</span></span> ![Icono del Centro de actividades](media/action-center-icon.png) 

<span data-ttu-id="1e511-116">Y una notificación de muestra:</span><span class="sxs-lookup"><span data-stu-id="1e511-116">And a sample notification:</span></span> ![No hay errores de memoria](media/no-memory-errors.png)

<span data-ttu-id="1e511-118">Si no llegó a ver la notificación, seleccione el icono del **Centro de actividades** en la barra de tareas para mostrar el **Centro de actividades**. Allí, verá una lista desplegable con todas las notificaciones.</span><span class="sxs-lookup"><span data-stu-id="1e511-118">If you missed the notification, you can select the **Action Center** icon  on the taskbar to display the **Action Center** and see a scrollable list of notifications.</span></span>

<span data-ttu-id="1e511-119">Para revisar información detallada, escriba **evento** en el cuadro de búsqueda de la barra de tareas y, a continuación, seleccione **Visor de eventos**.</span><span class="sxs-lookup"><span data-stu-id="1e511-119">To review detailed information, type **event** into the search box on your taskbar, and then select **Event Viewer**.</span></span> <span data-ttu-id="1e511-120">En el panel izquierdo del **Visor de eventos**, vaya a **Registros de Windows >** Sistema.</span><span class="sxs-lookup"><span data-stu-id="1e511-120">In the **Event Viewer**’s left-hand pane, navigate to **Windows Logs > System**.</span></span> <span data-ttu-id="1e511-121">En el panel derecho, desplácese por la lista sin perder de vista la columna **Origen**, hasta que vea eventos cuyo valor de Origen sea **MemoryDiagnostics-Results**.</span><span class="sxs-lookup"><span data-stu-id="1e511-121">In the right-hand pane, scan down the list while looking at the **Source** column, until you see events with Source value **MemoryDiagnostics-Results**.</span></span> <span data-ttu-id="1e511-122">Si marca uno de esos eventos, verá la información del resultado en el cuadro de la pestaña **General** situado debajo de la lista.</span><span class="sxs-lookup"><span data-stu-id="1e511-122">Highlight each such event and see the result information in the box under the **General** tab below the list.</span></span>
