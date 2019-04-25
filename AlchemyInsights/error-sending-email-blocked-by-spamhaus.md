---
title: Error al enviar correo electrónico bloqueado por SpamHaus
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 2/23/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: fa98ab4a-92eb-45e9-8d57-ad10fb123042
ms.openlocfilehash: 7d6ad2667613ae948a4abcefafe8d91cf89d2418
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "32402276"
---
# <a name="error-sending-email-client-host-blocked-using-spamhaus"></a>Error al enviar correo electrónico: host de cliente bloqueado con Spamhaus

La dirección IP que envió el mensaje está en una lista de bloqueados perteneciente a [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245). Los motivos por los que se bloquea Spamhaus incluyen cuentas comprometidas, equipos comprometidos que comparten una dirección IP pública y directivas de proveedor de servicios de Internet (ISP). Las posibles soluciones son:
  
- Para los mensajes entrantes bloqueados a Office 365 donde se controla el servidor de correo electrónico de origen, debe determinar la causa y quitar el bloque del sitio web Spamhaus.
    
- Para los mensajes entrantes bloqueados a Office 365 donde la dirección IP de origen pertenece a otro usuario, el propietario de la dirección debe quitar el bloque del sitio web Spamhaus. Si la dirección IP está en la lista de bloqueo de directiva (PBL), el propietario puede asignar una dirección IP estática diferente o quitar la dirección de la PBL.
    
- Para los mensajes salientes bloqueados del dominio de Office 365, puede recibir este error si los mensajes se enrutan a través de un servicio de terceros. Puede usar una herramienta de búsqueda WHOIS para buscar el propietario de direcciones IP bloqueadas.
    

