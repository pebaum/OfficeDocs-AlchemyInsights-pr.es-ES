---
title: Desuso de Exchange PowerShell y autenticación básica
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3500011"
- "4577"
ms.openlocfilehash: 24d59860732b42e8d62da8c1a8c37f2018a0d126
ms.sourcegitcommit: 264b782ac2fba8ffd84524180dc4f7d60b45e9a4
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 05/04/2020
ms.locfileid: "44015706"
---
# <a name="exchange-powershell-and-basic-authentication-deprecation"></a><span data-ttu-id="a04b9-102">Desuso de Exchange PowerShell y autenticación básica</span><span class="sxs-lookup"><span data-stu-id="a04b9-102">Exchange PowerShell and basic authentication deprecation</span></span>

<span data-ttu-id="a04b9-103">Para obtener la información más reciente sobre cómo conectarse a Exchange Online PowerShell sin usar autenticación básica, [vaya aquí](https://aka.ms/psbasicauth).</span><span class="sxs-lookup"><span data-stu-id="a04b9-103">For the latest information about how to connect to Exchange Online PowerShell without the use of Basic Authentication, [please go here](https://aka.ms/psbasicauth).</span></span>

<span data-ttu-id="a04b9-104">Tenga en cuenta que la Autenticación básica debe estar habilitada en el equipo cliente.</span><span class="sxs-lookup"><span data-stu-id="a04b9-104">Please note that Basic Authentication still needs to be enabled on your client machine.</span></span>
<span data-ttu-id="a04b9-105">El nuevo módulo PowerShell V2 usa la Autenticación moderna para establecer la conexión con el fin de habilitar todos los cmdlets V2 basados en REST.</span><span class="sxs-lookup"><span data-stu-id="a04b9-105">The new PowerShell V2 module uses Modern Auth to establish connection for enabling all of REST-based V2 Cmdlets.</span></span> <span data-ttu-id="a04b9-106">Además de los cmdlets V2, también le permite tener acceso a cmdlets antiguos remotos de PowerShell (RPS), lo que requiere que se establezca una sesión de PowerShell remota.</span><span class="sxs-lookup"><span data-stu-id="a04b9-106">In addition to V2 cmdlets, it also allows you to access older Remote PowerShell (RPS) Cmdlets which requires a Remote PowerShell session to be established.</span></span> <span data-ttu-id="a04b9-107">Establecer una sesión de RPS en un equipo con Windows requiere que se habilite la Autenticación básica WinRM en el equipo cliente aunque el módulo use un mecanismo de autenticación moderno para autenticarse en el servicio.</span><span class="sxs-lookup"><span data-stu-id="a04b9-107">Establishing an RPS session on Windows machine requires WinRM BasicAuth to be enabled on the client machine even though the module uses Modern Auth mechanism to authenticate to the service.</span></span> <span data-ttu-id="a04b9-108">La canalización de autenticación básica de WinRM se usa para transportar los tokens de autenticación modernos.</span><span class="sxs-lookup"><span data-stu-id="a04b9-108">The WinRM Basic Auth pipeline is used for transporting Modern Auth tokens.</span></span> <span data-ttu-id="a04b9-109">Si la Autenticación básica WinRM está deshabilitada en el equipo cliente, los nuevos cmdlets V2 seguirán funcionando (pero los cmdlets de RPS antiguos no se mostrarán).</span><span class="sxs-lookup"><span data-stu-id="a04b9-109">If WinRM Basic Auth is disabled on the client machine, the new V2 cmdlets will continue to work (but the older RPS cmdlets will not).</span></span>
