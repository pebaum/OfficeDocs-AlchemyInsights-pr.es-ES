---
title: Sincronización de perfiles
ms.author: arnek
author: arnek
ms.date: 6/20/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6b695be8-eaf5-44ff-b0ae-1e0d89e7ab36
ms.openlocfilehash: b9b90dad6c5fa41afcd4e4c9a929594735eca066
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36554350"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a>¿Cuándo se sincronizan mis cambios de perfil con la aplicación de Perfil de usuario de SharePoint?

SharePoint Online usa el trabajo del temporizador de importación de Active Directory (AD Import) para importar usuarios y grupos en la aplicación de Perfil de usuario. 
  
1. La importación de AD sincroniza los cambios del almacén de directorio de SharePoint Online con la aplicación de Perfil de usuario. Estos cambios se procesan por lotes.
    
2. El trabajo del temporizador se ejecuta hasta que se sincronicen los cambios.
    
> [!NOTE]
> El tiempo que tarda en ejecutarse el trabajo depende del número de cambios que se van a procesar. Un gran número de cambios lleva más tiempo. El contrato de nivel de servicio (SLA) indica que un cambio en un usuario en el directorio de SharePoint Online se reflejará en la aplicación de Perfil de usuario en 24 horas. 
  
[Más información sobre la sincronización de perfiles de usuario en SharePoint Online](https://go.microsoft.com/fwlink/?linkid=875671)
  

