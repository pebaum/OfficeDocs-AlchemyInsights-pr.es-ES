---
title: Problema de solución de problemas-el usuario no se encuentra en el directorio
ms.author: pebaum
author: Techwriter40
manager: pamgreen
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.openlocfilehash: 59713231da25be441e7c05d788337e66bf17265a
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/15/2019
ms.locfileid: "37768818"
---
# <a name="troubleshoot-issue---user-not-found-in-directory"></a><span data-ttu-id="7f049-102">Problema de solución de problemas-el usuario no se encuentra en el directorio</span><span class="sxs-lookup"><span data-stu-id="7f049-102">Troubleshoot issue - User not found in directory</span></span>

<span data-ttu-id="7f049-103">Si los usuarios reciben el mensaje de error "no se encuentra el usuario" en el directorio, vuelva a intentarlo donde el tipo de problema es usuario no está en el directorio.</span><span class="sxs-lookup"><span data-stu-id="7f049-103">If users are receiving error message "user can't be found" in the directory, please try again where the Issue Type is User not in directory.</span></span>

<span data-ttu-id="7f049-104">Puede completar los siguientes pasos para solucionar el problema.</span><span class="sxs-lookup"><span data-stu-id="7f049-104">The following steps can be completed to troubleshoot the issue.</span></span>

- <span data-ttu-id="7f049-105">Asegúrese de que la cuenta que aceptó la invitación por correo electrónico es la misma cuenta que se usa para iniciar sesión más adelante.</span><span class="sxs-lookup"><span data-stu-id="7f049-105">Ensure the account that accepted the email invitation is the same account that is being used to sign in later.</span></span> <span data-ttu-id="7f049-106">Asegúrese de que el usuario usa la misma cuenta para aceptar la invitación e inicie sesión en el sitio.</span><span class="sxs-lookup"><span data-stu-id="7f049-106">Make sure the user is using the same account to accept the invite and sign into the site.</span></span> 

<span data-ttu-id="7f049-107">Para obtener más información, vea [Cómo administrar los alias</a> de su cuenta de Microsoft para administrar el inicio de sesión de Office 365](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span><span class="sxs-lookup"><span data-stu-id="7f049-107">For more info, see [How to manage aliases for your Microsoft account</a> to manage the Office 365 login](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span></span> 

- <span data-ttu-id="7f049-108">Busque en cada sitio o sitios en los que el usuario recibe el error.</span><span class="sxs-lookup"><span data-stu-id="7f049-108">Browse to each site(s) in which the user is receiving the error.</span></span> 

<span data-ttu-id="7f049-109">Agregue "/_layouts/15/People.aspx/membershipgroupid = 0" (dentro de las comillas dobles) al final de la dirección URL del sitio.</span><span class="sxs-lookup"><span data-stu-id="7f049-109">Add "/_layouts/15/people.aspx/membershipgroupid=0" (within the double-quotes) to the end of the site URL.</span></span> 

<span data-ttu-id="7f049-110">Ejemplo: https://< "Contoso" >. sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span><span class="sxs-lookup"><span data-stu-id="7f049-110">Example: https://<"contoso">.sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span></span>

- <span data-ttu-id="7f049-111">Seleccione el usuario de la lista.</span><span class="sxs-lookup"><span data-stu-id="7f049-111">Select the user from the list.</span></span>

- <span data-ttu-id="7f049-112">Haga clic en **quitar permisos de usuario** de la cinta.</span><span class="sxs-lookup"><span data-stu-id="7f049-112">Click **Remove User Permissions** from the Ribbon.</span></span> 
-  <span data-ttu-id="7f049-113">Vuelva a agregar el usuario y a enviar la invitación al usuario.</span><span class="sxs-lookup"><span data-stu-id="7f049-113">Add back the User and Resend the invite to the user.</span></span>

