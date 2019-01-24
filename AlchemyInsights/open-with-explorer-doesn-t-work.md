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
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29490643"
---
# <a name="open-with-explorer-isnt-working"></a>Abrir con el explorador no funciona

Si no puedo **Abrir con el explorador** o **Ver en el Explorador de archivos** Asegúrese de que el servicio de cliente Web se establece a la **ejecución de** siguiendo los pasos siguientes. Por ejemplo, puede tardar mucho tiempo en abrir una biblioteca de SharePoint o OneDrive cuando no se está ejecutando el servicio. 
  
1. En el cuadro de búsqueda de Windows, escriba ejecutar, seleccione la aplicación de escritorio de ejecutar, escriba services.msc y, a continuación, seleccione **ENTRAR**.
    
2. Desplácese hacia abajo hasta el servicio de cliente Web y compruebe la columna **estado** . Si el estado del servicio de cliente Web no está **ejecutando**, haga doble clic en el servicio, haga clic en **Inicio**y, a continuación, haga clic en **Aceptar**. Habilite el servicio, si es necesario, mediante la selección **Manual** o **automática** en el cuadro **tipo de inicio** . 
    
> [!NOTE]
> Para solucionar problemas de apertura en el Explorador de archivos, vea [abierta en el explorador](https://go.microsoft.com/fwlink/?linkid=871665). Explore la sincronización como una alternativa mejor: [archivos de sincronización de SharePoint con el cliente de sincronización de OneDrive para la nueva](https://go.microsoft.com/fwlink/?linkid=871666). 
  

