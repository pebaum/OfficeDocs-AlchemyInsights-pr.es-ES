---
title: Error de Winsock 1554 10061
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: 96a9cfd11941158ddf13655c74974e3eb800e570
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28313601"
---
# <a name="winsock-error-10061"></a>Error de Winsock 10061

Este código de error significa que Office 365 no se ha podido establecer un Sockets TCP (conexión) con el host de destino. La causa más probable de este error es un problema con la configuración del firewall. Para solucionar el problema, compruebe estas opciones:
  
- Compruebe la configuración del servidor de seguridad con la información de [las direcciones URL de Office 365 y los intervalos de direcciones IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)
    
- Si el error es específico para Exchange Online Protection (EOP), debe han sido previamente notificados a un cambio en las [direcciones IP de protección en línea de Exchange](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).
    
- Compruebe que su proveedor de servicios de Internet (ISP) no esté bloqueando el puerto.
    
- Compruebe la configuración del servidor host y de destino inteligente en los conectores.
    
Tenga en cuenta que Office 365 no bloquea las conexiones *entrantes* de esta manera. 
  

