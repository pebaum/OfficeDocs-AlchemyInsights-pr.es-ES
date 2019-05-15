---
title: Jubilación de servicios de Access
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 395dac6abf1562aa0da0b1d87eddd943affefc3f
ms.sourcegitcommit: b2c9202b94fa1ce73dbeb3e43b219ba07e46e7e3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/14/2019
ms.locfileid: "33973952"
---
# <a name="access-services-retirement"></a><span data-ttu-id="96914-102">Jubilación de servicios de Access</span><span class="sxs-lookup"><span data-stu-id="96914-102">Access services retirement</span></span>

<span data-ttu-id="96914-103">Como se anunció originalmente en MC97576, en marzo de 2017, y se continuó la comunicación a través del último año, los servicios de Access se están retirando de Office 365.</span><span class="sxs-lookup"><span data-stu-id="96914-103">As we originally announced in MC97576, in March 2017, and continued to communicate over the past year Access Services are being retired from Office 365.</span></span> <span data-ttu-id="96914-104">La siguiente fase de este proceso será la eliminación de las bases de datos Web de Access que usan listas de SharePoint como almacenamiento de datos subyacente.</span><span class="sxs-lookup"><span data-stu-id="96914-104">The next phase in this process will be the removal of Access Web Databases that use SharePoint lists as their underlying data storage.</span></span>

## <a name="how-does-this-affect-me"></a><span data-ttu-id="96914-105">¿Qué me afecta?</span><span class="sxs-lookup"><span data-stu-id="96914-105">How does this affect me?</span></span>

<span data-ttu-id="96914-106">A partir del 2019 de junio, deteneremos la creación de nuevas bases de datos de Access en SharePoint Online y cerrará el servicio y el resto de las aplicaciones hasta el 2020 de abril.</span><span class="sxs-lookup"><span data-stu-id="96914-106">Starting June 2019, we will stop creation of new Access databases in SharePoint Online and shut down the service and any remaining apps by April 2020.</span></span>

## <a name="what-do-i-need-to-do-to-prepare-for-this-change"></a><span data-ttu-id="96914-107">¿Qué debo hacer para prepararse para este cambio?</span><span class="sxs-lookup"><span data-stu-id="96914-107">What do I need to do to prepare for this change?</span></span>

<span data-ttu-id="96914-108">Le recomendamos que cree un plan de transición para las bases de datos Web de Access de su organización.</span><span class="sxs-lookup"><span data-stu-id="96914-108">We encourage you to create a transition plan for your organization’s Access web databases.</span></span> <span data-ttu-id="96914-109">Los administradores pueden usar el [Explorador de aplicaciones de Access para SharePoint](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fgithub.com%2FSharePoint%2FPnP-Tools%2Ftree%2Fmaster%2FSolutions%2FSharePoint.AccessApp.Scanner&data=02%7C01%7Csalarson%40microsoft.com%7C0f8afc9cd02f45ac32d708d6d26c5b40%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C636927760189423652&sdata=xH%2FPQdPyyGEUBiXfMwUAhBE4UmsuBa4JhFDZUbjUkZU%3D&reserved=0) para obtener un inventario de las aplicaciones de Access que usan los sitios.</span><span class="sxs-lookup"><span data-stu-id="96914-109">Admins can use the [SharePoint Access app scanner](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fgithub.com%2FSharePoint%2FPnP-Tools%2Ftree%2Fmaster%2FSolutions%2FSharePoint.AccessApp.Scanner&data=02%7C01%7Csalarson%40microsoft.com%7C0f8afc9cd02f45ac32d708d6d26c5b40%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C636927760189423652&sdata=xH%2FPQdPyyGEUBiXfMwUAhBE4UmsuBa4JhFDZUbjUkZU%3D&reserved=0) to obtain an inventory of the Access apps that sites are using.</span></span> 

<span data-ttu-id="96914-110">Hay varias formas de migrar los datos de bases de datos Web de Access:</span><span class="sxs-lookup"><span data-stu-id="96914-110">There are several ways to migrate Access web databases data:</span></span>

- <span data-ttu-id="96914-111">Importación a una base de datos de Access local (. ACCDB) o a un archivo de Excel.</span><span class="sxs-lookup"><span data-stu-id="96914-111">Importing to a local Access database (.ACCDB) or to an Excel file.</span></span>
- <span data-ttu-id="96914-112">También se recomienda explorar Microsoft PowerApps como una plataforma alternativa para crear soluciones empresariales sin código para dispositivos móviles y Web.</span><span class="sxs-lookup"><span data-stu-id="96914-112">We also recommend exploring Microsoft PowerApps as an alternative platform to create no-code business solutions for web and mobile devices.</span></span>