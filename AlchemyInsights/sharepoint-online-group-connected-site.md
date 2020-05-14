---
title: Agregar un grupo a un sitio de SharePoint
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f7d730bf-0d6e-424c-970c-6137c71cb50b
ms.openlocfilehash: b54457427ffa563b6a6323d85e1c8800191eca11
ms.sourcegitcommit: a98b25fa3cac9ebba983f4932881d774880aca93
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/13/2020
ms.locfileid: "44064410"
---
# <a name="issues-when-creating-a-group-connected-site-in-sharepoint"></a>Problemas al crear un sitio conectado a grupo en SharePoint

1. Algunos problemas comunes que se producen al crear o volver a crear un sitio conectado a un grupo.
Si ha eliminado un grupo y su sitio conectado y desea crear otro sitio con la misma dirección URL, tendrá que quitar el sitio anterior de forma permanente.

   - Descargar el [Shell de administración de SpO](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)
   - Para obtener más información sobre cómo empezar a trabajar con PowerShell, vea [Introducción al shell de administración de SharePoint Online](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite).
   - Quite el sitio de los sitios eliminados mediante el cmdlet de PowerShell [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) . PowerShell es necesario para eliminar permanentemente los sitios de grupo.

1. Si está creando un sitio conectado a un grupo y recibe una advertencia: **ya existe otro grupo con el mismo alias**, compruebe los grupos existentes en el [centro de administración de Microsoft 365](https://admin.microsoft.com/AdminPortal/Home#/groups). Para resolver el problema, elimine el grupo existente si ya no es necesario o cree el sitio con un alias diferente asignado.

1. Hay diferentes maneras de crear y usar grupos modernos con SharePoint.

   - Puede conectar los sitios existentes a un grupo de Microsoft 365. Para obtener más información, vea [conectar un grupo de Microsoft 365 mediante la interfaz de usuario de SharePoint](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).
   - Para crear un sitio conectado a un grupo de 365 de Microsoft, tendrá que crear un [sitio](https://admin.microsoft.com/sharepoint)de grupo.
