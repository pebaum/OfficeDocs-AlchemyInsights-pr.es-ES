---
title: 1554 error de Winsock 10061
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1554"
- "9000079"
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: e8f62d97efc937518ef766b45e1747e83b7f99c3
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766186"
---
# <a name="winsock-error-10061"></a>Error de Winsock 10061

Este código de error significa que Microsoft no pudo establecer un socket TCP (conexión) con el host de destino. La causa más probable de este error es un problema con la configuración del firewall. Para solucionar el problema, compruebe estas opciones:

- Compruebe la configuración del firewall con la información de las [direcciones URL y los intervalos de direcciones IP de Microsoft 365](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)

- Si el error es específico de Exchange Online Protection (EOP), debería haber notificado previamente a un cambio en las [direcciones IP de Exchange Online Protection](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).

- Compruebe que el proveedor de servicios de Internet (ISP) no está bloqueando el puerto.

- Compruebe la configuración del host inteligente y del servidor de destino en los conectores.

Tenga en cuenta que Microsoft 365 no bloquea las conexiones *entrantes* de esta manera.
