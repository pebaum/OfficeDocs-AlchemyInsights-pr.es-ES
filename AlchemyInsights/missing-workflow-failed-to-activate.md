---
title: No se pudo activar el flujo de trabajo ausente
ms.author: pebaum
author: Techwriter40
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: e46ae8c5-3d81-457e-8c77-f7c1cbe267c4
ms.openlocfilehash: f03d7e1441465050c4b0608f4100f217b183d2e2
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/15/2019
ms.locfileid: "36753813"
---
# <a name="missing-workflow-failed-to-activate"></a><span data-ttu-id="f272b-102">No se pudo activar el flujo de trabajo ausente</span><span class="sxs-lookup"><span data-stu-id="f272b-102">Missing Workflow Failed to Activate</span></span>

<span data-ttu-id="f272b-103">En una colección de sitios de Microsoft SharePoint, no se puede Agregar un flujo de trabajo reutilizable globalmente (como "Approval-SharePoint 2010") a una lista o biblioteca.</span><span class="sxs-lookup"><span data-stu-id="f272b-103">In a Microsoft SharePoint site collection, you can't add a globally reusable workflow (such as "Approval - SharePoint 2010") to a list or library.</span></span>
  
<span data-ttu-id="f272b-104">Para resolver este problema, siga estos pasos:</span><span class="sxs-lookup"><span data-stu-id="f272b-104">To resolve this issue, follow these steps:</span></span> 
  
1. <span data-ttu-id="f272b-105">Abra el sitio Web raíz de la colección de sitios en SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="f272b-105">Open the root website of the site collection in SharePoint Designer 2013.</span></span>
  
2. <span data-ttu-id="f272b-106">En **objetos de sitio**, seleccione **flujos de trabajo**.</span><span class="sxs-lookup"><span data-stu-id="f272b-106">Under **Site Objects**, select **Workflows**.</span></span> 
  
3. <span data-ttu-id="f272b-107">En la sección **nuevo** de la cinta **flujos de trabajo** , seleccione flujo de **trabajo reutilizable**.</span><span class="sxs-lookup"><span data-stu-id="f272b-107">In the **New** section of the **Workflows** ribbon, select **Reusable Workflow**.</span></span> 
  
4. <span data-ttu-id="f272b-108">En el formulario **Crear flujo de trabajo reutilizable** , escriba el nombre \* \* *Repair2010* \* \*.</span><span class="sxs-lookup"><span data-stu-id="f272b-108">On the **Create Reusable Workflow** form, enter the name \*\* *Repair2010* \*\*.</span></span> <span data-ttu-id="f272b-109">En **tipo de plataforma**, haga clic en **flujo de trabajo de SharePoint 2010**y, a continuación, haga clic en **Aceptar**.</span><span class="sxs-lookup"><span data-stu-id="f272b-109">For **Platform Type**, click **SharePoint 2010 Workflow**, and then click **OK**.</span></span> 
  
1. <span data-ttu-id="f272b-110">En la sección **Guardar** de la cinta de opciones de **flujo de trabajo** , seleccione **publicar**.</span><span class="sxs-lookup"><span data-stu-id="f272b-110">In the **Save** section of the **Workflow** ribbon, select **Publish**.</span></span> 
  
2. <span data-ttu-id="f272b-111">En la sección **administrar** de la cinta de opciones de **flujo de trabajo** , seleccione **publicar globalmente**.</span><span class="sxs-lookup"><span data-stu-id="f272b-111">In the **Manage** section of the **Workflow** ribbon, select **Publish Globally**.</span></span> <span data-ttu-id="f272b-112">En el cuadro de diálogo de confirmación que aparece, seleccione **Aceptar**.</span><span class="sxs-lookup"><span data-stu-id="f272b-112">In the confirmation dialog box that appears, select **OK**.</span></span> 
  
3. <span data-ttu-id="f272b-113">En un explorador Web, busque el sitio Web raíz de la colección de sitios y, a continuación, obtenga acceso a **características de colección de sitios**de configuración \> del **sitio** .</span><span class="sxs-lookup"><span data-stu-id="f272b-113">In a web browser, locate the root website of the site collection, and then access **Site Settings** \> **Site Collection Features**.</span></span> <span data-ttu-id="f272b-114">A continuación, active la característica **flujos de trabajo** :</span><span class="sxs-lookup"><span data-stu-id="f272b-114">Then, toggle the **Workflows** feature:</span></span> 
  
<span data-ttu-id="f272b-115">· Si la característica está *activada* , haga clic en desactivar **y, a** continuación, haga clic en **Activar**.</span><span class="sxs-lookup"><span data-stu-id="f272b-115">· If the feature is  *Activated*  , click **Deactivate,** and then click **Activate**.</span></span> 
  
<span data-ttu-id="f272b-116">· Si la característica está *desactivada* , haga clic en **Activar**.</span><span class="sxs-lookup"><span data-stu-id="f272b-116">· If the feature is  *Deactivated*  , click **Activate**.</span></span> 
  
<span data-ttu-id="f272b-117">Para obtener más información, consulte el siguiente [artículo](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="f272b-117">For more information please refer to the following [article](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span></span>
  

