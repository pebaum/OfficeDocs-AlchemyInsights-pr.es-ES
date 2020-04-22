---
title: Solucionar problemas de mensajes de acceso denegado
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 82e11458529b8a49e583b1a6963a51e2a466bfd6
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43758534"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a>Solucionar problemas de mensajes de acceso denegado en el centro de administración de SharePoint/OneDrive

Si recibe un mensaje de acceso denegado al intentar ir a un centro de administración de SharePoint o OneDrive, asegúrese de [asignar una licencia al usuario](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One). Si el usuario tiene una licencia, también debe asegurarse de que tiene [asignado un rol de administrador](https://docs.microsoft.com/office365/admin/add-users/about-admin-roles?view=o365-worldwide) que puede tener acceso a los centros de administración.

Este problema también puede producirse cuando se elimina un usuario y se vuelve a crear con el mismo nombre principal de usuario (UPN). La nueva cuenta se crea con un valor de PUID (identificador único de pasaporte) diferente. Cuando el usuario intenta tener acceso a una colección de sitios o a su OneDrive, el usuario tiene un PUID incorrecto. Un segundo escenario implica la sincronización de directorios con una unidad organizativa (OU) de Active Directory. Si los usuarios ya han iniciado sesión en SharePoint y, a continuación, se mueven a otra unidad organizativa y se resincronizan con SharePoint, pueden experimentar este problema.

Para resolver este problema, restaure el UPN original con los pasos del artículo [restaurar un usuario en Microsoft 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).

Nota: Si un centro de administración de OneDrive o SharePoint no está disponible para varios usuarios que anteriormente tenían acceso, es posible que haya un problema de servicio temporal.  [Compruebe el panel de estado del servicio](https://portal.office.com/adminportal/home#/servicehealth).


