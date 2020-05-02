---
title: Canal privado
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001223"
- "3205"
ms.openlocfilehash: be518df0d40123c1f0da6596bd6e2e91a0c2c8fa
ms.sourcegitcommit: 057d87c9d866fa1371d02350420d13774545c028
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/02/2020
ms.locfileid: "44005455"
---
# <a name="private-channels-in-microsoft-teams"></a><span data-ttu-id="fbb2b-102">Canales privados en Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="fbb2b-102">Private channels in Microsoft Teams</span></span>

<span data-ttu-id="fbb2b-103">Canales privados es una nueva característica de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="fbb2b-103">Private channels is a new feature in Microsoft Teams.</span></span> <span data-ttu-id="fbb2b-104">Tenga en cuenta que los canales privados no se pueden convertir de los canales estándar o viceversa.</span><span class="sxs-lookup"><span data-stu-id="fbb2b-104">Note that private channels cannot be converted from standard channels or vice versa.</span></span>

<span data-ttu-id="fbb2b-105">Para obtener más información sobre los canales privados, como la información sobre la [creación y pertenencia](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-creation-and-membership) de canales privados y los [sitios de SharePoint de canal privado](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-sharepoint-sites), consulte [canales privados en Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/private-channels).</span><span class="sxs-lookup"><span data-stu-id="fbb2b-105">For details about private channels, such as information on [private channel creation and membership](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-creation-and-membership) and [private channel SharePoint sites](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-sharepoint-sites), see [Private channels in Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/private-channels).</span></span> 

<span data-ttu-id="fbb2b-106">**Nota:** Como la configuración para la retención de mensajes de canal privado todavía no se admite, los inquilinos con directivas de retención habilitadas no tendrán canales privados habilitados de forma predeterminada.</span><span class="sxs-lookup"><span data-stu-id="fbb2b-106">**Note:** Because configuration for retention of private channel messages is not yet supported, tenants with retention policies enabled will not have private channels enabled by default.</span></span> <span data-ttu-id="fbb2b-107">Los canales privados se pueden habilitar en el centro de administración de Teams.</span><span class="sxs-lookup"><span data-stu-id="fbb2b-107">Private channels can be enabled in the Teams admin center.</span></span> <span data-ttu-id="fbb2b-108">Además, tenga en cuenta que aunque no se admite la retención de mensajes de canal privado, se admite la retención de archivos compartidos en los canales privados.</span><span class="sxs-lookup"><span data-stu-id="fbb2b-108">Also, note that while retention of private channel messages is not supported, retention of files shared in private channels is supported.</span></span>

<span data-ttu-id="fbb2b-109">**¿Necesita un nuevo propietario de equipo?**</span><span class="sxs-lookup"><span data-stu-id="fbb2b-109">**Need a new team owner?**</span></span>

<span data-ttu-id="fbb2b-110">Si el propietario del canal privado sale, puede Agregar un nuevo propietario del equipo a través de Teams PowerShell.</span><span class="sxs-lookup"><span data-stu-id="fbb2b-110">If your private channel owner leaves, you can add a new team owner via Teams Powershell.</span></span>


- <span data-ttu-id="fbb2b-111">Vaya [aquí](https://www.powershellgallery.com/packages/MicrosoftTeams/1.0.6) para instalar Teams PowerShell.</span><span class="sxs-lookup"><span data-stu-id="fbb2b-111">Go [here](https://www.powershellgallery.com/packages/MicrosoftTeams/1.0.6) to install Teams Powershell.</span></span>

<span data-ttu-id="fbb2b-112">A continuación, se muestra el cmdlet que necesitará:</span><span class="sxs-lookup"><span data-stu-id="fbb2b-112">Here is the cmdlet you will need:</span></span>

`
    Add-TeamChannelUser -GroupId <group_id> -DisplayName "<channel_name>" -User <UPN> -Role Owner
`

<span data-ttu-id="fbb2b-113">Para obtener más información sobre PowerShell de Teams, vea [Team PowerShell Overview](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span><span class="sxs-lookup"><span data-stu-id="fbb2b-113">For more information on Teams Powershell, see [Teams PowerShell Overview](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span></span>
