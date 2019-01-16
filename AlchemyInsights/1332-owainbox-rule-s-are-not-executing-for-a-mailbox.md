---
title: 1332 OWA - reglas de bandeja de entrada no se ejecutan para un buzón de correo
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 383d1c77-5e4b-4a69-92d6-c404d890b6b7
ms.openlocfilehash: f090d0a9d84bc6a4d1a1f4c0af55102d4b0ddfbe
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28314240"
---
# <a name="an-inbox-rule-doesnt-work-as-expected"></a><span data-ttu-id="05abf-102">Una regla de bandeja de entrada no funciona como se esperaba</span><span class="sxs-lookup"><span data-stu-id="05abf-102">An Inbox rule doesn't work as expected</span></span>

<span data-ttu-id="05abf-103">Compruebe la configuración siguiente:</span><span class="sxs-lookup"><span data-stu-id="05abf-103">Verify the following settings:</span></span>
  
- <span data-ttu-id="05abf-p101">Puede redirigir un mensaje, reenviado o respondido automáticamente en función de las reglas de bandeja de entrada sólo una vez. Una regla de redirección (una regla de bandeja de entrada o una regla de flujo de correo, también conocido como una regla de transporte) puede agregar un máximo de diez de reenvío de destinatarios a un mensaje. Para obtener más información, vea [los límites de regla de diario, transporte y Bandeja de entrada](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).</span><span class="sxs-lookup"><span data-stu-id="05abf-p101">A message can be redirected, forwarded, or replied to automatically based on Inbox rules only one time. A redirecting rule (an Inbox rule or mail flow rule, also known as a transport rule) can add a maximum of ten forwarding recipients to a message. For more information, see [Journal, Transport, and Inbox rule limits](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).</span></span>
    
- <span data-ttu-id="05abf-p102">Reglas de bandeja de entrada no funcionan en el buzón de registro en diario alternativo. Para obtener más información acerca del buzón de registro en diario alternativo, consulte [mailbox de registro en diario alternativo](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).</span><span class="sxs-lookup"><span data-stu-id="05abf-p102">Inbox rules don't work on the alternate journaling mailbox. For more information about the alternate journaling mailbox, see [Alternate journaling mailbox](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).</span></span>
    
<span data-ttu-id="05abf-109">Para solucionar estos problemas, vea [KB 2829319](https://support.microsoft.com/kb/2829319).</span><span class="sxs-lookup"><span data-stu-id="05abf-109">To fix these issues, see [KB 2829319](https://support.microsoft.com/kb/2829319).</span></span>
  
<span data-ttu-id="05abf-110">Si no se aplican los problemas anteriores, ejecute el informe de diagnóstico de regla de bandeja de entrada antes de pasar el problema a Microsoft Support:</span><span class="sxs-lookup"><span data-stu-id="05abf-110">If the previous issues don't apply, run the Inbox rule diagnostic report before you escalate the issue to Microsoft Support:</span></span>
  
1. <span data-ttu-id="05abf-111">Abra el buzón de correo en Outlook en el web y haga clic en **configuración de** \> **Opciones** \> **correo electrónico organizar** \> **reglas de bandeja de entrada**.</span><span class="sxs-lookup"><span data-stu-id="05abf-111">Open the mailbox in Outlook on the web, and click **Settings** \> **Options** \> **Organize email** \> **Inbox rules**.</span></span>
    
2. <span data-ttu-id="05abf-112">En la parte inferior de la página, haga clic en **si las reglas no funcionan, haga clic aquí para generar un informe de diagnóstico**.</span><span class="sxs-lookup"><span data-stu-id="05abf-112">At the bottom of the page, click **If your rules are not working click here to generate a diagnostic report**.</span></span>
    

