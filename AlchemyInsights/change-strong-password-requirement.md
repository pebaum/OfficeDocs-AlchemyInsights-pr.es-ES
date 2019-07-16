---
title: Cambiar el requisito de contraseña segura
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000105"
- "1600"
ms.openlocfilehash: 53affd2a347c004e7b21b353c2b3df98bc30a585
ms.sourcegitcommit: a7e5ca472000dfec471950bafd12eee8d7144f74
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/16/2019
ms.locfileid: "35701600"
---
# <a name="change-strong-password-requirement"></a><span data-ttu-id="cf7c0-102">Cambiar el requisito de contraseña segura</span><span class="sxs-lookup"><span data-stu-id="cf7c0-102">Change strong password requirement</span></span>

<span data-ttu-id="cf7c0-103">Las contraseñas seguras son obligatorias de forma predeterminada.</span><span class="sxs-lookup"><span data-stu-id="cf7c0-103">Strong passwords are required by default.</span></span> 

<span data-ttu-id="cf7c0-104">Con PowerShell, puede deshabilitar las contraseñas seguras para determinados usuarios con este comando:</span><span class="sxs-lookup"><span data-stu-id="cf7c0-104">Using PowerShell you can disable strong passwords for specific users with this command:</span></span><br>
<span data-ttu-id="cf7c0-105">*Set-MsolUser – UserPrincipalName <UserPrincipalName> – StrongPasswordRequired $false*</span><span class="sxs-lookup"><span data-stu-id="cf7c0-105">*Set-MsolUser –UserPrincipalName <UserPrincipalName> –StrongPasswordRequired  $false*</span></span>

- [<span data-ttu-id="cf7c0-106">Más información sobre la Directiva de contraseñas</span><span class="sxs-lookup"><span data-stu-id="cf7c0-106">More information on password policy</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [<span data-ttu-id="cf7c0-107">Cómo conectarse a O365 con PowerShell</span><span class="sxs-lookup"><span data-stu-id="cf7c0-107">How to connect to O365 with PowerShell</span></span>](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [<span data-ttu-id="cf7c0-108">Más información acerca de los comandos de PowerShell MsolUser</span><span class="sxs-lookup"><span data-stu-id="cf7c0-108">More information on PowerShell MsolUser commands</span></span>](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)