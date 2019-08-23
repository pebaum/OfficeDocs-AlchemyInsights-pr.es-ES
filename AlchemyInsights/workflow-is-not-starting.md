---
title: El flujo de trabajo no se inicia
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 8/2/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000144"
- "1670"
ms.openlocfilehash: d4bfdb44c04eb6838f4a265e55a4873d14c78f6d
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36558003"
---
# <a name="workflow-is-not-starting"></a><span data-ttu-id="3c854-102">El flujo de trabajo no se inicia</span><span class="sxs-lookup"><span data-stu-id="3c854-102">Workflow is not starting</span></span>

- <span data-ttu-id="3c854-103">Los flujos de trabajo de SharePoint 2010 y SharePoint 2013 no se inician.</span><span class="sxs-lookup"><span data-stu-id="3c854-103">SharePoint 2010 and SharePoint 2013 workflows are not starting.</span></span>

    - <span data-ttu-id="3c854-104">Si el flujo de trabajo no se inicia, es posible que haya un problema de servicio temporal en el que los usuarios pueden experimentar retrasos intermitentes con el progreso del flujo de trabajo.</span><span class="sxs-lookup"><span data-stu-id="3c854-104">If your workflow is not starting, there may be a temporary service issue where users may experience intermittent delays with workflow progress.</span></span> <span data-ttu-id="3c854-105">Compruebe el [Panel de estado del servicio](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) para ver si su organización se ve afectada.</span><span class="sxs-lookup"><span data-stu-id="3c854-105">Check the [Service Health Dashboard](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) to see if your organization is impacted.</span></span>

    - <span data-ttu-id="3c854-106">Si ha pasado más de 24 horas desde que vio por primera vez este problema, registre un vale de soporte técnico.</span><span class="sxs-lookup"><span data-stu-id="3c854-106">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="3c854-107">En muchos casos, ya estamos trabajando en una solución.</span><span class="sxs-lookup"><span data-stu-id="3c854-107">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="3c854-108">Por lo menos, danos 24 horas para completar una soluci? a.</span><span class="sxs-lookup"><span data-stu-id="3c854-108">Please give us at least 24 hours to complete a solution.</span></span>

- <span data-ttu-id="3c854-109">Flujos de trabajo de SharePoint 2010 retrasados en el inicio.</span><span class="sxs-lookup"><span data-stu-id="3c854-109">SharePoint 2010 workflows delayed on start.</span></span>

    - <span data-ttu-id="3c854-110">Esto ocurre si el flujo de trabajo se activa en lotes grandes.</span><span class="sxs-lookup"><span data-stu-id="3c854-110">This occurs if the workflow is triggered in large batches.</span></span> <span data-ttu-id="3c854-111">(por ejemplo, cuando se agregan varios elementos a la vez).</span><span class="sxs-lookup"><span data-stu-id="3c854-111">(for example, when several items are added at once).</span></span>

    - <span data-ttu-id="3c854-112">Los flujos de trabajo no están diseñados para ejecutarse en tiempo real, por lo que un retraso es el comportamiento de diseño.</span><span class="sxs-lookup"><span data-stu-id="3c854-112">Workflows are not designed to run real-time, so a delay is by-design behavior.</span></span>

   -  <span data-ttu-id="3c854-113">Si el flujo de trabajo es un lenguaje de marcado de objetos extensible (XMOL) complejo, la compilación puede ser lenta.</span><span class="sxs-lookup"><span data-stu-id="3c854-113">If the Workflow is complex Extensible Object Markup Language (XMOL), compilation can be slow.</span></span> <span data-ttu-id="3c854-114">Consulte [este](https://support.microsoft.com/en-us/kb/3043697) artículo.</span><span class="sxs-lookup"><span data-stu-id="3c854-114">Check [this](https://support.microsoft.com/en-us/kb/3043697) article.</span></span>

    - <span data-ttu-id="3c854-115">Debe simplificar el flujo de trabajo o volver a diseñarlo con el tipo de plataforma de flujo de trabajo de Microsoft SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="3c854-115">You should simplify the workflow or redesign it using the Microsoft SharePoint 2013 Workflow platform type.</span></span>

    - <span data-ttu-id="3c854-116">Si el historial del flujo de trabajo ha crecido de gran tamaño, es posible que desee purgar los elementos o crear una nueva lista de historial.</span><span class="sxs-lookup"><span data-stu-id="3c854-116">If your workflow history has grown large, you may want to purge the items or create a new history list.</span></span>

        <span data-ttu-id="3c854-117">Más información: [purgar el historial del flujo de trabajo](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span><span class="sxs-lookup"><span data-stu-id="3c854-117">More Information : [Purge Workflow History](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span></span>


## <a name="related-topics"></a><span data-ttu-id="3c854-118">Temas relacionados</span><span class="sxs-lookup"><span data-stu-id="3c854-118">Related topics</span></span>
<span data-ttu-id="3c854-119">¿Desea probar Microsoft Flow en SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="3c854-119">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="3c854-120">Crear flujo</span><span class="sxs-lookup"><span data-stu-id="3c854-120">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="3c854-121">Flujo y SharePoint</span><span class="sxs-lookup"><span data-stu-id="3c854-121">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


