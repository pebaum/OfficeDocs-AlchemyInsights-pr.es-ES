---
title: Identificar la dirección IP y el cliente en los registros de auditoría
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1367"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: e0119762d2a34bd2b0da827faf55c832e29d8a2b
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36539046"
---
# <a name="identify-ip-address-and-client-in-audit-logs"></a><span data-ttu-id="bb1c9-102">Identificar la dirección IP y el cliente en los registros de auditoría</span><span class="sxs-lookup"><span data-stu-id="bb1c9-102">Identify IP address and client in audit logs</span></span>

<span data-ttu-id="bb1c9-103">En los registros de auditoría se muestra la dirección IP que corresponde a una actividad de un usuario o administrador de Office 365.</span><span class="sxs-lookup"><span data-stu-id="bb1c9-103">The IP address that corresponds to an activity by an Office 365 user or administrator is shown in the Audit Logs.</span></span> <span data-ttu-id="bb1c9-104">También se registra la información del cliente.</span><span class="sxs-lookup"><span data-stu-id="bb1c9-104">The client information is also logged.</span></span> <span data-ttu-id="bb1c9-105">Estos son los pasos para identificar dicha información</span><span class="sxs-lookup"><span data-stu-id="bb1c9-105">Here are the steps to identifying such information</span></span>

1. <span data-ttu-id="bb1c9-106">Inicie sesión en el [centro de cumplimiento de & de seguridad de Office 365](https://protection.office.com/).</span><span class="sxs-lookup"><span data-stu-id="bb1c9-106">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/).</span></span>

2. <span data-ttu-id="bb1c9-107">Vaya a la página de**búsqueda del registro de auditoría** de **búsqueda** > .</span><span class="sxs-lookup"><span data-stu-id="bb1c9-107">Go to the **Search** > **Audit log search** page.</span></span>

   <span data-ttu-id="bb1c9-108">Si está interesado en una actividad específica, selecciónela en la lista **actividades** .</span><span class="sxs-lookup"><span data-stu-id="bb1c9-108">If you're interested in a specific activity, select it from **Activities** list.</span></span> <span data-ttu-id="bb1c9-109">Si no es así, se devolverán todas las actividades del usuario seleccionado (configuración predeterminada).</span><span class="sxs-lookup"><span data-stu-id="bb1c9-109">If not, all activities will be returned for the selected user (default setting).</span></span>

   <span data-ttu-id="bb1c9-110">**Nota**: es posible que algunas actividades no estén disponibles en el menú **actividades** ; sin embargo, estos elementos de auditoría se devolverán si se selecciona **Mostrar resultados para todas las actividades** (configuración predeterminada).</span><span class="sxs-lookup"><span data-stu-id="bb1c9-110">**Note**: Certain activities may not be available in the **Activities** menu; however, those audit items will be returned if **Show Results for all activities** is selected (default setting).</span></span>

3. <span data-ttu-id="bb1c9-111">Especifique el nombre de usuario en el campo **usuarios** , seleccione el intervalo de fechas adecuado para la actividad y, a continuación, haga clic en **Buscar**.</span><span class="sxs-lookup"><span data-stu-id="bb1c9-111">Specify the username in the **Users** field, select the appropriate date range for the activity, and then click **Search**.</span></span>

<span data-ttu-id="bb1c9-112">En los resultados, puede ver la dirección IP de esa actividad en el panel de resultados.</span><span class="sxs-lookup"><span data-stu-id="bb1c9-112">In the results, you can see the IP address for that activity in the results pane.</span></span> <span data-ttu-id="bb1c9-113">Seleccione el registro de auditoría para ver información detallada en \*\*\*\* el control flotante (por ejemplo, el cliente, el usuario que realizó la acción, etc.).</span><span class="sxs-lookup"><span data-stu-id="bb1c9-113">Select the audit record to see detailed information in the **Details** flyout (for example, Client, User that performed action, etc.).</span></span>

<span data-ttu-id="bb1c9-114">Para obtener más información, consulte [Buscar la dirección IP del equipo usado para obtener acceso a una cuenta en peligro](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span><span class="sxs-lookup"><span data-stu-id="bb1c9-114">For more information, see [Finding the IP address of the computer used to access a compromised account](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span></span>
