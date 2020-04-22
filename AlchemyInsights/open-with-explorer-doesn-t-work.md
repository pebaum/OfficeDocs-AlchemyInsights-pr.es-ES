---
title: Abrir con el explorador no funciona
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: b8f07022-69fe-4112-a2f6-d3a6cedb966c
ms.openlocfilehash: dc939a3451ff4fe95e4aa5a999839a2c532b398c
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43713051"
---
# <a name="open-with-explorer-isnt-working"></a><span data-ttu-id="d9d3d-102">Abrir con el explorador no funciona</span><span class="sxs-lookup"><span data-stu-id="d9d3d-102">Open with Explorer isn't working</span></span>

<span data-ttu-id="d9d3d-103">Si **abrir con el explorador** o **ver en el explorador de archivos** no funciona, asegúrese de que el servicio WebClient está configurado para **ejecutarse** siguiendo los pasos que se indican a continuación.</span><span class="sxs-lookup"><span data-stu-id="d9d3d-103">If **Open with Explorer** or **View in File Explorer** doesn't work make sure the WebClient service is set to **Running** by following the steps below.</span></span> <span data-ttu-id="d9d3d-104">Por ejemplo, puede tardar mucho tiempo en abrir una biblioteca de SharePoint o de OneDrive cuando el servicio no se está ejecutando.</span><span class="sxs-lookup"><span data-stu-id="d9d3d-104">For example, it might take a long time to open a SharePoint or OneDrive library when the service is not running.</span></span> 
  
1. <span data-ttu-id="d9d3d-105">En el cuadro de búsqueda de Windows, escriba ejecutar, seleccione la aplicación de escritorio ejecutar, escriba Services. msc y, a continuación, seleccione **entrar**.</span><span class="sxs-lookup"><span data-stu-id="d9d3d-105">In the Windows search box, type run, select the Run desktop app, type services.msc, and then select **Enter**.</span></span>
    
2. <span data-ttu-id="d9d3d-106">Desplácese hacia abajo hasta el servicio WebClient y Compruebe la columna **Estado** .</span><span class="sxs-lookup"><span data-stu-id="d9d3d-106">Scroll down to the WebClient service and check the **Status** column.</span></span> <span data-ttu-id="d9d3d-107">Si el estado del servicio WebClient no se está **ejecutando**, haga doble clic en el servicio, haga clic en **iniciar**y, a continuación, haga clic en **Aceptar**.</span><span class="sxs-lookup"><span data-stu-id="d9d3d-107">If the WebClient service status is not **Running**, double-click the service, click **Start**, and then click **OK**.</span></span> <span data-ttu-id="d9d3d-108">Habilite el servicio, si es necesario, seleccionando **manual** o **automático** en el cuadro **tipo de inicio** .</span><span class="sxs-lookup"><span data-stu-id="d9d3d-108">Enable the service, if needed, by selecting either **Manual** or **Automatic** in the **Startup type** box.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="d9d3d-109">Para solucionar problemas de apertura en el explorador de archivos, consulte [abrir en el explorador](https://go.microsoft.com/fwlink/?linkid=871665).</span><span class="sxs-lookup"><span data-stu-id="d9d3d-109">To troubleshoot issues opening in File Explorer, see [Open in Explorer](https://go.microsoft.com/fwlink/?linkid=871665).</span></span> <span data-ttu-id="d9d3d-110">Explore Sync como una alternativa mejor: [sincronizar archivos de SharePoint con el nuevo cliente de sincronización de OneDrive](https://go.microsoft.com/fwlink/?linkid=871666).</span><span class="sxs-lookup"><span data-stu-id="d9d3d-110">Explore sync as a better alternative: [Sync SharePoint files with the new OneDrive sync client](https://go.microsoft.com/fwlink/?linkid=871666).</span></span> 
  

