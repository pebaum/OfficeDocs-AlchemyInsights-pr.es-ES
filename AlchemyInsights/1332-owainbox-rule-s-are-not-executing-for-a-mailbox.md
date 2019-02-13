---
title: 1332 OWA - reglas de bandeja de entrada no se ejecutan para un buzón de correo
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 383d1c77-5e4b-4a69-92d6-c404d890b6b7
ms.openlocfilehash: 0d3b7ce3d6b32d94a012eb3767c0747eed80f6e5
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29915821"
---
# <a name="an-inbox-rule-doesnt-work-as-expected"></a><span data-ttu-id="1d953-102">Una regla de bandeja de entrada no funciona como se esperaba</span><span class="sxs-lookup"><span data-stu-id="1d953-102">An Inbox rule doesn't work as expected</span></span>

<span data-ttu-id="1d953-103">Compruebe la configuración siguiente:</span><span class="sxs-lookup"><span data-stu-id="1d953-103">Verify the following settings:</span></span>
  
- <span data-ttu-id="1d953-p101">Puede redirigir un mensaje, reenviado o respondido automáticamente en función de las reglas de bandeja de entrada sólo una vez. Una regla de redirección (una regla de bandeja de entrada o una regla de flujo de correo, también conocido como una regla de transporte) puede agregar un máximo de diez de reenvío de destinatarios a un mensaje. Para obtener más información, vea [los límites de regla de diario, transporte y Bandeja de entrada](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).</span><span class="sxs-lookup"><span data-stu-id="1d953-p101">A message can be redirected, forwarded, or replied to automatically based on Inbox rules only one time. A redirecting rule (an Inbox rule or mail flow rule, also known as a transport rule) can add a maximum of ten forwarding recipients to a message. For more information, see [Journal, Transport, and Inbox rule limits](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).</span></span>
    
- <span data-ttu-id="1d953-p102">Reglas de bandeja de entrada no funcionan en el buzón de registro en diario alternativo. Para obtener más información acerca del buzón de registro en diario alternativo, consulte [mailbox de registro en diario alternativo](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).</span><span class="sxs-lookup"><span data-stu-id="1d953-p102">Inbox rules don't work on the alternate journaling mailbox. For more information about the alternate journaling mailbox, see [Alternate journaling mailbox](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).</span></span>
    
<span data-ttu-id="1d953-109">Para solucionar estos problemas, vea [KB 2829319](https://support.microsoft.com/kb/2829319).</span><span class="sxs-lookup"><span data-stu-id="1d953-109">To fix these issues, see [KB 2829319](https://support.microsoft.com/kb/2829319).</span></span>
  
<span data-ttu-id="1d953-110">Si no se aplican los problemas anteriores, ejecute el informe de diagnóstico de regla de bandeja de entrada antes de pasar el problema a Microsoft Support:</span><span class="sxs-lookup"><span data-stu-id="1d953-110">If the previous issues don't apply, run the Inbox rule diagnostic report before you escalate the issue to Microsoft Support:</span></span>
  
1. <span data-ttu-id="1d953-111">Abra el buzón de correo en Outlook en el web y haga clic en **configuración de** \> **Opciones** \> **correo electrónico organizar** \> **reglas de bandeja de entrada**.</span><span class="sxs-lookup"><span data-stu-id="1d953-111">Open the mailbox in Outlook on the web, and click **Settings** \> **Options** \> **Organize email** \> **Inbox rules**.</span></span>
    
2. <span data-ttu-id="1d953-112">En la parte inferior de la página, haga clic en **si las reglas no funcionan, haga clic aquí para generar un informe de diagnóstico**.</span><span class="sxs-lookup"><span data-stu-id="1d953-112">At the bottom of the page, click **If your rules are not working click here to generate a diagnostic report**.</span></span>
    
