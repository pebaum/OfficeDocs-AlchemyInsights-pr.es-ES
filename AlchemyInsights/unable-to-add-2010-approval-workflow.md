---
title: No se puede agregar el flujo de trabajo de aprobación de 2010
ms.author: kirks
author: Techwriter40
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 0df65cf9-7eae-4de7-88e9-1914635c8d11
ms.openlocfilehash: a83a9621ca0f7764d3f2c0a698dbffd80d55e80c
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29491567"
---
# <a name="unable-to-add-2010-approval-workflow"></a><span data-ttu-id="bd421-102">No se puede agregar el flujo de trabajo de aprobación de 2010</span><span class="sxs-lookup"><span data-stu-id="bd421-102">Unable to add 2010 Approval Workflow</span></span>

<span data-ttu-id="bd421-103">En una colección de sitios de Microsoft SharePoint, no se puede agregar un flujo de trabajo reutilizable globalmente (por ejemplo, "aprobación - SharePoint 2010") a una lista o biblioteca.</span><span class="sxs-lookup"><span data-stu-id="bd421-103">In a Microsoft SharePoint site collection, you can't add a globally reusable workflow (such as "Approval - SharePoint 2010") to a list or library.</span></span>
  
<span data-ttu-id="bd421-104">Para resolver este problema, siga estos pasos:</span><span class="sxs-lookup"><span data-stu-id="bd421-104">To resolve this issue, follow these steps:</span></span> 
  
1. <span data-ttu-id="bd421-105">Abra el sitio Web raíz de la colección de sitios en SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="bd421-105">Open the root website of the site collection in SharePoint Designer 2013.</span></span>
  
2. <span data-ttu-id="bd421-106">En los **Objetos del sitio**, seleccione **flujos de trabajo**.</span><span class="sxs-lookup"><span data-stu-id="bd421-106">Under **Site Objects**, select **Workflows**.</span></span> 
  
3. <span data-ttu-id="bd421-107">En la sección **nuevo** de la cinta de opciones de **flujos de trabajo** , seleccione **Flujo de trabajo reutilizable**.</span><span class="sxs-lookup"><span data-stu-id="bd421-107">In the **New** section of the **Workflows** ribbon, select **Reusable Workflow**.</span></span> 
  
4. <span data-ttu-id="bd421-p101">En el formulario de **Creación de flujo de trabajo reutilizable** , escriba el nombre \*\* *Repair2010* \*\*. Para **Tipo de plataforma**, haga clic en **El flujo de trabajo de SharePoint 2010**y, a continuación, haga clic en **Aceptar**.</span><span class="sxs-lookup"><span data-stu-id="bd421-p101">On the **Create Reusable Workflow** form, enter the name \*\* *Repair2010* \*\*. For **Platform Type**, click **SharePoint 2010 Workflow**, and then click **OK**.</span></span> 
  
1. <span data-ttu-id="bd421-110">En la sección **Guardar** de la cinta de opciones de **flujo de trabajo** , seleccione **Publicar**.</span><span class="sxs-lookup"><span data-stu-id="bd421-110">In the **Save** section of the **Workflow** ribbon, select **Publish**.</span></span> 
  
2. <span data-ttu-id="bd421-p102">En la sección **Administrar** de la cinta de opciones de **flujo de trabajo** , seleccione **Publicar globalmente**. En el cuadro de diálogo de confirmación que aparece, seleccione **Aceptar**.</span><span class="sxs-lookup"><span data-stu-id="bd421-p102">In the **Manage** section of the **Workflow** ribbon, select **Publish Globally**. In the confirmation dialog box that appears, select **OK**.</span></span> 
  
3. <span data-ttu-id="bd421-p103">En un explorador web, busque el sitio Web raíz de la colección de sitios y, a continuación, obtener acceso a **La configuración del sitio** \> **Características de colección de sitios**. Permite activar o desactivar la característica de **flujos de trabajo** :</span><span class="sxs-lookup"><span data-stu-id="bd421-p103">In a web browser, locate the root website of the site collection, and then access **Site Settings** \> **Site Collection Features**. Toggle the **Workflows** feature:</span></span> 
  
<span data-ttu-id="bd421-115">· Si la característica está *activado* , haga clic en **desactivar** y, a continuación, haga clic en **Activar**.</span><span class="sxs-lookup"><span data-stu-id="bd421-115">· If the feature is  *Activated*  , click **Deactivate,** and then click **Activate**.</span></span> 
  
<span data-ttu-id="bd421-116">· Si la característica está *desactivado* , haga clic en **Activar**.</span><span class="sxs-lookup"><span data-stu-id="bd421-116">· If the feature is  *Deactivated*  , click **Activate**.</span></span> 
  
<span data-ttu-id="bd421-117">Para obtener más información, consulte el siguiente [artículo](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="bd421-117">For more information please refer to the following [article](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span></span>
  

