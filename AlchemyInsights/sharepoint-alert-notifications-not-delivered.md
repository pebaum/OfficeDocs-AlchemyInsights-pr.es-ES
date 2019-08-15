---
title: Notificaciones de alerta de SharePoint no entregadas
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 1/3/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "1655"
ms.openlocfilehash: e682a1b3dbd0d3a1c2e52be725dd2b57fc66109a
ms.sourcegitcommit: a2c866d2f3cdc1e18a33a5b2a4209340e83ca3c2
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/14/2019
ms.locfileid: "36404819"
---
# <a name="sharepoint-alert-notifications-not-delivered"></a><span data-ttu-id="ddf57-102">Notificaciones de alerta de SharePoint no entregadas</span><span class="sxs-lookup"><span data-stu-id="ddf57-102">SharePoint alert notifications not delivered</span></span>

<span data-ttu-id="ddf57-103">Compruebe la carpeta de correo no deseado en el correo electrónico, ya que a veces podrían pasar alertas.</span><span class="sxs-lookup"><span data-stu-id="ddf57-103">Please check the JUNK folder in your email, as sometimes alerts might go there.</span></span>

<span data-ttu-id="ddf57-104">Determine si no **se entregan todas las alertas** o si no se entrega **una alerta individual** de un archivo o biblioteca específicos.</span><span class="sxs-lookup"><span data-stu-id="ddf57-104">Determine if **all alerts are not delivered** or if **an individual alert** from a specific file or library is not delivered.</span></span>

