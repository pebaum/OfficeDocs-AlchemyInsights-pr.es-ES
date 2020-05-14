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
# <a name="issues-when-creating-a-group-connected-site-in-sharepoint"></a><span data-ttu-id="6c9dc-102">Problemas al crear un sitio conectado a grupo en SharePoint</span><span class="sxs-lookup"><span data-stu-id="6c9dc-102">Issues when creating a group connected site in SharePoint</span></span>

1. <span data-ttu-id="6c9dc-103">Algunos problemas comunes que se producen al crear o volver a crear un sitio conectado a un grupo.</span><span class="sxs-lookup"><span data-stu-id="6c9dc-103">Some common issues encountered when creating or re-creating a group connected site.</span></span>
<span data-ttu-id="6c9dc-104">Si ha eliminado un grupo y su sitio conectado y desea crear otro sitio con la misma dirección URL, tendrá que quitar el sitio anterior de forma permanente.</span><span class="sxs-lookup"><span data-stu-id="6c9dc-104">If you have deleted a group and its connected site and wish to create another site with the same URL, you'll need to permanently remove the previous site.</span></span>

   - <span data-ttu-id="6c9dc-105">Descargar el [Shell de administración de SpO](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span><span class="sxs-lookup"><span data-stu-id="6c9dc-105">Download [SPO Management Shell](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span></span>
   - <span data-ttu-id="6c9dc-106">Para obtener más información sobre cómo empezar a trabajar con PowerShell, vea [Introducción al shell de administración de SharePoint Online](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite).</span><span class="sxs-lookup"><span data-stu-id="6c9dc-106">For more info on getting started with Powershell, see [Getting started with SharePoint Online Management Shell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite).</span></span>
   - <span data-ttu-id="6c9dc-107">Quite el sitio de los sitios eliminados mediante el cmdlet de PowerShell [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) .</span><span class="sxs-lookup"><span data-stu-id="6c9dc-107">Remove the Site from Deleted Sites using the [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) Powershell cmdlet.</span></span> <span data-ttu-id="6c9dc-108">PowerShell es necesario para eliminar permanentemente los sitios de grupo.</span><span class="sxs-lookup"><span data-stu-id="6c9dc-108">Powershell is required to permanently delete group sites.</span></span>

1. <span data-ttu-id="6c9dc-109">Si está creando un sitio conectado a un grupo y recibe una advertencia: **ya existe otro grupo con el mismo alias**, compruebe los grupos existentes en el [centro de administración de Microsoft 365](https://admin.microsoft.com/AdminPortal/Home#/groups).</span><span class="sxs-lookup"><span data-stu-id="6c9dc-109">If you're creating a group connected site and receive a warning: **Another group with the same alias already exists**, check the existing groups from the [Microsoft 365 admin center](https://admin.microsoft.com/AdminPortal/Home#/groups).</span></span> <span data-ttu-id="6c9dc-110">Para resolver el problema, elimine el grupo existente si ya no es necesario o cree el sitio con un alias diferente asignado.</span><span class="sxs-lookup"><span data-stu-id="6c9dc-110">To resolve the issue, delete the existing group if it's no longer needed or create the site with a different alias assigned.</span></span>

1. <span data-ttu-id="6c9dc-111">Hay diferentes maneras de crear y usar grupos modernos con SharePoint.</span><span class="sxs-lookup"><span data-stu-id="6c9dc-111">There are different ways to create and use modern groups with SharePoint.</span></span>

   - <span data-ttu-id="6c9dc-112">Puede conectar los sitios existentes a un grupo de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="6c9dc-112">You can connect existing sites to an Microsoft 365 group.</span></span> <span data-ttu-id="6c9dc-113">Para obtener más información, vea [conectar un grupo de Microsoft 365 mediante la interfaz de usuario de SharePoint](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span><span class="sxs-lookup"><span data-stu-id="6c9dc-113">For more info, see [Connect an Microsoft 365 group using the SharePoint user interface](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span></span>
   - <span data-ttu-id="6c9dc-114">Para crear un sitio conectado a un grupo de 365 de Microsoft, tendrá que crear un [sitio](https://admin.microsoft.com/sharepoint)de grupo.</span><span class="sxs-lookup"><span data-stu-id="6c9dc-114">To create an Microsoft 365 group connected site, you'll need to create a [Team Site](https://admin.microsoft.com/sharepoint).</span></span>
