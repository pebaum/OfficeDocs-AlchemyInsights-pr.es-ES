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
# <a name="private-channels-in-microsoft-teams"></a>Canales privados en Microsoft Teams

Canales privados es una nueva característica de Microsoft Teams. Tenga en cuenta que los canales privados no se pueden convertir de los canales estándar o viceversa.

Para obtener más información sobre los canales privados, como la información sobre la [creación y pertenencia](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-creation-and-membership) de canales privados y los [sitios de SharePoint de canal privado](https://docs.microsoft.com/MicrosoftTeams/private-channels#private-channel-sharepoint-sites), consulte [canales privados en Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/private-channels). 

**Nota:** Como la configuración para la retención de mensajes de canal privado todavía no se admite, los inquilinos con directivas de retención habilitadas no tendrán canales privados habilitados de forma predeterminada. Los canales privados se pueden habilitar en el centro de administración de Teams. Además, tenga en cuenta que aunque no se admite la retención de mensajes de canal privado, se admite la retención de archivos compartidos en los canales privados.

**¿Necesita un nuevo propietario de equipo?**

Si el propietario del canal privado sale, puede Agregar un nuevo propietario del equipo a través de Teams PowerShell.


- Vaya [aquí](https://www.powershellgallery.com/packages/MicrosoftTeams/1.0.6) para instalar Teams PowerShell.

A continuación, se muestra el cmdlet que necesitará:

`
    Add-TeamChannelUser -GroupId <group_id> -DisplayName "<channel_name>" -User <UPN> -Role Owner
`

Para obtener más información sobre PowerShell de Teams, vea [Team PowerShell Overview](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).
