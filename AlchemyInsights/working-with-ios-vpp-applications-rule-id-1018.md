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
# <a name="working-with-ios-vpp-applications"></a>Trabajar con aplicaciones de PCV para iOS

Obtenga información sobre [Cómo administrar aplicaciones de iOS adquiridas a través de un programa de compras por volumen con Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) para obtener información sobre las características, las restricciones y los pasos para usar el programa de compras por volumen de Apple y la compatibilidad en Microsoft Intune.
  
 **Problemas comunes:** "He asignado una aplicación de PCV de iOS a mis usuarios, pero se produjo un error en la instalación".
  
- Esto puede ocurrir si se usa un token de PCV único en varios proveedores de administración de dispositivos móviles. Los tokens de PCV de Apple solo se pueden usar con un proveedor. Si usó un token de PCV con varios proveedores, debe volver a cargar el token en Intune.

- La instalación también puede fallar si el número total de instalaciones supera el número de licencias. Para ver un informe de uso de las licencias, vaya a la página **licencias** de aplicaciones **móviles** \> de Intune. Para obtener información sobre cómo reclamar licencias en uso, vea [este artículo.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)
