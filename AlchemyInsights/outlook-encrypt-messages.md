---
title: S/MIME en Outlook en la web
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 9000329
ms.openlocfilehash: f2c047ca31c586c0aa36701e6e7ca9976cfd1734
ms.sourcegitcommit: b3e55405af384e868fcd32ea794eb15d1356c3fc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/29/2019
ms.locfileid: "36666857"
---
# <a name="encrypt-email-messages-in-outlook"></a><span data-ttu-id="c351f-102">Cifrar mensajes de correo electrónico en Outlook</span><span class="sxs-lookup"><span data-stu-id="c351f-102">Encrypt email messages in Outlook</span></span>

<span data-ttu-id="c351f-103">El cifrado de mensajes de Office 365 se basa en Microsoft Azure Rights Management (Azure RMS), que forma parte de Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="c351f-103">Office 365 Message Encryption is built on Microsoft Azure Rights Management (Azure RMS), which is part of Azure Information Protection.</span></span> <span data-ttu-id="c351f-104">Si su suscripción incluye Azure Rights Management o Azure Information Protection, **no necesita realizar ninguna acción para habilitar o activar manualmente** el servicio Rights Management.</span><span class="sxs-lookup"><span data-stu-id="c351f-104">If your subscription includes Azure Rights Management or Azure Information Protection, **you do not need to take any actions to manually enable or activate** the Rights Management Service.</span></span>

<span data-ttu-id="c351f-105">En función de los comentarios de los clientes, ya no se habilitarán las reglas de flujo de correo de Exchange para cifrar automáticamente el correo saliente que contiene determinados tipos de información confidencial en el espacio empresarial de forma predeterminada.</span><span class="sxs-lookup"><span data-stu-id="c351f-105">Based on customer feedback, we will no longer be enabling Exchange mail flow rules to automatically encrypt outbound email containing certain type of sensitive information in your tenant by default.</span></span> <span data-ttu-id="c351f-106">En su lugar, proporcionamos instrucciones detalladas sobre cómo puede hacerlo usted mismo.</span><span class="sxs-lookup"><span data-stu-id="c351f-106">Instead, we are providing detailed instructions on how you can do so yourselves.</span></span> <span data-ttu-id="c351f-107">Para obtener más información sobre cómo crear una regla de transporte para cifrar información confidencial, consulte [este artículo](https://aka.ms/OmeEtr).</span><span class="sxs-lookup"><span data-stu-id="c351f-107">For additional details on how to create a transport rule to encrypt sensitive information, see [this article](https://aka.ms/OmeEtr).</span></span>

- <span data-ttu-id="c351f-108">Si usa Outlook en la web (anteriormente, **OWA**): al redactar un mensaje de correo electrónico, simplemente haga clic en **proteger** en OWA.</span><span class="sxs-lookup"><span data-stu-id="c351f-108">If using Outlook on the Web (formerly **OWA**): When composing an email message, simply click **Protect** in OWA.</span></span> <span data-ttu-id="c351f-109">Se aplicará el permiso "no reenviar".</span><span class="sxs-lookup"><span data-stu-id="c351f-109">This will apply "Do not forward" permission.</span></span> <span data-ttu-id="c351f-110">Haga clic en **Cambiar permiso** y elija **cifrar** para cifrar solo el mensaje.</span><span class="sxs-lookup"><span data-stu-id="c351f-110">Click **Change permission** and choose **Encrypt** to only encrypt the message.</span></span>

- <span data-ttu-id="c351f-111">Si usa **el cliente de Outlook**: para enviar un mensaje cifrado desde Outlook 2013 o 2016 o Outlook 2016 para Mac, seleccione **Opciones** > **permisos**y, a continuación, seleccione la opción de protección que necesite.</span><span class="sxs-lookup"><span data-stu-id="c351f-111">If using **Outlook client**: To send an encrypted message from Outlook 2013 or 2016, or Outlook 2016 for Mac, select **Options** > **Permissions**, then select the protection option you need.</span></span>

- <span data-ttu-id="c351f-112">Para **cifrar automáticamente todo el correo electrónico** enviado a determinados destinatarios o organizaciones de asociados externos, debe crear una regla de transporte de flujo de correo en el centro de administración de Exchange.</span><span class="sxs-lookup"><span data-stu-id="c351f-112">To **automatically encrypt all email** sent to certain recipients or external partner organizations, you need to create a mail flow transport rule in the Exchange Admin Center.</span></span> <span data-ttu-id="c351f-113">Se proporcionan instrucciones detalladas en [este artículo de soporte técnico](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities).</span><span class="sxs-lookup"><span data-stu-id="c351f-113">Detailed instructions are provided in [this support article](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities).</span></span>

