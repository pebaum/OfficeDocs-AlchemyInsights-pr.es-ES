---
title: Buscar en SharePoint Online
ms.author: efrene
author: efrene
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fe00f4c0-44d5-49d4-9db0-a62698bcd1d1
ms.openlocfilehash: 3c3f6384172b2b4d59db6059618572db11059228
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36507648"
---
# <a name="content-crawling-and-indexing-in-sharepoint-online"></a>Rastreo de contenido e indización en SharePoint Online

El contenido debe rastrearse y agregarse al índice de búsqueda para que los usuarios encuentren lo que están buscando en SharePoint Online. El contenido se rastrea automáticamente según una programación de rastreo predefinida (no se puede cambiar la programación de rastreo). El rastreador toma el contenido que ha cambiado desde el último rastreo y actualiza el índice. Para asegurarse de que el contenido se rastrea y se actualiza el índice, tenga en cuenta lo siguiente:

- Asegúrese de que el contenido del sitio se pueda buscar haciendo búsquedas en el [contenido del sitio](https://docs.microsoft.com/sharepoint/make-site-content-searchable).

- Cuando haya cambiado una propiedad administrada, o cuando haya cambiado la asignación de propiedades administradas y rastreadas, se debe volver a rastrear el sitio antes de que los cambios se reflejen en el índice de búsqueda. 

    Como los cambios se realizan en el esquema de búsqueda y no en el sitio real, el rastreador no reindizará automáticamente el sitio. 

    Para obtener más información, consulte [solicitar manualmente el rastreo y la nueva indización de un sitio, una biblioteca o una lista](https://docs.microsoft.com/sharepoint/crawl-site-conten).

- Espere al menos 24 horas después de solicitar manualmente un rastreo y reindización completa para ver si sigue experimentando un problema. 

    Si han pasado más de 24 horas desde que ha iniciado el rastreo y la reindexación completa, registre un caso de soporte técnico. En muchos casos, ya estamos trabajando en una solución. Por lo menos, danos 24 horas para completar una soluci? a.

> [!IMPORTANT]
> Si se ha eliminado un sitio, documento (biblioteca) o una lista y todavía se muestra en los resultados de la búsqueda, los usuarios deben recibir un **Error 404 no se encuentra el archivo** al intentar tener acceso a él. Este problema debe registrarse como un caso de soporte técnico para una mayor investigación. 



