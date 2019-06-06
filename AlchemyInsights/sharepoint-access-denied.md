---
title: Solucionar problemas de mensajes de acceso denegado
ms.author: kirks
author: Techwriter40
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 5958ad06ca905f713b5f56aa5c536e95a485f01c
ms.sourcegitcommit: 241e21b6da226563bf70bdb1f5bad3d91c38cd2c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/05/2019
ms.locfileid: "34735754"
---
# <a name="troubleshoot-access-denied-messages"></a>Solucionar problemas de mensajes de acceso denegado

Si recibe un mensaje de acceso denegado al intentar examinar un sitio de SharePoint Online, vea los artículos siguientes.

## <a name="add-and-license-the-user"></a>Agregar y conceder una licencia al usuario

Asegúrese de [asignar licencias a usuarios en Office 365 para empresas](https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).

Asignar permisos

Si al usuario se le ha asignado una licencia de SharePoint y sigue recibiendo un mensaje de acceso denegado, asegúrese de que tiene [asignado el nivel de permisos adecuado](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels).

Considerar el uso de la característica de solicitud de acceso

La característica de [solicitud de acceso](https://support.office.com/en-us/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) permite que las personas soliciten acceso al contenido que actualmente no tiene permiso para ver. 

Permitir el script personalizado puede provocar problemas de denegación de acceso

Hay algunos escenarios en los que la característica "permitir secuencias de comandos personalizadas" puede presentar un acceso denegado. Para obtener una lista de características afectadas, consideraciones de seguridad y la posibilidad de deshabilitar la característica. Visite, [permita o impida el scripts personalizados](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script) .

Nota: Si un sitio de OneDrive o SharePoint no está disponible para varios usuarios que anteriormente tenían acceso, es posible que haya un problema de servicio temporal. [Compruebe el panel de estado del servicio](https://portal.office.com/adminportal/home#/servicehealth).


  

