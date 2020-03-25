---
title: Es posible que DLP necesite un tipo personalizado
ms.author: pebaum
author: pebaum
manager: laurawi
ms.date: ''
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1647"
- "3200001"
ms.assetid: ''
ms.openlocfilehash: 890bba57bc36c034c507e6124cd6593ef4d92af8
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932675"
---
# <a name="dlp-might-need-a-custom-type"></a>Es posible que DLP necesite un tipo personalizado

**Importante**: muchos clientes de SharePoint Online y OneDrive ejecutan aplicaciones críticas para la empresa en el servicio que se ejecutan en segundo plano. Estas incluyen la migración de contenido, la prevención de pérdida de datos (DLP) y soluciones de copia de seguridad. En estos tiempos sin precedente, aplicamos las medidas necesarias para garantizar que los servicios de SharePoint Online y OneDrive permanezcan altamente disponibles y confiables para los usuarios que dependen del servicio más que nunca en escenarios de trabajo remoto.

Para apoyar este objetivo, hemos implementado límites más estrictos para las aplicaciones en segundo plano (como la migración, DLP y las soluciones de copia de seguridad) durante las horas de la semana laboral. Se anticipa que estas aplicaciones obtengan un rendimiento muy limitado durante estas horas. Sin embargo, durante las horas de la noche y del fin de semana de la región, el servicio estará listo para procesar un volumen mucho más elevado de solicitudes de aplicaciones en segundo plano.

**Es posible que DLP requiera un tipo de información personalizada**

Con una directiva de prevención de pérdida de datos (DLP), puede identificar y proteger los datos confidenciales de su organización. En algunos escenarios, es posible que necesite crear su propio tipo **personalizado** de información confidencial para proteger los datos de su organización.

Por ejemplo, es posible que su organización necesite identificar y proteger los identificadores de los empleados u otros datos en algún formato específico de su organización. Si es así, consulte los artículos siguientes para obtener más información.
  
 **Personalizar un tipo de información confidencial integrado**
  
Si un tipo de información confidencial incorporado satisface sus necesidades con solo unos cuantos ajustes, puede [personalizar un tipo de información confidencial integrada](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type). Por ejemplo, puede Agregar o quitar palabras clave, o bien agregar o quitar evidencias auxiliares, como una fecha o una dirección.
  
 **Crear un tipo personalizado de información confidencial**
  
Pero si necesita identificar y proteger por completo un tipo diferente de información confidencial, puede [crear un tipo personalizado de información confidencial](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) en la interfaz de usuario del centro de seguridad & cumplimiento.
  
**Crear un tipo personalizado de información confidencial en PowerShell del Centro de seguridad y cumplimientol**

Por último, si la interfaz de usuario no proporciona todas las opciones que necesita, puede [crear un tipo personalizado de información confidencial en el PowerShell del centro de cumplimiento de & de seguridad](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell). Al comenzar con un archivo XML, puede usar todas las opciones disponibles.
