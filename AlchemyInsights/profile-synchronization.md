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
ms.openlocfilehash: d1a72a85767e36fefbfa8eee266befcaf2e48af0
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29920105"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a>¿Al sincronizar los cambios de perfiles a la aplicación de perfil de usuario de SharePoint?

SharePoint Online usa el trabajo del temporizador de importación de Active Directory (AD Import) para importar los usuarios y grupos en la aplicación de perfil de usuario. 
  
1. Importación de AD se sincroniza los cambios desde el almacén de directorios de SharePoint Online a la aplicación de perfil de usuario. Estos cambios se procesan en lotes.
    
2. El trabajo del temporizador se ejecuta hasta que se sincronicen los cambios.
    
> [!NOTE]
> El tiempo que tarda el trabajo para ejecutar depende del número de cambios para procesar. Un gran número de cambios tarda más. El contrato de nivel de servicio (SLA) indica que un cambio a un usuario en el directorio en línea de SharePoint se reflejará en la aplicación de perfil de usuario en 24 horas. 
  
[Obtener más información acerca de la sincronización de perfiles de usuario en SharePoint Online](https://go.microsoft.com/fwlink/?linkid=875671)
  

