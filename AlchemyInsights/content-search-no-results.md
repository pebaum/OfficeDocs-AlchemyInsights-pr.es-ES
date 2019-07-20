---
title: No hay resultados en la búsqueda de contenido
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000661"
- "2527"
ms.openlocfilehash: 9f2c0273762f1a4a2b905487f461dc1d05db9209
ms.sourcegitcommit: 8f97342d8b46ab05f1e89018473caad9d35431df
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/19/2019
ms.locfileid: "35800618"
---
# <a name="no-results-from-content-searchexports"></a><span data-ttu-id="2cc33-102">No hay resultados en la búsqueda/exportación de contenido</span><span class="sxs-lookup"><span data-stu-id="2cc33-102">No results from Content Search/Exports</span></span>

<span data-ttu-id="2cc33-103">Problemas con la búsqueda y las exportaciones de contenido que no devuelven datos puede deberse a ciertos filtros de seguridad de cumplimiento que han sido configurados por un administrador específico y no lo comunican a todos los administradores.</span><span class="sxs-lookup"><span data-stu-id="2cc33-103">Issues with Content Search/Exports not returning any data may be due to certain Compliance Security Filter that was setup by a specific Admin and not communicating it to all Admins.</span></span>

<span data-ttu-id="2cc33-104">Para solucionar esto, compruebe si hay filtros de seguridad de cumplimiento que puedan estar causando esto:</span><span class="sxs-lookup"><span data-stu-id="2cc33-104">To resolve this, check to see if there are any Compliance Security Filters that may be causing this:</span></span>
1. <span data-ttu-id="2cc33-105">Conectarse al centro de seguridad y cumplimiento PowerShell</span><span class="sxs-lookup"><span data-stu-id="2cc33-105">Connect to Security and Compliance Center Powershell</span></span>
2. <span data-ttu-id="2cc33-106">Ejecute el siguiente commandlets:</span><span class="sxs-lookup"><span data-stu-id="2cc33-106">Run the following commandlets:</span></span>
<br><span data-ttu-id="2cc33-107">$org = "yourdomain.com"</span><span class="sxs-lookup"><span data-stu-id="2cc33-107">$org = “yourdomain.com”</span></span>
<br><span data-ttu-id="2cc33-108">Get-ComplianceSecurityFilter-Organization $org</span><span class="sxs-lookup"><span data-stu-id="2cc33-108">Get-ComplianceSecurityFilter -Organization $org</span></span>