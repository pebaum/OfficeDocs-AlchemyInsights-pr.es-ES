---
title: 'Problema de activación: no se puede conectar ahora'
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3408"
- "9001423"
ms.openlocfilehash: 84e3a7700558ad8a5fad5b7ded6354fe8736e0f7
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/27/2019
ms.locfileid: "39628259"
---
# <a name="fixing-the-office-apps-we-are-unable-to-connect-right-now-message"></a><span data-ttu-id="e8f3c-102">Corrección del mensaje "no se puede conectar ahora de las aplicaciones de Office"</span><span class="sxs-lookup"><span data-stu-id="e8f3c-102">Fixing the Office apps "We are unable to connect right now" message</span></span>

<span data-ttu-id="e8f3c-103">Si recibe este mensaje, pruebe lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="e8f3c-103">If you receive this message, try the following:</span></span>

1. <span data-ttu-id="e8f3c-104">Compruebe el firewall, el software antivirus y la configuración de proxy para confirmar que no están bloqueando el acceso a Internet a las aplicaciones de Office.</span><span class="sxs-lookup"><span data-stu-id="e8f3c-104">Check your firewall, antivirus software, and proxy settings to confirm that they are not blocking Internet access to Office apps.</span></span> <span data-ttu-id="e8f3c-105">Consulte [Office 365 URL e intervalos de direcciones IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span><span class="sxs-lookup"><span data-stu-id="e8f3c-105">See [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span></span>

2. <span data-ttu-id="e8f3c-106">Vaya a **Inicio** > **Ejecutar**y, a continuación, escriba **Services. msc**.</span><span class="sxs-lookup"><span data-stu-id="e8f3c-106">Go to **Start** > **Run**, and then type **services.msc**.</span></span> <span data-ttu-id="e8f3c-107">Asegúrese de que se están ejecutando todos los servicios siguientes:</span><span class="sxs-lookup"><span data-stu-id="e8f3c-107">Make sure that the following services are all running:</span></span>
    - <span data-ttu-id="e8f3c-108">Configuración automática de dispositivos conectados a la red</span><span class="sxs-lookup"><span data-stu-id="e8f3c-108">Network Connected Devices Auto-Setup</span></span>
    - <span data-ttu-id="e8f3c-109">Servicio de lista de redes</span><span class="sxs-lookup"><span data-stu-id="e8f3c-109">Network List Service</span></span>
    - <span data-ttu-id="e8f3c-110">Reconocimiento de ubicación de red</span><span class="sxs-lookup"><span data-stu-id="e8f3c-110">Network Location Awareness</span></span>
    - <span data-ttu-id="e8f3c-111">Registro de eventos de Windows</span><span class="sxs-lookup"><span data-stu-id="e8f3c-111">Windows Event Log</span></span>

<span data-ttu-id="e8f3c-112">Si uno de estos servicios no se está ejecutando, intente iniciarlo.</span><span class="sxs-lookup"><span data-stu-id="e8f3c-112">If one of these services is not running, try to start it.</span></span> <span data-ttu-id="e8f3c-113">Si tiene un problema para iniciar el servicio, ejecute el siguiente comando abriendo un símbolo del sistema con permisos elevados:</span><span class="sxs-lookup"><span data-stu-id="e8f3c-113">If you have a problem starting the service, run the following command by opening a command prompt with elevated permissions:</span></span>

<span data-ttu-id="e8f3c-114">**SFC/scannow**</span><span class="sxs-lookup"><span data-stu-id="e8f3c-114">**sfc /scannow**</span></span>

<span data-ttu-id="e8f3c-115">Una vez finalizado este comando, reinicie el equipo.</span><span class="sxs-lookup"><span data-stu-id="e8f3c-115">After this command finishes, restart the computer.</span></span>

<span data-ttu-id="e8f3c-116">Para obtener información detallada, consulte ["lo sentimos, no podemos conectarnos a su cuenta. Intente de nuevo más tarde "al activar Office desde Office 365](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span><span class="sxs-lookup"><span data-stu-id="e8f3c-116">For detailed information, see ["Sorry, we can't connect to your account. Please try again later" error when you activate Office from Office 365](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span></span>