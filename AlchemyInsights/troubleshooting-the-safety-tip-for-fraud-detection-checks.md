---
title: Solución de problemas de la sugerencia de seguridad para las comprobaciones de detección de fraude
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 1/9/2019
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 96ebe3c5-66ea-4662-98b7-052c2181c2f3
ms.custom:
- "275"
- "3100004"
ms.openlocfilehash: ab7bd3ec66640d66e5f1ea7c1eeee0a1a9510241
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/28/2019
ms.locfileid: "35353266"
---
# <a name="troubleshooting-the-safety-tip-for-fraud-detection-checks"></a>Solución de problemas de la sugerencia de seguridad para las comprobaciones de detección de fraude

Si está recibiendo una sugerencia de seguridad que dice "el remitente produjo un error en nuestras comprobaciones de detección de fraude y puede no ser quien parece ser", entonces el remitente no ha podido pasar comprobaciones de autenticación DKIM o SPF. El mejor método para resolver esto es que el remitente autorice a sí mismo. Si el remitente está enviando en su nombre, debe autorizarlos agregando la dirección IP del remitente a su registro de SPF.
  
Consulte [solución de problemas de la sugerencia de seguridad en rojo (sospechoso) para](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) las comprobaciones de detección de fraude para obtener más información.
  
Estos son otros vínculos que pueden ayudarle:
  
- [Cómo Office 365 usa el marco de directivas de remitente (SPF) para evitar la suplantación de identidad](https://docs.microsoft.com/office365/SecurityCompliance/how-office-365-uses-spf-to-prevent-spoofing)

- [Configurar SPF en Office 365 para ayudar a evitar la suplantación de identidad](https://docs.microsoft.com/office365/SecurityCompliance/set-up-spf-in-office-365-to-help-prevent-spoofing)
