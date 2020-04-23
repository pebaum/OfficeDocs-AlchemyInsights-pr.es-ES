---
title: Retrasos en la recepción de alertas de SharePoint y OneDrive
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "2642"
ms.openlocfilehash: fb7ab6e8139c46d89b1cae1ee0ab9b9a601c8b64
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43742018"
---
# <a name="delays-in-receiving-sharepoint-and-onedrive-alerts"></a><span data-ttu-id="b2cbc-102">Retrasos en la recepción de alertas de SharePoint y OneDrive</span><span class="sxs-lookup"><span data-stu-id="b2cbc-102">Delays in receiving SharePoint and OneDrive alerts</span></span>

- <span data-ttu-id="b2cbc-103">Compruebe primero la carpeta de correo no deseado o no deseado en el correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="b2cbc-103">First check the Junk or Spam folder in your email.</span></span>
- <span data-ttu-id="b2cbc-104">Si **se retrasan todas las alertas de varios archivos o bibliotecas**, visite el [Panel de estado del servicio](https://portal.office.com/adminportal/home?ref=/servicehealth) para comprobar si hay algún asesor o incidente que pueda estar ocurriendo con SharePoint o Exchange.</span><span class="sxs-lookup"><span data-stu-id="b2cbc-104">If **all alerts from multiple files or libraries are delayed**, visit the [Service Health dashboard](https://portal.office.com/adminportal/home?ref=/servicehealth) to check for any advisories/incidents that may be occurring with SharePoint or Exchange.</span></span> <span data-ttu-id="b2cbc-105">El problema puede deberse a la capacidad de alerta de SharePoint o a los retrasos en los correos electrónicos a través de Exchange.</span><span class="sxs-lookup"><span data-stu-id="b2cbc-105">The issue might be with the SharePoint alert capability or delays in emails through Exchange.</span></span> <span data-ttu-id="b2cbc-106">Además, tenga en cuenta si se está entregando otro correo electrónico (si no es así, es probable que el problema se produzca con retrasos de Exchange).</span><span class="sxs-lookup"><span data-stu-id="b2cbc-106">Also note whether other email is being delivered—if not, the issue is likely with Exchange delays.</span></span>
- <span data-ttu-id="b2cbc-107">Si **no se entrega una alerta individual de un archivo o biblioteca específicos**, intente eliminarla y volver a crearla.</span><span class="sxs-lookup"><span data-stu-id="b2cbc-107">If **an individual alert from a specific file or library is not delivered**, attempt to delete and recreate it.</span></span> <span data-ttu-id="b2cbc-108">Consulte [administrar, ver o eliminar alertas de SharePoint](https://support.microsoft.com/office/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2) para volver a crear la alerta.</span><span class="sxs-lookup"><span data-stu-id="b2cbc-108">See [Manage, view, or delete SharePoint alerts](https://support.microsoft.com/office/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2) to recreate the alert.</span></span>

> [!NOTE]
> - <span data-ttu-id="b2cbc-109">No se pueden enviar alertas a un grupo de distribución.</span><span class="sxs-lookup"><span data-stu-id="b2cbc-109">Alerts cannot be sent to a Distribution Group.</span></span> <span data-ttu-id="b2cbc-110">Solo se admiten los grupos de seguridad y de O365.</span><span class="sxs-lookup"><span data-stu-id="b2cbc-110">Only Security and O365 groups are supported.</span></span>
> - <span data-ttu-id="b2cbc-111">No puede personalizar las plantillas de correo electrónico de alerta.</span><span class="sxs-lookup"><span data-stu-id="b2cbc-111">You cannot customize alert email templates.</span></span> <span data-ttu-id="b2cbc-112">Debe usar el flujo de trabajo de Microsoft Flow o SharePoint Designer para conseguirlos.</span><span class="sxs-lookup"><span data-stu-id="b2cbc-112">You must use Microsoft Flow or SharePoint Designer Workflow to achieve those.</span></span>
