---
title: Trabajar con iOS VPP aplicaciones regla identificador 1018
ms.author: pebaum
author: pebaum
ms.date: 9/10/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 2e51ae64-8ba2-42e1-9e3e-f4aad102c391
ms.openlocfilehash: 5bcfb6dd7222bd102ff2620c19bfb943e7bd9591
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28314397"
---
# <a name="working-with-ios-vpp-applications"></a>Trabajar con iOS VPP aplicaciones

Lea [cómo administrar aplicaciones de iOS adquiridas a través de un programa de compra de volumen con Intune de Microsoft](https://docs.microsoft.com/intune/vpp-apps-ios) para obtener más información sobre las características, las restricciones y los pasos para realizar el uso del programa de compra de Apple por volumen y la compatibilidad para él en Microsoft Intune. 
  
 **Problemas comunes:** "He asignado una aplicación de iOS VPP a Mis usuarios, pero la instalación no se pudo". 
  
- Esto puede ocurrir si se usa un símbolo (token) VPP único a través de varios proveedores de administración de dispositivos móviles. Los tokens de VPP desde Apple sólo se pueden usar con un proveedor. Si usa un símbolo (token) VPP con varios proveedores, que debe volver a cargar el token a Intune.
    
- También puede producirse un error en la instalación si el número total de instalaciones excede el número de licencias. Para ver un informe de uso de las licencias, vaya a las **aplicaciones de Intune Mobile** \> página **licencias de aplicaciones** . Para obtener información sobre cómo recuperar licencias en uso, vea [en este artículo.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)
    

