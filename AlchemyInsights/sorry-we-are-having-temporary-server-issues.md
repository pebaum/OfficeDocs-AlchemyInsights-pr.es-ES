---
title: Solución de las aplicaciones de Office el mensaje de problemas del servidor temporal es
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3420"
- "9001430"
ms.openlocfilehash: a1ac62f3587e318d563cfea1df8db23b720358a6
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43764134"
---
# <a name="fixing-the-office-apps-sorry-we-are-having-temporary-server-issues-message"></a><span data-ttu-id="8463a-102">Corrección de las aplicaciones de Office mensaje "lo sentimos, con problemas de servidor temporales"</span><span class="sxs-lookup"><span data-stu-id="8463a-102">Fixing the Office apps "Sorry, we are having temporary server issues" message</span></span>

<span data-ttu-id="8463a-103">Si recibe este mensaje, pruebe lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="8463a-103">If you receive this message, try the following:</span></span>

1. <span data-ttu-id="8463a-104">Compruebe el firewall, el software antivirus y la configuración de proxy para confirmar que no están bloqueando el acceso a Internet a las aplicaciones de Office.</span><span class="sxs-lookup"><span data-stu-id="8463a-104">Check your firewall, antivirus software, and proxy settings to confirm that they are not blocking Internet access to Office apps.</span></span> <span data-ttu-id="8463a-105">Consulte [direcciones URL e intervalos de direcciones IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span><span class="sxs-lookup"><span data-stu-id="8463a-105">See [URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span></span>

2. <span data-ttu-id="8463a-106">Vaya a **Inicio** > **Ejecutar**y, a continuación, escriba **Services. msc**.</span><span class="sxs-lookup"><span data-stu-id="8463a-106">Go to **Start** > **Run**, and then type **services.msc**.</span></span> <span data-ttu-id="8463a-107">Asegúrese de que se están ejecutando todos los servicios siguientes:</span><span class="sxs-lookup"><span data-stu-id="8463a-107">Make sure that the following services are all running:</span></span>
    - <span data-ttu-id="8463a-108">Configuración automática de dispositivos conectados a la red</span><span class="sxs-lookup"><span data-stu-id="8463a-108">Network Connected Devices Auto-Setup</span></span>
    - <span data-ttu-id="8463a-109">Servicio de lista de redes</span><span class="sxs-lookup"><span data-stu-id="8463a-109">Network List Service</span></span>
    - <span data-ttu-id="8463a-110">Reconocimiento de ubicación de red</span><span class="sxs-lookup"><span data-stu-id="8463a-110">Network Location Awareness</span></span>
    - <span data-ttu-id="8463a-111">Registro de eventos de Windows</span><span class="sxs-lookup"><span data-stu-id="8463a-111">Windows Event Log</span></span>

<span data-ttu-id="8463a-112">Si uno de estos servicios no se está ejecutando, intente iniciarlo.</span><span class="sxs-lookup"><span data-stu-id="8463a-112">If one of these services is not running, try to start it.</span></span> <span data-ttu-id="8463a-113">Si tiene un problema para iniciar el servicio, ejecute el siguiente comando abriendo un símbolo del sistema con permisos elevados:</span><span class="sxs-lookup"><span data-stu-id="8463a-113">If you have a problem starting the service, run the following command by opening a command prompt with elevated permissions:</span></span>

<span data-ttu-id="8463a-114">**SFC/scannow**</span><span class="sxs-lookup"><span data-stu-id="8463a-114">**sfc /scannow**</span></span>

<span data-ttu-id="8463a-115">Una vez finalizado este comando, reinicie el equipo.</span><span class="sxs-lookup"><span data-stu-id="8463a-115">After this command finishes, restart the computer.</span></span>

<span data-ttu-id="8463a-116">Para obtener información detallada, consulte ["lo sentimos, no podemos conectarnos a su cuenta. Intente de nuevo más tarde "al activar](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span><span class="sxs-lookup"><span data-stu-id="8463a-116">For detailed information, see ["Sorry, we can't connect to your account. Please try again later" error when you activate](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span></span>