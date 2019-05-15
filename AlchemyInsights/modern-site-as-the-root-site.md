---
title: Sitio moderno como sitio raíz
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 6166493f79379f44b1a9bbbaca6becfe624fe912
ms.sourcegitcommit: 22ce2315c8cf643137ab3420cdc1cda41433d44a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/14/2019
ms.locfileid: "34057779"
---
# <a name="modern-site-as-root-site"></a><span data-ttu-id="66f1b-102">Sitio moderno como sitio raíz</span><span class="sxs-lookup"><span data-stu-id="66f1b-102">Modern site as root site</span></span>

<span data-ttu-id="66f1b-103">Los clientes de [versiones de destino](https://docs.microsoft.com/en-us/office365/admin/manage/release-options-in-office-365?view=o365-worldwide) ahora pueden habilitar la experiencia de sitio de comunicación moderna en el sitio raíz clásico de su espacio empresarial de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="66f1b-103">[Target Release](https://docs.microsoft.com/en-us/office365/admin/manage/release-options-in-office-365?view=o365-worldwide) customers can now enable the modern communication site experience at the classic root site of their SharePoint tenant.</span></span>

<span data-ttu-id="66f1b-104">Esta característica se puede activar mediante la ejecución de un sencillo cmdlet de PowerShell.</span><span class="sxs-lookup"><span data-stu-id="66f1b-104">This feature can be activated by running a simple PowerShell cmdlet.</span></span> <span data-ttu-id="66f1b-105">En la correcta ejecución de los comandos de PowerShell, el sitio raíz tendrá una nueva página principal del sitio de comunicación.</span><span class="sxs-lookup"><span data-stu-id="66f1b-105">On the successful execution of the PowerShell command(s), the root site will have a new communication site home page.</span></span> <span data-ttu-id="66f1b-106">Los detalles sobre los requisitos de cmdlet y características de PowerShell están disponibles en el artículo [enable-SPOCommSite](https://docs.microsoft.com/en-us/powershell/module/sharepoint-online/Enable-SPOCommSite?view=sharepoint-ps).</span><span class="sxs-lookup"><span data-stu-id="66f1b-106">Details about the PowerShell cmdlet and feature requirements are available in the article [Enable-SPOCommSite](https://docs.microsoft.com/en-us/powershell/module/sharepoint-online/Enable-SPOCommSite?view=sharepoint-ps).</span></span> 

<span data-ttu-id="66f1b-107">Esta se descargará gradualmente, de forma predeterminada, para los clientes de la versión dirigidas a principios de 2019 y la implementación estará disponible en todo el mundo antes de que finalice el 2019 de junio.</span><span class="sxs-lookup"><span data-stu-id="66f1b-107">We'll be gradually rolling this out, off by default, to Targeted Release customers in early May 2019, and the roll out will be available worldwide by the end of June 2019.</span></span> <span data-ttu-id="66f1b-108">Siga haciendo referencia al [centro de mensajes](https://admin.microsoft.com/AdminPortal/Home#/MessageCenter) para obtener otras nuevas características con la moderna.</span><span class="sxs-lookup"><span data-stu-id="66f1b-108">Continue to refer to the [Message Center](https://admin.microsoft.com/AdminPortal/Home#/MessageCenter) for other new features with Modern.</span></span> 

<span data-ttu-id="66f1b-109">**Importante**: no elimine el sitio raíz clásico para crear un sitio de comunicación moderno.</span><span class="sxs-lookup"><span data-stu-id="66f1b-109">**Important**: Do not delete your classic root site to create a modern Communication Site.</span></span> <span data-ttu-id="66f1b-110">No es compatible con Microsoft.</span><span class="sxs-lookup"><span data-stu-id="66f1b-110">This is not supported by Microsoft.</span></span> <span data-ttu-id="66f1b-111">La eliminación del sitio raíz hará que todos los sitios de SharePoint de la organización sean inaccesibles para todos los usuarios, hasta que restaure el sitio o cree un sitio nuevo en la misma dirección URL.</span><span class="sxs-lookup"><span data-stu-id="66f1b-111">Deleting the root site will make all SharePoint sites in your organization inaccessible to all users, until you restore the site or create a new site at the same URL.</span></span> 
 
 