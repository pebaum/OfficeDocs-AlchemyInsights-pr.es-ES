---
title: No recibir alertas de SharePoint y OneDrive
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 9/25/19
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "2642"
ms.openlocfilehash: 80423791ad558fc414d50608c73f823036432e14
ms.sourcegitcommit: 5e6a805fb0b41d714ca1cf90e23b8e2daa90f90e
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/26/2019
ms.locfileid: "37205557"
---
# <a name="not-receiving-sharepoint-and-onedrive-alerts"></a><span data-ttu-id="4b9e7-102">No recibir alertas de SharePoint y OneDrive</span><span class="sxs-lookup"><span data-stu-id="4b9e7-102">Not receiving SharePoint and OneDrive alerts</span></span>

<span data-ttu-id="4b9e7-103">Compruebe primero la carpeta de correo no deseado o no deseado en el correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="4b9e7-103">First check the Junk or Spam folder in your email.</span></span>

<span data-ttu-id="4b9e7-104">A continuación, determine si no **se entregan todas las alertas** o si no se entrega **una alerta individual** de un archivo o biblioteca específicos.</span><span class="sxs-lookup"><span data-stu-id="4b9e7-104">Then determine if **all alerts are not delivered** or if **an individual alert** from a specific file or library is not delivered.</span></span>

- <span data-ttu-id="4b9e7-105">Si **no se entregan todas las alertas de varios archivos o bibliotecas**, visite el [Panel de estado del servicio](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fadmin.microsoft.com%2FAdminPortal%2FHome%23%2Fservicehealth&data=02%7C01%7Cv-todmc%40microsoft.com%7C2cd2037aa7304711d2bc08d741fae254%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C637050418099632638&sdata=35FUOTleK0Sc0z%2B7N7Vm0tOgXplyeOe3LcIzqRziGXc%3D&reserved=0) para comprobar si hay algún asesor o incidente que pueda estar ocurriendo con SharePoint o Exchange.</span><span class="sxs-lookup"><span data-stu-id="4b9e7-105">If **all alerts from multiple files or libraries are not delivered**, visit the [Service Health dashboard](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fadmin.microsoft.com%2FAdminPortal%2FHome%23%2Fservicehealth&data=02%7C01%7Cv-todmc%40microsoft.com%7C2cd2037aa7304711d2bc08d741fae254%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C637050418099632638&sdata=35FUOTleK0Sc0z%2B7N7Vm0tOgXplyeOe3LcIzqRziGXc%3D&reserved=0) to check for any advisories/incidents that may be occurring with SharePoint or Exchange.</span></span> <span data-ttu-id="4b9e7-106">El problema puede deberse a la capacidad de alerta de SharePoint o a los retrasos en los correos electrónicos a través de Exchange.</span><span class="sxs-lookup"><span data-stu-id="4b9e7-106">The issue might be with the SharePoint alert capability or delays in emails through Exchange.</span></span> <span data-ttu-id="4b9e7-107">Además, tenga en cuenta si se está entregando otro correo electrónico (si no es así, es probable que el problema se produzca con retrasos de Exchange).</span><span class="sxs-lookup"><span data-stu-id="4b9e7-107">Also note whether other email is being delivered—if not, the issue is likely with Exchange delays.</span></span>
- <span data-ttu-id="4b9e7-108">Si **no se entrega una alerta individual de un archivo o biblioteca específicos**, intente eliminarla y volver a crearla.</span><span class="sxs-lookup"><span data-stu-id="4b9e7-108">If **an individual alert from a specific file or library is not delivered**, attempt to delete and recreate it.</span></span> <span data-ttu-id="4b9e7-109">Consulte [administrar, ver o eliminar alertas de SharePoint](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsupport.office.com%2Farticle%2Fmanage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2%3Fui%3Den-US%26rs%3D%26ad%3DUS%23ID0EAADAAA%3DOnline&data=02%7C01%7Cv-todmc%40microsoft.com%7C2cd2037aa7304711d2bc08d741fae254%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C637050418099632638&sdata=AkE%2BjiG6%2BA59llp2DGcg4uHHUjaUDUnAlK5ax%2Fepn3E%3D&reserved=0) para volver a crear la alerta.</span><span class="sxs-lookup"><span data-stu-id="4b9e7-109">See [Manage, view, or delete SharePoint alerts](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsupport.office.com%2Farticle%2Fmanage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2%3Fui%3Den-US%26rs%3D%26ad%3DUS%23ID0EAADAAA%3DOnline&data=02%7C01%7Cv-todmc%40microsoft.com%7C2cd2037aa7304711d2bc08d741fae254%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C637050418099632638&sdata=AkE%2BjiG6%2BA59llp2DGcg4uHHUjaUDUnAlK5ax%2Fepn3E%3D&reserved=0) to recreate the alert.</span></span>

> [!NOTE]
> - <span data-ttu-id="4b9e7-110">No se pueden enviar alertas a un grupo de distribución.</span><span class="sxs-lookup"><span data-stu-id="4b9e7-110">Alerts cannot be sent to a Distribution Group.</span></span> <span data-ttu-id="4b9e7-111">Solo se admiten los grupos de seguridad y de O365.</span><span class="sxs-lookup"><span data-stu-id="4b9e7-111">Only Security and O365 groups are supported.</span></span>
> - <span data-ttu-id="4b9e7-112">No puede personalizar las plantillas de correo electrónico de alerta.</span><span class="sxs-lookup"><span data-stu-id="4b9e7-112">You cannot customize alert email templates.</span></span> <span data-ttu-id="4b9e7-113">Debe usar el flujo de trabajo de Microsoft Flow o SharePoint Designer para conseguirlos.</span><span class="sxs-lookup"><span data-stu-id="4b9e7-113">You must use Microsoft Flow or SharePoint Designer Workflow to achieve those.</span></span>
