---
title: Informes de registro de auditoría de SharePoint clásicos
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1372"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 3270f1ab03bacb235cbdc3d710053c858f0a5183
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43741982"
---
# <a name="sharepoint-and-onedrive-audit-logs"></a>Registros de auditoría de SharePoint y OneDrive

## <a name="sharepoint-classic-audit-logs"></a>Registros de auditoría clásicas de SharePoint

La auditoría heredada de SPO se migró al registro de auditoría unificado (UAL). Ahora, todos los informes de auditoría de SPO heredados se encenderán a través de UAL y las señales de auditoría heredadas se han migrado a UAL.

Cambios clave:

* El recorte no está disponible como función.
* La elección de eventos específicos para auditar no está disponible. Consulte [este documento](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) para obtener una lista completa de los eventos auditados disponibles de forma predeterminada.
* La opción **Ubicación** en **informes personalizados** no está disponible.
* La opción **abrir o descargar** los eventos de documentos no está disponible.

[Configurar las opciones de auditoría para una colección de sitios](https://support.office.com/article/Configure-audit-settings-for-a-site-collection-A9920C97-38C0-44F2-8BCB-4CF1E2AE22D2)

## <a name="sharepoint-and-onedrive-modern-unified-audit-logs-from-compliance"></a>Registros de auditoría unificada moderna de SharePoint y OneDrive desde el cumplimiento

* [Activar/desactivar el registro de auditoría unificado](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off) 

No se requiere ninguna configuración adicional dentro de SharePoint o OneDrive.

Use la búsqueda de registro de auditoría para comprobar la actividad de los archivos, carpetas, usuarios y permisos:

* [Actividades de páginas y archivos](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)
* [Actividades de carpetas](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#folder-activities)
* [Actividades de solicitud de acceso y uso compartido](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
* [Actividades de sincronización](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
* [Actividades de administración del sitio](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)

Para obtener más información acerca de cómo recuperar estos eventos, vea [Buscar en el registro de auditoría](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).
