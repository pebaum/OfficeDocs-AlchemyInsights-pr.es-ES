---
title: Las sugerencias de directivas de DLP no funcionan
ms.author: deniseb
author: denisebmsft
manager: laurawims
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: c03d30be-474a-4a34-b3c0-240eb2a2c466
ms.custom:
- "1428"
- "3200001"
ms.openlocfilehash: 51b4472fa721443192eb542cac45965df67634df
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932603"
---
# <a name="dlp-policy-tip-issues"></a>Problemas de la sugerencia de directiva DLP

**Importante**: muchos clientes de SharePoint Online y OneDrive ejecutan aplicaciones críticas para la empresa en el servicio que se ejecutan en segundo plano. Estas incluyen la migración de contenido, la prevención de pérdida de datos (DLP) y soluciones de copia de seguridad. En estos tiempos sin precedente, aplicamos las medidas necesarias para garantizar que los servicios de SharePoint Online y OneDrive permanezcan altamente disponibles y confiables para los usuarios que dependen del servicio más que nunca en escenarios de trabajo remoto.

Para apoyar este objetivo, hemos implementado límites más estrictos para las aplicaciones en segundo plano (como la migración, DLP y las soluciones de copia de seguridad) durante las horas de la semana laboral. Se anticipa que estas aplicaciones obtengan un rendimiento muy limitado durante estas horas. Sin embargo, durante las horas de la noche y del fin de semana de la región, el servicio estará listo para procesar un volumen mucho más elevado de solicitudes de aplicaciones en segundo plano.

**Sugerencias de directivas de DLP**

Cuando se usan **directivas de DLP**, se puede informar a los usuarios de una infracción de directiva con las sugerencias de **Directiva**. Los administradores pueden configurar las sugerencias de directiva para que se muestren mientras se prueba la Directiva DLP o cuando la Directiva está en el modo de cumplimiento completo.
  
Para configurar sugerencias de directiva en su Directiva DLP en el centro de seguridad y cumplimiento en el modo de cumplimiento completo, haga lo siguiente:
  
- Asegúrese de que las sugerencias de Directiva se hayan **habilitado** en la regla DLP siguiendo los pasos que se describen [aquí](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips).

- Asegúrese de que el **contenido coincida con** lo que se **necesita** para desencadenar la regla que se describe en este [artículo.](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)

- Las sugerencias de directivas se muestran en OWA y Outlook. Sin embargo, al usar **Outlook 2013 o versiones posteriores**, las sugerencias de directiva solo se muestran en ciertas condiciones. Estas condiciones se enumeran a continuación: [condiciones admitidas para Outlook 2013 o posterior para mostrar sugerencias de directiva](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips#outlook-2013-and-later-supports-showing-policy-tips-for-only-some-conditions)

Para obtener más información sobre las sugerencias de directivas de DLP, vea: [Show Policy Tips for DLP Policies](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips)
  