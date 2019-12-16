---
title: Solo lectura para el mensaje de mantenimiento al intentar usar SharePoint o OneDrive
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "127"
- "128"
ms.assetid: de7b6877-f3f9-4402-8072-c73783aaccaa
ms.openlocfilehash: 02cf1aa7abae365a3d317af9e785648d1c1517e1
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/15/2019
ms.locfileid: "40051298"
---
# <a name="read-only-for-maintenance-message-when-attempting-to-use-sharepoint-or-onedrive"></a><span data-ttu-id="944e2-102">Solo lectura para el mensaje de mantenimiento al intentar usar SharePoint o OneDrive</span><span class="sxs-lookup"><span data-stu-id="944e2-102">Read-Only for Maintenance message when attempting to use SharePoint or OneDrive</span></span>

<span data-ttu-id="944e2-103">Los usuarios pueden recibir un mensaje **de solo lectura para** el mensaje de mantenimiento al intentar usar SharePoint o OneDrive para uno de los siguientes escenarios.</span><span class="sxs-lookup"><span data-stu-id="944e2-103">Users may receive a **Read-Only for Maintenance** message when attempting to use SharePoint or OneDrive for one of the following scenarios.</span></span> 

-   <span data-ttu-id="944e2-104">Una actividad de mantenimiento planificado o activo.</span><span class="sxs-lookup"><span data-stu-id="944e2-104">A planned or active maintenance activity.</span></span>  <span data-ttu-id="944e2-105">Para buscarlos, navegue hasta el [centro de mensajes](https://portal.office.com/adminportal/home#/messagecenter).</span><span class="sxs-lookup"><span data-stu-id="944e2-105">Check for them by navigating to the [Message Center](https://portal.office.com/adminportal/home#/messagecenter).</span></span>
-   <span data-ttu-id="944e2-106">Un incidente de servicio activo de alta prioridad que pueda estar ocurriendo.</span><span class="sxs-lookup"><span data-stu-id="944e2-106">A high-priority, active service incident that may be occurring.</span></span> <span data-ttu-id="944e2-107">Compruebe si hay algún asesor o incidente desplazándose al [Estado del servicio](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="944e2-107">Check for any advisories/incidents by navigating to [Service Health](https://portal.office.com/adminportal/home#/servicehealth).</span></span>
-   <span data-ttu-id="944e2-108">Un escenario de recuperación de recuperación automática secundaria que podría estar ocurriendo debido a eventos inesperados en los servidores que pueden durar menos de 30 minutos o más.</span><span class="sxs-lookup"><span data-stu-id="944e2-108">A minor auto-healing recovery scenario that could be happening due to any unexpected events on the servers which might last for less than 30 min or so.</span></span> 
    
    <span data-ttu-id="944e2-109">No existen publicaciones de estado del servicio o del centro de mensajes para estas recuperaciones menores, pero debe volver a ser normal muy pronto.</span><span class="sxs-lookup"><span data-stu-id="944e2-109">There are no Message Center or Service Health posts for these minor recoveries but you should be back to normal very soon.</span></span>

<span data-ttu-id="944e2-110">En muy pocas ocasiones observamos que uno de los tres escenarios enumerados anteriormente ha sido la causa y que se ha restaurado el servicio, pero la memoria caché del explorador de usuarios no se ha borrado.</span><span class="sxs-lookup"><span data-stu-id="944e2-110">On very few occasions we observed that one of the three scenarios listed above have been the cause, and service has been restored, but the users browser cache hasn’t been cleared up.</span></span>

<span data-ttu-id="944e2-111">Intente borrar la memoria caché del explorador antes de navegar al sitio.</span><span class="sxs-lookup"><span data-stu-id="944e2-111">Please attempt to clear the browser cache before navigating to the site.</span></span>

1. <span data-ttu-id="944e2-112">En el explorador de Microsoft Edge, selecciona **configuración**y, a continuación, haz clic en **privacidad y seguridad**.</span><span class="sxs-lookup"><span data-stu-id="944e2-112">In your Microsoft Edge browser, select **Settings**, and then select **Privacy and Security**.</span></span>
2. <span data-ttu-id="944e2-113">En **borrar la búsqueda**, seleccione **elegir lo que desea borrar**.</span><span class="sxs-lookup"><span data-stu-id="944e2-113">Under **Clear browsing**, select **Choose what to clear**.</span></span>
3. <span data-ttu-id="944e2-114">Seleccione **cookies y datos del sitio web guardados**y seleccione **Borrar**.</span><span class="sxs-lookup"><span data-stu-id="944e2-114">Select **Cookies and saved website data**, and select **Clear**.</span></span>

>[!Note] 
> <span data-ttu-id="944e2-115">Estos pasos pueden variar cuando se usan otros exploradores como Mozilla Firefox o Google Chrome.</span><span class="sxs-lookup"><span data-stu-id="944e2-115">These steps may differ when using other browsers such as Mozilla Firefox or Google Chrome.</span></span>

>[!Note] 
> <span data-ttu-id="944e2-116">Otra opción sería abrir el sitio de SharePoint o OneDrive en una nueva ventana de InPrivate.</span><span class="sxs-lookup"><span data-stu-id="944e2-116">Another option would be to open your SharePoint site or OneDrive in a new InPrivate window.</span></span>