---
title: No se puede Agregar el flujo de trabajo de aprobación de 2010
ms.author: pebaum
author: pebaum
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 0df65cf9-7eae-4de7-88e9-1914635c8d11
ms.openlocfilehash: 11ba9bf04f826b0d7465a9a81a36c327e79f4d13
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/15/2019
ms.locfileid: "40049570"
---
# <a name="unable-to-add-2010-approval-workflow"></a>No se puede Agregar el flujo de trabajo de aprobación de 2010

En una colección de sitios de Microsoft SharePoint, no se puede Agregar un flujo de trabajo reutilizable globalmente (como "Approval-SharePoint 2010") a una lista o biblioteca.
  
Para resolver este problema, siga estos pasos: 
  
1. Abra el sitio Web raíz de la colección de sitios en SharePoint Designer 2013.
  
2. En **objetos de sitio**, seleccione **flujos de trabajo**. 
  
3. En la sección **nuevo** de la cinta **flujos de trabajo** , seleccione flujo de **trabajo reutilizable**. 
  
4. En el formulario **Crear flujo de trabajo reutilizable** , escriba el nombre * * *Repair2010* * *. En **tipo de plataforma**, haga clic en **flujo de trabajo de SharePoint 2010**y, a continuación, haga clic en **Aceptar**. 
  
1. En la sección **Guardar** de la cinta de opciones de **flujo de trabajo** , seleccione **publicar**. 
  
2. En la sección **administrar** de la cinta de opciones de **flujo de trabajo** , seleccione **publicar globalmente**. En el cuadro de diálogo de confirmación que aparece, seleccione **Aceptar**. 
  
3. En un explorador Web, busque el sitio Web raíz de la colección de sitios y, a continuación, obtenga acceso a **características de colección de sitios**de configuración \> del **sitio** . Activar o desactivar la característica **flujos de trabajo** : 
  
· Si la característica está *activada* , haga clic en desactivar **y, a** continuación, haga clic en **Activar**. 
  
· Si la característica está *desactivada* , haga clic en **Activar**. 
  
Para obtener más información, consulte el siguiente [artículo](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).
  

