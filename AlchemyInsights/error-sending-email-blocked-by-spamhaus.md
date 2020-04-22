---
title: Error al enviar correo electrónico bloqueado por SpamHaus
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "255"
- "3100003"
ms.assetid: fa98ab4a-92eb-45e9-8d57-ad10fb123042
ms.openlocfilehash: 3ff4f7a155fe74f5b42a1bd43e67ef0a751d7fbd
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43714275"
---
# <a name="error-sending-email-client-host-blocked-using-spamhaus"></a>Error al enviar correo electrónico: host de cliente bloqueado con Spamhaus

La dirección IP que envió el mensaje está en una lista de bloqueados perteneciente a [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245). Los motivos por los que se bloquea Spamhaus incluyen cuentas comprometidas, equipos comprometidos que comparten una dirección IP pública y directivas de proveedor de servicios de Internet (ISP). Las posibles soluciones son:
  
- Para los mensajes entrantes bloqueados donde se controla el servidor de correo electrónico de origen, debe determinar la causa y quitar el bloque del sitio web Spamhaus.

- Para los mensajes entrantes bloqueados donde la dirección IP de origen pertenece a otro usuario, el propietario de la dirección debe quitar el bloque del sitio web Spamhaus. Si la dirección IP está en la lista de bloqueo de directiva (PBL), el propietario puede asignar una dirección IP estática diferente o quitar la dirección de la PBL.

- Para los mensajes salientes bloqueados desde su dominio conectado a Microsoft, puede recibir este error si los mensajes se enrutan a través de un servicio de terceros. Puede usar una herramienta de búsqueda WHOIS para buscar el propietario de direcciones IP bloqueadas.
