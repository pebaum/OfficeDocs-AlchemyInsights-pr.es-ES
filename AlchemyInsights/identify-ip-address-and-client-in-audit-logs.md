---
title: Identificar la dirección IP y el cliente en los registros de auditoría
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1367"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: d1a0d412fc0c6d79e50b101ca759127522f45dcd
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716405"
---
# <a name="identify-ip-address-and-client-in-audit-logs"></a><span data-ttu-id="80b68-102">Identificar la dirección IP y el cliente en los registros de auditoría</span><span class="sxs-lookup"><span data-stu-id="80b68-102">Identify IP address and client in audit logs</span></span>

<span data-ttu-id="80b68-103">La dirección IP que corresponde a una actividad por parte de un usuario o administrador de Microsoft 365 se muestra en los registros de auditoría.</span><span class="sxs-lookup"><span data-stu-id="80b68-103">The IP address that corresponds to an activity by a Microsoft 365 user or administrator is shown in the Audit Logs.</span></span> <span data-ttu-id="80b68-104">También se registra la información del cliente.</span><span class="sxs-lookup"><span data-stu-id="80b68-104">The client information is also logged.</span></span> <span data-ttu-id="80b68-105">Estos son los pasos para identificar dicha información</span><span class="sxs-lookup"><span data-stu-id="80b68-105">Here are the steps to identifying such information</span></span>

1. <span data-ttu-id="80b68-106">Inicie sesión en el [centro de cumplimiento de & de seguridad de Microsoft 365](https://protection.office.com/).</span><span class="sxs-lookup"><span data-stu-id="80b68-106">Log in to the [Microsoft 365 Security & Compliance Center](https://protection.office.com/).</span></span>

2. <span data-ttu-id="80b68-107">Vaya a la página de**búsqueda del registro de auditoría** de **búsqueda** > .</span><span class="sxs-lookup"><span data-stu-id="80b68-107">Go to the **Search** > **Audit log search** page.</span></span>

   <span data-ttu-id="80b68-108">Si está interesado en una actividad específica, selecciónela en la lista **actividades** .</span><span class="sxs-lookup"><span data-stu-id="80b68-108">If you're interested in a specific activity, select it from **Activities** list.</span></span> <span data-ttu-id="80b68-109">Si no es así, se devolverán todas las actividades del usuario seleccionado (configuración predeterminada).</span><span class="sxs-lookup"><span data-stu-id="80b68-109">If not, all activities will be returned for the selected user (default setting).</span></span>

   <span data-ttu-id="80b68-110">**Nota**: es posible que algunas actividades no estén disponibles en el menú **actividades** ; sin embargo, estos elementos de auditoría se devolverán si se selecciona **Mostrar resultados para todas las actividades** (configuración predeterminada).</span><span class="sxs-lookup"><span data-stu-id="80b68-110">**Note**: Certain activities may not be available in the **Activities** menu; however, those audit items will be returned if **Show Results for all activities** is selected (default setting).</span></span>

3. <span data-ttu-id="80b68-111">Especifique el nombre de usuario en el campo **usuarios** , seleccione el intervalo de fechas adecuado para la actividad y, a continuación, haga clic en **Buscar**.</span><span class="sxs-lookup"><span data-stu-id="80b68-111">Specify the username in the **Users** field, select the appropriate date range for the activity, and then click **Search**.</span></span>

<span data-ttu-id="80b68-112">En los resultados, puede ver la dirección IP de esa actividad en el panel de resultados.</span><span class="sxs-lookup"><span data-stu-id="80b68-112">In the results, you can see the IP address for that activity in the results pane.</span></span> <span data-ttu-id="80b68-113">Seleccione el registro de auditoría para ver información detallada en **el control flotante** (por ejemplo, el cliente, el usuario que realizó la acción, etc.).</span><span class="sxs-lookup"><span data-stu-id="80b68-113">Select the audit record to see detailed information in the **Details** flyout (for example, Client, User that performed action, etc.).</span></span>

<span data-ttu-id="80b68-114">Para obtener más información, consulte [Buscar la dirección IP del equipo usado para obtener acceso a una cuenta en peligro](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span><span class="sxs-lookup"><span data-stu-id="80b68-114">For more information, see [Finding the IP address of the computer used to access a compromised account](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span></span>
