---
title: Sincronización de perfiles
ms.author: arnek
author: arnek
ms.date: 6/20/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 6b695be8-eaf5-44ff-b0ae-1e0d89e7ab36
ms.openlocfilehash: a32cf9e623d1be7a2c85ef4951c6eb7f001b7db0
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29491524"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a>¿Al sincronizar los cambios de perfiles a la aplicación de perfil de usuario de SharePoint?

SharePoint Online usa el trabajo del temporizador de importación de Active Directory (AD Import) para importar los usuarios y grupos en la aplicación de perfil de usuario. 
  
1. Importación de AD se sincroniza los cambios desde el almacén de directorios de SharePoint Online a la aplicación de perfil de usuario. Estos cambios se procesan en lotes.
    
2. El trabajo del temporizador se ejecuta hasta que se sincronicen los cambios.
    
> [!NOTE]
> El tiempo que tarda el trabajo para ejecutar depende del número de cambios para procesar. Un gran número de cambios tarda más. El contrato de nivel de servicio (SLA) indica que un cambio a un usuario en el directorio en línea de SharePoint se reflejará en la aplicación de perfil de usuario en 24 horas. 
  
[Obtener más información acerca de la sincronización de perfiles de usuario en SharePoint Online](https://go.microsoft.com/fwlink/?linkid=875671)
  

