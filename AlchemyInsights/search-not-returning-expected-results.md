---
title: 1491-búsqueda-no-devolución-resultados-esperado
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 1491
ms.assetid: ''
ms.openlocfilehash: 517d9b75fc3aef09c0c2d5870aa695cc0ab10f06
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/22/2019
ms.locfileid: "30776098"
---
# <a name="content-search-not-returning-expected-results"></a><span data-ttu-id="cb3f0-102">La búsqueda de contenido no devuelve los resultados esperados</span><span class="sxs-lookup"><span data-stu-id="cb3f0-102">Content Search not returning expected results</span></span>

<span data-ttu-id="cb3f0-103">Al ejecutar búsquedas de contenido desde el centro de cumplimiento de & de seguridad de Office 365, es posible que reciba resultados de búsqueda inesperados.</span><span class="sxs-lookup"><span data-stu-id="cb3f0-103">When running Content Searches from the Office 365 Security & Compliance Center, you may receive unexpected search results.</span></span> <span data-ttu-id="cb3f0-104">Tenga en cuenta lo siguiente que puede afectar a los resultados de la búsqueda:</span><span class="sxs-lookup"><span data-stu-id="cb3f0-104">Consider the following things that can affect your search results:</span></span>

- <span data-ttu-id="cb3f0-105">**Ubicaciones de contenido y condiciones de búsqueda**: Asegúrese de que ha seleccionado las ubicaciones de contenido y las condiciones de búsqueda adecuadas.</span><span class="sxs-lookup"><span data-stu-id="cb3f0-105">**Content locations and search conditions**: Make sure you have selected the proper content locations and search conditions.</span></span> <span data-ttu-id="cb3f0-106">Si ha ejecutado una búsqueda grande (con muchas ubicaciones), considere la posibilidad de dividirla en varias búsquedas.</span><span class="sxs-lookup"><span data-stu-id="cb3f0-106">If you ran a large search (with many locations), consider splitting it into multiple searches.</span></span>

- <span data-ttu-id="cb3f0-107">**Elementos parcialmente indizados**: los [elementos indexados parcialmente](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) de los buzones se incluyen en los resultados de búsqueda estimados.</span><span class="sxs-lookup"><span data-stu-id="cb3f0-107">**Partially indexed items**:  [Partially indexed items](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) from mailboxes are included in the estimated search results.</span></span> <span data-ttu-id="cb3f0-108">Sin embargo, los elementos parcialmente indizados de sitios de SharePoint y OneDrive no se incluyen en la estimación de la búsqueda.</span><span class="sxs-lookup"><span data-stu-id="cb3f0-108">However, partially indexed items from sites in SharePoint and OneDrive aren't included in the search estimate.</span></span>

- <span data-ttu-id="cb3f0-109">**Errores de búsqueda**: al buscar en un gran número de buzones (más de 100.000 buzones), es posible que obtenga errores de búsqueda, con códigos de error como CS008-009 y CS012-002).</span><span class="sxs-lookup"><span data-stu-id="cb3f0-109">**Search failures**: When searching a large number of mailboxes (over 100,000 mailboxes), you may get search errors, with error codes such as CS008-009 and CS012-002).</span></span> <span data-ttu-id="cb3f0-110">En este caso, vuelva a intentar la búsqueda solo para las ubicaciones de contenido con error.</span><span class="sxs-lookup"><span data-stu-id="cb3f0-110">In this case, retry the search only for the failed content locations.</span></span> <span data-ttu-id="cb3f0-111">Consulte [este artículo](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="cb3f0-111">See  [this article](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) for more information.</span></span>
