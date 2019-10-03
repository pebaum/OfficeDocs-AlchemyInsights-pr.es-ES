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
ms.openlocfilehash: de665ca6defcd0d00d227435473e5a4ccf61bc82
ms.sourcegitcommit: 0495112ad4fd0e695140ec66d190e62f03030584
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/02/2019
ms.locfileid: "37376849"
---
# <a name="control-lobby-settings-and-level-of-participation"></a><span data-ttu-id="b19f1-102">Controlar la configuración de la sala de espera y el nivel de participación</span><span class="sxs-lookup"><span data-stu-id="b19f1-102">Control lobby settings and level of participation</span></span>

<span data-ttu-id="b19f1-103">Esta configuración controla qué participantes de la reunión esperan en la sala de espera antes de que se admitan en la reunión y el nivel de participación que se les permite en una reunión.</span><span class="sxs-lookup"><span data-stu-id="b19f1-103">These settings control which meeting participants wait in the lobby before they are admitted to the meeting and the level of participation they are allowed in a meeting.</span></span> <span data-ttu-id="b19f1-104">Puede usar PowerShell para actualizar la configuración de la Directiva de reunión que todavía no se ha implementado (con la etiqueta "próximamente") en el centro de administración de Teams.</span><span class="sxs-lookup"><span data-stu-id="b19f1-104">You can use Powershell to update meeting policy settings that haven't yet been implemented (labeled "coming soon") in the Teams admin center.</span></span>  <span data-ttu-id="b19f1-105">Vea a continuación un cmdlet de PowerShell de ejemplo que permite a todos los usuarios omitir la sala de espera.</span><span class="sxs-lookup"><span data-stu-id="b19f1-105">See below for an example PowerShell cmdlet that allows all users to bypass the lobby.</span></span>  

- <span data-ttu-id="b19f1-106">[Admitir automáticamente personas](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) es una directiva por organizador que controla si las personas se unen a una reunión directamente o esperan en la sala de espera hasta que un usuario autenticado las admita.</span><span class="sxs-lookup"><span data-stu-id="b19f1-106">[Automatically admit people](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) is a per-organizer policy that controls whether people join a meeting directly or wait in the lobby until they are admitted by an authenticated user.</span></span>

- <span data-ttu-id="b19f1-107">Permitir que los usuarios [anónimos inicien una reunión](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) es una directiva por organizador que controla si los usuarios anónimos, incluidos los usuarios B2B y federados, pueden unirse a la reunión del usuario sin un usuario autenticado de la organización en asistencia.</span><span class="sxs-lookup"><span data-stu-id="b19f1-107">[Allow anonymous people to start a meeting](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) is a per-organizer policy that controls whether anonymous people, including B2B and federated users, can join the user's meeting without an authenticated user from the organization in attendance.</span></span>

- <span data-ttu-id="b19f1-108">[Permitir a los usuarios de acceso telefónico omitir la sala](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) de**espera (** próximamente) es una directiva por organizador que controla si las personas que llaman por teléfono se unen directamente a la reunión o esperan en la sala independientemente de la configuración **admitir automáticamente** a los usuarios.</span><span class="sxs-lookup"><span data-stu-id="b19f1-108">[Allow dial-in users to bypass the lobby](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (**coming soon**) is a per-organizer policy that controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the **Automatically admit people** setting.</span></span>

- <span data-ttu-id="b19f1-109">[Permitir que los organizadores invaliden la configuración](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) de la sala de**espera (** próximamente) es una directiva por organizador que controla si el organizador de la reunión puede invalidar la configuración de la sala de espera que un administrador estableció en **admitir automáticamente** a los usuarios y **permitir el acceso telefónico los usuarios omitan la sala de** espera cuando programen una nueva reunión.</span><span class="sxs-lookup"><span data-stu-id="b19f1-109">[Allow organizers to override lobby settings](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**coming soon**) is a per-organizer policy that controls whether the meeting organizer can override the lobby settings that an admin set in **Automatically admit people** and **Allow dial-in users to bypass the lobby** when they schedule a new meeting.</span></span>

<span data-ttu-id="b19f1-110">**Nota:** Lea [Manage Meeting policies in Teams](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams) para obtener una introducción completa a las directivas de reunión de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="b19f1-110">**Note:** Read [Manage meeting policies in Teams](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams) for a complete overview of Microsoft Teams meeting policies.</span></span> 


<span data-ttu-id="b19f1-111">**Ejemplo de PowerShell**</span><span class="sxs-lookup"><span data-stu-id="b19f1-111">**PowerShell example**</span></span>

<span data-ttu-id="b19f1-112">Si quiere permitir que todos los usuarios, incluidos los usuarios externos o anónimos, omitan la sala de espera, también puede usar PowerShell para llevar a cabo esta tarea.</span><span class="sxs-lookup"><span data-stu-id="b19f1-112">If you'd like to allow everyone, including external or anonymous users, to bypass the lobby, you can also use PowerShell to accomplish this task.</span></span>  <span data-ttu-id="b19f1-113">Este es un ejemplo de cómo modificar la Directiva de reunión global de su organización.</span><span class="sxs-lookup"><span data-stu-id="b19f1-113">Here's an example of modifying the global meeting policy for your organization.</span></span>   

<span data-ttu-id="b19f1-114">(Asegúrese de revisar la documentación anterior antes de realizar estos cambios para comprender exactamente lo que permite.)</span><span class="sxs-lookup"><span data-stu-id="b19f1-114">(Be sure to review the documentation above before making these changes to understand exactly what this allows.)</span></span>

<span data-ttu-id="b19f1-115">Set-CsTeamsMeetingPolicy-Identity global-AutoAdmittedUsers "everyone"-AllowPSTNUsersToBypassLobby $True</span><span class="sxs-lookup"><span data-stu-id="b19f1-115">Set-CsTeamsMeetingPolicy -Identity Global -AutoAdmittedUsers "Everyone" -AllowPSTNUsersToBypassLobby $True</span></span>

<span data-ttu-id="b19f1-116">Para obtener más información, vea [set-CsTeamsMeetingPolicy](https://docs.microsoft.com/powershell/module/skype/set-csteamsmeetingpolicy?view=skype-ps).</span><span class="sxs-lookup"><span data-stu-id="b19f1-116">For more information, see [Set-CsTeamsMeetingPolicy](https://docs.microsoft.com/powershell/module/skype/set-csteamsmeetingpolicy?view=skype-ps).</span></span>
