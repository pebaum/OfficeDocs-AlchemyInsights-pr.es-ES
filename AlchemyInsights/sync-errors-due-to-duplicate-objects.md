---
title: 902 (errores de sincronización debidos a objetos duplicados)
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 902
ms.assetid: 9d9277a5-c825-4512-8d54-7138b2ee0c40
ms.openlocfilehash: 6ea833e0c4aebe72bc5c02e3dc10c1edc4136dcc
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43767154"
---
# <a name="sync-errors-due-to-duplicate-objects"></a><span data-ttu-id="d594f-102">Errores de sincronización debidos a objetos duplicados</span><span class="sxs-lookup"><span data-stu-id="d594f-102">Sync errors due to duplicate objects</span></span>

<span data-ttu-id="d594f-103">Es posible que reciba uno de los siguientes mensajes de error cuando la sincronización de directorios finaliza en Microsoft 365:</span><span class="sxs-lookup"><span data-stu-id="d594f-103">You might receive one of the following error messages when directory synchronization finishes in Microsoft 365:</span></span>

- <span data-ttu-id="d594f-104">No se puede actualizar este objeto en Microsoft Online Services porque los siguientes atributos asociados a este objeto tienen valores que ya pueden estar asociados a otro objeto en el directorio local.</span><span class="sxs-lookup"><span data-stu-id="d594f-104">Unable to update this object in Microsoft Online Services because the following attributes associated with this object have values that may already be associated with another object in your local directory.</span></span>

- <span data-ttu-id="d594f-105">Ya existe un objeto sincronizado con la misma dirección proxy en el directorio de Microsoft Online Services.</span><span class="sxs-lookup"><span data-stu-id="d594f-105">A synchronized object with the same proxy address already exists in your Microsoft Online Services directory.</span></span>

- <span data-ttu-id="d594f-106">No se puede actualizar este objeto porque los siguientes atributos asociados a este objeto tienen valores que ya pueden estar asociados a otro objeto en los servicios de directorio local: UserPrincipalName.</span><span class="sxs-lookup"><span data-stu-id="d594f-106">Unable to update this object because the following attributes associated with this object have values that may already be associated with another object in your local directory services: UserPrincipalName.</span></span>

<span data-ttu-id="d594f-107">Para identificar y solucionar el problema, descargue y ejecute la [herramienta de corrección de errores de sincronización de directorios de IdFix](https://www.microsoft.com/download/details.aspx?id=36832).</span><span class="sxs-lookup"><span data-stu-id="d594f-107">To identify and fix the issue, download and run the [IdFix DirSync Error Remediation Tool](https://www.microsoft.com/download/details.aspx?id=36832).</span></span>

<span data-ttu-id="d594f-108">Para obtener más información, vea [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span><span class="sxs-lookup"><span data-stu-id="d594f-108">For more information, see [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span></span>
