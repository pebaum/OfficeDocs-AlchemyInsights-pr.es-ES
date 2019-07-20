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
# <a name="no-results-from-content-searchexports"></a>No hay resultados en la búsqueda/exportación de contenido

Problemas con la búsqueda y las exportaciones de contenido que no devuelven datos puede deberse a ciertos filtros de seguridad de cumplimiento que han sido configurados por un administrador específico y no lo comunican a todos los administradores.

Para solucionar esto, compruebe si hay filtros de seguridad de cumplimiento que puedan estar causando esto:
1. Conectarse al centro de seguridad y cumplimiento PowerShell
2. Ejecute el siguiente commandlets:
<br>$org = "yourdomain.com"
<br>Get-ComplianceSecurityFilter-Organization $org