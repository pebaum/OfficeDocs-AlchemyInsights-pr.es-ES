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
# <a name="error-sending-email-client-host-blocked-using-spamhaus"></a><span data-ttu-id="870ee-102">Error al enviar correo electrónico: host de cliente bloqueado con Spamhaus</span><span class="sxs-lookup"><span data-stu-id="870ee-102">Error sending email: Client host blocked using Spamhaus</span></span>

<span data-ttu-id="870ee-103">La dirección IP que envió el mensaje está en una lista de bloqueados perteneciente a [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245).</span><span class="sxs-lookup"><span data-stu-id="870ee-103">The IP address that sent the message is on a block list owned by [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245).</span></span> <span data-ttu-id="870ee-104">Los motivos por los que se bloquea Spamhaus incluyen cuentas comprometidas, equipos comprometidos que comparten una dirección IP pública y directivas de proveedor de servicios de Internet (ISP).</span><span class="sxs-lookup"><span data-stu-id="870ee-104">Reasons for being blocked by Spamhaus include compromised accounts, compromised machines sharing a public IP address, and Internet Service Provider (ISP) policies.</span></span> <span data-ttu-id="870ee-105">Las posibles soluciones son:</span><span class="sxs-lookup"><span data-stu-id="870ee-105">Possible fixes are:</span></span>
  
- <span data-ttu-id="870ee-106">Para los mensajes entrantes bloqueados donde se controla el servidor de correo electrónico de origen, debe determinar la causa y quitar el bloque del sitio web Spamhaus.</span><span class="sxs-lookup"><span data-stu-id="870ee-106">For blocked inbound messages where you control the source email server, you need to determine the cause and remove the block from the Spamhaus website.</span></span>

- <span data-ttu-id="870ee-107">Para los mensajes entrantes bloqueados donde la dirección IP de origen pertenece a otro usuario, el propietario de la dirección debe quitar el bloque del sitio web Spamhaus.</span><span class="sxs-lookup"><span data-stu-id="870ee-107">For blocked inbound messages where the source IP address belongs to someone else, the address owner needs to remove the block from the Spamhaus website.</span></span> <span data-ttu-id="870ee-108">Si la dirección IP está en la lista de bloqueo de directiva (PBL), el propietario puede asignar una dirección IP estática diferente o quitar la dirección de la PBL.</span><span class="sxs-lookup"><span data-stu-id="870ee-108">If the IP address is on the Policy Block List (PBL), the owner can assign a different static IP address or remove the address from the PBL.</span></span>

- <span data-ttu-id="870ee-109">Para los mensajes salientes bloqueados desde su dominio conectado a Microsoft, puede recibir este error si los mensajes se enrutan a través de un servicio de terceros.</span><span class="sxs-lookup"><span data-stu-id="870ee-109">For blocked outbound messages from your domain connected to Microsoft, you can receive this error if the messages are routed through a 3rd party service.</span></span> <span data-ttu-id="870ee-110">Puede usar una herramienta de búsqueda WHOIS para buscar el propietario de direcciones IP bloqueadas.</span><span class="sxs-lookup"><span data-stu-id="870ee-110">You can use a WHOIS lookup tool to find the blocked IP address owner.</span></span>
