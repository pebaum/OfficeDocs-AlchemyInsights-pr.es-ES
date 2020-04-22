---
title: Ubicación de datos
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "945"
- "5300023"
ms.assetid: 3bab036c-dbaa-406a-8b73-1e5f31993436
ms.openlocfilehash: c769c17796d805f88afb4d5b32adb7d4a9bb3ce0
ms.sourcegitcommit: 6bf1d945b4fd6a1fe37d00c5ea99adea7eef9910
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/21/2020
ms.locfileid: "43655299"
---
# <a name="data-location"></a><span data-ttu-id="1b3b7-102">Ubicación de datos</span><span class="sxs-lookup"><span data-stu-id="1b3b7-102">Data location</span></span>

<span data-ttu-id="1b3b7-103">Puede ver la ubicación del inquilino en el centro de administración o conectándose a Exchange Online a través de PowerShell.</span><span class="sxs-lookup"><span data-stu-id="1b3b7-103">You can view the location of your tenant in the admin center or by connecting to Exchange Online via PowerShell.</span></span>


<span data-ttu-id="1b3b7-104">**Centro de administración:**</span><span class="sxs-lookup"><span data-stu-id="1b3b7-104">**Admin center:**</span></span>
1. <span data-ttu-id="1b3b7-105">Inicie sesión en el [centro de administración](https://admin.microsoft.com/Adminportal/Home).</span><span class="sxs-lookup"><span data-stu-id="1b3b7-105">Log in to the [admin center](https://admin.microsoft.com/Adminportal/Home).</span></span>
2. <span data-ttu-id="1b3b7-106">Seleccione **configuración** > **Perfil de organización**.</span><span class="sxs-lookup"><span data-stu-id="1b3b7-106">Select **Settings** > **Organization profile**.</span></span>
3. <span data-ttu-id="1b3b7-107">En **Ubicación de datos**, seleccione **Ver detalles**.</span><span class="sxs-lookup"><span data-stu-id="1b3b7-107">Under **Data location**, select **View details**.</span></span>


<span data-ttu-id="1b3b7-108">**PowerShell**</span><span class="sxs-lookup"><span data-stu-id="1b3b7-108">**PowerShell:**</span></span>
1. <span data-ttu-id="1b3b7-109">Conéctese a Exchange online mediante Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="1b3b7-109">Connect to Exchange Online by using Windows PowerShell.</span></span>
2. <span data-ttu-id="1b3b7-110">Ejecute el cmdlet [Get-OrganizationalUnit](https://docs.microsoft.com/powershell/module/exchange/active-directory/get-organizationalunit) para mostrar una lista de las propiedades del espacio empresarial.</span><span class="sxs-lookup"><span data-stu-id="1b3b7-110">Execute the [Get-OrganizationalUnit](https://docs.microsoft.com/powershell/module/exchange/active-directory/get-organizationalunit) cmdlet to display a list of your tenant's properties.</span></span> 
3. <span data-ttu-id="1b3b7-111">Mire la propiedad OrganizationId.</span><span class="sxs-lookup"><span data-stu-id="1b3b7-111">Look at the OrganizationId property.</span></span>

<span data-ttu-id="1b3b7-112">Cuando tiene la ubicación de datos para EXO y SPO, puede determinar la ubicación de los datos para otros servicios que puede usar desde [donde se encuentran los datos](https://products.office.com/where-is-your-data-located).</span><span class="sxs-lookup"><span data-stu-id="1b3b7-112">When you have the data location for EXO and SPO, you can determine the data location for other services you may use from [Where your data is located](https://products.office.com/where-is-your-data-located).</span></span>