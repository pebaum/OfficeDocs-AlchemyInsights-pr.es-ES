---
title: No puedo abrir con el explorador
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 12/10/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: b8f07022-69fe-4112-a2f6-d3a6cedb966c
ms.openlocfilehash: b55fc7bd5670e655334ef7be368b245c8899633a
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28313300"
---
# <a name="open-with-explorer-isnt-working"></a><span data-ttu-id="899ae-102">Abrir con el explorador no funciona</span><span class="sxs-lookup"><span data-stu-id="899ae-102">Open with Explorer isn't working</span></span>

<span data-ttu-id="899ae-p101">Si no puedo **Abrir con el explorador** o **Ver en el Explorador de archivos** Asegúrese de que el servicio de cliente Web se establece a la **ejecución de** siguiendo los pasos siguientes. Por ejemplo, puede tardar mucho tiempo en abrir una biblioteca de SharePoint o OneDrive cuando no se está ejecutando el servicio.</span><span class="sxs-lookup"><span data-stu-id="899ae-p101">If **Open with Explorer** or **View in File Explorer** doesn't work make sure the WebClient service is set to **Running** by following the steps below. For example, it might take a long time to open a SharePoint or OneDrive library when the service is not running.</span></span> 
  
1. <span data-ttu-id="899ae-105">En el cuadro de búsqueda de Windows, escriba ejecutar, seleccione la aplicación de escritorio de ejecutar, escriba services.msc y, a continuación, seleccione **ENTRAR**.</span><span class="sxs-lookup"><span data-stu-id="899ae-105">In the Windows search box, type run, select the Run desktop app, type services.msc, and then select **Enter**.</span></span>
    
2. <span data-ttu-id="899ae-p102">Desplácese hacia abajo hasta el servicio de cliente Web y compruebe la columna **estado** . Si el estado del servicio de cliente Web no está **ejecutando**, haga doble clic en el servicio, haga clic en **Inicio**y, a continuación, haga clic en **Aceptar**. Habilite el servicio, si es necesario, mediante la selección **Manual** o **automática** en el cuadro **tipo de inicio** .</span><span class="sxs-lookup"><span data-stu-id="899ae-p102">Scroll down to the WebClient service and check the **Status** column. If the WebClient service status is not **Running**, double-click the service, click **Start**, and then click **OK**. Enable the service, if needed, by selecting either **Manual** or **Automatic** in the **Startup type** box.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="899ae-p103">Para solucionar problemas de apertura en el Explorador de archivos, vea [abierta en el explorador](https://go.microsoft.com/fwlink/?linkid=871665). Explore la sincronización como una alternativa mejor: [archivos de sincronización de SharePoint con el cliente de sincronización de OneDrive para la nueva](https://go.microsoft.com/fwlink/?linkid=871666).</span><span class="sxs-lookup"><span data-stu-id="899ae-p103">To troubleshoot issues opening in File Explorer, see [Open in Explorer](https://go.microsoft.com/fwlink/?linkid=871665). Explore sync as a better alternative: [Sync SharePoint files with the new OneDrive sync client](https://go.microsoft.com/fwlink/?linkid=871666).</span></span> 
  

