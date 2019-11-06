---
title: Informes de registro de auditoría de SharePoint clásicos
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1372"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: be95034bea3c58a4fde96cfb0f9ba525e810758e
ms.sourcegitcommit: 24e8248b0f061a76af50bf566d7a13fc24d29d99
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/05/2019
ms.locfileid: "37992635"
---
# <a name="sharepoint-and-onedrive-audit-logs"></a><span data-ttu-id="85a53-102">Registros de auditoría de SharePoint y OneDrive</span><span class="sxs-lookup"><span data-stu-id="85a53-102">SharePoint and OneDrive audit logs</span></span>

## <a name="sharepoint-classic-audit-logs"></a><span data-ttu-id="85a53-103">Registros de auditoría clásicas de SharePoint</span><span class="sxs-lookup"><span data-stu-id="85a53-103">SharePoint classic Audit logs</span></span>

<span data-ttu-id="85a53-104">La auditoría heredada de SPO se migró al registro de auditoría unificado (UAL).</span><span class="sxs-lookup"><span data-stu-id="85a53-104">SPO legacy auditing was migrated to Unified Audit Log (UAL).</span></span> <span data-ttu-id="85a53-105">Ahora, todos los informes de auditoría de SPO heredados se encenderán a través de UAL y las señales de auditoría heredadas se han migrado a UAL.</span><span class="sxs-lookup"><span data-stu-id="85a53-105">All SPO legacy audit reports will now be powered through UAL, and the legacy audit signals have been migrated to UAL.</span></span>

<span data-ttu-id="85a53-106">Cambios clave:</span><span class="sxs-lookup"><span data-stu-id="85a53-106">Key changes:</span></span>

* <span data-ttu-id="85a53-107">El recorte no está disponible como función.</span><span class="sxs-lookup"><span data-stu-id="85a53-107">Trimming is NOT available as a capability.</span></span>
* <span data-ttu-id="85a53-108">La elección de eventos específicos para auditar no está disponible.</span><span class="sxs-lookup"><span data-stu-id="85a53-108">Choosing specific events to audit is NOT available.</span></span> <span data-ttu-id="85a53-109">Consulte [este documento](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) para obtener una lista completa de los eventos auditados disponibles de forma predeterminada.</span><span class="sxs-lookup"><span data-stu-id="85a53-109">Refer to [this document](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) for a complete list of audited events available by default.</span></span>
* <span data-ttu-id="85a53-110">La opción **Ubicación** en **informes personalizados** no está disponible.</span><span class="sxs-lookup"><span data-stu-id="85a53-110">The **Location** option under **Customized reports** is NOT available.</span></span>
* <span data-ttu-id="85a53-111">La opción **abrir o descargar** los eventos de documentos no está disponible.</span><span class="sxs-lookup"><span data-stu-id="85a53-111">The **Opening or downloading documents** events option is NOT available.</span></span>

[<span data-ttu-id="85a53-112">Configurar las opciones de auditoría para una colección de sitios</span><span class="sxs-lookup"><span data-stu-id="85a53-112">Configure Audit settings for a site collection</span></span>](https://support.office.com/article/Configure-audit-settings-for-a-site-collection-A9920C97-38C0-44F2-8BCB-4CF1E2AE22D2)

## <a name="sharepoint-and-onedrive-modern-unified-audit-logs-from-compliance"></a><span data-ttu-id="85a53-113">Registros de auditoría unificada moderna de SharePoint y OneDrive desde el cumplimiento</span><span class="sxs-lookup"><span data-stu-id="85a53-113">SharePoint and OneDrive Modern Unified Audit logs from compliance</span></span>

* [<span data-ttu-id="85a53-114">Activar/desactivar el registro de auditoría unificado</span><span class="sxs-lookup"><span data-stu-id="85a53-114">Turn on/off Unified Audit Logging</span></span>](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off) 

<span data-ttu-id="85a53-115">No se requiere ninguna configuración adicional dentro de SharePoint o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="85a53-115">No additional configuration is required within SharePoint or OneDrive.</span></span>

<span data-ttu-id="85a53-116">Use la búsqueda de registro de auditoría para comprobar la actividad de los archivos, carpetas, usuarios y permisos:</span><span class="sxs-lookup"><span data-stu-id="85a53-116">Use audit logging search to check activity of the file(s), folder(s), user(s), permissions:</span></span>

* [<span data-ttu-id="85a53-117">Actividades de archivo y página</span><span class="sxs-lookup"><span data-stu-id="85a53-117">File and page activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)
* [<span data-ttu-id="85a53-118">Actividades de carpeta</span><span class="sxs-lookup"><span data-stu-id="85a53-118">Folder activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#folder-activities)
* [<span data-ttu-id="85a53-119">Actividades de solicitud de acceso y uso compartido</span><span class="sxs-lookup"><span data-stu-id="85a53-119">Sharing and access request activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
* [<span data-ttu-id="85a53-120">Actividades de sincronización</span><span class="sxs-lookup"><span data-stu-id="85a53-120">Synchronization activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
* [<span data-ttu-id="85a53-121">Actividades de administración del sitio</span><span class="sxs-lookup"><span data-stu-id="85a53-121">Site administration activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)

<span data-ttu-id="85a53-122">Para obtener más información acerca de cómo recuperar estos eventos, vea [Buscar en el registro de auditoría](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span><span class="sxs-lookup"><span data-stu-id="85a53-122">For more information about how to retrieve these events, see [Search the audit log](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span></span>
