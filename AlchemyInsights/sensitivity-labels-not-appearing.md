---
title: No aparecen las etiquetas de confidencialidad
ms.author: stephow
author: stephow-MSFT
manager: laurawi
ms.date: ''
ms.audience: admin
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.openlocfilehash: fac86806ac6931d7c69eaa7b6321c87f8c21ce26
ms.sourcegitcommit: ffe2f489b1ac3aae62aa784c959da6a41c3261eb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/17/2019
ms.locfileid: "31909577"
---
# <a name="sensitivity-labels-not-appearing"></a>No aparecen las etiquetas de confidencialidad

Las etiquetas de confidencialidad le permiten clasificar y ayudar a proteger el contenido confidencial. Para obtener más información acerca de esta característica, consulte [información general sobre las etiquetas de confidencialidad](https://docs.microsoft.com/en-us/office365/securitycompliance/sensitivity-labels).

Si ha configurado las etiquetas de confidencialidad pero no aparecen en las aplicaciones de Office, compruebe lo siguiente:

- Confirme que la etiqueta de confidencialidad se ha [publicado](https://docs.microsoft.com/en-us/Office365/SecurityCompliance/sensitivity-labels#what-label-policies-can-do) en los usuarios y grupos que desee.

- Confirme que el usuario usa una aplicación que admite etiquetas de confidencialidad (consulte [las etiquetas de confidencialidad en el documento](https://support.office.com/en-us/article/apply-sensitivity-labels-to-your-documents-and-email-within-office-2f96e7cd-d5a4-403b-8bd7-4cc636bae0f9?ad=US&ui=en-US&rs=en-US#bkmk_whereavailable)).
 
 
- Si va a [migrar las etiquetas de Azure Information Protection](https://docs.microsoft.com/en-us/azure/information-protection/configure-policy-migrate-labels), tenga en cuenta las consideraciones que se enumeran [aquí](https://docs.microsoft.com/en-us/azure/information-protection/configure-policy-migrate-labels#considerations-for-unified-labels).

- Compatibilidad con prevención de pérdida de datos (DLP): Actualmente, solo se pueden usar las etiquetas de retención como condición en las directivas de DLP.  La compatibilidad con las etiquetas de confidencialidad en una directiva DLP todavía no está disponible, pero estamos trabajando en ella.

Para obtener más información sobre posibles problemas, consulte [problemas conocidos con las etiquetas de confidencialidad](https://support.office.com/en-us/article/known-issues-with-sensitivity-labels-in-office-b169d687-2bbd-4e21-a440-7da1b2743edc?ui=en-US&rs=en-US&ad=US).