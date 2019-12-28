---
title: Omitir la sala de espera
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2673"
- "9000740"
ms.openlocfilehash: 311af365a94b788182bb6870bca3f67b2ad802d0
ms.sourcegitcommit: 932981641dd8e973e28dfe346bbdf9c923111b13
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/27/2019
ms.locfileid: "40889099"
---
# <a name="control-lobby-settings-and-level-of-participation-in-teams"></a>Controlar la configuración de la sala de espera y el nivel de participación en Microsoft Teams

Si quiere permitir que todos los usuarios, incluidos los usuarios de acceso telefónico, externo y anónimo, **omitan la sala**de espera, use PowerShell para realizar esta tarea. Este es un ejemplo de cómo modificar la Directiva de reunión global de su organización.

`Set-CsTeamsMeetingPolicy -Identity Global -AutoAdmittedUsers "Everyone" -AllowPSTNUsersToBypassLobby $True`

Actualmente, este cmdlet requiere el uso del módulo de PowerShell de Skype empresarial. Para configurar el uso de este cmdlet, consulte Administración de [directivas a través de PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview#managing-policies-via-powershell).

Una vez configurada una directiva, debe aplicarla a los usuarios; o bien, si modificó la directiva global, se aplicará automáticamente a los usuarios. Para cualquier cambio de Directiva, debe esperar al menos **4 horas hasta 24 horas** para que las directivas surtan efecto. 

Asegúrese de revisar la documentación siguiente antes de realizar estos cambios para comprender exactamente lo que permite.


## <a name="understanding-teams-meeting-lobby-policy-controls"></a>Información sobre los controles de directiva de sala de reuniones de Teams

Esta configuración controla qué participantes de la reunión esperan en la sala de espera antes de que se admitan en la reunión y el nivel de participación que se les permite en una reunión. Puede usar PowerShell para actualizar la configuración de la Directiva de reunión que todavía no se ha implementado (con la etiqueta "próximamente") en el centro de administración de Teams. Vea a continuación un cmdlet de PowerShell de ejemplo que permite a todos los usuarios omitir la sala de espera.

- [Admitir automáticamente personas](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) es una directiva por organizador que controla si las personas se unen a una reunión directamente o esperan en la sala de espera hasta que un usuario autenticado las admita.

- Permitir que los usuarios [anónimos inicien una reunión](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) es una directiva por organizador que controla si los usuarios anónimos, incluidos los usuarios B2B y federados, pueden unirse a la reunión del usuario sin un usuario autenticado de la organización en asistencia.

- [Permitir a los usuarios de acceso telefónico omitir la sala](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) de**espera (** próximamente) es una directiva por organizador que controla si las personas que llaman por teléfono se unen directamente a la reunión o esperan en la sala independientemente de la configuración **admitir automáticamente** a los usuarios.

- [Permitir que los organizadores invaliden la configuración](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) de la sala de**espera (** próximamente) es una directiva por organizador que controla si el organizador de la reunión puede invalidar la configuración de la sala de espera que un administrador estableció en **admitir automáticamente** a los **usuarios y permitir que los usuarios de acceso telefónico no usen la sala** de espera cuando programen una nueva reunión.

**Nota:** Lea [Manage Meeting policies in Teams](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams) para obtener una introducción completa a las directivas de reunión de Microsoft Teams.
