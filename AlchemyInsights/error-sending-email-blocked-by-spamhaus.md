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
ms.custom:
- "255"
- "3100003"
ms.assetid: fa98ab4a-92eb-45e9-8d57-ad10fb123042
ms.openlocfilehash: 39213f6f1b96c2bef9ea071f43c38766debf64d1
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36527159"
---
# <a name="error-sending-email-client-host-blocked-using-spamhaus"></a><span data-ttu-id="595f6-102">Error al enviar correo electrónico: host de cliente bloqueado con Spamhaus</span><span class="sxs-lookup"><span data-stu-id="595f6-102">Error sending email: Client host blocked using Spamhaus</span></span>

<span data-ttu-id="595f6-103">La dirección IP que envió el mensaje está en una lista de bloqueados perteneciente a [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245).</span><span class="sxs-lookup"><span data-stu-id="595f6-103">The IP address that sent the message is on a block list owned by [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245).</span></span> <span data-ttu-id="595f6-104">Los motivos por los que se bloquea Spamhaus incluyen cuentas comprometidas, equipos comprometidos que comparten una dirección IP pública y directivas de proveedor de servicios de Internet (ISP).</span><span class="sxs-lookup"><span data-stu-id="595f6-104">Reasons for being blocked by Spamhaus include compromised accounts, compromised machines sharing a public IP address, and Internet Service Provider (ISP) policies.</span></span> <span data-ttu-id="595f6-105">Las posibles soluciones son:</span><span class="sxs-lookup"><span data-stu-id="595f6-105">Possible fixes are:</span></span>
  
- <span data-ttu-id="595f6-106">Para los mensajes entrantes bloqueados a Office 365 donde se controla el servidor de correo electrónico de origen, debe determinar la causa y quitar el bloque del sitio web Spamhaus.</span><span class="sxs-lookup"><span data-stu-id="595f6-106">For blocked inbound messages to Office 365 where you control the source email server, you need to determine the cause and remove the block from the Spamhaus website.</span></span>

- <span data-ttu-id="595f6-107">Para los mensajes entrantes bloqueados a Office 365 donde la dirección IP de origen pertenece a otro usuario, el propietario de la dirección debe quitar el bloque del sitio web Spamhaus.</span><span class="sxs-lookup"><span data-stu-id="595f6-107">For blocked inbound messages to Office 365 where the source IP address belongs to someone else, the address owner needs to remove the block from the Spamhaus website.</span></span> <span data-ttu-id="595f6-108">Si la dirección IP está en la lista de bloqueo de directiva (PBL), el propietario puede asignar una dirección IP estática diferente o quitar la dirección de la PBL.</span><span class="sxs-lookup"><span data-stu-id="595f6-108">If the IP address is on the Policy Block List (PBL), the owner can assign a different static IP address or remove the address from the PBL.</span></span>

- <span data-ttu-id="595f6-109">Para los mensajes salientes bloqueados del dominio de Office 365, puede recibir este error si los mensajes se enrutan a través de un servicio de terceros.</span><span class="sxs-lookup"><span data-stu-id="595f6-109">For blocked outbound messages from your Office 365 domain, you can receive this error if the messages are routed through a 3rd party service.</span></span> <span data-ttu-id="595f6-110">Puede usar una herramienta de búsqueda WHOIS para buscar el propietario de direcciones IP bloqueadas.</span><span class="sxs-lookup"><span data-stu-id="595f6-110">You can use a WHOIS lookup tool to find the blocked IP address owner.</span></span>
