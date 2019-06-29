---
title: Administrar usuarios sincronizados
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000609"
- "2444"
ms.openlocfilehash: 5a383bdd17c5fa055c35a923ca36e0e0f6d429e4
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/28/2019
ms.locfileid: "35380522"
---
# <a name="unable-to-set-primary-email-address-or-change-user-attributes"></a><span data-ttu-id="c7c0f-102">No se puede establecer la dirección de correo electrónico principal ni cambiar los atributos de usuario</span><span class="sxs-lookup"><span data-stu-id="c7c0f-102">Unable to set primary email address or change user attributes</span></span>

<span data-ttu-id="c7c0f-103">Si la sincronización de directorios está habilitada para su entorno, algunos atributos de usuario o de objeto no se pueden cambiar mediante el centro de administración.</span><span class="sxs-lookup"><span data-stu-id="c7c0f-103">If directory synchronization is enabled for your environment some user or object attributes cannot be changed using the Admin Center.</span></span>
<span data-ttu-id="c7c0f-104">Para administrar por completo los usuarios sincronizados y todos sus atributos, use la consola de administración de usuarios y grupos de Active Directory (AdsiEdit. msc) local.</span><span class="sxs-lookup"><span data-stu-id="c7c0f-104">To fully manage synchronized users and all their attributes, use your local active directory users and groups management console (adsiedit.msc).</span></span>  

<span data-ttu-id="c7c0f-105">Como alternativa, puede cambiar usuarios individuales o atributos para los usuarios sincronizados mediante PowerShell, como se muestra en estos ejemplos comunes:</span><span class="sxs-lookup"><span data-stu-id="c7c0f-105">Alternatively, you can change individual users or attributes for synchronized users using powershell such as shown in these common examples:</span></span> 
- <span data-ttu-id="c7c0f-106">Set-MsolUser-UserPrincipalName user@yourdomain.onmicrosoft.com-AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="c7c0f-106">Set-MsolUser -UserPrincipalName user@yourdomain.onmicrosoft.com -AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com</span></span>
- <span data-ttu-id="c7c0f-107">Set-MsolUser-UserPrincipalName "user@yourdomain.onmicrosoft.com"-DisplayName "usuario de prueba"-LastName "User"-title "Manager"-Department "HR"</span><span class="sxs-lookup"><span data-stu-id="c7c0f-107">Set-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com" -DisplayName "Test User" -LastName "User" -Title "Manager" -Department "HR"</span></span>
- <span data-ttu-id="c7c0f-108">Remove-MsolUser-UserPrincipalName "user@yourdomain.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="c7c0f-108">Remove-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com</span></span>