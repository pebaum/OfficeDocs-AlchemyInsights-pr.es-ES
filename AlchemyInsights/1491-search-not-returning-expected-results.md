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
# <a name="content-search-not-returning-expected-results"></a>Búsqueda de contenido no devolver los resultados esperados

Al ejecutar búsquedas de contenido desde el centro de cumplimiento de seguridad de Office 365 &, puede recibir los resultados de búsqueda inesperados. Tenga en cuenta las siguientes acciones que pueden afectar a los resultados de búsqueda:

- **Ubicaciones de contenido y las condiciones de búsqueda**: asegúrese de que ha seleccionado las ubicaciones apropiadas de contenido y las condiciones de búsqueda. Si ejecutó una búsqueda de gran tamaño (con muchas ubicaciones), considere la posibilidad de división en varias búsquedas.

- **Elementos indizados parcialmente**: [elementos indizados parcialmente](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) desde los buzones de correo se incluyen en los resultados de búsqueda estimado. Sin embargo, no se incluyen elementos indizados parcialmente de los sitios de SharePoint y OneDrive en la estimación de la búsqueda.

- **Errores de búsqueda**: al buscar en un gran número de buzones (más de 100.000), es posible que obtenga errores de búsqueda, con códigos de error como CS008-009 y CS012-002). En este caso, vuelva a intentar la búsqueda sólo para las ubicaciones de contenido con errores. Vea [este artículo](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) para obtener más información.
