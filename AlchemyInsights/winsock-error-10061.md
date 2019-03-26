---
title: 1554 error de Winsock 10061
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1554
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: f44ed42906b85e63f1f694813f54710906969904
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/22/2019
ms.locfileid: "30772458"
---
# <a name="winsock-error-10061"></a>Error de Winsock 10061

Este código de error significa que Office 365 no pudo establecer un socket TCP (conexión) con el host de destino. La causa más probable de este error es un problema con la configuración del firewall. Para solucionar el problema, compruebe estas opciones:
  
- Compruebe la configuración del firewall con la información de las [direcciones URL y los intervalos de direcciones IP de Office 365](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)
    
- Si el error es específico de Exchange Online Protection (EOP), debería haber notificado previamente a un cambio en las [direcciones IP de Exchange Online Protection](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).
    
- Compruebe que el proveedor de servicios de Internet (ISP) no está bloqueando el puerto.
    
- Compruebe la configuración del host inteligente y del servidor de destino en los conectores.
    
Tenga en cuenta que Office 365 ** no bloquea las conexiones entrantes de esta manera. 
  
