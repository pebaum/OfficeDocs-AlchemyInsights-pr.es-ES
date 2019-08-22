---
title: No funciona el uso compartido con usuarios externos
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 5/18/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: d4c8fc75ff8db2319b88a20bea9b3ee661f2e36e
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36502248"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a>Solucionar problemas de uso compartido de contenido de SharePoint con usuarios externos

Asegúrese de que el uso compartido externo está activado para su organización:
  
1. Vaya a la [página &amp; complementos de servicios en el centro de administración de Microsoft 365](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns)y haga clic en **sitios**.
    
2. Asegúrese de que la configuración esté activada como "ON". Si se selecciona "solo usuarios externos existentes", asegúrese de que el usuario externo aparece en el centro de administración de Microsoft 365.
    
Asegúrese de que el uso compartido externo esté activado para el sitio. Para una colección de sitios clásica:
  
1. En el panel izquierdo del nuevo centro de administración de SharePoint, haga clic en **sitios**.
    
2. Seleccione el sitio o los sitios y, en la cinta de opciones, haga clic en **compartir**.
    
Para un sitio de grupo que pertenece a un grupo de Office 365 o a un sitio de comunicación:
  
- Estos nuevos tipos de sitio tienen la misma configuración de uso compartido que la configuración de toda la organización, a menos que la configuración de toda la organización permita compartir archivos mediante vínculos que no requieran el inicio de sesión. En este caso, los sitios permiten el uso compartido con usuarios externos nuevos y existentes que inician sesión. Para cambiar la configuración de sitios específicos, use el nuevo centro de administración de SharePoint o PowerShell. Obtener [más información](https://go.microsoft.com/fwlink/?linkid=871863).
    
> [!NOTE]
> La configuración de uso compartido externo de cualquier sitio puede ser más restrictiva que la configuración de toda la organización, pero no más permisiva que la configuración de toda la organización. 
  

