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
ms.openlocfilehash: 6e67c2916e0c5739f6126064d45e175a7fd6f8d4
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36500232"
---
# <a name="fix-problems-with-open-with-explorer"></a>Solucionar problemas con abrir con el explorador

Solucionar problemas comunes de la apertura de una biblioteca de documentos en SharePoint o OneDrive con el comando **abrir con el explorador** : 
  
- Usar Internet Explorer 10 o Internet Explorer 11. **Abrir con el explorador** no es compatible con Microsoft Edge, Google Chrome, Firefox y otros. **Abrir con el explorador** está deshabilitado en todos los exploradores excepto en Internet Explorer. 
    
- **Abrir con el explorador** no está disponible en la experiencia moderna de las bibliotecas de SharePoint. En su lugar, use **ver en el explorador de archivos** . Seleccione Ver **Opciones** \> **de vista en el explorador de archivos**. Ver en el explorador de archivos no es compatible con Microsoft Edge, Google Chrome, Firefox y otros. **Ver en el explorador de archivos** solo está disponible en Internet Explorer. 
    
- Asegúrese de que el servicio WebClient se está ejecutando. En el cuadro de búsqueda de Windows, escriba ejecutar, seleccione la aplicación de escritorio ejecutar, escriba Services. msc y, a continuación, presione Entrar. Desplácese hacia abajo hasta el servicio WebClient y asegúrese de que la columna **Estado** muestra "en ejecución". Si no es así, haga doble clic en el servicio, haga clic en **Inicio**y, a continuación, haga clic en **Aceptar**. (Es posible que tenga que habilitar primero el servicio seleccionando **manual** o **automático** en el cuadro **tipo de inicio** ). 
    
> [!NOTE]
> Abrir una biblioteca en el explorador de archivos es útil si necesita copiar o mover varios archivos y carpetas una vez, pero si desea trabajar con regularidad en la biblioteca, le recomendamos que lo sincronice. Para solucionar problemas de apertura en el explorador de archivos, consulte [abrir en el explorador](https://go.microsoft.com/fwlink/?linkid=871665). Para obtener información sobre cómo configurar la sincronización, vea [sincronizar archivos de SharePoint con el nuevo cliente de sincronización de OneDrive](https://go.microsoft.com/fwlink/?linkid=871666).
  
Consulte el artículo [Cómo usar el comando "abrir con el explorador" para solucionar problemas en SharePoint Online](https://support.office.com/article/How-to-use-the-Open-with-Explorer-command-to-troubleshoot-issues-in-SharePoint-Online-87155331-0c92-4224-a4c1-da5c21c4ade4) para obtener más información. 
  

