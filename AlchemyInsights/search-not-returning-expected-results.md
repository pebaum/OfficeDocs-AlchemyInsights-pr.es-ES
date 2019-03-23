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
# <a name="content-search-not-returning-expected-results"></a>La búsqueda de contenido no devuelve los resultados esperados

Al ejecutar búsquedas de contenido desde el centro de cumplimiento de & de seguridad de Office 365, es posible que reciba resultados de búsqueda inesperados. Tenga en cuenta lo siguiente que puede afectar a los resultados de la búsqueda:

- **Ubicaciones de contenido y condiciones de búsqueda**: Asegúrese de que ha seleccionado las ubicaciones de contenido y las condiciones de búsqueda adecuadas. Si ha ejecutado una búsqueda grande (con muchas ubicaciones), considere la posibilidad de dividirla en varias búsquedas.

- **Elementos parcialmente indizados**: los [elementos indexados parcialmente](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) de los buzones se incluyen en los resultados de búsqueda estimados. Sin embargo, los elementos parcialmente indizados de sitios de SharePoint y OneDrive no se incluyen en la estimación de la búsqueda.

- **Errores de búsqueda**: al buscar en un gran número de buzones (más de 100.000 buzones), es posible que obtenga errores de búsqueda, con códigos de error como CS008-009 y CS012-002). En este caso, vuelva a intentar la búsqueda solo para las ubicaciones de contenido con error. Consulte [este artículo](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) para obtener más información.
