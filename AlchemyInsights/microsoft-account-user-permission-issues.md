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
ms.openlocfilehash: 81b9dafe8e27e5f73fe232c51ff56fed3fec29b4
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/04/2019
ms.locfileid: "36754209"
---
# <a name="troubleshoot-issue---user-not-found-in-directory"></a><span data-ttu-id="134e6-102">Problema de solución de problemas-el usuario no se encuentra en el directorio</span><span class="sxs-lookup"><span data-stu-id="134e6-102">Troubleshoot issue - User not found in directory</span></span>

<span data-ttu-id="134e6-103">Si los usuarios reciben el mensaje de error "no se encuentra el usuario" en el directorio.</span><span class="sxs-lookup"><span data-stu-id="134e6-103">If users are receiving error message "user can't be found" in the directory.</span></span> <span data-ttu-id="134e6-104">Vuelva a intentarlo donde el tipo de problema es usuario no está en el directorio.</span><span class="sxs-lookup"><span data-stu-id="134e6-104">Please try again where the Issue Type is User not in directory.</span></span>

<span data-ttu-id="134e6-105">Puede completar los siguientes pasos para solucionar el problema.</span><span class="sxs-lookup"><span data-stu-id="134e6-105">The following steps can be completed to troubleshoot the issue.</span></span>

- <span data-ttu-id="134e6-106">Asegúrese de que la cuenta que aceptó la invitación por correo electrónico es la misma cuenta que se usa para iniciar sesión más adelante.</span><span class="sxs-lookup"><span data-stu-id="134e6-106">Ensure the account that accepted the email invitation is the same account that is being used to sign in later.</span></span> <span data-ttu-id="134e6-107">Asegúrese de que el usuario usa la misma cuenta para aceptar la invitación e inicie sesión en el sitio.</span><span class="sxs-lookup"><span data-stu-id="134e6-107">Make sure the user is using the same account to accept the invite and sign into the site.</span></span> 

<span data-ttu-id="134e6-108">Para obtener más información, vea [Cómo administrar los alias</a> de su cuenta de Microsoft para administrar el inicio de sesión de Office 365](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span><span class="sxs-lookup"><span data-stu-id="134e6-108">For more info, see [How to manage aliases for your Microsoft account</a> to manage the Office 365 login](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span></span> 

- <span data-ttu-id="134e6-109">Busque en cada sitio o sitios en los que el usuario recibe el error.</span><span class="sxs-lookup"><span data-stu-id="134e6-109">Browse to each site(s) in which the user is receiving the error.</span></span> 

<span data-ttu-id="134e6-110">Agregue "/_layouts/15/People.aspx/membershipgroupid = 0" (dentro de las comillas dobles) al final de la dirección URL del sitio.</span><span class="sxs-lookup"><span data-stu-id="134e6-110">Add "/_layouts/15/people.aspx/membershipgroupid=0" (within the double-quotes) to the end of the site URL.</span></span> 

<span data-ttu-id="134e6-111">Ejemplo: https://< "Contoso" >. sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span><span class="sxs-lookup"><span data-stu-id="134e6-111">Example: https://<"contoso">.sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span></span>

- <span data-ttu-id="134e6-112">Seleccione el usuario de la lista.</span><span class="sxs-lookup"><span data-stu-id="134e6-112">Select the user from the list.</span></span>

- <span data-ttu-id="134e6-113">Haga clic en **quitar permisos de usuario** de la cinta.</span><span class="sxs-lookup"><span data-stu-id="134e6-113">Click **Remove User Permissions** from the Ribbon.</span></span> 
-  <span data-ttu-id="134e6-114">Vuelva a agregar el usuario y a enviar la invitación al usuario.</span><span class="sxs-lookup"><span data-stu-id="134e6-114">Add back the User and Resend the invite to the user.</span></span>

