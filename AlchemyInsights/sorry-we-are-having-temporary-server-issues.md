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
ms.openlocfilehash: 4b90f843843416408d7f3091325fe436dc3ec9df
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/27/2019
ms.locfileid: "39628007"
---
# <a name="fixing-the-office-apps-sorry-we-are-having-temporary-server-issues-message"></a><span data-ttu-id="26e63-102">Corrección de las aplicaciones de Office mensaje "lo sentimos, con problemas de servidor temporales"</span><span class="sxs-lookup"><span data-stu-id="26e63-102">Fixing the Office apps "Sorry, we are having temporary server issues" message</span></span>

<span data-ttu-id="26e63-103">Si recibe este mensaje, pruebe lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="26e63-103">If you receive this message, try the following:</span></span>

1. <span data-ttu-id="26e63-104">Compruebe el firewall, el software antivirus y la configuración de proxy para confirmar que no están bloqueando el acceso a Internet a las aplicaciones de Office.</span><span class="sxs-lookup"><span data-stu-id="26e63-104">Check your firewall, antivirus software, and proxy settings to confirm that they are not blocking Internet access to Office apps.</span></span> <span data-ttu-id="26e63-105">Consulte [Office 365 URL e intervalos de direcciones IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span><span class="sxs-lookup"><span data-stu-id="26e63-105">See [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span></span>

2. <span data-ttu-id="26e63-106">Vaya a **Inicio** > **Ejecutar**y, a continuación, escriba **Services. msc**.</span><span class="sxs-lookup"><span data-stu-id="26e63-106">Go to **Start** > **Run**, and then type **services.msc**.</span></span> <span data-ttu-id="26e63-107">Asegúrese de que se están ejecutando todos los servicios siguientes:</span><span class="sxs-lookup"><span data-stu-id="26e63-107">Make sure that the following services are all running:</span></span>
    - <span data-ttu-id="26e63-108">Configuración automática de dispositivos conectados a la red</span><span class="sxs-lookup"><span data-stu-id="26e63-108">Network Connected Devices Auto-Setup</span></span>
    - <span data-ttu-id="26e63-109">Servicio de lista de redes</span><span class="sxs-lookup"><span data-stu-id="26e63-109">Network List Service</span></span>
    - <span data-ttu-id="26e63-110">Reconocimiento de ubicación de red</span><span class="sxs-lookup"><span data-stu-id="26e63-110">Network Location Awareness</span></span>
    - <span data-ttu-id="26e63-111">Registro de eventos de Windows</span><span class="sxs-lookup"><span data-stu-id="26e63-111">Windows Event Log</span></span>

<span data-ttu-id="26e63-112">Si uno de estos servicios no se está ejecutando, intente iniciarlo.</span><span class="sxs-lookup"><span data-stu-id="26e63-112">If one of these services is not running, try to start it.</span></span> <span data-ttu-id="26e63-113">Si tiene un problema para iniciar el servicio, ejecute el siguiente comando abriendo un símbolo del sistema con permisos elevados:</span><span class="sxs-lookup"><span data-stu-id="26e63-113">If you have a problem starting the service, run the following command by opening a command prompt with elevated permissions:</span></span>

<span data-ttu-id="26e63-114">**SFC/scannow**</span><span class="sxs-lookup"><span data-stu-id="26e63-114">**sfc /scannow**</span></span>

<span data-ttu-id="26e63-115">Una vez finalizado este comando, reinicie el equipo.</span><span class="sxs-lookup"><span data-stu-id="26e63-115">After this command finishes, restart the computer.</span></span>

<span data-ttu-id="26e63-116">Para obtener información detallada, consulte ["lo sentimos, no podemos conectarnos a su cuenta. Intente de nuevo más tarde "al activar Office desde Office 365](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span><span class="sxs-lookup"><span data-stu-id="26e63-116">For detailed information, see ["Sorry, we can't connect to your account. Please try again later" error when you activate Office from Office 365](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span></span>