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
ms.openlocfilehash: 09cdbc3cb0465e0e0bc08872c49e283081ad3e92
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36516796"
---
# <a name="no-results-from-content-searchexports"></a>No hay resultados en la búsqueda/exportación de contenido

Problemas con la búsqueda y las exportaciones de contenido que no devuelven datos puede deberse a ciertos filtros de seguridad de cumplimiento que han sido configurados por un administrador específico y no lo comunican a todos los administradores.

Para solucionar esto, compruebe si hay filtros de seguridad de cumplimiento que puedan estar causando esto:
1. Conectarse al centro de seguridad y cumplimiento PowerShell
2. Ejecute el siguiente commandlets:
<br>$org = "yourdomain.com"
<br>Get-ComplianceSecurityFilter-Organization $org