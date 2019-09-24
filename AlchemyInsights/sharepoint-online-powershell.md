---
title: PowerShell de SharePoint Online
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 9/18/19
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000266"
- "1867"
ms.openlocfilehash: 00ec337ce34da9d3c3fba0a71602c3078a556552
ms.sourcegitcommit: 6b102e079a7d30298105fd811a67efb707d6d5bf
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/23/2019
ms.locfileid: "37123015"
---
# <a name="sharepoint-online-powershell"></a>PowerShell de SharePoint Online

¿Trabaja con PowerShell o scripts en SharePoint Online? Visite los siguientes vínculos para obtener más información.
- [Introducción al shell de administración de SharePoint Online](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps)
- [Conectarse a la PowerShell de SPO con la autenticación multifactor (MFA)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps#to-connect-with-multifactor-authentication-mfa)
- [Modelos y prácticas de SharePoint (PNP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) contiene una biblioteca de comandos de PowerShell que le permite realizar acciones de administración complejas en SPO.

> [!NOTE]
> - Si tiene problemas para conectarse con el shell de administración de SPO, asegúrese de que se ha actualizado a la versión más reciente e intente [volver a importar el módulo](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) mediante *"Import-Module Microsoft. online. SharePoint. PowerShell".*
> - Si está intentando ejecutar scripts de modelo de objetos del lado cliente, deberá tener instalado el [SDK de componentes de cliente de SharePoint Online](https://www.microsoft.com/download/details.aspx?id=42038) en el equipo local.
> - Si tiene problemas al ejecutar scripts de PowerShell, es posible que desee considerar la posibilidad de ejecutar PowerShell como administrador y cambiar la [Directiva de ejecución](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).