---
title: 902 (errores de sincronización debido a objetos duplicados)
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 5/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 9d9277a5-c825-4512-8d54-7138b2ee0c40
ms.openlocfilehash: f8db233167a5e2b2ef7290438b8e6d92d0dccb1e
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29491591"
---
# <a name="sync-errors-due-to-duplicate-objects"></a>Errores de sincronización debido a objetos duplicados

Es posible que reciba uno de los siguientes mensajes de error cuando finaliza la sincronización de directorios:
  
- No se puede actualizar este objeto en Microsoft Online Services porque los siguientes atributos asociados a este objeto tienen valores que es posible que ya esté asociados a otro objeto en el directorio local.
    
- Un objeto sincronizado con la misma dirección de proxy ya existe en el directorio de Microsoft Online Services.
    
- No se puede actualizar este objeto porque los siguientes atributos asociados a este objeto tienen valores que es posible que ya esté asociados a otro objeto en los servicios de directorio local: UserPrincipalName.
    
Para identificar y solucionar el problema, descargue y ejecute la [Herramienta de corrección de Error de sincronización de directorios de IdFix](https://www.microsoft.com/download/details.aspx?id=36832).
  
Para obtener más información, vea [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).
  

