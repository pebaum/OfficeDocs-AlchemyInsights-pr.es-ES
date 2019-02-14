---
title: 1491-Search-Not-Returning-Expected-Results
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: ''
ms.openlocfilehash: 881a579d7098578452c994b7ac66fe22a1d90dc2
ms.sourcegitcommit: 5182c9a73641079be59740e4524434b2e8be613a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29964971"
---
# <a name="content-search-not-returning-expected-results"></a><span data-ttu-id="7278e-102">Búsqueda de contenido no devolver los resultados esperados</span><span class="sxs-lookup"><span data-stu-id="7278e-102">Content Search not returning expected results</span></span>

<span data-ttu-id="7278e-p101">Al ejecutar búsquedas de contenido desde el centro de cumplimiento de seguridad de Office 365 &, puede recibir los resultados de búsqueda inesperados. Tenga en cuenta las siguientes acciones que pueden afectar a los resultados de búsqueda:</span><span class="sxs-lookup"><span data-stu-id="7278e-p101">When running Content Searches from the Office 365 Security & Compliance Center, you may receive unexpected search results. Consider the following things that can affect your search results:</span></span>

- <span data-ttu-id="7278e-p102">**Ubicaciones de contenido y las condiciones de búsqueda**: asegúrese de que ha seleccionado las ubicaciones apropiadas de contenido y las condiciones de búsqueda. Si ejecutó una búsqueda de gran tamaño (con muchas ubicaciones), considere la posibilidad de división en varias búsquedas.</span><span class="sxs-lookup"><span data-stu-id="7278e-p102">**Content locations and search conditions**: Make sure you have selected the proper content locations and search conditions. If you ran a large search (with many locations), consider splitting it into multiple searches.</span></span>

- <span data-ttu-id="7278e-p103">**Elementos indizados parcialmente**: [elementos indizados parcialmente](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) desde los buzones de correo se incluyen en los resultados de búsqueda estimado. Sin embargo, no se incluyen elementos indizados parcialmente de los sitios de SharePoint y OneDrive en la estimación de la búsqueda.</span><span class="sxs-lookup"><span data-stu-id="7278e-p103">**Partially indexed items**:  [Partially indexed items](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) from mailboxes are included in the estimated search results. However, partially indexed items from sites in SharePoint and OneDrive aren't included in the search estimate.</span></span>

- <span data-ttu-id="7278e-p104">**Errores de búsqueda**: al buscar en un gran número de buzones (más de 100.000), es posible que obtenga errores de búsqueda, con códigos de error como CS008-009 y CS012-002). En este caso, vuelva a intentar la búsqueda sólo para las ubicaciones de contenido con errores. Vea [este artículo](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="7278e-p104">**Search failures**: When searching a large number of mailboxes (over 100,000 mailboxes), you may get search errors, with error codes such as CS008-009 and CS012-002). In this case, retry the search only for the failed content locations. See  [this article](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) for more information.</span></span>
