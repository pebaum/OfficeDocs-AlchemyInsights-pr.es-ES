---
title: Error de envío de correo electrónico bloqueado por las SpamHaus
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 2/23/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: fa98ab4a-92eb-45e9-8d57-ad10fb123042
ms.openlocfilehash: a16c998d2f289ea2da52454819f6677c405381a1
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28314138"
---
# <a name="error-sending-email-client-host-blocked-using-spamhaus"></a>Error al enviar correo electrónico: host de cliente bloqueado mediante Spamhaus

La dirección IP que envió el mensaje está en una lista de bloqueo que pertenecen a las [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245). Motivos para que se han bloqueado por Spamhaus incluyen cuentas en peligro, en peligro máquinas uso compartido de una dirección IP pública y las directivas de proveedor de servicios de Internet (ISP). Las revisiones de posibles son:
  
- Para los mensajes entrantes bloqueados a Office 365 donde controlar el servidor de correo electrónico de origen, debe determinar la causa y quite el bloque de desde el sitio Web de Spamhaus.
    
- Para los mensajes entrantes bloqueados a Office 365 donde la dirección IP de origen pertenece a otro usuario, debe quitar el bloque desde el sitio Web de Spamhaus el propietario de la dirección. Si la dirección IP está en la lista de bloqueo de directiva (PBL), el propietario puede asignar una dirección IP estática diferente o quitar la dirección de la PBL.
    
- Para los mensajes salientes bloqueados desde su dominio de Office 365, puede recibir este error si los mensajes se enrutan a través de un servicio de terceros 3ª. Puede usar una herramienta de búsqueda WHOIS para encontrar el propietario de direcciones IP bloqueado.
    

