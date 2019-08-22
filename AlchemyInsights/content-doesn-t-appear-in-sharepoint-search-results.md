---
title: El contenido no aparece en los resultados de la búsqueda de SharePoint
ms.author: tlarsen
author: tklarsen
ms.date: 1/8/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "750"
- "5300017"
ms.assetid: 693db84f-2737-4c21-b027-4ab3d121b4a8
ms.openlocfilehash: ffb6bf349f9e8c2323186a8fc3183325d1d7e1bf
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36517048"
---
# <a name="content-doesnt-appear-in-sharepoint-search-results"></a><span data-ttu-id="a84d8-102">El contenido no aparece en los resultados de la búsqueda de SharePoint</span><span class="sxs-lookup"><span data-stu-id="a84d8-102">Content doesn't appear in SharePoint search results</span></span>

<span data-ttu-id="a84d8-103">Siga estos pasos de solución de problemas cuando el contenido esperado no aparece en los resultados de búsqueda:</span><span class="sxs-lookup"><span data-stu-id="a84d8-103">Follow these troubleshooting steps when expected content doesn't appear in search results:</span></span>
  
1. <span data-ttu-id="a84d8-104">Compruebe que el **sitio** que contiene el contenido esperado está configurado para permitir que el contenido aparezca en los resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="a84d8-104">Check that the **site** that contains the expected content is set to allow content to appear in search results.</span></span> <span data-ttu-id="a84d8-105">Siga los pasos descritos en [Mostrar contenido en un sitio de los resultados de búsqueda](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-on-a-site-in-search-results).</span><span class="sxs-lookup"><span data-stu-id="a84d8-105">Follow the steps in [Show content on a site in search results](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-on-a-site-in-search-results).</span></span>

2. <span data-ttu-id="a84d8-106">Compruebe que la **lista** o **biblioteca** que contiene el contenido esperado esté configurada para permitir que el contenido aparezca en los resultados de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="a84d8-106">Check that the **list** or **library** that contains the expected content is set to allow content to appear in search results.</span></span> <span data-ttu-id="a84d8-107">Siga los pasos que se indican en [Mostrar contenido de listas o bibliotecas en los resultados de búsqueda](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-from-lists-or-libraries-in-search-results).</span><span class="sxs-lookup"><span data-stu-id="a84d8-107">Follow the steps in [Show content from lists or libraries in search results](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-from-lists-or-libraries-in-search-results).</span></span>

3. <span data-ttu-id="a84d8-108">Compruebe que la página, el documento o el diseño de página personalizado está publicado como una **versión principal.**</span><span class="sxs-lookup"><span data-stu-id="a84d8-108">Verify that the page, document, or custom page layout is published as a **Major version.**</span></span> <span data-ttu-id="a84d8-109">Seguir el paso 3 de la [búsqueda no devuelve todos los resultados en SharePoint Online](https://go.microsoft.com/fwlink/?linkid=874525).</span><span class="sxs-lookup"><span data-stu-id="a84d8-109">Follow step 3 in [Search doesn't return all results in SharePoint Online](https://go.microsoft.com/fwlink/?linkid=874525).</span></span>

4. <span data-ttu-id="a84d8-110">Compruebe que el usuario tiene **permisos** para ver el contenido.</span><span class="sxs-lookup"><span data-stu-id="a84d8-110">Verify that the user has **permissions** to view the content.</span></span> <span data-ttu-id="a84d8-111">Siga los pasos descritos en Understanding [Levels in SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span><span class="sxs-lookup"><span data-stu-id="a84d8-111">Follow the steps in [Understanding permission levels in SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span></span>
    
5. <span data-ttu-id="a84d8-112">Si se ha cambiado el esquema de búsqueda mediante la adición de una nueva propiedad administrada, mediante la edición de una propiedad administrada o mediante la eliminación de una propiedad administrada, será necesario solicitar un rastreo y volver a indizar.</span><span class="sxs-lookup"><span data-stu-id="a84d8-112">If the search schema has been changed by adding a new managed property, by editing a managed property, or by removing a managed property then requesting a crawl and re-index will be required.</span></span> <span data-ttu-id="a84d8-113">Para **volver** a indizar el contenido, siga los pasos descritos en [solicitar manualmente el rastreo y la reindización de un sitio, una biblioteca o una lista](https://docs.microsoft.com/sharepoint/crawl-site-content).</span><span class="sxs-lookup"><span data-stu-id="a84d8-113">**Re-index** the content by following the steps in [Manually request crawling and re-indexing of a site, a library or a list](https://docs.microsoft.com/sharepoint/crawl-site-content).</span></span> <span data-ttu-id="a84d8-114">Esto puede tardar un rato, esperar 24 horas antes de volver a revisar los resultados.</span><span class="sxs-lookup"><span data-stu-id="a84d8-114">This might take a while, wait 24 hours before checking the results again.</span></span>

<span data-ttu-id="a84d8-115">Para obtener más información, vea [Habilitar el contenido de un sitio para que se pueda buscar](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span><span class="sxs-lookup"><span data-stu-id="a84d8-115">For more information, see [Enable content on a site to be searchable](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span></span> 
  
