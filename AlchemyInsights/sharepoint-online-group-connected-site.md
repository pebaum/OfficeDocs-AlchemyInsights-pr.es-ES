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
ms.openlocfilehash: 352bad1b8fe219f95a37c9ac268c6c4dd8801dfc
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/04/2019
ms.locfileid: "34719498"
---
# <a name="create-group-connected-site-in-sharepoint-online"></a>Crear un sitio conectado a grupo en SharePoint Online

<p><strong>Hay un par de problemas comunes que se encuentran al crear o volver a crear un sitio conectado a un grupo.&nbsp;</strong></p>  <p>1.Si ha eliminado un grupo y su sitio conectado y desea crear otro sitio con la misma dirección URL, tendrá que quitar el sitio anterior de forma permanente.</p>  <ul>  <li>Descargar <a title="el shell de administración de SpO" href="https://support.office.com/en-ie/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429">Shell</a> - de administración de SpO para obtener más información sobre cómo empezar a <a title="trabajar con PowerShell, vea Introducción al shell de administración de SharePoint Online." href="https://docs.microsoft.com/en-us/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps">Introducción al shell</a>de administración de SharePoint Online. <br /><br /></li>  <li>Quitar el sitio de los sitios eliminados <a title="mediante el SPODeletedSite" href="https://docs.microsoft.com/en-us/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps">Remove-SPODeletedSite</a> PowerShell cmdlet.</li>  </ul>  <p>Si está creando un sitio conectado a un grupo y recibe una advertencia <strong>"ya existe otro grupo con el mismo alias"</strong>, compruebe los grupos existentes desde <a title="el centro de administración de Office 365" href="https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups">Office 365 desde el centro</a>de administración. Para resolver el problema, elimine el grupo existente si ya no es necesario o cree el sitio con un alias diferente asignado.&nbsp;</p>  <p><strong>Hay diferentes maneras de crear y usar grupos modernos con SharePoint.&nbsp;</strong></p>  <ol>  <li>Puede conectar los sitios existentes a un grupo de Office 365. Para obtener más información, <a title="vea conectar un grupo de Office 365 mediante el usuario de SharePoint ineterface" href="https://docs.microsoft.com/en-us/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface">Conecte un grupo de Office 365 mediante el usuario de</a>SharePoint ineterface.</li>  <li>Para crear un sitio conectado a un grupo de Office 365, deberá crear un sitio de grupo. Para obtener más información, <a title="vea crear un sitio de grupo en SharePoint" href="https://support.office.com/en-us/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d">Cree un sitio de grupo en SharePoint.</a></li>  </ol>

