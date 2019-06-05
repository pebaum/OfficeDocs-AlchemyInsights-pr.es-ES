---
title: Limitación de SharePoint Online
ms.author: kirks
author: Techwriter40
ms.date: 9/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.openlocfilehash: 620a1094c1926b2c095c057a1791aaed8383afb3
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/04/2019
ms.locfileid: "34716943"
---
# <a name="sharepoint-online-throttling"></a><span data-ttu-id="24d2b-102">Limitación de SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="24d2b-102">SharePoint Online Throttling</span></span>

<p><span data-ttu-id="24d2b-103"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Es posible que los usuarios reciban un error de un servidor de 503 al intentar navegar a sitios de SharePoint o de OneDrive.</span></span><span class="sxs-lookup"><span data-stu-id="24d2b-103"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Users may receive a 503 server is busy error when attempting to navigate to Sharepoint or OneDrive sites. </span></span></span></p> <p><span data-ttu-id="24d2b-104"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Este error puede deberse a una limitación en el servicio de SharePoint. SharePoint Online usa la limitación para mantener el rendimiento y la confiabilidad óptimos del servicio de SharePoint Online. La limitación limita el número de acciones de usuario o llamadas simultáneas (por secuencia de comandos o código) para evitar el uso excesivo de los recursos. Si obtiene el límite, el 99% del tiempo es debido al código personalizado.</span></span><span class="sxs-lookup"><span data-stu-id="24d2b-104"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">This error can be caused by throttling within the Sharepoint service. SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service. Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources. If you do get throttled, 99% of the time it is because of custom code.</span></span></span></p> <p><span data-ttu-id="24d2b-105"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Para obtener más información sobre la limitación de peticiones, consulte <a href="https://docs.microsoft.com/en-us/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online">limitar o bloqueado en SharePoint Online</a>.</span></span><span class="sxs-lookup"><span data-stu-id="24d2b-105"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">For more information on throttling see, <a href="https://docs.microsoft.com/en-us/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online">Avoid getting throttled or blocked in SharePoint Online</a>.</span></span></span></p> <p><span data-ttu-id="24d2b-106"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Si cree que este error no está relacionado con la limitación, puede comprobar si hay mantenimiento activo en su espacio empresarial desplazándose al <a href="https://portal.office.com/adminportal/home#/MessageCenter">centro de mensajes</a>. Por último, asegúrese de visitar la página de <a href="https://portal.office.com/adminportal/home#/servicehealth">Estado del servicio</a> para comprobar si hay algún asesor o incidente que pueda producirse.</span></span><span class="sxs-lookup"><span data-stu-id="24d2b-106"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">If you believe this error is unrelated to throttling, you can check if there is active maintenance occurring on your tenant by navigating to the <a href="https://portal.office.com/adminportal/home#/MessageCenter">Message center</a>. Finally , ensure you visit the <a href="https://portal.office.com/adminportal/home#/servicehealth">Service Health</a> page to check for any advisories/incidents that may be occurring.</span></span></span></p> <p>&nbsp;</p>


