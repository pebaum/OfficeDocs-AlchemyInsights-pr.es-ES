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
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29490693"
---
# <a name="cant-add-default-2010-approval-workflow"></a>No se puede agregar de forma predeterminada flujo de trabajo de aprobación de 2010

En una colección de sitios de Microsoft SharePoint, no se puede agregar un flujo de trabajo reutilizable globalmente (por ejemplo, "aprobación - SharePoint 2010") a una lista o biblioteca.
  
Para resolver este problema, siga estos pasos: 
  
1. Abra el sitio Web raíz de la colección de sitios en SharePoint Designer 2013.
  
2. En los **Objetos del sitio**, seleccione **flujos de trabajo**. 
  
3. En la sección **nuevo** de la cinta de opciones de **flujos de trabajo** , seleccione **Flujo de trabajo reutilizable**. 
  
4. En el formulario de **Creación de flujo de trabajo reutilizable** , escriba el nombre * **Repair2010***. Para **Tipo de plataforma**, seleccione **Flujo de trabajo de SharePoint 2010**y, a continuación, seleccione **Aceptar**. 
  
5. En la sección **Guardar** de la cinta de opciones de **flujo de trabajo** , seleccione **Publicar**. 
  
6. En la sección **Administrar** de la cinta de opciones de **flujo de trabajo** , seleccione **Publicar globalmente**. En el cuadro de diálogo de confirmación que aparece, seleccione **Aceptar**. 
  
7. En un explorador web, busque el sitio Web raíz de la colección de sitios y, a continuación, obtener acceso a **La configuración del sitio** \> **Características de colección de sitios**. A continuación, activar o desactivar la característica de **flujos de trabajo** : 
  
· Si la característica está *activado* , haga clic en **desactivar** y, a continuación, haga clic en **Activar**. 
  
· Si la característica está *desactivado* , haga clic en **Activar**. 
  
Para obtener más información, consulte el siguiente [artículo](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).
  

