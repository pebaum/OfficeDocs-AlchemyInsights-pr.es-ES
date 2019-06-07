---
title: Niveles de permisos de SharePoint Online
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 356fef8e02f2c1fd9d209c68194685bb0acaa367
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/07/2019
ms.locfileid: "34760709"
---
# <a name="sharepoint-designer-connection-issues"></a>Problemas de conexión de SharePoint Designer 

Si SharePoint Designer tiene problemas de conexión con los sitios de SharePoint, pruebe las siguientes soluciones comunes.

Paso 1: comprobar que SharePoint Designer está actualizado.

- [SharePoint Designer 2013](https://www.microsoft.com/download/details.aspx?id=35491)

- [SharePoint Designer Service Pack 1 (SP1)](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1)

- [Actualización de SharePoint Designer 2013 (KB3114721)](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721)

Paso 2: borrar los archivos de la caché local

- Cierre SharePoint Designer 2013.

- En el equipo local, vaya a las siguientes carpetas para quitar los archivos almacenados en caché.

- Haga clic en Inicio, ejecutar y eliminar todos los archivos encontrados en cada una de las siguientes ubicaciones.

%APPDATA%\Microsoft\Web Server Extensions\Cache%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache

Abra SharePoint Designer 2013 y vuelva a escribir la cuenta para ver si funciona.

Paso 3: [Habilitar la autenticación moderna para Office 2013 en dispositivos Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide)

Paso 4: los administradores deberán permitir que el script personalizado permita la conexión de SharePoint Designer.

Para ver los pasos detallados, ejemplos y consideraciones, consulte [Allow or impida Custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).


