---
title: 'Problemas de rendimiento: SharePoint o OneDrive'
ms.author: pebaum
author: Techwriter40
ms.date: 1/3/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.openlocfilehash: 7e218cfff81274cd16d55dec2c5243eb8b74a3b7
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2019
ms.locfileid: "36750573"
---
# <a name="sharepoint-or-onedrive-slow-inaccessible-or-unavailable-for-multiple-users"></a>SharePoint o OneDrive son lentos, inaccesibles o no disponibles para varios usuarios

Si un sitio de OneDrive o SharePoint no está disponible para varios usuarios que anteriormente tenían acceso, es posible que haya un problema de servicio temporal. [Compruebe el panel de estado del servicio](https://portal.office.com/adminportal/home#/servicehealth).

**Agregar y conceder una licencia al usuario**

Asegúrese de [asignar licencias a usuarios en Office 365 para empresas](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).


**Asignar permisos**

Si al usuario se le ha asignado una licencia de SharePoint y sigue recibiendo un mensaje de acceso denegado, asegúrese de que tiene asignado el [nivel de permisos adecuado](https://docs.microsoft.com/sharepoint/understanding-permission-levels) .

**Considerar el uso de la característica de solicitud de acceso**

La [característica de solicitud de acceso](https://support.office.com/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) permite que las personas soliciten acceso al contenido que actualmente no tiene permiso para ver.

**Permitir el script personalizado puede provocar problemas de denegación de acceso**

Hay algunos escenarios en los que la característica *permitir scripts personalizados* puede presentar un acceso denegado. Para obtener una lista de características afectadas, consideraciones de seguridad y la posibilidad de deshabilitar la característica. Visite [permitir o impedir scripts personalizados](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).

