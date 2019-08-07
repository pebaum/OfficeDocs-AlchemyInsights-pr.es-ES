---
title: 1332 OWA-las reglas de la bandeja de entrada no se ejecutan para un buzón
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 12/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1332"
- "3700002"
ms.assetid: 383d1c77-5e4b-4a69-92d6-c404d890b6b7
ms.openlocfilehash: 218a05a8d321b76dd07345ea48d6b3e158cc120e
ms.sourcegitcommit: 77f704672b7c7de541899e25c022ff10c111e304
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/05/2019
ms.locfileid: "36204077"
---
# <a name="an-inbox-rule-doesnt-work-as-expected"></a><span data-ttu-id="25a5a-102">Una regla de la bandeja de entrada no funciona como se esperaba</span><span class="sxs-lookup"><span data-stu-id="25a5a-102">An Inbox rule doesn't work as expected</span></span>

<span data-ttu-id="25a5a-103">Compruebe las siguientes opciones de configuración:</span><span class="sxs-lookup"><span data-stu-id="25a5a-103">Verify the following settings:</span></span>

- <span data-ttu-id="25a5a-104">Un mensaje puede redirigirse, reenviarse o responderse automáticamente en función de las reglas de la bandeja de entrada sólo una vez.</span><span class="sxs-lookup"><span data-stu-id="25a5a-104">A message can be redirected, forwarded, or replied to automatically based on Inbox rules only one time.</span></span> <span data-ttu-id="25a5a-105">Una regla de redireccionamiento (una regla de bandeja de entrada o una regla de flujo de correo, también denominada regla de transporte) puede Agregar un máximo de diez destinatarios de reenvío a un mensaje.</span><span class="sxs-lookup"><span data-stu-id="25a5a-105">A redirecting rule (an Inbox rule or mail flow rule, also known as a transport rule) can add a maximum of ten forwarding recipients to a message.</span></span> <span data-ttu-id="25a5a-106">Para obtener más información, vea los límites de las [reglas diario, transporte y bandeja de entrada](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).</span><span class="sxs-lookup"><span data-stu-id="25a5a-106">For more information, see [Journal, Transport, and Inbox rule limits](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).</span></span>

- <span data-ttu-id="25a5a-107">Las reglas de la bandeja de entrada no funcionan en el buzón de registro en diario alternativo.</span><span class="sxs-lookup"><span data-stu-id="25a5a-107">Inbox rules don't work on the alternate journaling mailbox.</span></span> <span data-ttu-id="25a5a-108">Para obtener más información acerca del buzón de correo de registro en diario alternativo, consulte [buzón de registro en diario alternativo](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).</span><span class="sxs-lookup"><span data-stu-id="25a5a-108">For more information about the alternate journaling mailbox, see [Alternate journaling mailbox](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).</span></span>

<span data-ttu-id="25a5a-109">Para solucionar estos problemas, consulte [KB 2829319](https://support.microsoft.com/kb/2829319).</span><span class="sxs-lookup"><span data-stu-id="25a5a-109">To fix these issues, see [KB 2829319](https://support.microsoft.com/kb/2829319).</span></span>

<span data-ttu-id="25a5a-110">Si no se aplican los problemas anteriores, ejecute el informe de diagnóstico de reglas de la bandeja de entrada antes de remitir el problema al soporte técnico de Microsoft:</span><span class="sxs-lookup"><span data-stu-id="25a5a-110">If the previous issues don't apply, run the Inbox rule diagnostic report before you escalate the issue to Microsoft Support:</span></span>

1. <span data-ttu-id="25a5a-111">Abra el buzón en Outlook en la web y haga clic en</span><span class="sxs-lookup"><span data-stu-id="25a5a-111">Open the mailbox in Outlook on the web, and click</span></span> <img src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAMAAABhEH5lAAAA51BMVEX6+fj6+fDr+fjK+fj69LRxsuj6+cjY+fi/+fin3ev6+ddMk81HdK5AaatHLn/ntXTrsW5cRmLOk0pAND5KNCl1NCOi3fiGwvjJ3fDBz+F6teFgpdt6stX68c314syTucirtchum8bjz8BQh7/6+b47fbrKtapiian63aFDaaHJuZJiQo36woVabH7ZtHiOQnTHm2wlKmqriWF/cFzVnVTFjlSyeUkrNEmBLkWfaUGsaT67fTrj9Pi19PjO8fiv5vj69OFWm9Pt3aZ1Qo0lNHQ1P2iYTWGOQmHcpV5kRlqvc0mrbERpPzMoEeekAAAAxElEQVQY03WQ5w6CUAyFy3Jv3HsrICoKqLj3fP/nsTcNakjsn9t+bW/OKfyL6iTCc49e/ktuRs2WEhE1U/qgQQfEzGkNyxzVXLdw0ASW+a7BZp3HpJ+cpovUjcv6PYtvSmKj4/SswTMaBgg9FQF5axWysKoson4cGMYCvlEAQDwK7XkZwEVbRBpDPC46ygbAbPl31p4Wvd8nwiRCLnIArJb1ZBD7KFWMkdQLSUVIhowsGaIwzzVHikfVV8lzHPv3OGTfTd4gnRNqGdZ49AAAAABJRU5ErkJggg==' />
 <span data-ttu-id="25a5a-112">**Configuración** > **ver todas** > \*\*\*\* > **las reglas**de correo de la configuración de Outlook.</span><span class="sxs-lookup"><span data-stu-id="25a5a-112">**Settings** > **View all Outlook Settings** > **Mail** > **Rules**.</span></span>

2. <span data-ttu-id="25a5a-113">En la parte inferior de la página, haga clic en **si las reglas no funcionan haga clic aquí para generar un informe de diagnóstico**.</span><span class="sxs-lookup"><span data-stu-id="25a5a-113">At the bottom of the page, click **If your rules are not working click here to generate a diagnostic report**.</span></span>
