---
title: Buscar en SharePoint Online
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fe00f4c0-44d5-49d4-9db0-a62698bcd1d1
ms.openlocfilehash: c4ff98f0cf928834c803542340b32da15a40d583
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/15/2019
ms.locfileid: "40044060"
---
# <a name="content-crawling-and-indexing-in-sharepoint-online"></a><span data-ttu-id="74aa2-102">Rastreo de contenido e indización en SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="74aa2-102">Content crawling and indexing in SharePoint Online</span></span>

<span data-ttu-id="74aa2-103">El contenido debe rastrearse y agregarse al índice de búsqueda para que los usuarios encuentren lo que están buscando en SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="74aa2-103">Content must be crawled and added to the search index for users to find what they're searching for in SharePoint Online.</span></span> <span data-ttu-id="74aa2-104">El contenido se rastrea automáticamente según una programación de rastreo predefinida (no se puede cambiar la programación de rastreo).</span><span class="sxs-lookup"><span data-stu-id="74aa2-104">Content is automatically crawled based on a pre-defined crawl schedule (the crawl schedule cannot be changed).</span></span> <span data-ttu-id="74aa2-105">El rastreador toma el contenido que ha cambiado desde el último rastreo y actualiza el índice.</span><span class="sxs-lookup"><span data-stu-id="74aa2-105">The crawler picks up content that has changed since the last crawl and updates the index.</span></span> <span data-ttu-id="74aa2-106">Para asegurarse de que el contenido se rastrea y se actualiza el índice, tenga en cuenta lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="74aa2-106">To ensure content is crawled and the index is updated, note the following:</span></span>

- <span data-ttu-id="74aa2-107">Asegúrese de que el contenido del sitio se pueda buscar haciendo búsquedas en el [contenido del sitio](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span><span class="sxs-lookup"><span data-stu-id="74aa2-107">Make sure content can be found by [making site content searchable](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span></span>

- <span data-ttu-id="74aa2-108">Cuando haya cambiado una propiedad administrada, o cuando haya cambiado la asignación de propiedades administradas y rastreadas, se debe volver a rastrear el sitio antes de que los cambios se reflejen en el índice de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="74aa2-108">When you have changed a managed property, or when you have changed the mapping of crawled and managed properties, the site must be re-crawled before your changes will be reflected in the search index.</span></span> 

    <span data-ttu-id="74aa2-109">Como los cambios se realizan en el esquema de búsqueda y no en el sitio real, el rastreador no reindizará automáticamente el sitio.</span><span class="sxs-lookup"><span data-stu-id="74aa2-109">Because your changes are made in the search schema, and not to the actual site, the crawler will not automatically re-index the site.</span></span> 

    <span data-ttu-id="74aa2-110">Para obtener más información, consulte [solicitar manualmente el rastreo y la nueva indización de un sitio, una biblioteca o una lista](https://docs.microsoft.com/sharepoint/crawl-site-conten).</span><span class="sxs-lookup"><span data-stu-id="74aa2-110">For more info, see [Manually request crawling and re-indexing of a site, a library or a list](https://docs.microsoft.com/sharepoint/crawl-site-conten).</span></span>

- <span data-ttu-id="74aa2-111">Espere al menos 24 horas después de solicitar manualmente un rastreo y reindización completa para ver si sigue experimentando un problema.</span><span class="sxs-lookup"><span data-stu-id="74aa2-111">Wait at least 24 hours after manually requesting a crawl and full re-index to see if you're still experiencing an issue.</span></span> 

    <span data-ttu-id="74aa2-112">Si han pasado más de 24 horas desde que ha iniciado el rastreo y la reindexación completa, registre un caso de soporte técnico.</span><span class="sxs-lookup"><span data-stu-id="74aa2-112">If more than 24 hours have passed since you initiated the crawl and full re-index, please log a support case.</span></span> <span data-ttu-id="74aa2-113">En muchos casos, ya estamos trabajando en una solución.</span><span class="sxs-lookup"><span data-stu-id="74aa2-113">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="74aa2-114">Por lo menos, danos 24 horas para completar una soluci? a.</span><span class="sxs-lookup"><span data-stu-id="74aa2-114">Please give us at least 24 hours to complete a solution.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="74aa2-115">Si se ha eliminado un sitio, documento (biblioteca) o una lista y todavía se muestra en los resultados de la búsqueda, los usuarios deben recibir un **Error 404 no se encuentra el archivo** al intentar tener acceso a él.</span><span class="sxs-lookup"><span data-stu-id="74aa2-115">If a site, document (library), or a list was deleted and still shows in the search results, users should receive an **Error 404 File Not Found** when trying to access it.</span></span> <span data-ttu-id="74aa2-116">Este problema debe registrarse como un caso de soporte técnico para una mayor investigación.</span><span class="sxs-lookup"><span data-stu-id="74aa2-116">This issue should be logged as a support case for further investigation.</span></span> 



