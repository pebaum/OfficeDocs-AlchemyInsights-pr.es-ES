---
title: Directiva de uso compartido de calendario 618
ms.author: chrisda
author: chrisda
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "618"
- "899"
- "3800014"
ms.assetid: bc3db17b-87f8-4e50-b3ee-8b105b70d67a
ms.openlocfilehash: cc5827975eff10a119281541622224d0e37f08a7
ms.sourcegitcommit: 2afad0b107d03cd8c4de0b85b5bee38a13a7960d
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/26/2020
ms.locfileid: "44373016"
---
# <a name="policy-error-when-sharing-a-calendar"></a><span data-ttu-id="60c43-102">Error de directiva al compartir un calendario</span><span class="sxs-lookup"><span data-stu-id="60c43-102">Policy error when sharing a calendar</span></span>

1. <span data-ttu-id="60c43-103">Realice una de las acciones siguientes, según corresponda a su situación:</span><span class="sxs-lookup"><span data-stu-id="60c43-103">Do one of the following, as appropriate for your situation:</span></span>
    - <span data-ttu-id="60c43-104">Conéctese a Exchange online mediante PowerShell remoto.</span><span class="sxs-lookup"><span data-stu-id="60c43-104">Connect to Exchange Online by using Remote PowerShell.</span></span> <span data-ttu-id="60c43-105">Para obtener más información, vea [conectarse a Exchange online mediante PowerShell remoto](https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx).</span><span class="sxs-lookup"><span data-stu-id="60c43-105">For more information, see [Connect to Exchange Online using Remote PowerShell](https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx).</span></span>
    - <span data-ttu-id="60c43-106">En el servidor local, abra el shell de administración de Exchange.</span><span class="sxs-lookup"><span data-stu-id="60c43-106">On the on-premises server, open the Exchange Management Shell.</span></span>
2. <span data-ttu-id="60c43-107">Determine la Directiva de uso compartido que está asignada al usuario.</span><span class="sxs-lookup"><span data-stu-id="60c43-107">Determine the sharing policy that's assigned to the user.</span></span> <span data-ttu-id="60c43-108">Para ello, ejecute el siguiente comando y observe la Directiva devuelta:</span><span class="sxs-lookup"><span data-stu-id="60c43-108">To do this, run the following command and note the policy returned:</span></span>

    `
    Get-Mailbox User1 | fl *sharing*
    `

3. <span data-ttu-id="60c43-109">Actualice la Directiva de uso compartido para el usuario.</span><span class="sxs-lookup"><span data-stu-id="60c43-109">Update the sharing policy for the user.</span></span> <span data-ttu-id="60c43-110">Para ello, siga estos pasos:</span><span class="sxs-lookup"><span data-stu-id="60c43-110">To do this, follow these steps:</span></span>
    - <span data-ttu-id="60c43-111">Abra el Centro de administración de Exchange.</span><span class="sxs-lookup"><span data-stu-id="60c43-111">Open the Exchange admin center.</span></span>
    - <span data-ttu-id="60c43-112">Haga clic en **organización**y, a continuación, haga doble clic en la directiva asignada al usuario bajo **uso compartido individual**.</span><span class="sxs-lookup"><span data-stu-id="60c43-112">Click **Organization**, and then double-click the policy that's assigned to the user under **Individual Sharing**.</span></span> <span data-ttu-id="60c43-113">Esta es la Directiva que se ha devuelto en el paso 2.</span><span class="sxs-lookup"><span data-stu-id="60c43-113">This is the policy that was returned in step 2.</span></span>
    - <span data-ttu-id="60c43-114">En la página regla de uso compartido, seleccione el nivel de uso compartido del calendario que desea permitir en **Especifique qué información desea compartir**; Haga clic en **Guardar**.</span><span class="sxs-lookup"><span data-stu-id="60c43-114">On the Sharing Rule page, select the calendar sharing level that you want to allow under **Specify what information you want to share**; click **Save**.</span></span>

<span data-ttu-id="60c43-115">Para obtener más información, vea: ["la Directiva no permite conceder permisos en este nivel a uno o más de los destinatarios" cuando el usuario intenta compartir el calendario](https://docs.microsoft.com/exchange/troubleshoot/calendar-sharing/policy-permissions-issue).</span><span class="sxs-lookup"><span data-stu-id="60c43-115">For more information see: ["Policy does not allow granting permissions at this level to one or more of the recipient(s)" error when user tries to share calendar](https://docs.microsoft.com/exchange/troubleshoot/calendar-sharing/policy-permissions-issue).</span></span>
