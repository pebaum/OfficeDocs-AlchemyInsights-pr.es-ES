---
title: Sitio moderno como sitio raíz
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 6166493f79379f44b1a9bbbaca6becfe624fe912
ms.sourcegitcommit: 22ce2315c8cf643137ab3420cdc1cda41433d44a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/14/2019
ms.locfileid: "34057779"
---
# <a name="modern-site-as-root-site"></a>Sitio moderno como sitio raíz

Los clientes de [versiones de destino](https://docs.microsoft.com/en-us/office365/admin/manage/release-options-in-office-365?view=o365-worldwide) ahora pueden habilitar la experiencia de sitio de comunicación moderna en el sitio raíz clásico de su espacio empresarial de SharePoint.

Esta característica se puede activar mediante la ejecución de un sencillo cmdlet de PowerShell. En la correcta ejecución de los comandos de PowerShell, el sitio raíz tendrá una nueva página principal del sitio de comunicación. Los detalles sobre los requisitos de cmdlet y características de PowerShell están disponibles en el artículo [enable-SPOCommSite](https://docs.microsoft.com/en-us/powershell/module/sharepoint-online/Enable-SPOCommSite?view=sharepoint-ps). 

Esta se descargará gradualmente, de forma predeterminada, para los clientes de la versión dirigidas a principios de 2019 y la implementación estará disponible en todo el mundo antes de que finalice el 2019 de junio. Siga haciendo referencia al [centro de mensajes](https://admin.microsoft.com/AdminPortal/Home#/MessageCenter) para obtener otras nuevas características con la moderna. 

**Importante**: no elimine el sitio raíz clásico para crear un sitio de comunicación moderno. No es compatible con Microsoft. La eliminación del sitio raíz hará que todos los sitios de SharePoint de la organización sean inaccesibles para todos los usuarios, hasta que restaure el sitio o cree un sitio nuevo en la misma dirección URL. 
 
 