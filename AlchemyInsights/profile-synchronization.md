---
title: Sincronización de perfiles
ms.author: arnek
author: arnek
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6b695be8-eaf5-44ff-b0ae-1e0d89e7ab36
ms.openlocfilehash: dc6e0280961d14aa3e6bd466afbe0cbe89418d17
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43768130"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a>¿Cuándo se sincronizan mis cambios de perfil con la aplicación de Perfil de usuario de SharePoint?

SharePoint Online usa el trabajo del temporizador de importación de Active Directory (AD Import) para importar usuarios y grupos en la aplicación de Perfil de usuario. 
  
1. La importación de AD sincroniza los cambios del almacén de directorio de SharePoint Online con la aplicación de Perfil de usuario. Estos cambios se procesan por lotes.
    
2. El trabajo del temporizador se ejecuta hasta que se sincronicen los cambios.
    
> [!NOTE]
> El tiempo que tarda en ejecutarse el trabajo depende del número de cambios que se van a procesar. Un gran número de cambios lleva más tiempo. El contrato de nivel de servicio (SLA) indica que un cambio en un usuario en el directorio de SharePoint Online se reflejará en la aplicación de Perfil de usuario en 24 horas. 
  
[Más información sobre la sincronización de perfiles de usuario en SharePoint Online](https://go.microsoft.com/fwlink/?linkid=875671)
  

