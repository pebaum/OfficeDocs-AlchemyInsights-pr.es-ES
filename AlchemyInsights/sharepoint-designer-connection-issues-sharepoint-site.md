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
ms.openlocfilehash: 7451cfe957545537298f57feb5b47bd6d43cddbf
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/04/2019
ms.locfileid: "34716908"
---
# <a name="sharepoint-designer-connection-issues"></a>Problemas de conexión de SharePoint Designer 

<p>Si SharePoint Designer tiene problemas de conexión con los sitios de SharePoint, pruebe las siguientes soluciones comunes.</p> <p><strong>Paso 1:</strong> <strong>Comprobar que SharePoint Designer está&nbsp; actualizado</strong></p> <ul> <li><a href="https://www.microsoft.com/en-us/download/details.aspx?id=35491">SharePoint Designer 2013</a></li> <li><a href="https://support.microsoft.com/en-us/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1">SharePoint Designer Service Pack 1 (SP1)</a></li> <li><a href="https://support.microsoft.com/en-us/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721">Actualización de SharePoint Designer 2013 (KB3114721)</a></li> </ul> <p><strong>Paso 2:</strong> <strong>Borrar los archivos de la caché local</strong>&nbsp;</p> <ol> <li style="font-weight: 400;">Cierre SharePoint Designer 2013.&nbsp;</li> <li style="font-weight: 400;">En el equipo local, vaya a las siguientes carpetas para quitar los archivos almacenados en caché.&nbsp;</li> <li style="font-weight: 400;">Haga clic en <strong>iniciar-&gt; ejecutar</strong> y elimine todos los archivos encontrados en cada una de las siguientes ubicaciones.&nbsp;<br /><br />%APPDATA%\Microsoft\Web Server Extensions\Cache<br />%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache<br />%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</li> <li style="font-weight: 400;">Abra SharePoint Designer 2013 y vuelva a escribir la cuenta para ver si funciona.</li> </ol> <p><strong>Paso 3:</strong> <a href="https://docs.microsoft.com/en-us/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=%252fen-us%252farticle%252fEnable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&amp;view=o365-worldwide"> <strong>Habilitar la autenticación moderna para Office 2013 en dispositivos Windows</strong></a>&nbsp;</p> <p><strong>Paso 4:</strong> <strong>Los administradores deberán permitir que el script personalizado permita la conexión de SharePoint Designer</strong>.</p> <p>Para ver los pasos detallados, ejemplos y consideraciones, consulte <a href="https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script">Allow or impida Custom script</a>.&nbsp;</p>


