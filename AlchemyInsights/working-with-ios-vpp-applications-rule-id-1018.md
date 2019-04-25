---
title: Uso del identificador de regla 1018 de las aplicaciones de PCV para iOS
ms.author: pebaum
author: pebaum
ms.date: 9/10/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 2e51ae64-8ba2-42e1-9e3e-f4aad102c391
ms.openlocfilehash: 65b9a727171a7551068717f6327f15e1aa8e6bed
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "32420501"
---
# <a name="working-with-ios-vpp-applications"></a><span data-ttu-id="ecb72-102">Trabajar con aplicaciones de PCV para iOS</span><span class="sxs-lookup"><span data-stu-id="ecb72-102">Working with iOS VPP Applications</span></span>

<span data-ttu-id="ecb72-103">Obtenga información sobre [Cómo administrar aplicaciones de iOS adquiridas a través de un programa de compras por volumen con Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) para obtener información sobre las características, las restricciones y los pasos para usar el programa de compras por volumen de Apple y la compatibilidad en Microsoft Intune.</span><span class="sxs-lookup"><span data-stu-id="ecb72-103">Read [How to manage iOS apps purchased through a volume-purchase program with Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) to learn about features, constraints, and steps to make use of the Apple Volume Purchase Program and the support for it in Microsoft Intune.</span></span> 
  
 <span data-ttu-id="ecb72-104">**Problemas comunes:** "He asignado una aplicación de PCV de iOS a mis usuarios, pero se produjo un error en la instalación".</span><span class="sxs-lookup"><span data-stu-id="ecb72-104">**Common Issues:** "I assigned an iOS VPP app to my users, but the installation failed."</span></span> 
  
- <span data-ttu-id="ecb72-105">Esto puede ocurrir si se usa un token de PCV único en varios proveedores de administración de dispositivos móviles.</span><span class="sxs-lookup"><span data-stu-id="ecb72-105">This can happen if a single VPP token is used across multiple mobile device management providers.</span></span> <span data-ttu-id="ecb72-106">Los tokens de PCV de Apple solo se pueden usar con un proveedor.</span><span class="sxs-lookup"><span data-stu-id="ecb72-106">VPP tokens from Apple may only be used with one provider.</span></span> <span data-ttu-id="ecb72-107">Si usó un token de PCV con varios proveedores, debe volver a cargar el token en Intune.</span><span class="sxs-lookup"><span data-stu-id="ecb72-107">If you used a VPP token with multiple providers, you must re-upload the token to Intune.</span></span>
    
- <span data-ttu-id="ecb72-108">La instalación también puede fallar si el número total de instalaciones supera el número de licencias.</span><span class="sxs-lookup"><span data-stu-id="ecb72-108">The installation can also fail if the total number of installations exceed the number of licenses.</span></span> <span data-ttu-id="ecb72-109">Para ver un informe de uso de las licencias, vaya a la página **licencias** de aplicaciones **móviles** \> de Intune.</span><span class="sxs-lookup"><span data-stu-id="ecb72-109">To view a usage report for your licenses, go to the **Intune Mobile apps** \> **App licenses** page.</span></span> <span data-ttu-id="ecb72-110">Para obtener información sobre cómo reclamar licencias en uso, vea [este artículo.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span><span class="sxs-lookup"><span data-stu-id="ecb72-110">To learn how to reclaim licenses in use, see [this article.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span></span>
    

