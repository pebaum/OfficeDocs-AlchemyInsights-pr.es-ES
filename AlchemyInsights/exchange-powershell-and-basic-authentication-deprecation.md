---
title: Desuso de Exchange PowerShell y autenticación básica
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3500011"
- "4577"
ms.openlocfilehash: 24d59860732b42e8d62da8c1a8c37f2018a0d126
ms.sourcegitcommit: 264b782ac2fba8ffd84524180dc4f7d60b45e9a4
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 05/04/2020
ms.locfileid: "44015706"
---
# <a name="exchange-powershell-and-basic-authentication-deprecation"></a>Desuso de Exchange PowerShell y autenticación básica

Para obtener la información más reciente sobre cómo conectarse a Exchange Online PowerShell sin usar autenticación básica, [vaya aquí](https://aka.ms/psbasicauth).

Tenga en cuenta que la Autenticación básica debe estar habilitada en el equipo cliente.
El nuevo módulo PowerShell V2 usa la Autenticación moderna para establecer la conexión con el fin de habilitar todos los cmdlets V2 basados en REST. Además de los cmdlets V2, también le permite tener acceso a cmdlets antiguos remotos de PowerShell (RPS), lo que requiere que se establezca una sesión de PowerShell remota. Establecer una sesión de RPS en un equipo con Windows requiere que se habilite la Autenticación básica WinRM en el equipo cliente aunque el módulo use un mecanismo de autenticación moderno para autenticarse en el servicio. La canalización de autenticación básica de WinRM se usa para transportar los tokens de autenticación modernos. Si la Autenticación básica WinRM está deshabilitada en el equipo cliente, los nuevos cmdlets V2 seguirán funcionando (pero los cmdlets de RPS antiguos no se mostrarán).
