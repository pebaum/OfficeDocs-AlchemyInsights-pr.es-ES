---
title: Configuración de la Directiva de reunión
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2657"
- "9000734"
ms.openlocfilehash: dac06690b51459ca166c15a5ef0f4c7e7a6d36f0
ms.sourcegitcommit: 0495112ad4fd0e695140ec66d190e62f03030584
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/02/2019
ms.locfileid: "37376844"
---
# <a name="manage-meeting-policies-in-microsoft-teams"></a><span data-ttu-id="cf438-102">Administrar directivas de reuniones en Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="cf438-102">Manage meeting policies in Microsoft Teams</span></span>

<span data-ttu-id="cf438-103">Las directivas de reunión se usan para controlar las características que están disponibles para los participantes de la reunión en las reuniones programadas por los usuarios de la organización.</span><span class="sxs-lookup"><span data-stu-id="cf438-103">Meeting policies are used to control the features that are available to meeting participants for meetings that are scheduled by users in your organization.</span></span> <span data-ttu-id="cf438-104">Es posible que algunas características de las directivas de reunión no se implementen todavía en el centro de administración de Microsoft Teams (se les etiqueta "próximamente" en la documentación).</span><span class="sxs-lookup"><span data-stu-id="cf438-104">Some features of meeting policies might not be implemented in the Teams admin center yet (these are labeled "coming soon" in the documentation).</span></span> <span data-ttu-id="cf438-105">En este caso, o si recibe un error como "no se puede actualizar la Directiva en este momento, pero vuelva a intentarlo más tarde" en el centro de administración de Microsoft Teams, se recomienda usar PowerShell para crear o modificar las directivas de reunión de Teams.</span><span class="sxs-lookup"><span data-stu-id="cf438-105">In this case, or if you are getting an error like "We can't update the policy right now but try it again later" in the Microsoft Teams admin center, we recommend that you use PowerShell to create or modify Teams meeting policies.</span></span> 

<span data-ttu-id="cf438-106">Para obtener más información acerca de las directivas de reunión, vea los siguientes recursos:</span><span class="sxs-lookup"><span data-stu-id="cf438-106">For more information about meeting policies, see the following resources:</span></span>

- <span data-ttu-id="cf438-107">Para obtener información sobre cómo crear directivas, realizar cambios y asignar usuarios a la Directiva, consulte [Administrar directivas de reuniones en Microsoft Teams](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams).</span><span class="sxs-lookup"><span data-stu-id="cf438-107">To learn about creating policies, making changes, and assigning users to the policy, see [Manage meeting policies in Teams](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams).</span></span>

- <span data-ttu-id="cf438-108">Para realizar cambios en la Directiva con los cmdlets de PowerShell, vea [Team PowerShell Overview](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span><span class="sxs-lookup"><span data-stu-id="cf438-108">To make policy changes using PowerShell cmdlets, see [Teams PowerShell Overview](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span></span> 
    - <span data-ttu-id="cf438-109">Debe usar el módulo de [PowerShell de Skype empresarial](https://www.microsoft.com/download/details.aspx?id=39366) para las directivas de reunión de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="cf438-109">You need to use the [Skype for Business PowerShell module](https://www.microsoft.com/download/details.aspx?id=39366) for Teams meeting policies.</span></span> 
    - <span data-ttu-id="cf438-110">Para obtener más información, consulte la documentación de los [cmdlets \*-CsTeamsMeetingPolicy](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps) .</span><span class="sxs-lookup"><span data-stu-id="cf438-110">Review the [\*-CsTeamsMeetingPolicy cmdlets documentation](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps) for more information.</span></span>

<span data-ttu-id="cf438-111">**Nota:** Los cambios en la Directiva pueden tardar hasta 24 horas en surtir efecto para los usuarios.</span><span class="sxs-lookup"><span data-stu-id="cf438-111">**Note:** It can take up to 24 hours for policy changes to take effect for users.</span></span> <span data-ttu-id="cf438-112">Es posible que no pueda realizar cambios en las directivas recién creadas inmediatamente; Espere 4 horas e intente volver a modificar una Directiva recién creada.</span><span class="sxs-lookup"><span data-stu-id="cf438-112">You might not be able to make changes to newly created policies immediately; wait 4 hours and attempt to modify a newly created policy again.</span></span> <span data-ttu-id="cf438-113">Si sigue teniendo problemas, pruebe PowerShell.</span><span class="sxs-lookup"><span data-stu-id="cf438-113">If you're still having problems, try PowerShell.</span></span>  