---
title: Uso del identificador de regla 1018 de las aplicaciones de PCV para iOS
ms.author: pebaum
author: pebaum
ms.date: 9/10/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1018"
- "6700004"
ms.assetid: 2e51ae64-8ba2-42e1-9e3e-f4aad102c391
ms.openlocfilehash: a0bbc1f49f251ef4f16300c8cca98e219008d17e
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36558022"
---
# <a name="working-with-ios-vpp-applications"></a><span data-ttu-id="c683b-102">Trabajar con aplicaciones de PCV para iOS</span><span class="sxs-lookup"><span data-stu-id="c683b-102">Working with iOS VPP Applications</span></span>

<span data-ttu-id="c683b-103">Obtenga información sobre [Cómo administrar aplicaciones de iOS adquiridas a través de un programa de compras por volumen con Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) para obtener información sobre las características, las restricciones y los pasos para usar el programa de compras por volumen de Apple y la compatibilidad en Microsoft Intune.</span><span class="sxs-lookup"><span data-stu-id="c683b-103">Read [How to manage iOS apps purchased through a volume-purchase program with Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) to learn about features, constraints, and steps to make use of the Apple Volume Purchase Program and the support for it in Microsoft Intune.</span></span>
  
 <span data-ttu-id="c683b-104">**Problemas comunes:** "He asignado una aplicación de PCV de iOS a mis usuarios, pero se produjo un error en la instalación".</span><span class="sxs-lookup"><span data-stu-id="c683b-104">**Common Issues:** "I assigned an iOS VPP app to my users, but the installation failed."</span></span>
  
- <span data-ttu-id="c683b-105">Esto puede ocurrir si se usa un token de PCV único en varios proveedores de administración de dispositivos móviles.</span><span class="sxs-lookup"><span data-stu-id="c683b-105">This can happen if a single VPP token is used across multiple mobile device management providers.</span></span> <span data-ttu-id="c683b-106">Los tokens de PCV de Apple solo se pueden usar con un proveedor.</span><span class="sxs-lookup"><span data-stu-id="c683b-106">VPP tokens from Apple may only be used with one provider.</span></span> <span data-ttu-id="c683b-107">Si usó un token de PCV con varios proveedores, debe volver a cargar el token en Intune.</span><span class="sxs-lookup"><span data-stu-id="c683b-107">If you used a VPP token with multiple providers, you must re-upload the token to Intune.</span></span>

- <span data-ttu-id="c683b-108">La instalación también puede fallar si el número total de instalaciones supera el número de licencias.</span><span class="sxs-lookup"><span data-stu-id="c683b-108">The installation can also fail if the total number of installations exceed the number of licenses.</span></span> <span data-ttu-id="c683b-109">Para ver un informe de uso de las licencias, vaya a la página **licencias** de aplicaciones **móviles** \> de Intune.</span><span class="sxs-lookup"><span data-stu-id="c683b-109">To view a usage report for your licenses, go to the **Intune Mobile apps** \> **App licenses** page.</span></span> <span data-ttu-id="c683b-110">Para obtener información sobre cómo reclamar licencias en uso, vea [este artículo.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span><span class="sxs-lookup"><span data-stu-id="c683b-110">To learn how to reclaim licenses in use, see [this article.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span></span>
