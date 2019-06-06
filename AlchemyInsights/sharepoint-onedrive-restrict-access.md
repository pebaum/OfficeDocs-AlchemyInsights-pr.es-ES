---
title: Restringir el acceso a SharePoint o OneDrive
ms.author: kirks
author: Techwriter40
ms.date: 8/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: 5101366ff65f477c19b9c7f2c0d7065cf88501b0
ms.sourcegitcommit: 241e21b6da226563bf70bdb1f5bad3d91c38cd2c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/05/2019
ms.locfileid: "34735159"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a><span data-ttu-id="b5fb8-102">Restringir el acceso a SharePoint o OneDrive</span><span class="sxs-lookup"><span data-stu-id="b5fb8-102">Restrict access in SharePoint or OneDrive</span></span>

<span data-ttu-id="b5fb8-103">Hay muchas formas de restringir el acceso a los servicios de SharePoint Online/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="b5fb8-103">There are many ways to restrict access to SharePoint Online/OneDrive services.</span></span> <span data-ttu-id="b5fb8-104">Estos varios métodos de restricción de acceso se describen a continuación.</span><span class="sxs-lookup"><span data-stu-id="b5fb8-104">These various access restriction methods are outlined below.</span></span> 

<span data-ttu-id="b5fb8-105">Restricción de permisos</span><span class="sxs-lookup"><span data-stu-id="b5fb8-105">Permission Restriction</span></span>

<span data-ttu-id="b5fb8-106">En SharePoint Online y OneDrive para la empresa, se restringe el acceso a elementos como sitios, archivos y carpetas mediante la concesión solo de acceso a los grupos o usuarios que deben tener acceso.</span><span class="sxs-lookup"><span data-stu-id="b5fb8-106">In SharePoint Online and OneDrive for Business, we restrict access to items like sites, files and folders by only granting access to those groups/individuals who should have access.</span></span>

[<span data-ttu-id="b5fb8-107">Personalización de permisos para una lista o biblioteca de SharePoint</span><span class="sxs-lookup"><span data-stu-id="b5fb8-107">Customize permissions for a SharePoint list or library</span></span>](https://support.office.com/en-us/article/Customize-permissions-for-a-SharePoint-list-or-library-02d770f3-59eb-4910-a608-5f84cc297782)

[<span data-ttu-id="b5fb8-108">Personalizar permisos del sitio de SharePoint</span><span class="sxs-lookup"><span data-stu-id="b5fb8-108">Customize SharePoint site permissions</span></span>](https://docs.microsoft.com/en-us/sharepoint/customize-sharepoint-site-permissions)

[<span data-ttu-id="b5fb8-109">Cambiar permisos en una subcarpeta</span><span class="sxs-lookup"><span data-stu-id="b5fb8-109">Change the permissions on a subfolder</span></span>](https://support.office.com/en-us/article/Change-the-permissions-on-a-subfolder-5427BD7C-F20A-4F75-8CF2-5359DD45A1A6)

[<span data-ttu-id="b5fb8-110">Control de acceso desde dispositivos no administrados</span><span class="sxs-lookup"><span data-stu-id="b5fb8-110">Control access from unmanaged devices</span></span>](https://docs.microsoft.com/en-us/sharepoint/control-access-from-unmanaged-devices)

<span data-ttu-id="b5fb8-111">Como administrador global o de SharePoint en Office 365, puede bloquear o limitar el acceso a SharePoint y el contenido de OneDrive desde dispositivos no administrados (los que no son compatibles con AD híbrido o son compatibles con Intune).</span><span class="sxs-lookup"><span data-stu-id="b5fb8-111">As a SharePoint or global admin in Office 365, you can block or limit access to SharePoint and OneDrive content from unmanaged devices (those not hybrid AD joined or compliant in Intune).</span></span>

<span data-ttu-id="b5fb8-112">Restricción de ubicación de red</span><span class="sxs-lookup"><span data-stu-id="b5fb8-112">Network Location Restriction</span></span>

<span data-ttu-id="b5fb8-113">Como administrador de ti, puede controlar el acceso a los recursos de SharePoint y OneDrive en función de las ubicaciones de red definidas en las que confíe.</span><span class="sxs-lookup"><span data-stu-id="b5fb8-113">As an IT admin, you can control access to SharePoint and OneDrive resources based on defined network locations that you trust.</span></span> <span data-ttu-id="b5fb8-114">También se conoce como directiva basada en la ubicación.</span><span class="sxs-lookup"><span data-stu-id="b5fb8-114">This is also known as location-based policy.</span></span> <span data-ttu-id="b5fb8-115">Para obtener más información, vea [controlar el acceso a los datos de SharePoint Online y OneDrive en función de la ubicación de la red](https://docs.microsoft.com/en-us/sharepoint/control-access-based-on-network-location) .</span><span class="sxs-lookup"><span data-stu-id="b5fb8-115">For more information, please see [Control access to SharePoint Online and OneDrive data based on network location](https://docs.microsoft.com/en-us/sharepoint/control-access-based-on-network-location)</span></span>

<span data-ttu-id="b5fb8-116">Restricción de bloqueo del sitio</span><span class="sxs-lookup"><span data-stu-id="b5fb8-116">Site Lock Restriction</span></span> 

<span data-ttu-id="b5fb8-117">En SharePoint Online tiene la posibilidad de bloquear una colección de sitios, por lo que nadie tiene acceso.</span><span class="sxs-lookup"><span data-stu-id="b5fb8-117">Within SharePoint Online you have the ability to lock down a site collection, so no one has access.</span></span> <span data-ttu-id="b5fb8-118">Esto se establece a través de PowerShell y el [Shell de administración de SharePoint Online](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) con la propiedad [set-SPOSite](https://docs.microsoft.com/en-us/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) -LockState.</span><span class="sxs-lookup"><span data-stu-id="b5fb8-118">This is set via PowerShell and the [SharePoint Online Management Shell](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) using the [Set-SPOSite](https://docs.microsoft.com/en-us/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) -LockState property.</span></span>

<span data-ttu-id="b5fb8-119">Restringir a los usuarios la creación de sitios o subsitios</span><span class="sxs-lookup"><span data-stu-id="b5fb8-119">Restrict users from creating sites or subsites</span></span>

<span data-ttu-id="b5fb8-120">Como administrador de SharePoint o administrador global de Office 365, puede permitir a los usuarios crear y administrar sus propios sitios de SharePoint, determinar qué tipo de sitios pueden crear y especificar la ubicación de los sitios.</span><span class="sxs-lookup"><span data-stu-id="b5fb8-120">As a SharePoint admin or Office 365 global admin, you can let your users create and administer their own SharePoint sites, determine what kind of sites they can create, and specify the location of the sites.</span></span> <span data-ttu-id="b5fb8-121">Para obtener más información, vea [administrar la creación de sitios en SharePoint Online](https://docs.microsoft.com/en-us/sharepoint/manage-site-creation) .</span><span class="sxs-lookup"><span data-stu-id="b5fb8-121">For more information, please see [Manage site creation in SharePoint Online](https://docs.microsoft.com/en-us/sharepoint/manage-site-creation)</span></span>

