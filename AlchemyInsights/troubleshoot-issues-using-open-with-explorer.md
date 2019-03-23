---
title: Solución de problemas al usar abrir con el explorador
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 12/10/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: ed852342-e33f-4450-8400-63d30df09476
ms.openlocfilehash: 03bb3ad01a716390ec50845b29ddf6cc81a83116
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/22/2019
ms.locfileid: "30759311"
---
# <a name="fix-problems-with-open-with-explorer"></a><span data-ttu-id="32da7-102">Solucionar problemas con abrir con el explorador</span><span class="sxs-lookup"><span data-stu-id="32da7-102">Fix problems with Open with Explorer</span></span>

<span data-ttu-id="32da7-103">Solucionar problemas comunes de la apertura de una biblioteca de documentos en SharePoint o OneDrive con el comando **abrir con el explorador** :</span><span class="sxs-lookup"><span data-stu-id="32da7-103">Fix common problems with opening a document library in SharePoint or OneDrive using the **Open with Explorer** command:</span></span> 
  
- <span data-ttu-id="32da7-104">Usar Internet Explorer 10 o Internet Explorer 11.</span><span class="sxs-lookup"><span data-stu-id="32da7-104">Use Internet Explorer 10 or Internet Explorer 11.</span></span> <span data-ttu-id="32da7-105">**Abrir con el explorador** no es compatible con Microsoft Edge, Google Chrome, Firefox y otros.</span><span class="sxs-lookup"><span data-stu-id="32da7-105">**Open with Explorer** isn't compatible with Microsoft Edge, Google Chrome, Firefox and others.</span></span> <span data-ttu-id="32da7-106">**Abrir con el explorador** está deshabilitado en todos los exploradores excepto en Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="32da7-106">**Open with Explorer** is disabled in all browsers except Internet Explorer.</span></span> 
    
- <span data-ttu-id="32da7-107">**Abrir con el explorador** no está disponible en la experiencia moderna de las bibliotecas de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="32da7-107">**Open with Explorer** is not available in the modern experience for SharePoint libraries.</span></span> <span data-ttu-id="32da7-108">En su lugar, use **ver en el explorador de archivos** .</span><span class="sxs-lookup"><span data-stu-id="32da7-108">Use **View in File Explorer** instead.</span></span> <span data-ttu-id="32da7-109">Seleccione Ver **Opciones** \> **de vista en el explorador de archivos**.</span><span class="sxs-lookup"><span data-stu-id="32da7-109">Select **View options** \> **View in File Explorer**.</span></span> <span data-ttu-id="32da7-110">Ver en el explorador de archivos no es compatible con Microsoft Edge, Google Chrome, Firefox y otros.</span><span class="sxs-lookup"><span data-stu-id="32da7-110">View in File Explorer is not compatible with Microsoft Edge, Google Chrome, Firefox and others.</span></span> <span data-ttu-id="32da7-111">**Ver en el explorador de archivos** solo está disponible en Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="32da7-111">**View in File Explorer** in available only in Internet Explorer.</span></span> 
    
- <span data-ttu-id="32da7-112">Asegúrese de que el servicio WebClient se está ejecutando.</span><span class="sxs-lookup"><span data-stu-id="32da7-112">Make sure the WebClient service is running.</span></span> <span data-ttu-id="32da7-113">En el cuadro de búsqueda de Windows, escriba ejecutar, seleccione la aplicación de escritorio ejecutar, escriba Services. msc y, a continuación, presione Entrar.</span><span class="sxs-lookup"><span data-stu-id="32da7-113">In the Windows search box, type run, select the Run desktop app, type services.msc, and then press Enter.</span></span> <span data-ttu-id="32da7-114">Desplácese hacia abajo hasta el servicio WebClient y asegúrese de que la columna **Estado** muestra "en ejecución".</span><span class="sxs-lookup"><span data-stu-id="32da7-114">Scroll down to the WebClient service and make sure the **Status** column displays "Running."</span></span> <span data-ttu-id="32da7-115">Si no es así, haga doble clic en el servicio, haga clic en **Inicio**y, a continuación, haga clic en **Aceptar**.</span><span class="sxs-lookup"><span data-stu-id="32da7-115">If it doesn't, double-click the service, click **Start**, and then click **OK**.</span></span> <span data-ttu-id="32da7-116">(Es posible que tenga que habilitar primero el servicio seleccionando **manual** o **automático** en el cuadro **tipo de inicio** ).</span><span class="sxs-lookup"><span data-stu-id="32da7-116">(You might need to first enable the service by selecting either **Manual** or **Automatic** in the **Startup type** box.)</span></span> 
    
> [!NOTE]
> <span data-ttu-id="32da7-117">Abrir una biblioteca en el explorador de archivos es útil si necesita copiar o mover varios archivos y carpetas una vez, pero si desea trabajar con regularidad en la biblioteca, le recomendamos que lo sincronice.</span><span class="sxs-lookup"><span data-stu-id="32da7-117">Opening a library in File Explorer is handy if you need to copy or move multiple files and folders once, but if you want to regularly work in the library, we recommend syncing it.</span></span> <span data-ttu-id="32da7-118">Para solucionar problemas de apertura en el explorador de archivos, consulte [abrir en el explorador](https://go.microsoft.com/fwlink/?linkid=871665).</span><span class="sxs-lookup"><span data-stu-id="32da7-118">To troubleshoot issues opening in File Explorer, see [Open in Explorer](https://go.microsoft.com/fwlink/?linkid=871665).</span></span> <span data-ttu-id="32da7-119">Para obtener información sobre cómo configurar la sincronización, vea [sincronizar archivos de SharePoint con el nuevo cliente de sincronización de OneDrive](https://go.microsoft.com/fwlink/?linkid=871666).</span><span class="sxs-lookup"><span data-stu-id="32da7-119">For info about setting up sync, see [Sync SharePoint files with the new OneDrive sync client](https://go.microsoft.com/fwlink/?linkid=871666).</span></span>
  
<span data-ttu-id="32da7-120">Consulte el artículo [Cómo usar el comando "abrir con el explorador" para solucionar problemas en SharePoint Online](https://support.office.com/article/How-to-use-the-Open-with-Explorer-command-to-troubleshoot-issues-in-SharePoint-Online-87155331-0c92-4224-a4c1-da5c21c4ade4) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="32da7-120">Please see the article [How to use the "Open with Explorer" command to troubleshoot issues in SharePoint Online](https://support.office.com/article/How-to-use-the-Open-with-Explorer-command-to-troubleshoot-issues-in-SharePoint-Online-87155331-0c92-4224-a4c1-da5c21c4ade4) for more information.</span></span> 
  

