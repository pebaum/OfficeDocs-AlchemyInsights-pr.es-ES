---
title: Uso compartido con usuarios externos no funciona
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 5/18/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: 305b3891e6c83e27b5c55c13757640e6e9d51a81
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28314093"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a>Solucionar problemas de uso compartido de contenido de SharePoint con usuarios externos

Asegúrese de que está activado el uso compartido externo para su organización:
  
1. Vaya a la [servicios &amp; página de complementos en el centro de administración de Office 365](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns)y haga clic en **sitios**.
    
2. Asegúrese de que está activada la opción "Activado". Si se selecciona "Solo existente los usuarios externos", asegúrese de que el usuario externo aparece en el centro de administración de Office 365.
    
Asegúrese de que externo compartirla activado para el sitio. Para una colección de sitios clásico:
  
1. En el centro de administración de SharePoint clásico, en el panel izquierdo, haga clic en **las colecciones de sitios**.
    
2. Seleccione el sitio o los sitios y, en la cinta de opciones, haga clic en **Compartir**.
    
Para un sitio de grupo que pertenece a un grupo de Office 365, o un sitio de comunicación:
  
- Estos nuevos tipos de sitios tienen la misma configuración uso compartido como la configuración de toda la organización, a menos que la configuración de toda la organización permite el uso compartido de archivos con vínculos que no requieren inicio de sesión. En este caso, los sitios de permiten el uso compartido con usuarios externos nuevos y existentes que inician sesión en. Para cambiar la configuración para sitios específicos, use el nuevo centro de administración de SharePoint (vista previa) o PowerShell. [Más información](https://go.microsoft.com/fwlink/?linkid=871863).
    
> [!NOTE]
> La opción de uso compartido externo para cualquier sitio puede ser más restrictivo que la configuración de toda la organización, pero no más permisivo que el valor de toda la organización. 
  

