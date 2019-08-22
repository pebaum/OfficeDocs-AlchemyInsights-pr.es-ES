---
title: Problemas de conexión de SharePoint Designer
ms.author: efrene
author: efrene
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: a4aeaeaea5743c276b907c78317ff30f5610be81
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36508440"
---
# <a name="sharepoint-designer-connection-issues"></a>Problemas de conexión de SharePoint Designer 

Si SharePoint Designer tiene problemas de conexión con los sitios de SharePoint, pruebe las siguientes soluciones comunes.

Paso 1: comprobar que SharePoint Designer 2013 se ha actualizado con [SharePoint Designer Service Pack 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) y la [actualización de 2 de agosto de 2016 para SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).



Paso 2: borrar los archivos de la caché local:

1. Cierre SharePoint Designer 2013.

2. En el equipo local, quite todos los archivos que se encuentren en cada una de las carpetas siguientes.

    - %APPDATA%\Microsoft\Web Server Extensions\Cache
    - %APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache
    - %USERPROFILE%\AppData\Local\Microsoft\WebsiteCache

3. Abra SharePoint Designer 2013 y vuelva a escribir la cuenta para ver si funciona.

Paso 3: [Habilitar la autenticación moderna para Office 2013 en dispositivos Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide).

Paso 4: los administradores deberán permitir el **script personalizado** en la configuración del centro de administración de SharePoint para permitir la conexión de SharePoint Designer. Consulte [permitir o impedir el script personalizado](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) para obtener más información.


