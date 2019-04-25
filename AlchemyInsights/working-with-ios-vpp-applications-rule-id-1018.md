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
# <a name="working-with-ios-vpp-applications"></a>Trabajar con aplicaciones de PCV para iOS

Obtenga información sobre [Cómo administrar aplicaciones de iOS adquiridas a través de un programa de compras por volumen con Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) para obtener información sobre las características, las restricciones y los pasos para usar el programa de compras por volumen de Apple y la compatibilidad en Microsoft Intune. 
  
 **Problemas comunes:** "He asignado una aplicación de PCV de iOS a mis usuarios, pero se produjo un error en la instalación". 
  
- Esto puede ocurrir si se usa un token de PCV único en varios proveedores de administración de dispositivos móviles. Los tokens de PCV de Apple solo se pueden usar con un proveedor. Si usó un token de PCV con varios proveedores, debe volver a cargar el token en Intune.
    
- La instalación también puede fallar si el número total de instalaciones supera el número de licencias. Para ver un informe de uso de las licencias, vaya a la página **licencias** de aplicaciones **móviles** \> de Intune. Para obtener información sobre cómo reclamar licencias en uso, vea [este artículo.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)
    

