---
title: Cambiar el sitio raíz clásico por un sitio moderno
ms.author: efrene
author: efrene
ms.date: 8/6/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: ''
ms.custom:
- "9000687"
- "2579"
ms.openlocfilehash: 0f6f962314d9099bd21c281a23ad2e95742da4a8
ms.sourcegitcommit: 631e527967f4d641bc9227642ffe38967ae87a00
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/09/2019
ms.locfileid: "36270761"
---
# <a name="swap-your-classic-root-site-with-a-modern-site"></a>Cambiar el sitio raíz clásico por un sitio moderno

Si el entorno se configuró antes del 2019 de abril, puede cambiar el sitio raíz a un sitio moderno mediante PowerShell de Microsoft:

- Si tiene un sitio diferente que desea usar como sitio raíz, puede reemplazar (intercambiar) el sitio raíz con él. 
    - Use [Invoke-SPSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) para intercambiar la ubicación de un sitio con otro sitio mientras archiva el sitio original. Disponible tanto para el sitio de grupo (no conectado a un grupo) como para el sitio de comunicación. 

- Se presentarán funciones adicionales próximamente que le permitirán seguir usando el contenido en el sitio, pero convertir el sitio existente en un sitio de comunicación. 
>[!Important]
>Estas funciones se implementarán gradualmente. Continúe con la comprobación del centro de mensajes de Office 365 para obtener actualizaciones. 

## <a name="known-issues-with-swapping-sites"></a>Problemas conocidos con el intercambio de sitios

- El sitio de destino puede devolver un error "no se encontró" (HTTP 404) durante un breve período de tiempo.
- Será necesario volver a rastrear el contenido para actualizar el índice de búsqueda. No es necesario ningún paso manual; esto se realizará automáticamente.
- Todo lo que dependa de los vínculos "estáticos" (como los archivos de OneNote y la sincronización de archivos) deberá corregirse manualmente.
- Si el sitio de origen era un sitio de noticias de la organización, actualice la dirección URL.Obtenga una lista de todos los sitios de noticias de la organización.
- Es posible que sea necesario validar los sitios de Project Server para asegurarse de que siguen asociados correctamente.





