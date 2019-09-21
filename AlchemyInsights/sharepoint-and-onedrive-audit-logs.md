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
ms.openlocfilehash: af5b3c76b82db13bc89c917247e41fa1d8779b68
ms.sourcegitcommit: d5bf97a0bf0547f36b6da9684ce9f16a13a7749e
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/20/2019
ms.locfileid: "37068040"
---
# <a name="sharepoint-and-onedrive-audit-logs"></a><span data-ttu-id="dd8b8-102">Registros de auditoría de SharePoint y OneDrive</span><span class="sxs-lookup"><span data-stu-id="dd8b8-102">SharePoint and OneDrive audit logs</span></span>

<span data-ttu-id="dd8b8-103">**Registros de auditoría unificada moderna de SharePoint y OneDrive desde el cumplimiento**</span><span class="sxs-lookup"><span data-stu-id="dd8b8-103">**SharePoint and OneDrive Modern Unified Audit logs from compliance**</span></span>

- [<span data-ttu-id="dd8b8-104">Activar/desactivar el registro de auditoría unificado</span><span class="sxs-lookup"><span data-stu-id="dd8b8-104">Turn on/off Unified Audit Logging</span></span>](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off) 

<span data-ttu-id="dd8b8-105">No se requiere ninguna configuración adicional dentro de SharePoint o OneDrive.</span><span class="sxs-lookup"><span data-stu-id="dd8b8-105">No additional configuration is required within SharePoint or OneDrive.</span></span>

- <span data-ttu-id="dd8b8-106">Use la búsqueda de registro de auditoría para comprobar la actividad de los archivos, carpetas, usuarios y permisos:</span><span class="sxs-lookup"><span data-stu-id="dd8b8-106">Use audit logging search to check activity of the file(s), folder(s), user(s), permissions:</span></span>

    - [<span data-ttu-id="dd8b8-107">Actividades de archivo y página</span><span class="sxs-lookup"><span data-stu-id="dd8b8-107">File and page activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)
    - [<span data-ttu-id="dd8b8-108">Actividades de carpeta</span><span class="sxs-lookup"><span data-stu-id="dd8b8-108">Folder activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#folder-activities)
    - [<span data-ttu-id="dd8b8-109">Actividades de solicitud de acceso y uso compartido</span><span class="sxs-lookup"><span data-stu-id="dd8b8-109">Sharing and access request activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
    - [<span data-ttu-id="dd8b8-110">Actividades de sincronización</span><span class="sxs-lookup"><span data-stu-id="dd8b8-110">Synchronization activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
    - [<span data-ttu-id="dd8b8-111">Actividades de administración del sitio</span><span class="sxs-lookup"><span data-stu-id="dd8b8-111">Site administration activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)
- <span data-ttu-id="dd8b8-112">Para obtener más información acerca de cómo recuperar estos eventos, vea [Buscar en el registro de auditoría](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span><span class="sxs-lookup"><span data-stu-id="dd8b8-112">For more information about how to retrieve these events, see [Search the audit log](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span></span>

<span data-ttu-id="dd8b8-113">**Registros de auditoría clásicas de SharePoint**</span><span class="sxs-lookup"><span data-stu-id="dd8b8-113">**SharePoint classic Audit logs**</span></span>

<span data-ttu-id="dd8b8-114">Migramos la auditoría heredada de SPO a un registro de auditoría unificado (UAL).</span><span class="sxs-lookup"><span data-stu-id="dd8b8-114">We migrated SPO legacy auditing to Unified Audit Log (UAL).</span></span> <span data-ttu-id="dd8b8-115">Básicamente, esto significa que todos los informes de auditoría de SPO heredados ahora se encenderán a través de UAL y las señales de auditoría heredadas se han migrado a UAL.</span><span class="sxs-lookup"><span data-stu-id="dd8b8-115">This essentially means that all SPO legacy audit reports will now be powered through UAL, and the legacy audit signals have been migrated to UAL.</span></span>

<span data-ttu-id="dd8b8-116">Cambios clave:</span><span class="sxs-lookup"><span data-stu-id="dd8b8-116">Key changes:</span></span>

- <span data-ttu-id="dd8b8-117">NO se puede recortar como capacidad.</span><span class="sxs-lookup"><span data-stu-id="dd8b8-117">Trimming as a capability is NOT available.</span></span>
- <span data-ttu-id="dd8b8-118">La sección en la que puede elegir eventos específicos para auditar no está disponible.</span><span class="sxs-lookup"><span data-stu-id="dd8b8-118">The section where you choose specific events to audit is NOT available.</span></span> <span data-ttu-id="dd8b8-119">Consulte [este documento](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) para obtener una lista completa de los eventos auditados disponibles de forma predeterminada.</span><span class="sxs-lookup"><span data-stu-id="dd8b8-119">Please refer to [this document](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) for a complete list of audited events available by default.</span></span>
- <span data-ttu-id="dd8b8-120">La opción "ubicación" en **informes personalizados** no está disponible.</span><span class="sxs-lookup"><span data-stu-id="dd8b8-120">The "Location" option under **Customized reports** is NOT available.</span></span> 
- <span data-ttu-id="dd8b8-121">Los eventos "abrir o descargar documentos" no están disponibles.</span><span class="sxs-lookup"><span data-stu-id="dd8b8-121">“Opening or downloading documents” events is NOT available.</span></span> 

