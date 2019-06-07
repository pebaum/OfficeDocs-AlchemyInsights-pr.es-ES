---
title: Agregar un grupo a un sitio de SharePoint
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f7d730bf-0d6e-424c-970c-6137c71cb50b
ms.openlocfilehash: f0126f7f753275e9bbf8c3a09a6af5faf9a27862
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/07/2019
ms.locfileid: "34758747"
---
# <a name="create-group-connected-site-in-sharepoint-online"></a>Crear un sitio conectado a grupo en SharePoint Online

Hay un par de problemas comunes que se encuentran al crear o volver a crear un sitio conectado a un grupo.

 Si ha eliminado un grupo y su sitio conectado y desea crear otro sitio con la misma dirección URL, tendrá que quitar el sitio anterior de forma permanente.

Descargar el [Shell de administración de SpO](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)

 Para obtener más información sobre cómo empezar a trabajar con PowerShell, vea [Introducción al shell de administración de SharePoint Online](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) .

Quite el sitio de los sitios eliminados mediante el cmdlet de PowerShell [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) .

Si está creando un sitio conectado a un grupo y recibe una advertencia de que ya existe otro grupo con el mismo alias, compruebe los grupos existentes desde el [Office 365 desde el centro de administración](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups). Para resolver el problema, elimine el grupo existente si ya no es necesario o cree el sitio con un alias diferente asignado.

Hay diferentes maneras de crear y usar grupos modernos con SharePoint.

Puede conectar los sitios existentes a un grupo de Office 365. Para obtener más información, vea [conectar un grupo de Office 365 mediante el usuario de SharePoint ineterface](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).

Para crear un sitio conectado a un grupo de Office 365, deberá crear un sitio de grupo. Para obtener más información, vea [crear un sitio de grupo en SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).