- <span data-ttu-id="ddf57-105">**No se entregan alertas individuales**: Si no se entrega una alerta individual de un archivo o biblioteca específicos, puede intentar eliminarla y volver a crearla.</span><span class="sxs-lookup"><span data-stu-id="ddf57-105">**Individual alerts are not delivered**: If an individual alert from a specific file or library is not delivered, you can attempt to delete and recreate it.</span></span> <span data-ttu-id="ddf57-106">Consulte [administrar, ver o eliminar alertas de SharePoint](https://support.office.com/en-us/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2?ui=en-US&rs=en-US&ad=US#ID0EAADAAA=Online) para volver a crear la alerta.</span><span class="sxs-lookup"><span data-stu-id="ddf57-106">See [Manage, view, or delete SharePoint alerts](https://support.office.com/en-us/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2?ui=en-US&rs=en-US&ad=US#ID0EAADAAA=Online) to recreate the alert.</span></span>
- <span data-ttu-id="ddf57-107">**No se entregan todas las alertas**: Si no se entregan todas las alertas de varios archivos o bibliotecas, visite el [Panel de estado del servicio](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) para comprobar si hay algún asesor o incidente que pueda producirse con SharePoint o Exchange.</span><span class="sxs-lookup"><span data-stu-id="ddf57-107">**All alerts are not delivered**: If all alerts from multiple files or libraries are not delivered, visit the [Service Health dashboard](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) to check for any advisories/incidents that may be occurring with SharePoint or Exchange.</span></span> <span data-ttu-id="ddf57-108">El problema podría estar relacionado con la capacidad de alerta de SharePoint o con retrasos en los correos electrónicos a través de Exchange.</span><span class="sxs-lookup"><span data-stu-id="ddf57-108">The issue could be with the SharePoint alert capability or delays in emails through Exchange.</span></span> <span data-ttu-id="ddf57-109">También será importante tener en cuenta si se va a entregar otro correo electrónico y, de no ser así, es probable que el problema se produzca con retrasos de Exchange.</span><span class="sxs-lookup"><span data-stu-id="ddf57-109">It will also be important to note whether other email is being delivered, and if not, the issue is likely with Exchange delays.</span></span>

<span data-ttu-id="ddf57-110">Preguntas más frecuentes sobre alertas:</span><span class="sxs-lookup"><span data-stu-id="ddf57-110">FAQ on alerts:</span></span>

- <span data-ttu-id="ddf57-111">No se pueden enviar alertas a un grupo de distribución, solo se admiten los grupos de seguridad y de O365.</span><span class="sxs-lookup"><span data-stu-id="ddf57-111">It is not possible to send alerts to Distribution Group, only Security and O365 groups are supported.</span></span>
- <span data-ttu-id="ddf57-112">No puede personalizar plantillas de correo electrónico de alerta; tiene que usar Microsoft FLOW o el flujo de trabajo de SharePoint Designer para conseguirlos.</span><span class="sxs-lookup"><span data-stu-id="ddf57-112">You cannot customize alert email templates; you need to use Microsoft FLOW or SharePoint Designer Workflow to achieve those.</span></span>

<span data-ttu-id="ddf57-113">Más información:</span><span class="sxs-lookup"><span data-stu-id="ddf57-113">More Information:</span></span>

- <span data-ttu-id="ddf57-114">**Configuración de alertas**: para obtener más información sobre cómo configurar las alertas, vea [crear una alerta para recibir una notificación cuando cambia un archivo o una carpeta en SharePoint](https://support.office.com/en-us/article/create-an-alert-to-get-notified-when-a-file-or-folder-changes-in-sharepoint-e5a79e7b-a146-46da-a9ef-d65409ba8918).</span><span class="sxs-lookup"><span data-stu-id="ddf57-114">**Alert setup**: For more information about setting up alerts, see [Create an alert to get notified when a file or folder changes in SharePoint](https://support.office.com/en-us/article/create-an-alert-to-get-notified-when-a-file-or-folder-changes-in-sharepoint-e5a79e7b-a146-46da-a9ef-d65409ba8918).</span></span>
- <span data-ttu-id="ddf57-115">**Solucionar problemas de alertas**: para obtener más información sobre la solución de problemas de alertas, consulte [usuarios que no reciben notificaciones de alertas de SharePoint Online](https://docs.microsoft.com/en-us/sharepoint/support/sites/no-alert-notifications).</span><span class="sxs-lookup"><span data-stu-id="ddf57-115">**Troubleshoot alerts**: For more information about troubleshooting alerts, see [Users don't receive SharePoint Online alert notifications](https://docs.microsoft.com/en-us/sharepoint/support/sites/no-alert-notifications).</span></span>
- <span data-ttu-id="ddf57-116">**Directivas avanzadas de alertas de cumplimiento de O365**: para obtener más información acerca de cómo configurar estas alertas, consulte [directivas de alertas de cumplimiento](https://docs.microsoft.com/en-us/office365/securitycompliance/alert-policies).</span><span class="sxs-lookup"><span data-stu-id="ddf57-116">**Advanced O365 Compliance Alert Policies**: For more information about setting up these alerts, see [Compliance Alert Policies](https://docs.microsoft.com/en-us/office365/securitycompliance/alert-policies).</span></span>
- <span data-ttu-id="ddf57-117">**Registros de auditoría de SharePoint y OneDrive**: para obtener más información sobre cómo recuperar estos eventos, vea [Buscar en el registro de auditoría](https://docs.microsoft.com/en-us/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span><span class="sxs-lookup"><span data-stu-id="ddf57-117">**SharePoint and OneDrive Audit Logs**: For more information about how to retrieve these events, see [Search the audit log](https://docs.microsoft.com/en-us/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span></span>
- <span data-ttu-id="ddf57-118">**Alertas enviadas por la protección contra amenazas avanzada**: consulte [ATP para SharePoint y OneDrive](https://docs.microsoft.com/en-us/office365/securitycompliance/atp-for-spo-odb-and-teams).</span><span class="sxs-lookup"><span data-stu-id="ddf57-118">**Alerts sent by Advanced Threat Protection**: See [ATP for SharePoint and OneDrive](https://docs.microsoft.com/en-us/office365/securitycompliance/atp-for-spo-odb-and-teams).</span></span>
- <span data-ttu-id="ddf57-119">**Alertas enviadas por directivas de prevención de pérdida de datos**: consulte [notificaciones de correo electrónico para directivas de DLP](https://docs.microsoft.com/en-us/office365/securitycompliance/use-notifications-and-policy-tips).</span><span class="sxs-lookup"><span data-stu-id="ddf57-119">**Alerts sent by Data Loss Prevention polices**: See [Email notifications for DLP policies](https://docs.microsoft.com/en-us/office365/securitycompliance/use-notifications-and-policy-tips).</span></span>

## <a name="related-topics"></a><span data-ttu-id="ddf57-120">Temas relacionados</span><span class="sxs-lookup"><span data-stu-id="ddf57-120">Related Topics</span></span>

<span data-ttu-id="ddf57-121">¿Desea probar Microsoft Flow en SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="ddf57-121">Want to try Microsoft Flow in SharePoint Online?</span></span>

- [<span data-ttu-id="ddf57-122">Crear flujo</span><span class="sxs-lookup"><span data-stu-id="ddf57-122">Create Flow</span></span>](https://support.office.com/en-us/article/create-a-flow-for-a-list-or-library-in-sharepoint-online-or-onedrive-for-business-a9c3e03b-0654-46af-a254-20252e580d01)

- [<span data-ttu-id="ddf57-123">Flujo y SharePoint</span><span class="sxs-lookup"><span data-stu-id="ddf57-123">SharePoint and Flow</span></span>](https://flow.microsoft.com/en-us/blog/sharepoint-and-flow/)
