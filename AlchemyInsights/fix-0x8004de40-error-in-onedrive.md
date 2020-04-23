---
title: Error de corrección 0x8004de40 en OneDrive
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 5da4271f242597b195ef61d553fd4a2ffb313025
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716045"
---
# <a name="fix-0x8004de40-error-in-onedrive"></a><span data-ttu-id="8c31c-102">Error de corrección 0x8004de40 en OneDrive</span><span class="sxs-lookup"><span data-stu-id="8c31c-102">Fix 0x8004de40 error in OneDrive</span></span>

<span data-ttu-id="8c31c-103">Si recibe un error 0x8004de40 con OneDrive:</span><span class="sxs-lookup"><span data-stu-id="8c31c-103">If you receive an 0x8004de40 error with OneDrive:</span></span>

- <span data-ttu-id="8c31c-104">Reinicie el equipo afectado mientras está conectado a su dominio de directorio de Acitve.</span><span class="sxs-lookup"><span data-stu-id="8c31c-104">Reboot the affected computer while connected to your Acitve Directory domain.</span></span>
- <span data-ttu-id="8c31c-105">Si un reinicio no soluciona el problema, separe y vuelva a unirse al dispositivo desde Azure AD.</span><span class="sxs-lookup"><span data-stu-id="8c31c-105">If a reboot doesn't fix the issue, unjoin and rejoin your device from Azure AD.</span></span> 

<span data-ttu-id="8c31c-106">**Nota**: debe estar en la red corporativa mientras realiza estos pasos.</span><span class="sxs-lookup"><span data-stu-id="8c31c-106">**Note**: You should be on your corporate network while performing these steps.</span></span> <span data-ttu-id="8c31c-107">No realice estos pasos cuando no pueda conectarse a su infraestructura corporativa (por ejemplo, mientras viaja).</span><span class="sxs-lookup"><span data-stu-id="8c31c-107">Don't perform these steps when you aren't able to connect to your corporate infrastructure (for example, while traveling).</span></span> 

- <span data-ttu-id="8c31c-108">Abra un símbolo del sistema elevado.</span><span class="sxs-lookup"><span data-stu-id="8c31c-108">Open an elevated command prompt.</span></span> 
- <span data-ttu-id="8c31c-109">Para abrir un símbolo del sistema con privilegios elevados, haga clic en- **iniciar**, haga clic con el botón secundario en **símbolo del sistema**y haga clic en **Ejecutar como administrador**.</span><span class="sxs-lookup"><span data-stu-id="8c31c-109">To open an elevated command prompt, click - **Start**, right-click **Command Prompt**, and then click **Run as administrator**.</span></span>
- <span data-ttu-id="8c31c-110">Escriba *dsregcmd/Leave* y presione **entrar**.</span><span class="sxs-lookup"><span data-stu-id="8c31c-110">Type *dsregcmd /leave* and press **Enter**.</span></span>
- <span data-ttu-id="8c31c-111">Cuando termine, escriba *dsregcmd/join* y presione **entrar**.</span><span class="sxs-lookup"><span data-stu-id="8c31c-111">When complete, type *dsregcmd /join* and press **Enter**.</span></span>
- <span data-ttu-id="8c31c-112">Cuando termine, cierre el símbolo del sistema.</span><span class="sxs-lookup"><span data-stu-id="8c31c-112">When complete, close the command prompt.</span></span>
- <span data-ttu-id="8c31c-113">Reinicie el equipo e inicie sesión en OneDrive.</span><span class="sxs-lookup"><span data-stu-id="8c31c-113">Reboot the computer, and log into OneDrive.</span></span>