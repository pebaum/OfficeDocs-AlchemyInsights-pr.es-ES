---
title: Identificar la actividad de las reglas de entrada en los registros de auditoría
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1368
ms.assetid: ''
ms.openlocfilehash: f130846dd24cef81177934aa2a200c1056172d3f
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/07/2019
ms.locfileid: "34755054"
---
# <a name="identify-inbox-rule-activity-in-audit-logs"></a><span data-ttu-id="d883e-102">Identificar la actividad de las reglas de entrada en los registros de auditoría</span><span class="sxs-lookup"><span data-stu-id="d883e-102">Identify inbox rule activity in audit logs</span></span>

<span data-ttu-id="d883e-103">Puede usar la búsqueda de registros de auditoría en el centro de seguridad & cumplimiento para ver los eventos de las reglas de la bandeja de entrada (crear, modificar y eliminar reglas de la bandeja de entrada).</span><span class="sxs-lookup"><span data-stu-id="d883e-103">You can use audit log search in the Security & Compliance Center to view inbox rule events (creating, modifying, and deleting inbox rules).</span></span>

1. <span data-ttu-id="d883e-104">Inicie sesión en el [centro de cumplimiento de & de seguridad de Office 365](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="d883e-104">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="d883e-105">Haga clic en **búsqueda e investigación** y seleccione **búsqueda de registros de auditoría**.</span><span class="sxs-lookup"><span data-stu-id="d883e-105">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

3. <span data-ttu-id="d883e-106">Seleccione el intervalo de fechas en los campos **fecha de inicio** y **fecha** de finalización.</span><span class="sxs-lookup"><span data-stu-id="d883e-106">Select the date range in the **Start date** and **End date** fields.</span></span>

4. <span data-ttu-id="d883e-107">En **actividades de buzón de Exchange**, compruebe que el campo **actividades** está establecido en **nueva-InboxRule crear/modificar/habilitar/deshabilitar la regla de bandeja de entrada**.</span><span class="sxs-lookup"><span data-stu-id="d883e-107">Under **Exchange Mailbox Activities**, verify the **Activities** field is set to **New-InboxRule Create/modify/enable/disable inbox rule**.</span></span>

5. <span data-ttu-id="d883e-108">Haga clic en **Buscar**.</span><span class="sxs-lookup"><span data-stu-id="d883e-108">Click **Search**.</span></span>

<span data-ttu-id="d883e-109">En los resultados, seleccione un registro de auditoría.</span><span class="sxs-lookup"><span data-stu-id="d883e-109">In the results, select an audit record.</span></span> <span data-ttu-id="d883e-110">En el control flotante de detalles, haga clic en **más información**.</span><span class="sxs-lookup"><span data-stu-id="d883e-110">In the details flyout, click **More Information**.</span></span> <span data-ttu-id="d883e-111">La información sobre la configuración de las reglas de la bandeja de entrada se muestra en el campo **parámetros** .</span><span class="sxs-lookup"><span data-stu-id="d883e-111">Information about the inbox rule settings is displayed in the **Parameters** field.</span></span>

<span data-ttu-id="d883e-112">Para obtener más información, vea [determinar si un usuario creó una regla de bandeja de entrada](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule) .</span><span class="sxs-lookup"><span data-stu-id="d883e-112">For more information, see [Determining if a user created an inbox rule](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)</span></span>
