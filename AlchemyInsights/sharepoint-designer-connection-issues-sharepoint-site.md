---
title: Problemas de conexión de SharePoint Designer
ms.author: efrene
author: efrene
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 1d3f6ad3128292a9dbcc46cc7da23af59a63fbb4
ms.sourcegitcommit: a285c609319ade038461e090e14a701830031825
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/24/2019
ms.locfileid: "35840568"
---
# <a name="sharepoint-designer-connection-issues"></a><span data-ttu-id="5168f-102">Problemas de conexión de SharePoint Designer</span><span class="sxs-lookup"><span data-stu-id="5168f-102">SharePoint Designer connection issues</span></span> 

<span data-ttu-id="5168f-103">Si SharePoint Designer tiene problemas de conexión con los sitios de SharePoint, pruebe las siguientes soluciones comunes.</span><span class="sxs-lookup"><span data-stu-id="5168f-103">If SharePoint Designer is experiencing connection issues to SharePoint sites, please try the following common solutions.</span></span>

<span data-ttu-id="5168f-104">Paso 1: comprobar que SharePoint Designer 2013 se ha actualizado con [SharePoint Designer Service Pack 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) y la [actualización de 2 de agosto de 2016 para SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).</span><span class="sxs-lookup"><span data-stu-id="5168f-104">Step 1: Verify that SharePoint Designer 2013 is updated with [SharePoint Designer Service Pack 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) and the [August 2, 2016 Update for SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).</span></span>



<span data-ttu-id="5168f-105">Paso 2: borrar los archivos de la caché local:</span><span class="sxs-lookup"><span data-stu-id="5168f-105">Step 2: Clear the local cache files:</span></span>

1. <span data-ttu-id="5168f-106">Cierre SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="5168f-106">Close SharePoint Designer 2013.</span></span>

2. <span data-ttu-id="5168f-107">En el equipo local, quite todos los archivos que se encuentren en cada una de las carpetas siguientes.</span><span class="sxs-lookup"><span data-stu-id="5168f-107">On the local computer, remove all files found in each of the following folders.</span></span>

    - <span data-ttu-id="5168f-108">%APPDATA%\Microsoft\Web Server Extensions\Cache</span><span class="sxs-lookup"><span data-stu-id="5168f-108">%APPDATA%\Microsoft\Web Server Extensions\Cache</span></span>
    - <span data-ttu-id="5168f-109">%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache</span><span class="sxs-lookup"><span data-stu-id="5168f-109">%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache</span></span>
    - <span data-ttu-id="5168f-110">%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span><span class="sxs-lookup"><span data-stu-id="5168f-110">%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span></span>

3. <span data-ttu-id="5168f-111">Abra SharePoint Designer 2013 y vuelva a escribir la cuenta para ver si funciona.</span><span class="sxs-lookup"><span data-stu-id="5168f-111">Open SharePoint Designer 2013 and enter the account again to see if it works.</span></span>

<span data-ttu-id="5168f-112">Paso 3: [Habilitar la autenticación moderna para Office 2013 en dispositivos Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="5168f-112">Step 3: [Enable Modern Authentication for Office 2013 on Windows Devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide).</span></span>

<span data-ttu-id="5168f-113">Paso 4: los administradores deberán permitir el **script personalizado** en la configuración del centro de administración de SharePoint para permitir la conexión de SharePoint Designer.</span><span class="sxs-lookup"><span data-stu-id="5168f-113">Step 4: Administrators will need to **Allow Custom Script** in the SharePoint Admin Center settings to allow the SharePoint Designer connection.</span></span> <span data-ttu-id="5168f-114">Consulte [permitir o impedir el script personalizado](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="5168f-114">See [Allow or prevent custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) for more information.</span></span>


