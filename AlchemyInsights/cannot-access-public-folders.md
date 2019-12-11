---
title: No se puede tener acceso a las carpetas públicas
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3462"
ms.openlocfilehash: a9305b175e1ca0b992c014a73705447d67e037bc
ms.sourcegitcommit: cbbd46fa9a32873c5446d9fd5a532cea0300b795
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/10/2019
ms.locfileid: "39959511"
---
# <a name="outlook-cannot-connect-to-public-folders"></a><span data-ttu-id="2fa7b-102">Outlook no puede conectarse a las carpetas públicas</span><span class="sxs-lookup"><span data-stu-id="2fa7b-102">Outlook cannot connect to public folders</span></span>

<span data-ttu-id="2fa7b-103">Si el acceso a la carpeta pública no funciona con pocos usuarios, pruebe lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="2fa7b-103">If public folder access isn't working for few users, try the following:</span></span>

<span data-ttu-id="2fa7b-104">Conéctese a la PowerShell EXO y configure DefaultPublicFolderMailbox en la cuenta de usuario con problemas para que sea igual a una en una cuenta de usuario que funcione.</span><span class="sxs-lookup"><span data-stu-id="2fa7b-104">Connect to EXO PowerShell, and configure the DefaultPublicFolderMailbox on the problem user account to match one on a working user account.</span></span>

<span data-ttu-id="2fa7b-105">Ejemplo:</span><span class="sxs-lookup"><span data-stu-id="2fa7b-105">Example:</span></span>

<span data-ttu-id="2fa7b-106">Get-Mailbox WorkingUser | DefaultPublicFolderMailbox ft, EffectivePublicFolderMailbox</span><span class="sxs-lookup"><span data-stu-id="2fa7b-106">Get-Mailbox WorkingUser | ft DefaultPublicFolderMailbox,EffectivePublicFolderMailbox</span></span>

<span data-ttu-id="2fa7b-107">Set-Mailbox ProblemUser-DefaultPublicFolderMailbox \<valor del comando anterior></span><span class="sxs-lookup"><span data-stu-id="2fa7b-107">Set-Mailbox ProblemUser -DefaultPublicFolderMailbox \<value from previous command></span></span>

<span data-ttu-id="2fa7b-108">Espere al menos una hora para que el cambio surta efecto.</span><span class="sxs-lookup"><span data-stu-id="2fa7b-108">Wait at least one hour for the change to take effect.</span></span>