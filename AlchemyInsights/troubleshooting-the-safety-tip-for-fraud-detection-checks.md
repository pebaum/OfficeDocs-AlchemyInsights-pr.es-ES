---
title: Solución de problemas de la sugerencia de seguridad para la detección de loterías comprueba
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 1/9/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 96ebe3c5-66ea-4662-98b7-052c2181c2f3
ms.openlocfilehash: 24842e8cc5c6e47fb0eb637e6a3211637ede1ed8
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29491101"
---
# <a name="troubleshooting-the-safety-tip-for-fraud-detection-checks"></a>Solución de problemas de la sugerencia de seguridad para la detección de loterías comprueba

Si está obteniendo una sugerencia de seguridad dice "el remitente no pudo nuestras comprobaciones de detección de loterías y puede no ser que parecen ser", a continuación, el remitente no se pudo pasar comprobaciones de autenticación con DKIM o SPF. Es el mejor método para resolver este problema para que el remitente autorizar a sí mismos. Si el remitente está enviando en su nombre, debe autorizar a ellos mediante la adición de dirección IP del remitente para su registro SPF.
  
Para obtener más información, vea [solución de problemas de la punta de color rojo seguridad (sospechosos) para la detección de loterías comprueba](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) . 
  
A continuación presentamos algunos otros vínculos que pueden ayudar a:
  
- Cómo Office 365 usa el marco de directivas de remitente (SPF) para evitar la suplantación de identidad
    
- [Configurar SPF en Office 365 para ayudar a evitar la suplantación de identidad](https://docs.microsoft.com/en-us/office365/SecurityCompliance/set-up-spf-in-office-365-to-help-prevent-spoofing)
    

