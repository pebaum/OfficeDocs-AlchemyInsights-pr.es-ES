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
ms.openlocfilehash: ec8fb91dfe77cb251579ce23eb0579b114b101d9
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/27/2019
ms.locfileid: "39627863"
---
# <a name="data-location"></a><span data-ttu-id="19d89-102">Ubicación de datos</span><span class="sxs-lookup"><span data-stu-id="19d89-102">Data location</span></span>

<span data-ttu-id="19d89-103">Puede ver la ubicación del inquilino de Office 365 en el centro de administración o conectándose a Exchange Online a través de PowerShell.</span><span class="sxs-lookup"><span data-stu-id="19d89-103">You can view the location of your Office 365 tenant in the admin center or by connecting to Exchange Online via PowerShell.</span></span>


<span data-ttu-id="19d89-104">**Centro de administración:**</span><span class="sxs-lookup"><span data-stu-id="19d89-104">**Admin center:**</span></span>
1. <span data-ttu-id="19d89-105">Inicie sesión en el [centro de administración](https://admin.microsoft.com/Adminportal/Home).</span><span class="sxs-lookup"><span data-stu-id="19d89-105">Log in to the [admin center](https://admin.microsoft.com/Adminportal/Home).</span></span>
2. <span data-ttu-id="19d89-106">Seleccione **configuración** > **Perfil de organización**.</span><span class="sxs-lookup"><span data-stu-id="19d89-106">Select **Settings** > **Organization profile**.</span></span>
3. <span data-ttu-id="19d89-107">En **Ubicación de datos**, seleccione **Ver detalles**.</span><span class="sxs-lookup"><span data-stu-id="19d89-107">Under **Data location**, select **View details**.</span></span>


<span data-ttu-id="19d89-108">**PowerShell**</span><span class="sxs-lookup"><span data-stu-id="19d89-108">**PowerShell:**</span></span>
1. <span data-ttu-id="19d89-109">Conéctese a Exchange online mediante Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="19d89-109">Connect to Exchange Online by using Windows PowerShell.</span></span>
2. <span data-ttu-id="19d89-110">Ejecute el cmdlet [Get-OrganizationalUnit](https://docs.microsoft.com/powershell/module/exchange/active-directory/get-organizationalunit) para mostrar una lista de las propiedades del espacio empresarial.</span><span class="sxs-lookup"><span data-stu-id="19d89-110">Execute the [Get-OrganizationalUnit](https://docs.microsoft.com/powershell/module/exchange/active-directory/get-organizationalunit) cmdlet to display a list of your tenant’s properties.</span></span> 
3. <span data-ttu-id="19d89-111">Mire la propiedad OrganizationId.</span><span class="sxs-lookup"><span data-stu-id="19d89-111">Look at the OrganizationId property.</span></span>

<span data-ttu-id="19d89-112">Cuando tiene la ubicación de datos para EXO y SPO, puede determinar la ubicación de los datos para otros servicios que puede usar desde [donde se encuentran los datos](https://products.office.com/where-is-your-data-located).</span><span class="sxs-lookup"><span data-stu-id="19d89-112">When you have the data location for EXO and SPO, you can determine the data location for other services you may use from [Where your data is located](https://products.office.com/where-is-your-data-located).</span></span>