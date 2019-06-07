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
ms.openlocfilehash: a689769dab24e12832ddc0937bc5ddc3d71dbee3
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/07/2019
ms.locfileid: "34759272"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a>Dar acceso a los usuarios a SharePoint y OneDrive

Este problema se produce con más frecuencia cuando se elimina un usuario y se vuelve a crear con el mismo nombre principal de usuario (UPN). La nueva cuenta se crea con un valor de PUID (identificador único de pasaporte) diferente. Cuando el usuario intenta tener acceso a una colección de sitios o a su OneDrive, el usuario tiene un PUID incorrecto. Un segundo escenario implica la sincronización de directorios con una unidad organizativa (OU) de Active Directory. Si los usuarios ya han iniciado sesión en SharePoint y, a continuación, se mueven a otra unidad organizativa y se resincronizan con SharePoint, pueden experimentar este problema.

Para resolver este problema, restaure el UPN original con los pasos del artículo[restaurar un usuario en Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).

Una vez hecho esto, puede comprobar que el usuario tiene derechos de administrador en el sitio de OneDrive siguiendo los pasos para [Agregar un administrador para el onedrive de un usuario](https://docs.microsoft.com/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive)

Para obtener más información sobre los niveles de permisos, vea el artículo [sobre los niveles de permisos en SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).