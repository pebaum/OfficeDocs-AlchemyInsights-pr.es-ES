---
title: No se puede agregar de forma predeterminada flujo de trabajo de aprobación de 2010
ms.author: kirks
author: Techwriter40
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 2060c9a1-e714-4d93-925e-629c82c35986
ms.openlocfilehash: 758b0339b842478f9609eb716b5b4ddab6579c80
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28313303"
---
# <a name="cant-add-default-2010-approval-workflow"></a><span data-ttu-id="d0e0d-102">No se puede agregar de forma predeterminada flujo de trabajo de aprobación de 2010</span><span class="sxs-lookup"><span data-stu-id="d0e0d-102">Can't add default 2010 Approval Workflow</span></span>

<span data-ttu-id="d0e0d-103">En una colección de sitios de Microsoft SharePoint, no se puede agregar un flujo de trabajo reutilizable globalmente (por ejemplo, "aprobación - SharePoint 2010") a una lista o biblioteca.</span><span class="sxs-lookup"><span data-stu-id="d0e0d-103">In a Microsoft SharePoint site collection, you can't add a globally reusable workflow (such as "Approval - SharePoint 2010") to a list or library.</span></span>
  
<span data-ttu-id="d0e0d-104">Para resolver este problema, siga estos pasos:</span><span class="sxs-lookup"><span data-stu-id="d0e0d-104">To resolve this issue, follow these steps:</span></span> 
  
1. <span data-ttu-id="d0e0d-105">Abra el sitio Web raíz de la colección de sitios en SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="d0e0d-105">Open the root website of the site collection in SharePoint Designer 2013.</span></span>
  
2. <span data-ttu-id="d0e0d-106">En los **Objetos del sitio**, seleccione **flujos de trabajo**.</span><span class="sxs-lookup"><span data-stu-id="d0e0d-106">Under **Site Objects**, select **Workflows**.</span></span> 
  
3. <span data-ttu-id="d0e0d-107">En la sección **nuevo** de la cinta de opciones de **flujos de trabajo** , seleccione **Flujo de trabajo reutilizable**.</span><span class="sxs-lookup"><span data-stu-id="d0e0d-107">In the **New** section of the **Workflows** ribbon, select **Reusable Workflow**.</span></span> 
  
4. <span data-ttu-id="d0e0d-p101">En el formulario de **Creación de flujo de trabajo reutilizable** , escriba el nombre \* \*\*Repair2010\*\*\*. Para **Tipo de plataforma**, seleccione **Flujo de trabajo de SharePoint 2010**y, a continuación, seleccione **Aceptar**.</span><span class="sxs-lookup"><span data-stu-id="d0e0d-p101">On the **Create Reusable Workflow** form, enter the name  \* **Repair2010**\* . For **Platform Type**, select **SharePoint 2010 Workflow**, and then select **OK**.</span></span> 
  
5. <span data-ttu-id="d0e0d-110">En la sección **Guardar** de la cinta de opciones de **flujo de trabajo** , seleccione **Publicar**.</span><span class="sxs-lookup"><span data-stu-id="d0e0d-110">In the **Save** section of the **Workflow** ribbon, select **Publish**.</span></span> 
  
6. <span data-ttu-id="d0e0d-p102">En la sección **Administrar** de la cinta de opciones de **flujo de trabajo** , seleccione **Publicar globalmente**. En el cuadro de diálogo de confirmación que aparece, seleccione **Aceptar**.</span><span class="sxs-lookup"><span data-stu-id="d0e0d-p102">In the **Manage** section of the **Workflow** ribbon, select **Publish Globally**. In the confirmation dialog box that appears, select **OK**.</span></span> 
  
7. <span data-ttu-id="d0e0d-p103">En un explorador web, busque el sitio Web raíz de la colección de sitios y, a continuación, obtener acceso a **La configuración del sitio** \> **Características de colección de sitios**. A continuación, activar o desactivar la característica de **flujos de trabajo** :</span><span class="sxs-lookup"><span data-stu-id="d0e0d-p103">In a web browser, locate the root website of the site collection, and then access **Site Settings** \> **Site Collection Features**. Then, toggle the **Workflows** feature:</span></span> 
  
<span data-ttu-id="d0e0d-115">· Si la característica está *activado* , haga clic en **desactivar** y, a continuación, haga clic en **Activar**.</span><span class="sxs-lookup"><span data-stu-id="d0e0d-115">· If the feature is  *Activated*  , click **Deactivate,** and then click **Activate**.</span></span> 
  
<span data-ttu-id="d0e0d-116">· Si la característica está *desactivado* , haga clic en **Activar**.</span><span class="sxs-lookup"><span data-stu-id="d0e0d-116">· If the feature is  *Deactivated*  , click **Activate**.</span></span> 
  
<span data-ttu-id="d0e0d-117">Para obtener más información, consulte el siguiente [artículo](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="d0e0d-117">For more information please refer to the following [article](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span></span>
  

