---
title: ¿Necesita ayuda con los límites de envío de correo electrónico?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002938"
- "5630"
ms.openlocfilehash: 7f563df313c869d18c3e4240d271c649a74914af
ms.sourcegitcommit: 88d2918aa51f4ba10771527380c3e0db0f5a9147
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 05/20/2020
ms.locfileid: "44328807"
---
# <a name="need-help-with-email-sending-limits"></a><span data-ttu-id="8bd49-102">¿Necesita ayuda con los límites de envío de correo electrónico?</span><span class="sxs-lookup"><span data-stu-id="8bd49-102">Need help with email sending limits?</span></span>

<span data-ttu-id="8bd49-103">A continuación se muestran los **límites de envío por diseño** aplicados en el servicio.</span><span class="sxs-lookup"><span data-stu-id="8bd49-103">Below is the **by-design sending limits** enforced in the service.</span></span> <span data-ttu-id="8bd49-104">Más información sobre estos límites [aquí](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#receiving-and-sending-limits).</span><span class="sxs-lookup"><span data-stu-id="8bd49-104">More information on these limits is documented [here](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#receiving-and-sending-limits).</span></span>

- <span data-ttu-id="8bd49-105">Para desalentar la entrega de mensajes masivos no solicitados, aplicamos **límites de tasa de destinatario por usuario a todos los mensajes salientes e internos**.</span><span class="sxs-lookup"><span data-stu-id="8bd49-105">To discourage the delivery of unsolicited bulk messages, we apply per-user **recipient rate limits to all outbound and internal messages**.</span></span> <span data-ttu-id="8bd49-106">En todas las SKU, este límite es **10 000 destinatarios por día**.</span><span class="sxs-lookup"><span data-stu-id="8bd49-106">Across all SKUs, this limit is **10,000 recipients per day**.</span></span>  <span data-ttu-id="8bd49-107">Los clientes que deban enviar un correo electrónico comercial masivo válido (por ejemplo, boletines para clientes) deberían usar proveedores de terceros especializados en dichos servicios.</span><span class="sxs-lookup"><span data-stu-id="8bd49-107">Customers who need to send legitimate bulk commercial email (for example, customer newsletters) should use third-party providers that specialize in these services.</span></span>
    - <span data-ttu-id="8bd49-108">**Nota**: una vez que se alcanza el límite de tasa de destinatarios, no se pueden enviar mensajes desde el buzón de correo hasta que la cantidad de destinatarios a los que se enviaron mensajes en las últimas 24 horas baje por debajo del límite.</span><span class="sxs-lookup"><span data-stu-id="8bd49-108">**Note**: Once the recipient rate limit is reached, messages can't be sent from the mailbox until the number of recipients that were sent messages in the past 24 hours drops below the limit.</span></span> <span data-ttu-id="8bd49-109">El usuario no podrá enviar mensajes hasta ese momento.</span><span class="sxs-lookup"><span data-stu-id="8bd49-109">The user will not be able to send messages until that point.</span></span>
- <span data-ttu-id="8bd49-110">Se aplica un límite de tasa de mensajes de **30 mensajes por minuto** en todas las SKU.</span><span class="sxs-lookup"><span data-stu-id="8bd49-110">Message rate limit of **30 messages per minute** is applied across all SKUs.</span></span> <span data-ttu-id="8bd49-111">Esto determina cuántos mensajes puede enviar un usuario desde la cuenta de Exchange online en un período de tiempo especificado.</span><span class="sxs-lookup"><span data-stu-id="8bd49-111">This determines how many messages a user can send from their Exchange Online account within a specified period.</span></span>
- <span data-ttu-id="8bd49-112">El **número máximo de destinatarios permitido en los campos Para, CC y CCO** para un solo mensaje de correo electrónico, en todas las SKU, es **1 000 destinatarios**.</span><span class="sxs-lookup"><span data-stu-id="8bd49-112">The **maximum number of recipients allowed in the To, Cc, and Bcc** fields for a single email message, across all SKUs, is **1000 recipients**.</span></span> <span data-ttu-id="8bd49-113">Para personalizar este límite, vaya [aquí](https://techcommunity.microsoft.com/t5/exchange-team-blog/customizable-recipient-limits-in-office-365/ba-p/1183228).</span><span class="sxs-lookup"><span data-stu-id="8bd49-113">To customize this limit, go [here](https://techcommunity.microsoft.com/t5/exchange-team-blog/customizable-recipient-limits-in-office-365/ba-p/1183228).</span></span>
