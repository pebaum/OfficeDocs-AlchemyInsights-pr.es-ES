---
title: Jubilación de servicios de Access
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: f5a1e88e4443fdf43cdd4f07cf9e784810df7540
ms.sourcegitcommit: 136b8209c52c2a05d0f2fdaab93b2cd92253fa2c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/07/2019
ms.locfileid: "34769477"
---
# <a name="access-services-retirement"></a>Jubilación de servicios de Access

Como se anunció originalmente en MC97576, en marzo de 2017, y se continuó la comunicación a través del último año, los servicios de Access se están retirando de Office 365. La siguiente fase de este proceso será la eliminación de las bases de datos Web de Access que usan listas de SharePoint como almacenamiento de datos subyacente.

**¿Qué me afecta?**

A partir del 2019 de junio, deteneremos la creación de nuevas bases de datos de Access en SharePoint Online y cerrará el servicio y el resto de las aplicaciones hasta el 2020 de abril.

**¿Qué debo hacer para prepararse para este cambio?**

Le recomendamos que cree un plan de transición para las bases de datos Web de Access de su organización. Los administradores pueden usar el [Explorador de aplicaciones de Access para SharePoint](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.AccessApp.Scanner) para obtener un inventario de las aplicaciones de Access que usan los sitios. 

Hay varias formas de migrar los datos de bases de datos Web de Access:

- Importación a una base de datos de Access local (. ACCDB) o a un archivo de Excel.
- También se recomienda explorar Microsoft PowerApps como una plataforma alternativa para crear soluciones empresariales sin código para dispositivos móviles y Web.