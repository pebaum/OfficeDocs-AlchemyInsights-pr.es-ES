---
title: El flujo de trabajo no se inicia
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 8/2/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000144"
- "1670"
ms.openlocfilehash: 2d85dcf9111d48cb529c583c733823b404eb3188
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/04/2019
ms.locfileid: "36738106"
---
# <a name="workflow-is-not-starting"></a>El flujo de trabajo no se inicia

- Los flujos de trabajo de SharePoint 2010 y SharePoint 2013 no se inician.

    - Si el flujo de trabajo no se inicia, es posible que haya un problema de servicio temporal en el que los usuarios pueden experimentar retrasos intermitentes con el progreso del flujo de trabajo. Compruebe el [Panel de estado del servicio](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) para ver si su organización se ve afectada.

    - Si ha pasado más de 24 horas desde que vio por primera vez este problema, registre un vale de soporte técnico. En muchos casos, ya estamos trabajando en una solución. Por lo menos, danos 24 horas para completar una soluci? a.

- Flujos de trabajo de SharePoint 2010 retrasados en el inicio.

    - Esto ocurre si el flujo de trabajo se activa en lotes grandes. (por ejemplo, cuando se agregan varios elementos a la vez).

    - Los flujos de trabajo no están diseñados para ejecutarse en tiempo real, por lo que un retraso es el comportamiento de diseño.

   -  Si el flujo de trabajo es un lenguaje de marcado de objetos extensible (XMOL) complejo, la compilación puede ser lenta. Consulte [este](https://support.microsoft.com//kb/3043697) artículo.

    - Debe simplificar el flujo de trabajo o volver a diseñarlo con el tipo de plataforma de flujo de trabajo de Microsoft SharePoint 2013.

    - Si el historial del flujo de trabajo ha crecido de gran tamaño, es posible que desee purgar los elementos o crear una nueva lista de historial.

        Más información: [purgar el historial del flujo de trabajo](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)


## <a name="related-topics"></a>Temas relacionados
¿Desea probar Microsoft Flow en SharePoint Online?
- [Crear flujo](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [Flujo y SharePoint](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


