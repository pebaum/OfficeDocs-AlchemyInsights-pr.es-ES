---
title: Dar acceso a los usuarios a SharePoint y OneDrive
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.date: 11/14/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: ae4d2c00be6387744bdc84e1d8a021530f80f8fa
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/04/2019
ms.locfileid: "34715228"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a>Dar acceso a los usuarios a SharePoint y OneDrive

<p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Este problema se produce con más frecuencia cuando se elimina un usuario y se vuelve a crear con el mismo nombre principal de usuario (UPN). La nueva cuenta se crea con un valor de PUID (identificador único de pasaporte) diferente. Cuando el usuario intenta tener acceso a una colección de sitios o a su OneDrive, el usuario tiene un PUID incorrecto. Un segundo escenario implica la sincronización de directorios con una unidad organizativa (OU) de Active Directory. Si los usuarios ya han iniciado sesión en SharePoint y, a continuación, se mueven a otra unidad organizativa y se resincronizan con SharePoint, pueden experimentar este problema.</span></p> <p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Para resolver este problema, restaure el UPN original con los pasos del artículo <a href="https://docs.microsoft.com/en-us/office365/admin/add-users/restore-user?view=o365-worldwide">restaurar un usuario en Office 365.</a></span></p> <p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Una vez hecho esto, puede comprobar que el usuario tiene derechos de administrador en el sitio de OneDrive siguiendo los pasos para <a href="https://docs.microsoft.com/en-us/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive">Agregar un administrador para el onedrive de un usuario.</a></span></p> <p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Para obtener más información sobre los niveles de permisos, vea el artículo <a href="https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels">sobre los niveles de permisos en SharePoint.</a>&nbsp;</span></p>
