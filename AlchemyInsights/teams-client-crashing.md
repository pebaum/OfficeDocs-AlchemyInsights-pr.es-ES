---
title: ¿El cliente de Teams está fallando?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002323"
- "4512"
ms.openlocfilehash: c49dfbf422b312f4744711d5f12b0eb83b6ebf2e
ms.sourcegitcommit: b398afd92d4259f893c25b48aec65921e6cc68d6
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 05/16/2020
ms.locfileid: "44268789"
---
# <a name="teams-client-crashing"></a>¿El cliente de Teams está fallando?

Si el cliente de Teams está fallando, intenta lo siguiente:

- Si está usando la aplicación de escritorio de Teams, asegúrese de que la aplicación esté completamente actualizada.

- Asegúrese de que todas las [URL e intervalos de direcciones de Microsoft 365](https://docs.microsoft.com/microsoftteams/connectivity-issues) sean accesibles.

- Inicie sesión con su cuenta de administrador de inquilino y compruebe el [panel de estado del servicio](https://docs.microsoft.com/office365/enterprise/view-service-health) para verificar que no exista ninguna interrupción o degradación del servicio.

 - Como último paso, puede intentar borrar la memoria caché del cliente de Teams:

    1.  Salir completamente del cliente de escritorio de Microsoft Teams. Puede hacer clic con el botón derecho del ratón en **Teams** desde la Bandeja de Iconos y luego hacer clic en **Salir**, o ejecutar el Administrador de Tareas y finalizar el proceso por completo.

    2.  Ve al Explorador de archivos, y escribe %appdata%\Microsoft\teams.

    3.  Una vez en el directorio, verá algunas de las siguientes carpetas:

         - Desde la memoria **caché de aplicaciones**, vaya a almacenamiento en caché y elimine cualquiera de los archivos en la ubicación de caché: %appdata%\Microsoft\teams\application cache\cache.

        - En **Blob_storage**, elimine todos los archivos: %appdata%\Microsoft\teams\blob_storage.

        - En **Cache**, elimine todos los archivos: %appdata%\Microsoft\teams\Cache.

        - En **databases**, elimine todos los archivos: %appdata%\Microsoft\teams\databases.

        - En **GPUCache**, elimine todos los archivos: %appdata%\Microsoft\teams\GPUcache.

        - En **IndexedDB**, elimine el archivo con extensión .db: %appdata%\Microsoft\teams\IndexedDB.

        - En **Local Storage**, elimine todos los archivos: %appdata%\Microsoft\teams\Local Storage.

        - Por último, en **tmp**, elimine cualquier archivo: %appdata%\Microsoft\teams\tmp.

    4. Reinicie su cliente de Teams.

Si el cliente de su equipo aún se bloquea, ¿puede reproducir el problema? En ese caso: 

1. Use la Grabación de acciones de usuario para capturar los pasos.
    - Cierre todas las aplicaciones innecesarias o confidenciales.
    - Inicie sesión con la cuenta de usuario afectada, abra la Grabación de acciones de usuario y reproduzca el problema.
    
2. Anexe el archivo a su caso de soporte técnico.
