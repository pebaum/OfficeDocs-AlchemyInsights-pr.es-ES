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
ms.openlocfilehash: a579b89b68bfb8432adfe64b155803eda2c3b086
ms.sourcegitcommit: a3b42ee05224846327d353b48a8c67dab724f6eb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/21/2020
ms.locfileid: "42891766"
---
# <a name="outlook-cannot-connect-to-public-folders"></a><span data-ttu-id="2db29-102">Outlook no puede conectarse a las carpetas públicas</span><span class="sxs-lookup"><span data-stu-id="2db29-102">Outlook cannot connect to public folders</span></span>

<span data-ttu-id="2db29-103">Si el acceso a la carpeta pública no funciona para algunos usuarios, intente lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="2db29-103">If public folder access isn't working for some users, try the following:</span></span>

<span data-ttu-id="2db29-104">Conéctese a EXO PowerShell y configure el parámetro DefaultPublicFolderMailbox en la cuenta de usuario problemática para que cumpla el parámetro en una cuenta de usuario que funcione.</span><span class="sxs-lookup"><span data-stu-id="2db29-104">Connect to EXO PowerShell and configure the DefaultPublicFolderMailbox parameter on the problem user account to match the parameter on a working user account.</span></span>

<span data-ttu-id="2db29-105">Ejemplo:</span><span class="sxs-lookup"><span data-stu-id="2db29-105">Example:</span></span>

<span data-ttu-id="2db29-106">Get-Mailbox WorkingUser | DefaultPublicFolderMailbox ft, EffectivePublicFolderMailbox</span><span class="sxs-lookup"><span data-stu-id="2db29-106">Get-Mailbox WorkingUser | ft DefaultPublicFolderMailbox,EffectivePublicFolderMailbox</span></span>

<span data-ttu-id="2db29-107">Set-Mailbox ProblemUser-DefaultPublicFolderMailbox \<valor del comando anterior></span><span class="sxs-lookup"><span data-stu-id="2db29-107">Set-Mailbox ProblemUser -DefaultPublicFolderMailbox \<value from previous command></span></span>

<span data-ttu-id="2db29-108">Espere al menos una hora para que el cambio surta efecto.</span><span class="sxs-lookup"><span data-stu-id="2db29-108">Wait at least one hour for the change to take effect.</span></span>

<span data-ttu-id="2db29-109">Si el problema persiste, siga [este procedimiento](https://aka.ms/pfcte) para solucionar problemas de acceso a carpetas públicas con Outlook.</span><span class="sxs-lookup"><span data-stu-id="2db29-109">If the issue remains, please follow [this procedure](https://aka.ms/pfcte) to troubleshoot public folder access issues using Outlook.</span></span>