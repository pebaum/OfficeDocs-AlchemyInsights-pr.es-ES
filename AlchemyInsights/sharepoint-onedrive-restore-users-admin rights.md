---
title: Solución de problemas de los mensajes de acceso denegado a los sitios de OneDrive para la empresa
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: a83936acf969926c113b28ceb22b006cdb96e2b4
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43692818"
---
# <a name="troubleshooting-access-denied-messages-to-onedrive-for-business-sites"></a>Solución de problemas de los mensajes de acceso denegado a los sitios de OneDrive para la empresa

Este problema se produce con más frecuencia cuando se elimina un usuario y se vuelve a crear con el mismo nombre principal de usuario (UPN). La nueva cuenta se crea con un valor de PUID (identificador único de pasaporte) diferente. Cuando el usuario intenta tener acceso a una colección de sitios o a su OneDrive, el usuario tiene un PUID incorrecto. Un segundo escenario implica la sincronización de directorios con una unidad organizativa (OU) de Active Directory. Si los usuarios ya han iniciado sesión en SharePoint y, a continuación, se mueven a otra unidad organizativa y se resincronizan con SharePoint, pueden experimentar este problema.

1. Para resolver este problema, restaure el UPN original con los pasos del artículo [restaurar un usuario en Microsoft 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).
2. Si no puede restaurar el usuario original, debe quitar el usuario antiguo del sitio de OneDrive mediante estos pasos, [quitar un usuario de la lista de información de usuario](). 
3. Una vez hecho esto, puede comprobar que el usuario tiene derechos de administrador en el sitio de OneDrive siguiendo los pasos para [Agregar un administrador para el onedrive de un usuario](https://docs.microsoft.com/sharepoint/manage-user-profiles)

Para obtener más información sobre los niveles de permisos, vea el artículo [sobre los niveles de permisos en SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).
