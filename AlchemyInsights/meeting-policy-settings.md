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
- "9000734"
- "2657"
ms.openlocfilehash: 509bd0c686830c04ed27f97372411677c0a7f4a4
ms.sourcegitcommit: 9aaa61d717e0fd475d2e9f0507c42aa40d073b5f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/15/2020
ms.locfileid: "42042861"
---
# <a name="manage-meeting-policies-in-microsoft-teams"></a><span data-ttu-id="d1cdb-102">Administrar directivas de reuniones en Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="d1cdb-102">Manage meeting policies in Microsoft Teams</span></span>

<span data-ttu-id="d1cdb-103">**Nota: los cambios en la Directiva pueden tardar hasta 24 horas en surtir efecto para los usuarios.**</span><span class="sxs-lookup"><span data-stu-id="d1cdb-103">**Note: It can take up to 24 hours for policy changes to take effect for users.**</span></span> <span data-ttu-id="d1cdb-104">Es posible que no pueda realizar cambios en las directivas recién creadas inmediatamente; Espere 4 horas e intente volver a modificar una Directiva recién creada.</span><span class="sxs-lookup"><span data-stu-id="d1cdb-104">You might not be able to make changes to newly created policies immediately; wait 4 hours and attempt to modify a newly created policy again.</span></span>

<span data-ttu-id="d1cdb-105">Las directivas de reunión se usan para controlar las características que están disponibles para los participantes de la reunión en las reuniones programadas por los usuarios de la organización.</span><span class="sxs-lookup"><span data-stu-id="d1cdb-105">Meeting policies are used to control the features that are available to meeting participants for meetings that are scheduled by users in your organization.</span></span> <span data-ttu-id="d1cdb-106">Es posible que algunas características de las directivas de reunión no se implementen todavía en el centro de administración de Microsoft Teams (se les etiqueta "próximamente" en la documentación).</span><span class="sxs-lookup"><span data-stu-id="d1cdb-106">Some features of meeting policies might not be implemented in the Teams admin center yet (these are labeled "coming soon" in the documentation).</span></span> <span data-ttu-id="d1cdb-107">En este caso, o si recibe un error como "no se puede actualizar la Directiva en este momento, pero vuelva a intentarlo más tarde" en el centro de administración de Microsoft Teams, se recomienda usar PowerShell para crear o modificar las directivas de reunión de Teams.</span><span class="sxs-lookup"><span data-stu-id="d1cdb-107">In this case, or if you are getting an error like "We can't update the policy right now but try it again later" in the Microsoft Teams admin center, we recommend that you use PowerShell to create or modify Teams meeting policies.</span></span> 

<span data-ttu-id="d1cdb-108">Para obtener más información acerca de las directivas de reunión, vea los siguientes recursos:</span><span class="sxs-lookup"><span data-stu-id="d1cdb-108">For more information about meeting policies, see the following resources:</span></span>

- <span data-ttu-id="d1cdb-109">Para obtener información sobre cómo crear directivas, realizar cambios y asignar usuarios a la Directiva, consulte [Administrar directivas de reuniones en Microsoft Teams](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams).</span><span class="sxs-lookup"><span data-stu-id="d1cdb-109">To learn about creating policies, making changes, and assigning users to the policy, see [Manage meeting policies in Teams](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams).</span></span>

- <span data-ttu-id="d1cdb-110">Para realizar cambios en la Directiva con los cmdlets de PowerShell, vea [Team PowerShell Overview](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span><span class="sxs-lookup"><span data-stu-id="d1cdb-110">To make policy changes using PowerShell cmdlets, see [Teams PowerShell Overview](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span></span> 
    - <span data-ttu-id="d1cdb-111">Debe usar el módulo de [PowerShell de Skype empresarial](https://www.microsoft.com/download/details.aspx?id=39366) para las directivas de reunión de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="d1cdb-111">You need to use the [Skype for Business PowerShell module](https://www.microsoft.com/download/details.aspx?id=39366) for Teams meeting policies.</span></span> 
    - <span data-ttu-id="d1cdb-112">Para obtener más información, consulte la documentación de los [cmdlets \*-CsTeamsMeetingPolicy](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps) .</span><span class="sxs-lookup"><span data-stu-id="d1cdb-112">Review the [\*-CsTeamsMeetingPolicy cmdlets documentation](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps) for more information.</span></span>

