---
title: Cambiar el requisito de contraseña segura
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000105"
- "1600"
ms.openlocfilehash: 21f80a7cc8b00ac56acdb05add1e1bfdfac9d827
ms.sourcegitcommit: c061f1dfa6f557a9ec083dd030b73b121d9864ea
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/14/2020
ms.locfileid: "43286295"
---
# <a name="change-strong-password-requirement"></a><span data-ttu-id="15f59-102">Cambiar el requisito de contraseña segura</span><span class="sxs-lookup"><span data-stu-id="15f59-102">Change strong password requirement</span></span>

<span data-ttu-id="15f59-103">Microsoft requiere contraseñas seguras de forma predeterminada.</span><span class="sxs-lookup"><span data-stu-id="15f59-103">Microsoft requires strong passwords by default.</span></span> 

<span data-ttu-id="15f59-104">Con PowerShell, puede deshabilitar las contraseñas seguras para determinados usuarios con este comando:</span><span class="sxs-lookup"><span data-stu-id="15f59-104">Using PowerShell, you can disable strong passwords for specific users with this command:</span></span><br>
<span data-ttu-id="15f59-105">*Set-MsolUser – UserPrincipalName <UserPrincipalName> – StrongPasswordRequired $false*</span><span class="sxs-lookup"><span data-stu-id="15f59-105">*Set-MsolUser –UserPrincipalName <UserPrincipalName> –StrongPasswordRequired  $false*</span></span>

- [<span data-ttu-id="15f59-106">Más información sobre la Directiva de contraseñas</span><span class="sxs-lookup"><span data-stu-id="15f59-106">More information on password policy</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [<span data-ttu-id="15f59-107">Cómo conectarse a Office 365 con PowerShell</span><span class="sxs-lookup"><span data-stu-id="15f59-107">How to connect to Office 365 with PowerShell</span></span>](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [<span data-ttu-id="15f59-108">Más información acerca de los comandos de PowerShell MsolUser</span><span class="sxs-lookup"><span data-stu-id="15f59-108">More information on PowerShell MsolUser commands</span></span>](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)
- [<span data-ttu-id="15f59-109">Establecer la contraseña de un usuario individual para que nunca expire</span><span class="sxs-lookup"><span data-stu-id="15f59-109">Set an individual user's password to never expire</span></span>](https://docs.microsoft.com/microsoft-365/admin/add-users/set-password-to-never-expire)
