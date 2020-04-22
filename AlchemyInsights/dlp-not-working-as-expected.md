---
title: DLP no funciona como se esperaba
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1241"
- "3200001"
ms.assetid: f6fcf5ad-55a1-4f25-af27-1f7c1ce06409
ms.openlocfilehash: efb4a19f345fe6b8a1e8bb72abeba4a923c05777
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43704430"
---
# <a name="dlp-not-working-as-expected"></a>DLP no funciona como se esperaba

**Importante**: durante estos tiempos, se siguen pasos para asegurarse de que los servicios de SharePoint Online y OneDrive estén altamente disponibles. Para obtener más información, visite [Ajustes temporales de características de SharePoint Online](https://aka.ms/ODSPAdjustments).

 **Configuración de DLP**

¿Tiene problemas con la **prevención de pérdida de datos (DLP)** en Office 365 que no funciona como se esperaba? Si es así, asegúrese de que la **Directiva DLP** está correctamente configurada y de que los datos contienen lo que la **Directiva DLP** busca cuando se evalúa.
  
Las directivas de DLP le permiten identificar y proteger la información confidencial de su organización. Para configurar directivas de DLP, use la información que se muestra [aquí](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).
  
 **Qué buscan las directivas de DLP**
  
Al usar los **tipos de información confidencial integrados** en los centros de seguridad y cumplimiento, las directivas de DLP buscan patrones y elementos específicos al detectar estos tipos confidenciales.
  
- **Tipos de información confidencial integrados**

    Para obtener información sobre los tipos confidenciales integrados y qué busca una directiva DLP cuando se detecta el tipo confidencial, vea: [Qué buscan los tipos de información confidencial](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).

- **Tipos personalizados de información confidencial**

    Si está intentando crear tipos personalizados de información confidencial, use el siguiente artículo para obtener información sobre cómo crear un tipo confidencial personalizado: [crear un tipo personalizado de información confidencial](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).

**Probar una directiva DLP**

Para probar los datos con un tipo de información confidencial integrado o personalizado, use la opción **tipo de prueba** en **clasificaciones** > de**información confidencial**. Para obtener más información, vea [probar tipos personalizados de información confidencial](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).

 **Informes**
  
- Obtenga información confidencial sobre los datos con [informes de DLP.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)

- Vea los detalles específicos del evento con un [Informe de incidentes](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).
