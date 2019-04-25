---
title: Identificar el reenvío externo de correo electrónico en los buzones de registros de auditoría
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1369
ms.assetid: ''
ms.openlocfilehash: 7fb2c161c558a7eb961f86ca2b86e33750d902fd
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "32417228"
---
# <a name="identify-when-external-email-forwarding-is-configured-on-mailboxes"></a><span data-ttu-id="e3315-102">Identificar cuándo se configura el reenvío externo de correo electrónico en los buzones</span><span class="sxs-lookup"><span data-stu-id="e3315-102">Identify when external email forwarding is configured on mailboxes</span></span>

<span data-ttu-id="e3315-103">Cuando un usuario configura el reenvío externo de correo electrónico en un buzón, la actividad se audita como parte del cmdlet **set-Mailbox** .</span><span class="sxs-lookup"><span data-stu-id="e3315-103">When a user configures external email forwarding on a mailbox, the activity is audited as part of the **Set-Mailbox** cmdlet.</span></span> <span data-ttu-id="e3315-104">Puede ver la actividad mediante la búsqueda de registros de auditoría en el centro de seguridad & cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="e3315-104">You can see the activity using audit log search in the Security & Compliance Center.</span></span>

1. <span data-ttu-id="e3315-105">Inicie sesión en el [centro de cumplimiento de & de seguridad de Office 365](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="e3315-105">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="e3315-106">Haga clic en **búsqueda e investigación** y seleccione **búsqueda de registros de auditoría**.</span><span class="sxs-lookup"><span data-stu-id="e3315-106">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

3. <span data-ttu-id="e3315-107">Seleccione el intervalo de fechas en los campos **fecha de inicio** y **fecha** de finalización.</span><span class="sxs-lookup"><span data-stu-id="e3315-107">Select the date range in the **Start date** and **End date** fields.</span></span> <span data-ttu-id="e3315-108">No es necesario especificar un nombre de usuario.</span><span class="sxs-lookup"><span data-stu-id="e3315-108">You don't need to specify a username.</span></span> <span data-ttu-id="e3315-109">Compruebe que el campo **actividades** está configurado para **Mostrar resultados para todas las actividades**.</span><span class="sxs-lookup"><span data-stu-id="e3315-109">Verify the **Activities** field is set to **Show results for all activities**.</span></span>

4. <span data-ttu-id="e3315-110">Haga clic en **Buscar**.</span><span class="sxs-lookup"><span data-stu-id="e3315-110">Click **Search**.</span></span>

<span data-ttu-id="e3315-111">En los resultados, haga clic en **filtrar resultados** y escriba **set-Mailbox** en el cuadro filtro de actividad.</span><span class="sxs-lookup"><span data-stu-id="e3315-111">In the results, click **Filter Results** and type **Set-Mailbox** in the activity filter box.</span></span> <span data-ttu-id="e3315-112">Seleccione un registro de auditoría en los resultados.</span><span class="sxs-lookup"><span data-stu-id="e3315-112">Select an audit record in the results.</span></span> <span data-ttu-id="e3315-113">En el control flotante de **detalles** , haga clic en **más información**.</span><span class="sxs-lookup"><span data-stu-id="e3315-113">In the **Details** flyout, click **More information**.</span></span> <span data-ttu-id="e3315-114">Tiene que mirar los detalles de cada registro de auditoría para determinar si la actividad está relacionada con el reenvío de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="e3315-114">You have to look at the details of each audit record to determine if the activity is related to email forwarding.</span></span>

- <span data-ttu-id="e3315-115">**ObjectId**: el valor de alias del buzón que se modificó.</span><span class="sxs-lookup"><span data-stu-id="e3315-115">**ObjectId**: The alias value of the mailbox that was modified.</span></span>

- <span data-ttu-id="e3315-116">\*\*\*\* Parameters: _ForwardingSmtpAddress_ indica la dirección de correo electrónico de destino.</span><span class="sxs-lookup"><span data-stu-id="e3315-116">**Parameters**: _ForwardingSmtpAddress_ indicates the target email address.</span></span>

- <span data-ttu-id="e3315-117">**Userid**: usuario que configuró el reenvío de correo electrónico en el buzón del campo **objectId** .</span><span class="sxs-lookup"><span data-stu-id="e3315-117">**UserId**: The user who configured email forwarding on the mailbox in the **ObjectId** field.</span></span>

<span data-ttu-id="e3315-118">Para obtener más información, vea [determinar quién ha configurado el reenvío de correo para un buzón](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-who-set-up-email-forwarding-for-a-mailbox).</span><span class="sxs-lookup"><span data-stu-id="e3315-118">For more information, see [Determining who set up email forwarding for a mailbox](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-who-set-up-email-forwarding-for-a-mailbox).</span></span>
