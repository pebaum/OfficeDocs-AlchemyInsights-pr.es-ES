---
title: Agregar un grupo a un sitio de SharePoint
ms.author: pebaum
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f7d730bf-0d6e-424c-970c-6137c71cb50b
ms.openlocfilehash: 423db4e5bbb85e75aee3548d5b6b46a64ebc6fa0
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/04/2019
ms.locfileid: "36750537"
---
# <a name="issues-when-creating-or-group-connected-sites-in-sharepoint-online"></a><span data-ttu-id="0edcf-102">Problemas al crear o agrupar sitios conectados en SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="0edcf-102">Issues when creating or group connected sites in SharePoint Online</span></span>

<span data-ttu-id="0edcf-103">Hay un par de problemas comunes que se encuentran al crear o volver a crear un sitio conectado a un grupo.</span><span class="sxs-lookup"><span data-stu-id="0edcf-103">There are a couple of common issues encountered when creating or re-creating a group connected site.</span></span>

 <span data-ttu-id="0edcf-104">Si ha eliminado un grupo y su sitio conectado y desea crear otro sitio con la misma dirección URL, tendrá que quitar el sitio anterior de forma permanente.</span><span class="sxs-lookup"><span data-stu-id="0edcf-104">If you have deleted a group and its connected site and wish to create another site with the same URL, you'll need to permanently remove the previous site.</span></span>

<span data-ttu-id="0edcf-105">Descargar el [Shell de administración de SpO](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span><span class="sxs-lookup"><span data-stu-id="0edcf-105">Download [SPO Management Shell](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span></span>

 <span data-ttu-id="0edcf-106">Para obtener más información sobre cómo empezar a trabajar con PowerShell, vea [Introducción al shell de administración de SharePoint Online](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) .</span><span class="sxs-lookup"><span data-stu-id="0edcf-106">For more info on getting started with powershell, see [Getting started with SharePoint Online Management Shell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps)</span></span>

<span data-ttu-id="0edcf-107">Quite el sitio de los sitios eliminados mediante el cmdlet de PowerShell [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) .</span><span class="sxs-lookup"><span data-stu-id="0edcf-107">Remove the Site from Deleted Sites using the [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) powershell cmdlet.</span></span>

<span data-ttu-id="0edcf-108">Si está creando un sitio conectado a un grupo y recibe una advertencia de que ya existe otro grupo con el mismo alias, compruebe los grupos existentes desde el [Office 365 desde el centro de administración](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups).</span><span class="sxs-lookup"><span data-stu-id="0edcf-108">If you're creating a group connected site and receive a warning Another group with the same alias already exists, check the existing groups from the [Office 365 from the Admin Center](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups).</span></span> <span data-ttu-id="0edcf-109">Para resolver el problema, elimine el grupo existente si ya no es necesario o cree el sitio con un alias diferente asignado.</span><span class="sxs-lookup"><span data-stu-id="0edcf-109">To resolve the issue, delete the existing group if it's no longer needed or create the site with a different alias assigned.</span></span>

<span data-ttu-id="0edcf-110">Hay diferentes maneras de crear y usar grupos modernos con SharePoint.</span><span class="sxs-lookup"><span data-stu-id="0edcf-110">There are different ways to create and use modern groups with SharePoint.</span></span>

<span data-ttu-id="0edcf-111">Puede conectar los sitios existentes a un grupo de Office 365.</span><span class="sxs-lookup"><span data-stu-id="0edcf-111">You can connect existing sites to an Office 365 group.</span></span> <span data-ttu-id="0edcf-112">Para obtener más información, vea [conectar un grupo de Office 365 mediante el usuario de SharePoint ineterface](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span><span class="sxs-lookup"><span data-stu-id="0edcf-112">For more info, see [Connect an Office 365 group using the SharePoint user ineterface](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span></span>

<span data-ttu-id="0edcf-113">Para crear un sitio conectado a un grupo de Office 365, deberá crear un sitio de grupo.</span><span class="sxs-lookup"><span data-stu-id="0edcf-113">To create an Office 365 group connected site, you'll need to create a Team Site.</span></span> <span data-ttu-id="0edcf-114">Para obtener más información, vea [crear un sitio de grupo en SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).</span><span class="sxs-lookup"><span data-stu-id="0edcf-114">For more info, see [Create a team site in SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).</span></span>

