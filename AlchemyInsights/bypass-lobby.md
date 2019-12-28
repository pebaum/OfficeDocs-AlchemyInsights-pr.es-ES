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
# <a name="control-lobby-settings-and-level-of-participation-in-teams"></a><span data-ttu-id="4e9e2-102">Controlar la configuración de la sala de espera y el nivel de participación en Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="4e9e2-102">Control lobby settings and level of participation in Teams</span></span>

<span data-ttu-id="4e9e2-103">Si quiere permitir que todos los usuarios, incluidos los usuarios de acceso telefónico, externo y anónimo, **omitan la sala**de espera, use PowerShell para realizar esta tarea.</span><span class="sxs-lookup"><span data-stu-id="4e9e2-103">If you'd like to allow everyone, including Dial-in, external, and anonymous users, to **bypass the lobby**, use PowerShell to accomplish this task.</span></span> <span data-ttu-id="4e9e2-104">Este es un ejemplo de cómo modificar la Directiva de reunión global de su organización.</span><span class="sxs-lookup"><span data-stu-id="4e9e2-104">Here's an example of modifying the global meeting policy for your organization.</span></span>

`Set-CsTeamsMeetingPolicy -Identity Global -AutoAdmittedUsers "Everyone" -AllowPSTNUsersToBypassLobby $True`

<span data-ttu-id="4e9e2-105">Actualmente, este cmdlet requiere el uso del módulo de PowerShell de Skype empresarial.</span><span class="sxs-lookup"><span data-stu-id="4e9e2-105">This cmdlet currently requires the use of Skype for Business PowerShell module.</span></span> <span data-ttu-id="4e9e2-106">Para configurar el uso de este cmdlet, consulte Administración de [directivas a través de PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview#managing-policies-via-powershell).</span><span class="sxs-lookup"><span data-stu-id="4e9e2-106">To get set up to use this cmdlet, check out [Managing policies via PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview#managing-policies-via-powershell).</span></span>

<span data-ttu-id="4e9e2-107">Una vez configurada una directiva, debe aplicarla a los usuarios; o bien, si modificó la directiva global, se aplicará automáticamente a los usuarios.</span><span class="sxs-lookup"><span data-stu-id="4e9e2-107">Once you’ve set up a policy, you need to apply it to users; or, if you modified the Global policy, it will automatically apply to users.</span></span> <span data-ttu-id="4e9e2-108">Para cualquier cambio de Directiva, debe esperar al menos **4 horas hasta 24 horas** para que las directivas surtan efecto.</span><span class="sxs-lookup"><span data-stu-id="4e9e2-108">For any policy change, you need to wait at least **4 hours up to 24 hours** for the policies to take effect.</span></span> 

<span data-ttu-id="4e9e2-109">Asegúrese de revisar la documentación siguiente antes de realizar estos cambios para comprender exactamente lo que permite.</span><span class="sxs-lookup"><span data-stu-id="4e9e2-109">Be sure to review the documentation below before making these changes to understand exactly what this allows.</span></span>


## <a name="understanding-teams-meeting-lobby-policy-controls"></a><span data-ttu-id="4e9e2-110">Información sobre los controles de directiva de sala de reuniones de Teams</span><span class="sxs-lookup"><span data-stu-id="4e9e2-110">Understanding Teams meeting lobby policy controls</span></span>

<span data-ttu-id="4e9e2-111">Esta configuración controla qué participantes de la reunión esperan en la sala de espera antes de que se admitan en la reunión y el nivel de participación que se les permite en una reunión.</span><span class="sxs-lookup"><span data-stu-id="4e9e2-111">These settings control which meeting participants wait in the lobby before they are admitted to the meeting and the level of participation they are allowed in a meeting.</span></span> <span data-ttu-id="4e9e2-112">Puede usar PowerShell para actualizar la configuración de la Directiva de reunión que todavía no se ha implementado (con la etiqueta "próximamente") en el centro de administración de Teams.</span><span class="sxs-lookup"><span data-stu-id="4e9e2-112">You can use PowerShell to update meeting policy settings that haven't yet been implemented (labeled "coming soon") in the Teams admin center.</span></span> <span data-ttu-id="4e9e2-113">Vea a continuación un cmdlet de PowerShell de ejemplo que permite a todos los usuarios omitir la sala de espera.</span><span class="sxs-lookup"><span data-stu-id="4e9e2-113">See below for an example PowerShell cmdlet that allows all users to bypass the lobby.</span></span>

- <span data-ttu-id="4e9e2-114">[Admitir automáticamente personas](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) es una directiva por organizador que controla si las personas se unen a una reunión directamente o esperan en la sala de espera hasta que un usuario autenticado las admita.</span><span class="sxs-lookup"><span data-stu-id="4e9e2-114">[Automatically admit people](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) is a per-organizer policy that controls whether people join a meeting directly or wait in the lobby until they are admitted by an authenticated user.</span></span>

- <span data-ttu-id="4e9e2-115">Permitir que los usuarios [anónimos inicien una reunión](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) es una directiva por organizador que controla si los usuarios anónimos, incluidos los usuarios B2B y federados, pueden unirse a la reunión del usuario sin un usuario autenticado de la organización en asistencia.</span><span class="sxs-lookup"><span data-stu-id="4e9e2-115">[Allow anonymous people to start a meeting](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) is a per-organizer policy that controls whether anonymous people, including B2B and federated users, can join the user's meeting without an authenticated user from the organization in attendance.</span></span>

- <span data-ttu-id="4e9e2-116">[Permitir a los usuarios de acceso telefónico omitir la sala](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) de**espera (** próximamente) es una directiva por organizador que controla si las personas que llaman por teléfono se unen directamente a la reunión o esperan en la sala independientemente de la configuración **admitir automáticamente** a los usuarios.</span><span class="sxs-lookup"><span data-stu-id="4e9e2-116">[Allow dial-in users to bypass the lobby](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (**coming soon**) is a per-organizer policy that controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the **Automatically admit people** setting.</span></span>

- <span data-ttu-id="4e9e2-117">[Permitir que los organizadores invaliden la configuración](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) de la sala de**espera (** próximamente) es una directiva por organizador que controla si el organizador de la reunión puede invalidar la configuración de la sala de espera que un administrador estableció en **admitir automáticamente** a los **usuarios y permitir que los usuarios de acceso telefónico no usen la sala** de espera cuando programen una nueva reunión.</span><span class="sxs-lookup"><span data-stu-id="4e9e2-117">[Allow organizers to override lobby settings](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**coming soon**) is a per-organizer policy that controls whether the meeting organizer can override the lobby settings that an admin set in **Automatically admit people** and **Allow dial-in users to bypass the lobby** when they schedule a new meeting.</span></span>

<span data-ttu-id="4e9e2-118">**Nota:** Lea [Manage Meeting policies in Teams](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams) para obtener una introducción completa a las directivas de reunión de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="4e9e2-118">**Note:** Read [Manage meeting policies in Teams](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams) for a complete overview of Microsoft Teams meeting policies.</span></span>
