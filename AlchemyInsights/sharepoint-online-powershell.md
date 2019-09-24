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
# <a name="sharepoint-online-powershell"></a><span data-ttu-id="88309-102">PowerShell de SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="88309-102">Sharepoint Online PowerShell</span></span>

<span data-ttu-id="88309-103">¿Trabaja con PowerShell o scripts en SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="88309-103">Working with PowerShell or Scripts within Sharepoint Online?</span></span> <span data-ttu-id="88309-104">Visite los siguientes vínculos para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="88309-104">Visit the links below for more information.</span></span>
- [<span data-ttu-id="88309-105">Introducción al shell de administración de SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="88309-105">Getting started with SharePoint Online Management Shell</span></span>](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps)
- [<span data-ttu-id="88309-106">Conectarse a la PowerShell de SPO con la autenticación multifactor (MFA)</span><span class="sxs-lookup"><span data-stu-id="88309-106">Connect to SPO PowerShell with multifactor authentication (MFA)</span></span>](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps#to-connect-with-multifactor-authentication-mfa)
- <span data-ttu-id="88309-107">[Modelos y prácticas de SharePoint (PNP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) contiene una biblioteca de comandos de PowerShell que le permite realizar acciones de administración complejas en SPO.</span><span class="sxs-lookup"><span data-stu-id="88309-107">[SharePoint Patterns and Practices (PnP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) contains a library of PowerShell commands that allows you to perform complex management actions towards SPO.</span></span>

> [!NOTE]
> - <span data-ttu-id="88309-108">Si tiene problemas para conectarse con el shell de administración de SPO, asegúrese de que se ha actualizado a la versión más reciente e intente [volver a importar el módulo](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) mediante *"Import-Module Microsoft. online. SharePoint. PowerShell".*</span><span class="sxs-lookup"><span data-stu-id="88309-108">If you are having issues connecting with the SPO management shell, make sure that you have updated to the latest version and try to [re-import the module](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) using *“Import-Module Microsoft.Online.SharePoint.PowerShell”.*</span></span>
> - <span data-ttu-id="88309-109">Si está intentando ejecutar scripts de modelo de objetos del lado cliente, deberá tener instalado el [SDK de componentes de cliente de SharePoint Online](https://www.microsoft.com/download/details.aspx?id=42038) en el equipo local.</span><span class="sxs-lookup"><span data-stu-id="88309-109">If you are attempting to run client-side object model scripts, you will need to have the [Sharepoint Online Client Components SDK](https://www.microsoft.com/download/details.aspx?id=42038) installed on your local machine.</span></span>
> - <span data-ttu-id="88309-110">Si tiene problemas al ejecutar scripts de PowerShell, es posible que desee considerar la posibilidad de ejecutar PowerShell como administrador y cambiar la [Directiva de ejecución](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).</span><span class="sxs-lookup"><span data-stu-id="88309-110">If you are having issues running scripts from PowerShell, you may want to consider running PowerShell as an Administrator and changing the [Execution Policy](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).</span></span>