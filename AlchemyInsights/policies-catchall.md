---
title: Directivas catchall
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
- "3207"
ms.openlocfilehash: c4694399b9ae5aa459357ed1610cccae762c0374
ms.sourcegitcommit: 01c4ee1339ea5303de48d51d22da5ce6073549f3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/12/2019
ms.locfileid: "38274985"
---
# <a name="teams-policies"></a><span data-ttu-id="2dcdb-102">Directivas de Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="2dcdb-102">Teams policies</span></span>

<span data-ttu-id="2dcdb-103">La configuración de Microsoft Teams se controla mediante directivas.</span><span class="sxs-lookup"><span data-stu-id="2dcdb-103">Microsoft Teams settings are controlled by policies.</span></span> <span data-ttu-id="2dcdb-104">Para realizar un cambio, debe configurar la Directiva adecuada y, a continuación, aplicarla a los usuarios.</span><span class="sxs-lookup"><span data-stu-id="2dcdb-104">To make a change, you must configure the appropriate policy, and then apply it to users.</span></span> <span data-ttu-id="2dcdb-105">La forma más rápida de hacerlo para todos los usuarios es modificar la directiva predeterminada denominada global.</span><span class="sxs-lookup"><span data-stu-id="2dcdb-105">The quickest way to do this for all your users is to modify the default policy named Global.</span></span> 

<span data-ttu-id="2dcdb-106">**Nota:** Los cambios de Directiva deben tener ***un mínimo de 4 a 48 horas para que surtan efecto***.</span><span class="sxs-lookup"><span data-stu-id="2dcdb-106">**NOTE** Policy changes take ***at least 4 up to 48 hours to take effect***.</span></span> <span data-ttu-id="2dcdb-107">Si crea una directiva personalizada, debe esperar al menos 4 horas antes de poder realizar cambios adicionales en ella.</span><span class="sxs-lookup"><span data-stu-id="2dcdb-107">If you create a custom policy, you need to wait at least 4 hours before you can make additional changes to it.</span></span> <span data-ttu-id="2dcdb-108">A continuación, puede aplicar esa Directiva a los usuarios.</span><span class="sxs-lookup"><span data-stu-id="2dcdb-108">Then you can apply that policy to users.</span></span> <span data-ttu-id="2dcdb-109">Esto significa que las directivas personalizadas pueden tardar hasta 48 horas en surtir efecto.</span><span class="sxs-lookup"><span data-stu-id="2dcdb-109">This means that custom policies can take up to 48 hours to take effect.</span></span> <span data-ttu-id="2dcdb-110">Las directivas globales se establecen como predeterminadas para todos los usuarios, y los cambios en la directiva global pueden tardar hasta 24 horas en surtir efecto.</span><span class="sxs-lookup"><span data-stu-id="2dcdb-110">Global policies are set as default for all users, and changes to the Global policy can take up to 24 hours to take effect.</span></span> <span data-ttu-id="2dcdb-111">Si ha creado una directiva personalizada, la ha aplicado a los usuarios y sigue teniendo efecto después de 48 horas, o ha modificado la directiva global y ha esperado al menos 24 horas, abra un caso de soporte técnico.</span><span class="sxs-lookup"><span data-stu-id="2dcdb-111">If you have created a custom policy, applied it to users, and it still hasn't taken effect after 48 hours, or you've modified the Global policy and waited at least 24 hours, please open a support case.</span></span>

<span data-ttu-id="2dcdb-112">Las directivas de Microsoft Teams se dividen en las siguientes áreas:</span><span class="sxs-lookup"><span data-stu-id="2dcdb-112">Teams policies are divided into the following areas:</span></span>

- <span data-ttu-id="2dcdb-113">[Las directivas](https://docs.microsoft.com/MicrosoftTeams/teams-policies) de Microsoft controlan la detección de usuarios de equipos privados en la búsqueda y la creación de canales privados.</span><span class="sxs-lookup"><span data-stu-id="2dcdb-113">[Teams policies](https://docs.microsoft.com/MicrosoftTeams/teams-policies) control user discovery of private teams in search and creation of private channels.</span></span>  
- <span data-ttu-id="2dcdb-114">[Las directivas de reunión](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams) controlan lo que pueden hacer los usuarios con las reuniones de Microsoft Teams, incluido el control del vestíbulo.</span><span class="sxs-lookup"><span data-stu-id="2dcdb-114">[Meeting policies](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams) control what users can do with Teams meetings, including controlling the lobby.</span></span> <span data-ttu-id="2dcdb-115">Para obtener ayuda con los problemas de la sala de espera, como la configuración de Teams para admitir a todos, consulte [control de la sala de espera y niveles de participación](https://docs.microsoft.com/en-us/alchemyinsights/bypass-lobby).</span><span class="sxs-lookup"><span data-stu-id="2dcdb-115">For help with lobby issues, like configuring Teams to admit everyone, see [Control lobby settings and levels of participation](https://docs.microsoft.com/en-us/alchemyinsights/bypass-lobby).</span></span>
- <span data-ttu-id="2dcdb-116">[Las directivas de mensajería](https://docs.microsoft.com/microsoftteams/messaging-policies-in-teams) controlan lo que los usuarios pueden hacer con los chats y los mensajes, como activar o desactivar el chat, eliminar los chats, solicitar confirmaciones de lectura, usar giphy y adhesivos, entre otras cosas.</span><span class="sxs-lookup"><span data-stu-id="2dcdb-116">[Messaging policies](https://docs.microsoft.com/microsoftteams/messaging-policies-in-teams) control what users can do with chat and messages, including turning chat on or off, deleting chats, requesting read receipts, using giphys and stickers, and more.</span></span>
- <span data-ttu-id="2dcdb-117">[Las directivas de configuración](https://docs.microsoft.com/MicrosoftTeams/teams-app-setup-policies) de la aplicación controlan qué aplicaciones están disponibles para los usuarios, incluidas las aplicaciones personalizadas y de terceros, y el orden en que aparecen.</span><span class="sxs-lookup"><span data-stu-id="2dcdb-117">[App setup policies](https://docs.microsoft.com/MicrosoftTeams/teams-app-setup-policies) control which apps are available to users, including custom and third-party apps, and the order in which they appear.</span></span>  
- <span data-ttu-id="2dcdb-118">[Las directivas de retención](https://docs.microsoft.com/microsoftteams/retention-policies) de datos para Teams se encuentran en el centro de seguridad y cumplimiento de Office 365.</span><span class="sxs-lookup"><span data-stu-id="2dcdb-118">Data [retention policies](https://docs.microsoft.com/microsoftteams/retention-policies) for Teams are found in the Office 365 Security and Compliance Center.</span></span>
- <span data-ttu-id="2dcdb-119">Las directivas de la libreta de direcciones de Microsoft Teams se establecen mediante la [búsqueda de directorios con ámbito](https://docs.microsoft.com/MicrosoftTeams/teams-scoped-directory-search).</span><span class="sxs-lookup"><span data-stu-id="2dcdb-119">Teams address book policies are set via [scoped directory search](https://docs.microsoft.com/MicrosoftTeams/teams-scoped-directory-search).</span></span>