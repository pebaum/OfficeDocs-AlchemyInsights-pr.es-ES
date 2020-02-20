---
title: No se puede establecer ni ver la Directiva de AllowSelfServicePurchase
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001212"
- "3526"
ms.openlocfilehash: 587a05cccbc71a970d4bd7723bff0df0c3b64ccc
ms.sourcegitcommit: 2a9d059262c07c33f9a740b3da4e6e3366b2f925
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/20/2020
ms.locfileid: "42158578"
---
# <a name="unable-to-set-or-view-the-allowselfservicepurchase-policy"></a><span data-ttu-id="238a4-102">No se puede establecer ni ver la Directiva de AllowSelfServicePurchase</span><span class="sxs-lookup"><span data-stu-id="238a4-102">Unable to set or view the AllowSelfServicePurchase policy</span></span>

<span data-ttu-id="238a4-103">Al intentar establecer o ver la Directiva AllowSelfServicePurchase, recibe el siguiente mensaje de error:</span><span class="sxs-lookup"><span data-stu-id="238a4-103">When attempting to set or view the AllowSelfServicePurchase policy, you receive the following error message:</span></span>

<span data-ttu-id="238a4-104">*HandleError: no se pudo recuperar la Directiva de producto con PolicyId ' AllowSelfServicePurchase ', ErrorMessage-se ha cerrado la conexión subyacente: se ha producido un error inesperado en un envío.*</span><span class="sxs-lookup"><span data-stu-id="238a4-104">*HandleError : Failed to retrieve product policy with PolicyId 'AllowSelfServicePurchase', ErrorMessage - The underlying connection was closed: An unexpected error occurred on a send.*</span></span>

<span data-ttu-id="238a4-105">Esto puede deberse a una versión anterior de la seguridad de la capa de transporte (TLS).</span><span class="sxs-lookup"><span data-stu-id="238a4-105">This may be due to an older version of Transport Layer Security (TLS).</span></span> <span data-ttu-id="238a4-106">Para conectar el servicio MSCommerce, debe usar TLS 1,2 o posterior.</span><span class="sxs-lookup"><span data-stu-id="238a4-106">To connect the MSCommerce service, you need to use TLS 1.2 or greater.</span></span>  

<span data-ttu-id="238a4-107">Pruebe los pasos siguientes para habilitar o configurar el protocolo TLS en 1,2, comprobar y reintentar.</span><span class="sxs-lookup"><span data-stu-id="238a4-107">Try the following steps to enable/set the TLS protocol to 1.2, verify, and retry.</span></span>
 1. <span data-ttu-id="238a4-108">En el símbolo del sistema de PowerShell (PS\) C:, escriba el siguiente comando para establecer el protocolo TLS en la versión 1,2:</span><span class="sxs-lookup"><span data-stu-id="238a4-108">At the PowerShell command prompt (PS C:\) enter the following command to set the TLS protocol to version 1.2:</span></span>

    `[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12`

2. <span data-ttu-id="238a4-109">Compruebe el protocolo o los protocolos TLS en uso, con el siguiente comando:</span><span class="sxs-lookup"><span data-stu-id="238a4-109">Verify the TLS protocol(s) in use, with the following command:</span></span>

    `[Net.ServicePointManager]::SecurityProtocol` 

3. <span data-ttu-id="238a4-110">Vuelva a intentar los comandos GET o Update según sea necesario.</span><span class="sxs-lookup"><span data-stu-id="238a4-110">Retry the Get or Update commands as needed.</span></span>

