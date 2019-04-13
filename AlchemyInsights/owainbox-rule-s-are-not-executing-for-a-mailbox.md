---
title: 1332 OWA-las reglas de la bandeja de entrada no se ejecutan para un buzón
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1332
ms.assetid: 383d1c77-5e4b-4a69-92d6-c404d890b6b7
ms.openlocfilehash: c0b221b5335254bd0f1eb4b258efa6946376ca12
ms.sourcegitcommit: 1a4b8fa9e38a95ca811085af516edb81caf2018c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/13/2019
ms.locfileid: "31858761"
---
# <a name="an-inbox-rule-doesnt-work-as-expected"></a><span data-ttu-id="80d76-102">Una regla de la bandeja de entrada no funciona como se esperaba</span><span class="sxs-lookup"><span data-stu-id="80d76-102">An Inbox rule doesn't work as expected</span></span>

<span data-ttu-id="80d76-103">Compruebe las siguientes opciones de configuración:</span><span class="sxs-lookup"><span data-stu-id="80d76-103">Verify the following settings:</span></span>

- <span data-ttu-id="80d76-104">Un mensaje puede redirigirse, reenviarse o responderse automáticamente en función de las reglas de la bandeja de entrada sólo una vez.</span><span class="sxs-lookup"><span data-stu-id="80d76-104">A message can be redirected, forwarded, or replied to automatically based on Inbox rules only one time.</span></span> <span data-ttu-id="80d76-105">Una regla de redireccionamiento (una regla de bandeja de entrada o una regla de flujo de correo, también denominada regla de transporte) puede Agregar un máximo de diez destinatarios de reenvío a un mensaje.</span><span class="sxs-lookup"><span data-stu-id="80d76-105">A redirecting rule (an Inbox rule or mail flow rule, also known as a transport rule) can add a maximum of ten forwarding recipients to a message.</span></span> <span data-ttu-id="80d76-106">Para obtener más información, vea los límites de las [reglas diario, transporte y bandeja de entrada](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).</span><span class="sxs-lookup"><span data-stu-id="80d76-106">For more information, see [Journal, Transport, and Inbox rule limits](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).</span></span>

- <span data-ttu-id="80d76-107">Las reglas de la bandeja de entrada no funcionan en el buzón de registro en diario alternativo.</span><span class="sxs-lookup"><span data-stu-id="80d76-107">Inbox rules don't work on the alternate journaling mailbox.</span></span> <span data-ttu-id="80d76-108">Para obtener más información acerca del buzón de correo de registro en diario alternativo, consulte [buzón de registro en diario alternativo](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).</span><span class="sxs-lookup"><span data-stu-id="80d76-108">For more information about the alternate journaling mailbox, see [Alternate journaling mailbox](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).</span></span>

<span data-ttu-id="80d76-109">Para solucionar estos problemas, consulte [KB 2829319](https://support.microsoft.com/kb/2829319).</span><span class="sxs-lookup"><span data-stu-id="80d76-109">To fix these issues, see [KB 2829319](https://support.microsoft.com/kb/2829319).</span></span>

<span data-ttu-id="80d76-110">Si no se aplican los problemas anteriores, ejecute el informe de diagnóstico de reglas de la bandeja de entrada antes de remitir el problema al soporte técnico de Microsoft:</span><span class="sxs-lookup"><span data-stu-id="80d76-110">If the previous issues don't apply, run the Inbox rule diagnostic report before you escalate the issue to Microsoft Support:</span></span>

1. <span data-ttu-id="80d76-111">Abra el buzón en Outlook en la web y haga clic en **Opciones** \> de **configuración** \> para organizar **las reglas**de la bandeja de entrada de **correo electrónico** \> .</span><span class="sxs-lookup"><span data-stu-id="80d76-111">Open the mailbox in Outlook on the web, and click **Settings** \> **Options** \> **Organize email** \> **Inbox rules**.</span></span>

2. <span data-ttu-id="80d76-112">En la parte inferior de la página, haga clic en **si las reglas no funcionan haga clic aquí para generar un informe de diagnóstico**.</span><span class="sxs-lookup"><span data-stu-id="80d76-112">At the bottom of the page, click **If your rules are not working click here to generate a diagnostic report**.</span></span>
