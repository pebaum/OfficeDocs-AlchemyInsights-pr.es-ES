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
# <a name="sync-errors-due-to-duplicate-objects"></a><span data-ttu-id="774bb-102">Errores de sincronización debido a objetos duplicados</span><span class="sxs-lookup"><span data-stu-id="774bb-102">Sync errors due to duplicate objects</span></span>

<span data-ttu-id="774bb-103">Es posible que reciba uno de los siguientes mensajes de error cuando finaliza la sincronización de directorios:</span><span class="sxs-lookup"><span data-stu-id="774bb-103">You might receive one of the following error messages when directory synchronization finishes:</span></span>
  
- <span data-ttu-id="774bb-104">No se puede actualizar este objeto en Microsoft Online Services porque los siguientes atributos asociados a este objeto tienen valores que es posible que ya esté asociados a otro objeto en el directorio local.</span><span class="sxs-lookup"><span data-stu-id="774bb-104">Unable to update this object in Microsoft Online Services because the following attributes associated with this object have values that may already be associated with another object in your local directory.</span></span>
    
- <span data-ttu-id="774bb-105">Un objeto sincronizado con la misma dirección de proxy ya existe en el directorio de Microsoft Online Services.</span><span class="sxs-lookup"><span data-stu-id="774bb-105">A synchronized object with the same proxy address already exists in your Microsoft Online Services directory.</span></span>
    
- <span data-ttu-id="774bb-106">No se puede actualizar este objeto porque los siguientes atributos asociados a este objeto tienen valores que es posible que ya esté asociados a otro objeto en los servicios de directorio local: UserPrincipalName.</span><span class="sxs-lookup"><span data-stu-id="774bb-106">Unable to update this object because the following attributes associated with this object have values that may already be associated with another object in your local directory services: UserPrincipalName.</span></span>
    
<span data-ttu-id="774bb-107">Para identificar y solucionar el problema, descargue y ejecute la [Herramienta de corrección de Error de sincronización de directorios de IdFix](https://www.microsoft.com/download/details.aspx?id=36832).</span><span class="sxs-lookup"><span data-stu-id="774bb-107">To identify and fix the issue, download and run the [IdFix DirSync Error Remediation Tool](https://www.microsoft.com/download/details.aspx?id=36832).</span></span>
  
<span data-ttu-id="774bb-108">Para obtener más información, vea [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span><span class="sxs-lookup"><span data-stu-id="774bb-108">For more information, see [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span></span>
  

