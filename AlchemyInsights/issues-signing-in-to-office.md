---
title: Problemas al iniciar sesión en las aplicaciones de Office
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000571"
- "2556"
ms.openlocfilehash: 08bb0a94066f071f2ba0e9c54378f0d479191496
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938351"
---
# <a name="blank-sign-in-screen-in-office-apps"></a><span data-ttu-id="887e8-102">Pantalla de inicio de sesión en blanco en las aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="887e8-102">Blank sign-in screen in Office apps</span></span>

<span data-ttu-id="887e8-103">Para solucionar este problema, pruebe lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="887e8-103">To fix this issue, try the following:</span></span>
- <span data-ttu-id="887e8-104">Instale las actualizaciones más recientes para [Windows](https://support.microsoft.com/help/4027667/windows-10-update) y [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span><span class="sxs-lookup"><span data-stu-id="887e8-104">Install the latest updates for [Windows](https://support.microsoft.com/help/4027667/windows-10-update) and [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span></span>
- <span data-ttu-id="887e8-105">Restablecer opciones de Internet Explorer: vaya a **herramientas** > **Opciones** > de Internet**avanzada** > **restablecer configuración de Internet Explorer** (tenga en cuenta que perderá la configuración personalizada) y, a continuación, intente iniciar sesión de nuevo en Office.</span><span class="sxs-lookup"><span data-stu-id="887e8-105">Reset Internet Explorer options: Go to **Tools** > **Internet Options** > **Advanced** > **Reset Internet Explorer Settings** (note that you will lose custom settings), and then try signing in to Office again.</span></span>
- <span data-ttu-id="887e8-106">Deshabilite la protección de aplicaciones de Windows Defender (WDAG) o cualquier programa de firewall o antivirus similar:</span><span class="sxs-lookup"><span data-stu-id="887e8-106">Disable the Windows Defender Application Guard (WDAG) or any similar firewall or anti-virus program:</span></span>
    1. <span data-ttu-id="887e8-107">En el panel de control, vaya a **programas**y, a continuación, elija **activar o desactivar las características de Windows**.</span><span class="sxs-lookup"><span data-stu-id="887e8-107">In Control Panel, go to **Programs**, and then choose **Turn Windows features on or off**.</span></span>
    2. <span data-ttu-id="887e8-108">Si la protección de aplicaciones de Windows Defender está habilitada, prueba a deshabilitarla.</span><span class="sxs-lookup"><span data-stu-id="887e8-108">If Windows Defender Application Guard is enabled, try disabling it.</span></span><br/>
    <span data-ttu-id="887e8-109">**Nota:** Es posible que deba reiniciar el equipo.</span><span class="sxs-lookup"><span data-stu-id="887e8-109">**Note:** You may need to restart the computer.</span></span>
- <span data-ttu-id="887e8-110">Asegúrese de que el [complemento WAM](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-1) Microsoft. AAD. BrokerPlugin AAD no está bloqueado por ninguna aplicación o programa de firewall o antivirus.</span><span class="sxs-lookup"><span data-stu-id="887e8-110">Ensure that the Microsoft.AAD.BrokerPlugin [AAD WAM plug-in](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-1) is not being blocked by any application or firewall/anti-virus program.</span></span>
- <span data-ttu-id="887e8-111">[Borre las credenciales de Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) con el administrador de credenciales de Windows.</span><span class="sxs-lookup"><span data-stu-id="887e8-111">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="887e8-112">**Nota:** Las rutas del registro para Office 2016 han cambiado a 16,0.</span><span class="sxs-lookup"><span data-stu-id="887e8-112">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="887e8-113">(Por ejemplo: \Software\Microsoft\Office\16.0\Common\Identity\)</span><span class="sxs-lookup"><span data-stu-id="887e8-113">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>

<span data-ttu-id="887e8-114">Para obtener más información, vea [problemas de conexión en el inicio de sesión después de actualizar a Office 2016 Build 16.0.7967 en Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span><span class="sxs-lookup"><span data-stu-id="887e8-114">For more information, see [Connection issues in sign-in after update to Office 2016 build 16.0.7967 on Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span></span>