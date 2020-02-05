---
title: Retrasos en la recepción de alertas de SharePoint y OneDrive
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 02/04/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "2642"
ms.openlocfilehash: 0bc9f614047e06e8654a9b3ff64e87427f33139f
ms.sourcegitcommit: 317eeed39c7777a922442992d67733726c41d9e1
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/04/2020
ms.locfileid: "41771232"
---
# <a name="delays-in-receiving-sharepoint-and-onedrive-alerts"></a><span data-ttu-id="e33cb-102">Retrasos en la recepción de alertas de SharePoint y OneDrive</span><span class="sxs-lookup"><span data-stu-id="e33cb-102">Delays in receiving SharePoint and OneDrive alerts</span></span>

- <span data-ttu-id="e33cb-103">Compruebe primero la carpeta de correo no deseado o no deseado en el correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="e33cb-103">First check the Junk or Spam folder in your email.</span></span>
- <span data-ttu-id="e33cb-104">Si **se retrasan todas las alertas de varios archivos o bibliotecas**, visite el [Panel de estado del servicio](https://nam06.safelinks.protection.outlook.com/?url=https://admin.microsoft.com/AdminPortal/Home%23/servicehealth&data=02%7c01%7cv-todmc%40microsoft.com%7c2cd2037aa7304711d2bc08d741fae254%7c72f988bf86f141af91ab2d7cd011db47%7c1%7c0%7c637050418099632638&sdata=35FUOTleK0Sc0z%2B7N7Vm0tOgXplyeOe3LcIzqRziGXc%3D&reserved=0) para comprobar si hay algún asesor o incidente que pueda estar ocurriendo con SharePoint o Exchange.</span><span class="sxs-lookup"><span data-stu-id="e33cb-104">If **all alerts from multiple files or libraries are delayed**, visit the [Service Health dashboard](https://nam06.safelinks.protection.outlook.com/?url=https://admin.microsoft.com/AdminPortal/Home%23/servicehealth&data=02%7c01%7cv-todmc%40microsoft.com%7c2cd2037aa7304711d2bc08d741fae254%7c72f988bf86f141af91ab2d7cd011db47%7c1%7c0%7c637050418099632638&sdata=35FUOTleK0Sc0z%2B7N7Vm0tOgXplyeOe3LcIzqRziGXc%3D&reserved=0) to check for any advisories/incidents that may be occurring with SharePoint or Exchange.</span></span> <span data-ttu-id="e33cb-105">El problema puede deberse a la capacidad de alerta de SharePoint o a los retrasos en los correos electrónicos a través de Exchange.</span><span class="sxs-lookup"><span data-stu-id="e33cb-105">The issue might be with the SharePoint alert capability or delays in emails through Exchange.</span></span> <span data-ttu-id="e33cb-106">Además, tenga en cuenta si se está entregando otro correo electrónico (si no es así, es probable que el problema se produzca con retrasos de Exchange).</span><span class="sxs-lookup"><span data-stu-id="e33cb-106">Also note whether other email is being delivered—if not, the issue is likely with Exchange delays.</span></span>
- <span data-ttu-id="e33cb-107">Si **no se entrega una alerta individual de un archivo o biblioteca específicos**, intente eliminarla y volver a crearla.</span><span class="sxs-lookup"><span data-stu-id="e33cb-107">If **an individual alert from a specific file or library is not delivered**, attempt to delete and recreate it.</span></span> <span data-ttu-id="e33cb-108">Consulte [administrar, ver o eliminar alertas de SharePoint](https://nam06.safelinks.protection.outlook.com/?url=https://support.office.com/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2?ui%3Den-US%26rs%3D%26ad%3DUS%23ID0EAADAAA%3DOnline&data=02%7c01%7cv-todmc%40microsoft.com%7c2cd2037aa7304711d2bc08d741fae254%7c72f988bf86f141af91ab2d7cd011db47%7c1%7c0%7c637050418099632638&sdata=AkE%2BjiG6%2BA59llp2DGcg4uHHUjaUDUnAlK5ax/epn3E%3D&reserved=0) para volver a crear la alerta.</span><span class="sxs-lookup"><span data-stu-id="e33cb-108">See [Manage, view, or delete SharePoint alerts](https://nam06.safelinks.protection.outlook.com/?url=https://support.office.com/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2?ui%3Den-US%26rs%3D%26ad%3DUS%23ID0EAADAAA%3DOnline&data=02%7c01%7cv-todmc%40microsoft.com%7c2cd2037aa7304711d2bc08d741fae254%7c72f988bf86f141af91ab2d7cd011db47%7c1%7c0%7c637050418099632638&sdata=AkE%2BjiG6%2BA59llp2DGcg4uHHUjaUDUnAlK5ax/epn3E%3D&reserved=0) to recreate the alert.</span></span>

> [!NOTE]
> - <span data-ttu-id="e33cb-109">No se pueden enviar alertas a un grupo de distribución.</span><span class="sxs-lookup"><span data-stu-id="e33cb-109">Alerts cannot be sent to a Distribution Group.</span></span> <span data-ttu-id="e33cb-110">Solo se admiten los grupos de seguridad y de O365.</span><span class="sxs-lookup"><span data-stu-id="e33cb-110">Only Security and O365 groups are supported.</span></span>
> - <span data-ttu-id="e33cb-111">No puede personalizar las plantillas de correo electrónico de alerta.</span><span class="sxs-lookup"><span data-stu-id="e33cb-111">You cannot customize alert email templates.</span></span> <span data-ttu-id="e33cb-112">Debe usar el flujo de trabajo de Microsoft Flow o SharePoint Designer para conseguirlos.</span><span class="sxs-lookup"><span data-stu-id="e33cb-112">You must use Microsoft Flow or SharePoint Designer Workflow to achieve those.</span></span>
