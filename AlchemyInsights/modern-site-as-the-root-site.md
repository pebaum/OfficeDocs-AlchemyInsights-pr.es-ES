---
title: Sitio moderno como sitio raíz
ms.author: efrene
author: efrene
ms.audience: ITPro
ms.topic: article
ms.date: 8/7/2019
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000265"
- "1874"
ms.openlocfilehash: 2f75f1e60af06da47fe846e84bbb370dd60084e9
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36543870"
---
# <a name="modern-site-as-root-site"></a>Sitio moderno como sitio raíz

Hemos empezado a distribuir una nueva característica que le permitirá intercambiar el sitio de raíz del sitio clásico con un sitio moderno. Use [Invoke-SPSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) para intercambiar la ubicación de un sitio con otro sitio mientras archiva el sitio original. Disponible tanto para el sitio de grupo (no conectado a un grupo) como para el sitio de comunicación. 

>[!Important]
> No elimine el sitio raíz clásico para crear un sitio de comunicación moderno. No es compatible con Microsoft. La eliminación del sitio raíz hará que todos los sitios de SharePoint de la organización sean inaccesibles para todos los usuarios, hasta que restaure el sitio o cree un sitio nuevo en la misma dirección URL. Se comunicará esta característica a través del centro de mensajes. Es de esperar que la característica se active en su espacio empresarial en breve.

## <a name="known-issues-with-swapping-sites"></a>Problemas conocidos con el intercambio de sitios
- El sitio de destino puede devolver un error "no se encontró" (HTTP 404) durante un breve período de tiempo.
- Será necesario volver a rastrear el contenido para actualizar el índice de búsqueda. No se requiere ningún paso manual aquí, esto se realizará automáticamente.
- Todo lo que dependa de los vínculos "estáticos" (como los archivos de OneNote y la sincronización de archivos) deberá corregirse manualmente.
- Es posible que sea necesario validar los sitios de Project Server para asegurarse de que siguen asociados correctamente. 
