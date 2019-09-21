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
# <a name="sharepoint-and-onedrive-audit-logs"></a>Registros de auditoría de SharePoint y OneDrive

**Registros de auditoría unificada moderna de SharePoint y OneDrive desde el cumplimiento**

- [Activar/desactivar el registro de auditoría unificado](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off) 

No se requiere ninguna configuración adicional dentro de SharePoint o OneDrive.

- Use la búsqueda de registro de auditoría para comprobar la actividad de los archivos, carpetas, usuarios y permisos:

    - [Actividades de archivo y página](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)
    - [Actividades de carpeta](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#folder-activities)
    - [Actividades de solicitud de acceso y uso compartido](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
    - [Actividades de sincronización](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
    - [Actividades de administración del sitio](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)
- Para obtener más información acerca de cómo recuperar estos eventos, vea [Buscar en el registro de auditoría](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).

**Registros de auditoría clásicas de SharePoint**

Migramos la auditoría heredada de SPO a un registro de auditoría unificado (UAL). Básicamente, esto significa que todos los informes de auditoría de SPO heredados ahora se encenderán a través de UAL y las señales de auditoría heredadas se han migrado a UAL.

Cambios clave:

- NO se puede recortar como capacidad.
- La sección en la que puede elegir eventos específicos para auditar no está disponible. Consulte [este documento](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) para obtener una lista completa de los eventos auditados disponibles de forma predeterminada.
- La opción "ubicación" en **informes personalizados** no está disponible. 
- Los eventos "abrir o descargar documentos" no están disponibles. 

