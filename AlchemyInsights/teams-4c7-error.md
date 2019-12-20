---
title: Error de 4c7 de Teams
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3472"
- "9001211"
ms.openlocfilehash: 0945a341c6456ee4178c0485f3bfb9232fa78a11
ms.sourcegitcommit: 802537a54ef8bde1bdd758ee9a60b6c19d37d6e1
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/19/2019
ms.locfileid: "40796392"
---
# <a name="4c7-error-in-microsoft-teams"></a><span data-ttu-id="17ed3-102">error de 4c7 en Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="17ed3-102">4c7 error in Microsoft Teams</span></span>

<span data-ttu-id="17ed3-103">Este error se produce porque Microsoft Teams requiere la autenticación mediante formularios.</span><span class="sxs-lookup"><span data-stu-id="17ed3-103">This error occurs because Microsoft Teams requires Forms Authentication.</span></span> <span data-ttu-id="17ed3-104">Al implementar los servicios de Federación de Active Directory (AD FS), la autenticación de formularios no está habilitada para la intranet de forma predeterminada.</span><span class="sxs-lookup"><span data-stu-id="17ed3-104">When you deploy Active Directory Federation Services (AD FS), Forms Authentication is not enabled for the intranet by default.</span></span> <span data-ttu-id="17ed3-105">Si se produce un error en la autenticación integrada de Windows, se le pedirá que inicie sesión con la autenticación de formularios.</span><span class="sxs-lookup"><span data-stu-id="17ed3-105">If Windows Integrated Authentication fails, you are prompted to sign in by using Forms Authentication.</span></span>

<span data-ttu-id="17ed3-106">Para resolver este problema, habilite la autenticación mediante formularios con el complemento Microsoft Management Console (MMC) de AD FS en el equipo que tiene la copia local de Active Directory.</span><span class="sxs-lookup"><span data-stu-id="17ed3-106">To resolve this issue, enable Forms Authentication by using the AD FS Microsoft Management Console (MMC) snap-in on the computer that has the local copy of Active Directory.</span></span> <span data-ttu-id="17ed3-107">Para ello, siga estos pasos:</span><span class="sxs-lookup"><span data-stu-id="17ed3-107">To do this, follow these steps:</span></span> 

1. <span data-ttu-id="17ed3-108">En el panel de navegación, vaya a **directivas de autenticación**.</span><span class="sxs-lookup"><span data-stu-id="17ed3-108">In the navigation pane, browse to **Authentication Policies**.</span></span>
2. <span data-ttu-id="17ed3-109">En **acciones** en el panel de detalles, seleccione **Editar autenticación principal global**.</span><span class="sxs-lookup"><span data-stu-id="17ed3-109">Under **Actions** in the details pane, select **Edit Global Primary Authentication**.</span></span>
3. <span data-ttu-id="17ed3-110">En la pestaña **intranet** , seleccione **autenticación de formularios**.</span><span class="sxs-lookup"><span data-stu-id="17ed3-110">On the **Intranet** tab, select **Forms Authentication**.</span></span>
4. <span data-ttu-id="17ed3-111">Seleccione **Aceptar** (o **aplicar**).</span><span class="sxs-lookup"><span data-stu-id="17ed3-111">Select **OK** (or **Apply**).</span></span>