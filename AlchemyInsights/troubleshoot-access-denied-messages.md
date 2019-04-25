---
title: Solucionar problemas de mensajes de acceso deNegado
ms.author: kaarins
author: kaarins
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: f1a4803838b6511ef4fe7f03cafa4aa13b3c9734
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "32420717"
---
# <a name="troubleshoot-access-denied-messages"></a><span data-ttu-id="5edbd-102">Solucionar problemas de mensajes de acceso deNegado</span><span class="sxs-lookup"><span data-stu-id="5edbd-102">Troubleshoot Access Denied messages</span></span>

<span data-ttu-id="5edbd-103">Si alguien recibe un mensaje "acceso deNegado" a una carpeta compartida, es posible que el administrador de la colección de sitios haya habilitado el modo de bloqueo de permisos de usuario de acceso limitado.</span><span class="sxs-lookup"><span data-stu-id="5edbd-103">If someone got an "Access Denied" message to a shared folder, the site collection administrator might have enabled "Limited-access user permission lockdown mode."</span></span> <span data-ttu-id="5edbd-104">Para desactivarlo:</span><span class="sxs-lookup"><span data-stu-id="5edbd-104">To turn this off:</span></span> 
  
1. <span data-ttu-id="5edbd-105">Vaya al sitio, haga clic en el icono configuración y, a continuación, haga clic en **configuración del sitio**.</span><span class="sxs-lookup"><span data-stu-id="5edbd-105">Browse to the site, click the Settings icon, and then click **Site Settings**.</span></span>
    
2. <span data-ttu-id="5edbd-106">En **Administración de la colección de sitios**, haga clic en **Características de la colección de sitios**.</span><span class="sxs-lookup"><span data-stu-id="5edbd-106">Under **Site Collection Administration**, click **Site collection features**.</span></span>
    
3. <span data-ttu-id="5edbd-107">Junto a **modo de bloqueo de permisos de usuario de acceso limitado**, haga clic en **desactivar**.</span><span class="sxs-lookup"><span data-stu-id="5edbd-107">Next to **Limited-access user permission lockdown mode**, click **Deactivate**.</span></span>
    
<span data-ttu-id="5edbd-108">Un mensaje de acceso deNegado también puede producirse para carpetas compartidas si el sitio es un sitio de publicación.</span><span class="sxs-lookup"><span data-stu-id="5edbd-108">An Access Denied message can also occur for shared folders if the site is a publishing site.</span></span> <span data-ttu-id="5edbd-109">Para obtener información, vea [acceso denegado cuando se tiene acceso a una carpeta compartida](https://go.microsoft.com/fwlink/?linkid=2004317).</span><span class="sxs-lookup"><span data-stu-id="5edbd-109">For info, see [Access Denied when accessing a shared folder](https://go.microsoft.com/fwlink/?linkid=2004317).</span></span>
  
<span data-ttu-id="5edbd-110">Si un usuario obtuvo un mensaje de "acceso deNegado" al intentar ver las solicitudes de acceso, el usuario debe agregarse como administrador de la colección de sitios o como miembro del grupo de propietarios del sitio.</span><span class="sxs-lookup"><span data-stu-id="5edbd-110">If a someone got an "Access Denied" message when trying to view access requests, the user needs to be added as either a site collection administrator or a member of the Owners group for the site.</span></span> <span data-ttu-id="5edbd-111">Para obtener más información, consulte [acceso denegado a solicitudes de acceso a la lista de solicitudes](https://go.microsoft.com/fwlink/?linkid=2004220).</span><span class="sxs-lookup"><span data-stu-id="5edbd-111">For more info, see [Access Denied to Access Requests list](https://go.microsoft.com/fwlink/?linkid=2004220).</span></span>
  
<span data-ttu-id="5edbd-112">Si un usuario obtuvo un mensaje de "acceso deNegado" después de que se quitó de Active Directory local y después se volvió a agregar, vea [acceso denegado cuando una cuenta de usuario se sincroniza con Office 365](https://go.microsoft.com/fwlink/?linkid=2004318).</span><span class="sxs-lookup"><span data-stu-id="5edbd-112">If a user got an "Access Denied" message after they were removed from Active Directory on-premises and then added back, see [Access Denied when a user account is synced to Office 365](https://go.microsoft.com/fwlink/?linkid=2004318).</span></span>
  

