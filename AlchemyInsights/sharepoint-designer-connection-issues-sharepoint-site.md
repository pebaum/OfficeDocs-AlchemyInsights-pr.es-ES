---
title: Niveles de permisos de SharePoint Online
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 356fef8e02f2c1fd9d209c68194685bb0acaa367
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/07/2019
ms.locfileid: "34760709"
---
# <a name="sharepoint-designer-connection-issues"></a><span data-ttu-id="0e2c4-102">Problemas de conexión de SharePoint Designer</span><span class="sxs-lookup"><span data-stu-id="0e2c4-102">SharePoint Designer connection issues</span></span> 

<span data-ttu-id="0e2c4-103">Si SharePoint Designer tiene problemas de conexión con los sitios de SharePoint, pruebe las siguientes soluciones comunes.</span><span class="sxs-lookup"><span data-stu-id="0e2c4-103">If SharePoint Designer is experiencing connection issues to SharePoint sites, please attempt the following common solutions.</span></span>

<span data-ttu-id="0e2c4-104">Paso 1: comprobar que SharePoint Designer está actualizado.</span><span class="sxs-lookup"><span data-stu-id="0e2c4-104">Step 1: Verify SharePoint Designer is updated.</span></span>

- [<span data-ttu-id="0e2c4-105">SharePoint Designer 2013</span><span class="sxs-lookup"><span data-stu-id="0e2c4-105">SharePoint Designer 2013</span></span>](https://www.microsoft.com/download/details.aspx?id=35491)

- [<span data-ttu-id="0e2c4-106">SharePoint Designer Service Pack 1 (SP1)</span><span class="sxs-lookup"><span data-stu-id="0e2c4-106">SharePoint Designer Service Pack 1 (SP1)</span></span>](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1)

- [<span data-ttu-id="0e2c4-107">Actualización de SharePoint Designer 2013 (KB3114721)</span><span class="sxs-lookup"><span data-stu-id="0e2c4-107">Update for SharePoint Designer 2013 (KB3114721)</span></span>](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721)

<span data-ttu-id="0e2c4-108">Paso 2: borrar los archivos de la caché local</span><span class="sxs-lookup"><span data-stu-id="0e2c4-108">Step 2: Clear the local cache files</span></span>

- <span data-ttu-id="0e2c4-109">Cierre SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="0e2c4-109">Close SharePoint Designer 2013.</span></span>

- <span data-ttu-id="0e2c4-110">En el equipo local, vaya a las siguientes carpetas para quitar los archivos almacenados en caché.</span><span class="sxs-lookup"><span data-stu-id="0e2c4-110">On the local computer, browse to the following folders to remove cached files.</span></span>

- <span data-ttu-id="0e2c4-111">Haga clic en Inicio, ejecutar y eliminar todos los archivos encontrados en cada una de las siguientes ubicaciones.</span><span class="sxs-lookup"><span data-stu-id="0e2c4-111">Click Start, Run and delete all files found under each of the below locations.</span></span>

<span data-ttu-id="0e2c4-112">%APPDATA%\Microsoft\Web Server Extensions\Cache%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span><span class="sxs-lookup"><span data-stu-id="0e2c4-112">%APPDATA%\Microsoft\Web Server Extensions\Cache %APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache %USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span></span>

<span data-ttu-id="0e2c4-113">Abra SharePoint Designer 2013 y vuelva a escribir la cuenta para ver si funciona.</span><span class="sxs-lookup"><span data-stu-id="0e2c4-113">Open SharePoint Designer 2013 and enter the account again to see if it works.</span></span>

<span data-ttu-id="0e2c4-114">Paso 3: [Habilitar la autenticación moderna para Office 2013 en dispositivos Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide)</span><span class="sxs-lookup"><span data-stu-id="0e2c4-114">Step 3: [Enable Modern Authentication for Office 2013 on Windows Devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide)</span></span>

<span data-ttu-id="0e2c4-115">Paso 4: los administradores deberán permitir que el script personalizado permita la conexión de SharePoint Designer.</span><span class="sxs-lookup"><span data-stu-id="0e2c4-115">Step 4: Administrators will need to Allow Custom Script to allow the SharePoint Designer connection.</span></span>

<span data-ttu-id="0e2c4-116">Para ver los pasos detallados, ejemplos y consideraciones, consulte [Allow or impida Custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span><span class="sxs-lookup"><span data-stu-id="0e2c4-116">For detailed steps, examples and considerations see [Allow or prevent custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span></span>


