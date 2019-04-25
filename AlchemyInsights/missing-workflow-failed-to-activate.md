---
title: No se pudo activar el flujo de trabajo ausente
ms.author: kirks
author: Techwriter40
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: e46ae8c5-3d81-457e-8c77-f7c1cbe267c4
ms.openlocfilehash: ce088227a3206fa05b99331fdb022fbe4886203f
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "32418450"
---
# <a name="missing-workflow-failed-to-activate"></a>No se pudo activar el flujo de trabajo ausente

En una colección de sitios de Microsoft SharePoint, no se puede Agregar un flujo de trabajo reutilizable globalmente (como "Approval-SharePoint 2010") a una lista o biblioteca.
  
Para resolver este problema, siga estos pasos: 
  
1. Abra el sitio Web raíz de la colección de sitios en SharePoint Designer 2013.
  
2. En **objetos de sitio**, seleccione **flujos de trabajo**. 
  
3. En la sección **nuevo** de la cinta **flujos de trabajo** , seleccione flujo de trabajo reutilizable. **** 
  
4. En el formulario **Crear flujo de trabajo** reutilizable, escriba el nombre * * *Repair2010* * *. En **tipo de plataforma**, haga clic en **flujo de trabajo de SharePoint 2010**y, a continuación, haga clic en **Aceptar**. 
  
1. En la sección **Guardar** de la cinta de opciones de **flujo de trabajo** , seleccione **publicar**. 
  
2. En la sección **administrar** de la cinta de opciones de **flujo de trabajo** , seleccione **publicar globalmente**. En el cuadro de diálogo de confirmación que aparece, seleccione **Aceptar**. 
  
3. En un explorador Web, busque el sitio Web raíz de la colección de sitios y, a continuación, obtenga acceso a **características de colección de sitios**de configuración \> del **sitio** . A continuación, active la característica **flujos de trabajo** : 
  
· Si la característica está *activada* , haga **** clic en desactivar y, a continuación, haga clic en **Activar**. 
  
· Si la característica está ** desactivada, haga clic en **Activar**. 
  
Para obtener más información, consulte el siguiente [artículo](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).
  

