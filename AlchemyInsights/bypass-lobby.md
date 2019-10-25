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
ms.openlocfilehash: 6632bb0c09c7ce99f14cd55582025b37a846369d
ms.sourcegitcommit: ee719f011f766fc20d23e935e98d7e33c326183b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/24/2019
ms.locfileid: "37654273"
---
# <a name="control-lobby-settings-and-level-of-participation"></a><span data-ttu-id="ab3a7-102">Controlar la configuración de la sala de espera y el nivel de participación</span><span class="sxs-lookup"><span data-stu-id="ab3a7-102">Control lobby settings and level of participation</span></span>

<span data-ttu-id="ab3a7-103">Si quiere permitir que todos los usuarios, incluidos los usuarios de acceso telefónico, externos y anónimos, omitan la sala de espera, puede usar PowerShell para hacerlo.</span><span class="sxs-lookup"><span data-stu-id="ab3a7-103">If you'd like to allow everyone, including Dial-in, external, and anonymous users to bypass the lobby, you can use PowerShell to do it.</span></span> <span data-ttu-id="ab3a7-104">Este es un ejemplo de cómo modificar la Directiva de reunión global de su organización:</span><span class="sxs-lookup"><span data-stu-id="ab3a7-104">Here's an example of modifying the global meeting policy for your organization:</span></span>

`Set-CsTeamsMeetingPolicy -Identity Global -AutoAdmittedUsers "Everyone" -AllowPSTNUsersToBypassLobby $True`

<span data-ttu-id="ab3a7-105">Actualmente, este cmdlet requiere el uso del módulo de PowerShell de Skype empresarial.</span><span class="sxs-lookup"><span data-stu-id="ab3a7-105">This cmdlet currently requires the use of Skype for Business PowerShell module.</span></span> <span data-ttu-id="ab3a7-106">Para obtener el programa de instalación para usar este cmdlet, consulte [Managing Policies Via PowerShell](https://docs.microsoft.com/en-us/microsoftteams/teams-powershell-overview#managing-policies-via-powershell).</span><span class="sxs-lookup"><span data-stu-id="ab3a7-106">To get setup to use this cmdlet, check out [Managing policies via PowerShell](https://docs.microsoft.com/en-us/microsoftteams/teams-powershell-overview#managing-policies-via-powershell).</span></span>

<span data-ttu-id="ab3a7-107">Puede configurar una nueva Directiva, que tendrá que aplicarla a los usuarios.</span><span class="sxs-lookup"><span data-stu-id="ab3a7-107">You can set up a new policy, which you'll then need to apply it to users.</span></span> <span data-ttu-id="ab3a7-108">Si modifica la directiva global, se aplicará automáticamente a los usuarios.</span><span class="sxs-lookup"><span data-stu-id="ab3a7-108">If you modify the Global policy it'll automatically apply to users.</span></span> <span data-ttu-id="ab3a7-109">Para cualquier cambio de Directiva, debe esperar al menos 4 horas y hasta 24 horas para que las directivas surtan efecto.</span><span class="sxs-lookup"><span data-stu-id="ab3a7-109">For any policy change you need to wait at least 4 hours and up to 24 hours for the policies to take effect.</span></span>

<span data-ttu-id="ab3a7-110">Asegúrese de revisar la documentación siguiente antes de realizar estos cambios para comprender exactamente lo que permite.</span><span class="sxs-lookup"><span data-stu-id="ab3a7-110">Be sure to review the documentation below before making these changes to understand exactly what this allows.</span></span>

## <a name="understanding-teams-meeting-lobby-policy-controls"></a><span data-ttu-id="ab3a7-111">Información sobre los controles de directiva de sala de reuniones de Teams</span><span class="sxs-lookup"><span data-stu-id="ab3a7-111">Understanding Teams meeting lobby policy controls</span></span>

- <span data-ttu-id="ab3a7-112">[Admitir automáticamente personas](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) es una directiva por organizador que controla si las personas se unen a una reunión directamente o esperan en la sala de espera hasta que un usuario autenticado las admita.</span><span class="sxs-lookup"><span data-stu-id="ab3a7-112">[Automatically admit people](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) is a per-organizer policy that controls whether people join a meeting directly or wait in the lobby until they are admitted by an authenticated user.</span></span>

- <span data-ttu-id="ab3a7-113">Permitir que los usuarios [anónimos inicien una reunión](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) es una directiva por organizador que controla si los usuarios anónimos, incluidos los usuarios B2B y federados, pueden unirse a la reunión del usuario sin un usuario autenticado de la organización en asistencia.</span><span class="sxs-lookup"><span data-stu-id="ab3a7-113">[Allow anonymous people to start a meeting](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) is a per-organizer policy that controls whether anonymous people, including B2B and federated users, can join the user's meeting without an authenticated user from the organization in attendance.</span></span>

- <span data-ttu-id="ab3a7-114">[Permitir a los usuarios de acceso telefónico omitir la sala](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) de**espera (** próximamente) es una directiva por organizador que controla si las personas que llaman por teléfono se unen directamente a la reunión o esperan en la sala independientemente de la configuración **admitir automáticamente** a los usuarios.</span><span class="sxs-lookup"><span data-stu-id="ab3a7-114">[Allow dial-in users to bypass the lobby](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (**coming soon**) is a per-organizer policy that controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the **Automatically admit people** setting.</span></span>

- <span data-ttu-id="ab3a7-115">[Permitir que los organizadores invaliden la configuración](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) de la sala de**espera (** próximamente) es una directiva por organizador que controla si el organizador de la reunión puede invalidar la configuración de la sala de espera que un administrador estableció en **admitir automáticamente** a los usuarios y **permitir el acceso telefónico los usuarios omitan la sala de** espera cuando programen una nueva reunión.</span><span class="sxs-lookup"><span data-stu-id="ab3a7-115">[Allow organizers to override lobby settings](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**coming soon**) is a per-organizer policy that controls whether the meeting organizer can override the lobby settings that an admin set in **Automatically admit people** and **Allow dial-in users to bypass the lobby** when they schedule a new meeting.</span></span>

<span data-ttu-id="ab3a7-116">**Nota:** Lea [Manage Meeting policies in Teams](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams) para obtener una introducción completa a las directivas de reunión de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="ab3a7-116">**Note:** Read [Manage meeting policies in Teams](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams) for a complete overview of Microsoft Teams meeting policies.</span></span>
