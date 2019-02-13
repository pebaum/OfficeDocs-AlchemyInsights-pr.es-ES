---
title: Error de envío de correo electrónico bloqueado por las SpamHaus
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 2/23/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: fa98ab4a-92eb-45e9-8d57-ad10fb123042
ms.openlocfilehash: 249f16d057b0539d71dc514ac35df28ab78fa061
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29912365"
---
# <a name="error-sending-email-client-host-blocked-using-spamhaus"></a><span data-ttu-id="a0753-102">Error al enviar correo electrónico: host de cliente bloqueado mediante Spamhaus</span><span class="sxs-lookup"><span data-stu-id="a0753-102">Error sending email: Client host blocked using Spamhaus</span></span>

<span data-ttu-id="a0753-p101">La dirección IP que envió el mensaje está en una lista de bloqueo que pertenecen a las [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245). Motivos para que se han bloqueado por Spamhaus incluyen cuentas en peligro, en peligro máquinas uso compartido de una dirección IP pública y las directivas de proveedor de servicios de Internet (ISP). Las revisiones de posibles son:</span><span class="sxs-lookup"><span data-stu-id="a0753-p101">The IP address that sent the message is on a block list owned by [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245). Reasons for being blocked by Spamhaus include compromised accounts, compromised machines sharing a public IP address, and Internet Service Provider (ISP) policies. Possible fixes are:</span></span>
  
- <span data-ttu-id="a0753-106">Para los mensajes entrantes bloqueados a Office 365 donde controlar el servidor de correo electrónico de origen, debe determinar la causa y quite el bloque de desde el sitio Web de Spamhaus.</span><span class="sxs-lookup"><span data-stu-id="a0753-106">For blocked inbound messages to Office 365 where you control the source email server, you need to determine the cause and remove the block from the Spamhaus website.</span></span>
    
- <span data-ttu-id="a0753-p102">Para los mensajes entrantes bloqueados a Office 365 donde la dirección IP de origen pertenece a otro usuario, debe quitar el bloque desde el sitio Web de Spamhaus el propietario de la dirección. Si la dirección IP está en la lista de bloqueo de directiva (PBL), el propietario puede asignar una dirección IP estática diferente o quitar la dirección de la PBL.</span><span class="sxs-lookup"><span data-stu-id="a0753-p102">For blocked inbound messages to Office 365 where the source IP address belongs to someone else, the address owner needs to remove the block from the Spamhaus website. If the IP address is on the Policy Block List (PBL), the owner can assign a different static IP address or remove the address from the PBL.</span></span>
    
- <span data-ttu-id="a0753-p103">Para los mensajes salientes bloqueados desde su dominio de Office 365, puede recibir este error si los mensajes se enrutan a través de un servicio de terceros 3ª. Puede usar una herramienta de búsqueda WHOIS para encontrar el propietario de direcciones IP bloqueado.</span><span class="sxs-lookup"><span data-stu-id="a0753-p103">For blocked outbound messages from your Office 365 domain, you can receive this error if the messages are routed through a 3rd party service. You can use a WHOIS lookup tool to find the blocked IP address owner.</span></span>
    

