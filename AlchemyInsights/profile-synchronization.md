---
title: Sincronización de perfiles
ms.author: arnek
author: arnek
ms.date: 6/20/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6b695be8-eaf5-44ff-b0ae-1e0d89e7ab36
ms.openlocfilehash: d1a72a85767e36fefbfa8eee266befcaf2e48af0
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "32372001"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a><span data-ttu-id="ca64a-102">¿Cuándo se sincronizan mis cambios de perfil con la aplicación de Perfil de usuario de SharePoint?</span><span class="sxs-lookup"><span data-stu-id="ca64a-102">When do my profile changes sync to the SharePoint User Profile Application?</span></span>

<span data-ttu-id="ca64a-103">SharePoint Online usa el trabajo del temporizador de importación de Active Directory (AD Import) para importar usuarios y grupos en la aplicación de Perfil de usuario.</span><span class="sxs-lookup"><span data-stu-id="ca64a-103">SharePoint Online uses the Active Directory Import timer job (AD Import) to import users and groups into the User Profile Application.</span></span> 
  
1. <span data-ttu-id="ca64a-104">La importación de AD sincroniza los cambios del almacén de directorio de SharePoint Online con la aplicación de Perfil de usuario.</span><span class="sxs-lookup"><span data-stu-id="ca64a-104">AD Import syncs changes from the SharePoint Online Directory Store to the User Profile Application.</span></span> <span data-ttu-id="ca64a-105">Estos cambios se procesan por lotes.</span><span class="sxs-lookup"><span data-stu-id="ca64a-105">These changes are processed in batches.</span></span>
    
2. <span data-ttu-id="ca64a-106">El trabajo del temporizador se ejecuta hasta que se sincronicen los cambios.</span><span class="sxs-lookup"><span data-stu-id="ca64a-106">The timer job runs until the changes are synced.</span></span>
    
> [!NOTE]
> <span data-ttu-id="ca64a-107">El tiempo que tarda en ejecutarse el trabajo depende del número de cambios que se van a procesar.</span><span class="sxs-lookup"><span data-stu-id="ca64a-107">The time it takes the job to run depends on the number of changes to process.</span></span> <span data-ttu-id="ca64a-108">Un gran número de cambios lleva más tiempo.</span><span class="sxs-lookup"><span data-stu-id="ca64a-108">A large number of changes takes longer.</span></span> <span data-ttu-id="ca64a-109">El contrato de nivel de servicio (SLA) indica que un cambio en un usuario en el directorio de SharePoint Online se reflejará en la aplicación de Perfil de usuario en 24 horas.</span><span class="sxs-lookup"><span data-stu-id="ca64a-109">The Service Level Agreement (SLA) states that a change to a user in the SharePoint Online Directory will be reflected in the User Profile Application in 24 hours.</span></span> 
  
[<span data-ttu-id="ca64a-110">Más información sobre la sincronización de perfiles de usuario en SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="ca64a-110">More info about user profile sync in SharePoint Online</span></span>](https://go.microsoft.com/fwlink/?linkid=875671)
  

