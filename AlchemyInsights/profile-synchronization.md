---
title: Sincronización de perfiles
ms.author: arnek
author: arnek
ms.date: 6/20/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 6b695be8-eaf5-44ff-b0ae-1e0d89e7ab36
ms.openlocfilehash: a32cf9e623d1be7a2c85ef4951c6eb7f001b7db0
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29491524"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a><span data-ttu-id="e1eb4-102">¿Al sincronizar los cambios de perfiles a la aplicación de perfil de usuario de SharePoint?</span><span class="sxs-lookup"><span data-stu-id="e1eb4-102">When do my profile changes sync to the SharePoint User Profile Application?</span></span>

<span data-ttu-id="e1eb4-103">SharePoint Online usa el trabajo del temporizador de importación de Active Directory (AD Import) para importar los usuarios y grupos en la aplicación de perfil de usuario.</span><span class="sxs-lookup"><span data-stu-id="e1eb4-103">SharePoint Online uses the Active Directory Import timer job (AD Import) to import users and groups into the User Profile Application.</span></span> 
  
1. <span data-ttu-id="e1eb4-p101">Importación de AD se sincroniza los cambios desde el almacén de directorios de SharePoint Online a la aplicación de perfil de usuario. Estos cambios se procesan en lotes.</span><span class="sxs-lookup"><span data-stu-id="e1eb4-p101">AD Import syncs changes from the SharePoint Online Directory Store to the User Profile Application. These changes are processed in batches.</span></span>
    
2. <span data-ttu-id="e1eb4-106">El trabajo del temporizador se ejecuta hasta que se sincronicen los cambios.</span><span class="sxs-lookup"><span data-stu-id="e1eb4-106">The timer job runs until the changes are synced.</span></span>
    
> [!NOTE]
> <span data-ttu-id="e1eb4-p102">El tiempo que tarda el trabajo para ejecutar depende del número de cambios para procesar. Un gran número de cambios tarda más. El contrato de nivel de servicio (SLA) indica que un cambio a un usuario en el directorio en línea de SharePoint se reflejará en la aplicación de perfil de usuario en 24 horas.</span><span class="sxs-lookup"><span data-stu-id="e1eb4-p102">The time it takes the job to run depends on the number of changes to process. A large number of changes takes longer. The Service Level Agreement (SLA) states that a change to a user in the SharePoint Online Directory will be reflected in the User Profile Application in 24 hours.</span></span> 
  
[<span data-ttu-id="e1eb4-110">Obtener más información acerca de la sincronización de perfiles de usuario en SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="e1eb4-110">More info about user profile sync in SharePoint Online</span></span>](https://go.microsoft.com/fwlink/?linkid=875671)
  

