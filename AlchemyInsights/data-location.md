---
title: Ubicación de datos
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "945"
- "5300023"
ms.assetid: 3bab036c-dbaa-406a-8b73-1e5f31993436
ms.openlocfilehash: ec8fb91dfe77cb251579ce23eb0579b114b101d9
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/27/2019
ms.locfileid: "39627863"
---
# <a name="data-location"></a>Ubicación de datos

Puede ver la ubicación del inquilino de Office 365 en el centro de administración o conectándose a Exchange Online a través de PowerShell.


**Centro de administración:**
1. Inicie sesión en el [centro de administración](https://admin.microsoft.com/Adminportal/Home).
2. Seleccione **configuración** > **Perfil de organización**.
3. En **Ubicación de datos**, seleccione **Ver detalles**.


**PowerShell**
1. Conéctese a Exchange online mediante Windows PowerShell.
2. Ejecute el cmdlet [Get-OrganizationalUnit](https://docs.microsoft.com/powershell/module/exchange/active-directory/get-organizationalunit) para mostrar una lista de las propiedades del espacio empresarial. 
3. Mire la propiedad OrganizationId.

Cuando tiene la ubicación de datos para EXO y SPO, puede determinar la ubicación de los datos para otros servicios que puede usar desde [donde se encuentran los datos](https://products.office.com/where-is-your-data-located).