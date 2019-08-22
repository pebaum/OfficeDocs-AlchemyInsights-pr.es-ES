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
ms.custom:
- "1368"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 1201a625948743cacfaa58410abeb4108ed2eb56
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36539190"
---
# <a name="identify-inbox-rule-activity-in-audit-logs"></a><span data-ttu-id="86406-102">Identificar la actividad de las reglas de entrada en los registros de auditoría</span><span class="sxs-lookup"><span data-stu-id="86406-102">Identify inbox rule activity in audit logs</span></span>

<span data-ttu-id="86406-103">Puede usar la búsqueda de registros de auditoría en el centro de cumplimiento de & de seguridad de Office 365 para ver eventos de reglas de la bandeja de entrada (crear, modificar y eliminar reglas de la bandeja de entrada).</span><span class="sxs-lookup"><span data-stu-id="86406-103">You can use audit log search in the Office 365 Security & Compliance Center to view inbox rule events (creating, modifying, and deleting inbox rules).</span></span>

1. <span data-ttu-id="86406-104">Inicie sesión en el [centro de cumplimiento de & de seguridad de Office 365](https://protection.office.com/).</span><span class="sxs-lookup"><span data-stu-id="86406-104">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/).</span></span>

2. <span data-ttu-id="86406-105">Vaya a la página de**búsqueda del registro de auditoría** de **búsqueda** > .</span><span class="sxs-lookup"><span data-stu-id="86406-105">Go to the **Search** > **Audit log search** page.</span></span>

3. <span data-ttu-id="86406-106">Seleccione el intervalo de fechas en los campos **fecha de inicio** y **fecha** de finalización.</span><span class="sxs-lookup"><span data-stu-id="86406-106">Select the date range in the **Start date** and **End date** fields.</span></span>

4. <span data-ttu-id="86406-107">En **actividades de buzón de Exchange**, compruebe que el campo **actividades** está establecido en **nueva-InboxRule crear/modificar/habilitar/deshabilitar la regla de bandeja de entrada**.</span><span class="sxs-lookup"><span data-stu-id="86406-107">Under **Exchange Mailbox Activities**, verify the **Activities** field is set to **New-InboxRule Create/modify/enable/disable inbox rule**.</span></span>

5. <span data-ttu-id="86406-108">Haga clic en **Buscar**.</span><span class="sxs-lookup"><span data-stu-id="86406-108">Click **Search**.</span></span>

<span data-ttu-id="86406-109">En los resultados, seleccione un registro de auditoría.</span><span class="sxs-lookup"><span data-stu-id="86406-109">In the results, select an audit record.</span></span> <span data-ttu-id="86406-110">En el control flotante de detalles, haga clic en **más información**.</span><span class="sxs-lookup"><span data-stu-id="86406-110">In the details flyout, click **More Information**.</span></span> <span data-ttu-id="86406-111">La información sobre la configuración de las reglas de la bandeja de entrada se muestra en el campo **parámetros** .</span><span class="sxs-lookup"><span data-stu-id="86406-111">Information about the inbox rule settings is displayed in the **Parameters** field.</span></span>

<span data-ttu-id="86406-112">Para obtener más información, vea [determinar si un usuario creó una regla de bandeja de entrada](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule) .</span><span class="sxs-lookup"><span data-stu-id="86406-112">For more information, see [Determining if a user created an inbox rule](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)</span></span>
