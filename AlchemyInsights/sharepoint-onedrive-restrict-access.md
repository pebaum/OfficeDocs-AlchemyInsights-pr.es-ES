---
title: Restringir el acceso a SharePoint o OneDrive
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: 39aa8cd6e649eca4a1e196eeb589a825364d0977
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43692782"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a><span data-ttu-id="f91b2-102">Restringir el acceso a SharePoint o OneDrive</span><span class="sxs-lookup"><span data-stu-id="f91b2-102">Restrict access in SharePoint or OneDrive</span></span>

<span data-ttu-id="f91b2-103">Hay muchas formas de restringir el acceso a los servicios de SharePoint Online/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="f91b2-103">There are many ways to restrict access to SharePoint Online/OneDrive services.</span></span> <span data-ttu-id="f91b2-104">Estos varios métodos de restricción de acceso se describen a continuación.</span><span class="sxs-lookup"><span data-stu-id="f91b2-104">These various access restriction methods are outlined below.</span></span> 

<span data-ttu-id="f91b2-105">**Restricción de permisos**</span><span class="sxs-lookup"><span data-stu-id="f91b2-105">**Permission Restriction**</span></span>

<span data-ttu-id="f91b2-106">En SharePoint Online y OneDrive para la empresa, se restringe el acceso a elementos como sitios, archivos y carpetas mediante la concesión solo de acceso a los grupos o usuarios que deben tener acceso.</span><span class="sxs-lookup"><span data-stu-id="f91b2-106">In SharePoint Online and OneDrive for Business, we restrict access to items like sites, files and folders by only granting access to those groups/individuals who should have access.</span></span>

- [<span data-ttu-id="f91b2-107">Personalización de permisos para una lista o biblioteca de SharePoint</span><span class="sxs-lookup"><span data-stu-id="f91b2-107">Customize permissions for a SharePoint list or library</span></span>](https://support.office.com/article/Customize-permissions-for-a-SharePoint-list-or-library-02d770f3-59eb-4910-a608-5f84cc297782)

- [<span data-ttu-id="f91b2-108">Personalizar permisos del sitio de SharePoint</span><span class="sxs-lookup"><span data-stu-id="f91b2-108">Customize SharePoint site permissions</span></span>](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions)

- [<span data-ttu-id="f91b2-109">Cambiar permisos en una subcarpeta</span><span class="sxs-lookup"><span data-stu-id="f91b2-109">Change the permissions on a subfolder</span></span>](https://support.office.com/article/Change-the-permissions-on-a-subfolder-5427BD7C-F20A-4F75-8CF2-5359DD45A1A6)

- [<span data-ttu-id="f91b2-110">Control de acceso desde dispositivos no administrados</span><span class="sxs-lookup"><span data-stu-id="f91b2-110">Control access from unmanaged devices</span></span>](https://docs.microsoft.com/sharepoint/control-access-from-unmanaged-devices)

<span data-ttu-id="f91b2-111">Como administrador global o de SharePoint, puede bloquear o limitar el acceso a contenido de SharePoint y OneDrive desde dispositivos no administrados (no compatibles con AD híbrido o compatibles con Intune).</span><span class="sxs-lookup"><span data-stu-id="f91b2-111">As a SharePoint or global admin, you can block or limit access to SharePoint and OneDrive content from unmanaged devices (those not hybrid AD joined or compliant in Intune).</span></span>

<span data-ttu-id="f91b2-112">**Restricción de ubicación de red**</span><span class="sxs-lookup"><span data-stu-id="f91b2-112">**Network Location Restriction**</span></span>

<span data-ttu-id="f91b2-113">Como administrador de ti, puede controlar el acceso a los recursos de SharePoint y OneDrive en función de las ubicaciones de red definidas en las que confíe.</span><span class="sxs-lookup"><span data-stu-id="f91b2-113">As an IT admin, you can control access to SharePoint and OneDrive resources based on defined network locations that you trust.</span></span> <span data-ttu-id="f91b2-114">Esto también se conoce como directiva basada en la ubicación.</span><span class="sxs-lookup"><span data-stu-id="f91b2-114">This is also known as location-based policy.</span></span> <span data-ttu-id="f91b2-115">Para obtener más información, vea [controlar el acceso a los datos de SharePoint Online y OneDrive en función de la ubicación de la red](https://docs.microsoft.com/sharepoint/control-access-based-on-network-location) .</span><span class="sxs-lookup"><span data-stu-id="f91b2-115">For more information, please see [Control access to SharePoint Online and OneDrive data based on network location](https://docs.microsoft.com/sharepoint/control-access-based-on-network-location)</span></span>

<span data-ttu-id="f91b2-116">**Restricción de bloqueo del sitio**</span><span class="sxs-lookup"><span data-stu-id="f91b2-116">**Site Lock Restriction**</span></span> 

<span data-ttu-id="f91b2-117">En SharePoint Online tiene la posibilidad de bloquear una colección de sitios, por lo que nadie tiene acceso.</span><span class="sxs-lookup"><span data-stu-id="f91b2-117">Within SharePoint Online you have the ability to lock down a site collection, so no one has access.</span></span> <span data-ttu-id="f91b2-118">Esto se establece a través de PowerShell y el [Shell de administración de SharePoint Online](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) con la propiedad [set-SPOSite](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) -LockState.</span><span class="sxs-lookup"><span data-stu-id="f91b2-118">This is set via PowerShell and the [SharePoint Online Management Shell](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) using the [Set-SPOSite](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) -LockState property.</span></span>

<span data-ttu-id="f91b2-119">**Restringir a los usuarios la creación de sitios o subsitios**</span><span class="sxs-lookup"><span data-stu-id="f91b2-119">**Restrict users from creating sites or subsites**</span></span>

<span data-ttu-id="f91b2-120">Como administrador de SharePoint o administrador global, puede permitir a los usuarios crear y administrar sus propios sitios de SharePoint, determinar el tipo de sitios que pueden crear y especificar la ubicación de los sitios.</span><span class="sxs-lookup"><span data-stu-id="f91b2-120">As a SharePoint admin or Global admin, you can let your users create and administer their own SharePoint sites, determine what kind of sites they can create, and specify the location of the sites.</span></span> <span data-ttu-id="f91b2-121">Para obtener más información, vea [administrar la creación de sitios en SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation) .</span><span class="sxs-lookup"><span data-stu-id="f91b2-121">For more information, please see [Manage site creation in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation)</span></span>

