---
title: Solucionar los mensajes de acceso denegado
ms.author: kaarins
author: kaarins
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 3973f5bf584343d3353e7389f22bc727827b5c35
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28314029"
---
# <a name="troubleshoot-access-denied-messages"></a><span data-ttu-id="624f6-102">Solucionar los mensajes de acceso denegado</span><span class="sxs-lookup"><span data-stu-id="624f6-102">Troubleshoot Access Denied messages</span></span>

<span data-ttu-id="624f6-p101">Si alguien aparece un mensaje de "Acceso denegado" en una carpeta compartida, es posible que habilitó el Administrador de colección de sitios "modo bloqueo del usuario permiso de acceso limitado". Para desactivar esta:</span><span class="sxs-lookup"><span data-stu-id="624f6-p101">If someone got an "Access Denied" message to a shared folder, the site collection administrator might have enabled "Limited-access user permission lockdown mode." To turn this off:</span></span> 
  
1. <span data-ttu-id="624f6-105">Vaya al sitio, haga clic en el icono de configuración y, a continuación, haga clic en **Configuración del sitio**.</span><span class="sxs-lookup"><span data-stu-id="624f6-105">Browse to the site, click the Settings icon, and then click **Site Settings**.</span></span>
    
2. <span data-ttu-id="624f6-106">En **Administración de la colección de sitios**, haga clic en **Características de la colección de sitios**.</span><span class="sxs-lookup"><span data-stu-id="624f6-106">Under **Site Collection Administration**, click **Site collection features**.</span></span>
    
3. <span data-ttu-id="624f6-107">Junto a **modo de bloqueo de permisos de usuario de acceso limitado**, haga clic en **desactivar**.</span><span class="sxs-lookup"><span data-stu-id="624f6-107">Next to **Limited-access user permission lockdown mode**, click **Deactivate**.</span></span>
    
<span data-ttu-id="624f6-p102">También puede producirse un mensaje de acceso denegado para carpetas compartidas si el sitio es un sitio de publicación. Para obtener información, vea [Acceso denegado al obtener acceso a una carpeta compartida](https://go.microsoft.com/fwlink/?linkid=2004317).</span><span class="sxs-lookup"><span data-stu-id="624f6-p102">An Access Denied message can also occur for shared folders if the site is a publishing site. For info, see [Access Denied when accessing a shared folder](https://go.microsoft.com/fwlink/?linkid=2004317).</span></span>
  
<span data-ttu-id="624f6-p103">Si un alguien aparece un mensaje de "Acceso denegado" al intentar ver las solicitudes de acceso, el usuario debe agregarse como un administrador de colección de sitios o un miembro del grupo Propietarios del sitio. Para obtener más información, vea [Acceso denegado a la lista de las solicitudes de acceso](https://go.microsoft.com/fwlink/?linkid=2004220).</span><span class="sxs-lookup"><span data-stu-id="624f6-p103">If a someone got an "Access Denied" message when trying to view access requests, the user needs to be added as either a site collection administrator or a member of the Owners group for the site. For more info, see [Access Denied to Access Requests list](https://go.microsoft.com/fwlink/?linkid=2004220).</span></span>
  
<span data-ttu-id="624f6-112">Si un usuario tiene un mensaje de "Acceso denegado" después de que se han quitado de Active Directory local y, a continuación, agregar, vea [Acceso denegado cuando se sincroniza una cuenta de usuario a Office 365](https://go.microsoft.com/fwlink/?linkid=2004318).</span><span class="sxs-lookup"><span data-stu-id="624f6-112">If a user got an "Access Denied" message after they were removed from Active Directory on-premises and then added back, see [Access Denied when a user account is synced to Office 365](https://go.microsoft.com/fwlink/?linkid=2004318).</span></span>
  

