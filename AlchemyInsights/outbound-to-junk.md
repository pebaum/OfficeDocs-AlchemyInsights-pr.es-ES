---
title: Correo electrónico saliente a la carpeta correo electrónico no deseado
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2697"
ms.assetid: ''
ms.openlocfilehash: 2350586e95f316061ff855d152e86db0547eb209
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43761185"
---
# <a name="outbound-email-to-junk-email-folder"></a><span data-ttu-id="3544b-102">Correo electrónico saliente a la carpeta correo electrónico no deseado</span><span class="sxs-lookup"><span data-stu-id="3544b-102">Outbound email to Junk Email folder</span></span>

<span data-ttu-id="3544b-103">Si ve los mensajes salientes que se marcan como correo no deseado, siga estos pasos:</span><span class="sxs-lookup"><span data-stu-id="3544b-103">If you're seeing outbound messages being marked as Junk, do the following steps:</span></span>

- <span data-ttu-id="3544b-104">Si todavía no lo ha hecho, considere la posibilidad de [configurar notificaciones de directivas de correo no deseado salientes](https://docs.microsoft.com/office365/securitycompliance/configure-the-outbound-spam-policy).</span><span class="sxs-lookup"><span data-stu-id="3544b-104">If you haven't already, consider [configuring outbound spam policy notifications](https://docs.microsoft.com/office365/securitycompliance/configure-the-outbound-spam-policy).</span></span>

- <span data-ttu-id="3544b-105">Use el [seguimiento de mensajes](https://docs.microsoft.com/office365/securitycompliance/message-trace-scc) para ver si el mensaje saliente tiene el valor de evento **correo no deseado** con los detalles adicionales: **usar grupo de entrega de alto riesgo**.</span><span class="sxs-lookup"><span data-stu-id="3544b-105">Use [message trace](https://docs.microsoft.com/office365/securitycompliance/message-trace-scc) to see if the outbound message has the event value **Spam** with the additional detail: **Use high risk delivery pool**.</span></span>

  <span data-ttu-id="3544b-106">Para estos mensajes, compruebe el contenido del mensaje para ver lo que puede considerarse como correo no deseado.</span><span class="sxs-lookup"><span data-stu-id="3544b-106">For these messages, check the message content to see what might be considered spam.</span></span> <span data-ttu-id="3544b-107">Por ejemplo, las firmas pueden causar problemas a muchos usuarios.</span><span class="sxs-lookup"><span data-stu-id="3544b-107">For example, signatures can sometimes cause problems for many users.</span></span>

  <span data-ttu-id="3544b-108">Si tiene varios ejemplos de mensajes salientes legítimos que se marcan como correo no deseado, abra una incidencia de soporte técnico y solicite al agente de soporte técnico que envíe sus mensajes como falsos positivos a nuestros analistas de correo no deseado.</span><span class="sxs-lookup"><span data-stu-id="3544b-108">If you have multiple examples of legitimate outbound messages that are being marked as Junk, open a support ticket and ask the support agent to submit your messages as false positives to our spam analysts.</span></span> <span data-ttu-id="3544b-109">Prepárese para proporcionar mensajes de ejemplo que incluyan todos los encabezados de mensajes.</span><span class="sxs-lookup"><span data-stu-id="3544b-109">Be prepared to provide sample messages that include all message headers.</span></span>
