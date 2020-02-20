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
# <a name="unable-to-set-or-view-the-allowselfservicepurchase-policy"></a>No se puede establecer ni ver la Directiva de AllowSelfServicePurchase

Al intentar establecer o ver la Directiva AllowSelfServicePurchase, recibe el siguiente mensaje de error:

*HandleError: no se pudo recuperar la Directiva de producto con PolicyId ' AllowSelfServicePurchase ', ErrorMessage-se ha cerrado la conexión subyacente: se ha producido un error inesperado en un envío.*

Esto puede deberse a una versión anterior de la seguridad de la capa de transporte (TLS). Para conectar el servicio MSCommerce, debe usar TLS 1,2 o posterior.  

Pruebe los pasos siguientes para habilitar o configurar el protocolo TLS en 1,2, comprobar y reintentar.
 1. En el símbolo del sistema de PowerShell (PS\) C:, escriba el siguiente comando para establecer el protocolo TLS en la versión 1,2:

    `[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12`

2. Compruebe el protocolo o los protocolos TLS en uso, con el siguiente comando:

    `[Net.ServicePointManager]::SecurityProtocol` 

3. Vuelva a intentar los comandos GET o Update según sea necesario.

