---
title: Trabajar con iOS VPP aplicaciones regla identificador 1018
ms.author: pebaum
author: pebaum
ms.date: 9/10/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 2e51ae64-8ba2-42e1-9e3e-f4aad102c391
ms.openlocfilehash: 65b9a727171a7551068717f6327f15e1aa8e6bed
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29917513"
---
# <a name="working-with-ios-vpp-applications"></a><span data-ttu-id="876b1-102">Trabajar con iOS VPP aplicaciones</span><span class="sxs-lookup"><span data-stu-id="876b1-102">Working with iOS VPP Applications</span></span>

<span data-ttu-id="876b1-103">Lea [cómo administrar aplicaciones de iOS adquiridas a través de un programa de compra de volumen con Intune de Microsoft](https://docs.microsoft.com/intune/vpp-apps-ios) para obtener más información sobre las características, las restricciones y los pasos para realizar el uso del programa de compra de Apple por volumen y la compatibilidad para él en Microsoft Intune.</span><span class="sxs-lookup"><span data-stu-id="876b1-103">Read [How to manage iOS apps purchased through a volume-purchase program with Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) to learn about features, constraints, and steps to make use of the Apple Volume Purchase Program and the support for it in Microsoft Intune.</span></span> 
  
 <span data-ttu-id="876b1-104">**Problemas comunes:** "He asignado una aplicación de iOS VPP a Mis usuarios, pero la instalación no se pudo".</span><span class="sxs-lookup"><span data-stu-id="876b1-104">**Common Issues:** "I assigned an iOS VPP app to my users, but the installation failed."</span></span> 
  
- <span data-ttu-id="876b1-p101">Esto puede ocurrir si se usa un símbolo (token) VPP único a través de varios proveedores de administración de dispositivos móviles. Los tokens de VPP desde Apple sólo se pueden usar con un proveedor. Si usa un símbolo (token) VPP con varios proveedores, que debe volver a cargar el token a Intune.</span><span class="sxs-lookup"><span data-stu-id="876b1-p101">This can happen if a single VPP token is used across multiple mobile device management providers. VPP tokens from Apple may only be used with one provider. If you used a VPP token with multiple providers, you must re-upload the token to Intune.</span></span>
    
- <span data-ttu-id="876b1-p102">También puede producirse un error en la instalación si el número total de instalaciones excede el número de licencias. Para ver un informe de uso de las licencias, vaya a las **aplicaciones de Intune Mobile** \> página **licencias de aplicaciones** . Para obtener información sobre cómo recuperar licencias en uso, vea [en este artículo.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span><span class="sxs-lookup"><span data-stu-id="876b1-p102">The installation can also fail if the total number of installations exceed the number of licenses. To view a usage report for your licenses, go to the **Intune Mobile apps** \> **App licenses** page. To learn how to reclaim licenses in use, see [this article.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span></span>
    

