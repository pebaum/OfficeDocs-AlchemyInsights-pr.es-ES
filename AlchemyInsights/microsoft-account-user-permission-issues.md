---
title: Problema de solución de problemas-el usuario no se encuentra en el directorio
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.openlocfilehash: 537b27d06acd17cbb3fe99bcb89e153099e92bb4
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36544880"
---
# <a name="troubleshoot-issue---user-not-found-in-directory"></a><span data-ttu-id="a305a-102">Problema de solución de problemas-el usuario no se encuentra en el directorio</span><span class="sxs-lookup"><span data-stu-id="a305a-102">Troubleshoot issue - User not found in directory</span></span>

<span data-ttu-id="a305a-103">Si los usuarios reciben el mensaje de error "no se encuentra el usuario" en el directorio.</span><span class="sxs-lookup"><span data-stu-id="a305a-103">If users are receiving error message "user can't be found" in the directory.</span></span> <span data-ttu-id="a305a-104">Vuelva a intentarlo donde el tipo de problema es usuario no está en el directorio.</span><span class="sxs-lookup"><span data-stu-id="a305a-104">Please try again where the Issue Type is User not in directory.</span></span>

<span data-ttu-id="a305a-105">Puede completar los siguientes pasos para solucionar el problema.</span><span class="sxs-lookup"><span data-stu-id="a305a-105">The following steps can be completed to troubleshoot the issue.</span></span>

- <span data-ttu-id="a305a-106">Asegúrese de que la cuenta que aceptó la invitación por correo electrónico es la misma cuenta que se usa para iniciar sesión más adelante.</span><span class="sxs-lookup"><span data-stu-id="a305a-106">Ensure the account that accepted the email invitation is the same account that is being used to sign in later.</span></span> <span data-ttu-id="a305a-107">Asegúrese de que el usuario usa la misma cuenta para aceptar la invitación e inicie sesión en el sitio.</span><span class="sxs-lookup"><span data-stu-id="a305a-107">Make sure the user is using the same account to accept the invite and sign into the site.</span></span> 

<span data-ttu-id="a305a-108">Para obtener más información, vea [Cómo administrar los alias</a> de su cuenta de Microsoft para administrar el inicio de sesión de Office 365](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span><span class="sxs-lookup"><span data-stu-id="a305a-108">For more info, see [How to manage aliases for your Microsoft account</a> to manage the Office 365 login](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span></span> 

- <span data-ttu-id="a305a-109">Busque en cada sitio o sitios en los que el usuario recibe el error.</span><span class="sxs-lookup"><span data-stu-id="a305a-109">Browse to each site(s) in which the user is receiving the error.</span></span> 

<span data-ttu-id="a305a-110">Agregue "/_layouts/15/People.aspx/membershipgroupid = 0" (dentro de las comillas dobles) al final de la dirección URL del sitio.</span><span class="sxs-lookup"><span data-stu-id="a305a-110">Add "/_layouts/15/people.aspx/membershipgroupid=0" (within the double-quotes) to the end of the site URL.</span></span> 

<span data-ttu-id="a305a-111">Ejemplo: https://< "Contoso" >. sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span><span class="sxs-lookup"><span data-stu-id="a305a-111">Example: https://<"contoso">.sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span></span>

- <span data-ttu-id="a305a-112">Seleccione el usuario de la lista.</span><span class="sxs-lookup"><span data-stu-id="a305a-112">Select the user from the list.</span></span>

- <span data-ttu-id="a305a-113">Haga clic en **quitar permisos de usuario** de la cinta.</span><span class="sxs-lookup"><span data-stu-id="a305a-113">Click **Remove User Permissions** from the Ribbon.</span></span> 
-  <span data-ttu-id="a305a-114">Vuelva a agregar el usuario y a enviar la invitación al usuario.</span><span class="sxs-lookup"><span data-stu-id="a305a-114">Add back the User and Resend the invite to the user.</span></span>

