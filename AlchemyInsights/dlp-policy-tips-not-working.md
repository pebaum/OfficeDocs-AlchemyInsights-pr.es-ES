---
title: Las sugerencias de directivas de DLP no funcionan
ms.author: deniseb
author: denisebmsft
manager: laurawims
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: c03d30be-474a-4a34-b3c0-240eb2a2c466
ms.custom:
- "1428"
- "3200001"
ms.openlocfilehash: 51b4472fa721443192eb542cac45965df67634df
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932603"
---
# <a name="dlp-policy-tip-issues"></a><span data-ttu-id="cc18c-102">Problemas de la sugerencia de directiva DLP</span><span class="sxs-lookup"><span data-stu-id="cc18c-102">DLP Policy Tip issues</span></span>

<span data-ttu-id="cc18c-103">**Importante**: muchos clientes de SharePoint Online y OneDrive ejecutan aplicaciones críticas para la empresa en el servicio que se ejecutan en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="cc18c-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="cc18c-104">Estas incluyen la migración de contenido, la prevención de pérdida de datos (DLP) y soluciones de copia de seguridad.</span><span class="sxs-lookup"><span data-stu-id="cc18c-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="cc18c-105">En estos tiempos sin precedente, aplicamos las medidas necesarias para garantizar que los servicios de SharePoint Online y OneDrive permanezcan altamente disponibles y confiables para los usuarios que dependen del servicio más que nunca en escenarios de trabajo remoto.</span><span class="sxs-lookup"><span data-stu-id="cc18c-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="cc18c-106">Para apoyar este objetivo, hemos implementado límites más estrictos para las aplicaciones en segundo plano (como la migración, DLP y las soluciones de copia de seguridad) durante las horas de la semana laboral.</span><span class="sxs-lookup"><span data-stu-id="cc18c-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="cc18c-107">Se anticipa que estas aplicaciones obtengan un rendimiento muy limitado durante estas horas.</span><span class="sxs-lookup"><span data-stu-id="cc18c-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="cc18c-108">Sin embargo, durante las horas de la noche y del fin de semana de la región, el servicio estará listo para procesar un volumen mucho más elevado de solicitudes de aplicaciones en segundo plano.</span><span class="sxs-lookup"><span data-stu-id="cc18c-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="cc18c-109">**Sugerencias de directivas de DLP**</span><span class="sxs-lookup"><span data-stu-id="cc18c-109">**DLP policy tips**</span></span>

<span data-ttu-id="cc18c-110">Cuando se usan **directivas de DLP**, se puede informar a los usuarios de una infracción de directiva con las sugerencias de **Directiva**.</span><span class="sxs-lookup"><span data-stu-id="cc18c-110">When using **DLP policies**, users can be notified of a policy violation with **policy tips**.</span></span> <span data-ttu-id="cc18c-111">Los administradores pueden configurar las sugerencias de directiva para que se muestren mientras se prueba la Directiva DLP o cuando la Directiva está en el modo de cumplimiento completo.</span><span class="sxs-lookup"><span data-stu-id="cc18c-111">Admins can configure policy tips to display while testing their DLP policy or when the policy is in full enforcement mode.</span></span>
  
<span data-ttu-id="cc18c-112">Para configurar sugerencias de directiva en su Directiva DLP en el centro de seguridad y cumplimiento en el modo de cumplimiento completo, haga lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="cc18c-112">To configure policy tips on your DLP policy in the Security and Compliance center in full enforcement mode, do the following:</span></span>
  
- <span data-ttu-id="cc18c-113">Asegúrese de que las sugerencias de Directiva se hayan **habilitado** en la regla DLP siguiendo los pasos que se describen [aquí](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips).</span><span class="sxs-lookup"><span data-stu-id="cc18c-113">Ensure policy tips have been **enabled** on the DLP rule using the steps [here](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips).</span></span>

- <span data-ttu-id="cc18c-114">Asegúrese de que el **contenido coincida con** lo que se **necesita** para desencadenar la regla que se describe en este [artículo.](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="cc18c-114">Ensure your **content matches** what is **required** to trigger the rule outlined in this article [here](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span></span>

- <span data-ttu-id="cc18c-115">Las sugerencias de directivas se muestran en OWA y Outlook.</span><span class="sxs-lookup"><span data-stu-id="cc18c-115">Policy tips display in both OWA and Outlook.</span></span> <span data-ttu-id="cc18c-116">Sin embargo, al usar **Outlook 2013 o versiones posteriores**, las sugerencias de directiva solo se muestran en ciertas condiciones.</span><span class="sxs-lookup"><span data-stu-id="cc18c-116">However, when using **Outlook 2013 or later**, policy tips are only displayed under certain conditions.</span></span> <span data-ttu-id="cc18c-117">Estas condiciones se enumeran a continuación: [condiciones admitidas para Outlook 2013 o posterior para mostrar sugerencias de directiva](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips#outlook-2013-and-later-supports-showing-policy-tips-for-only-some-conditions)</span><span class="sxs-lookup"><span data-stu-id="cc18c-117">These conditions are listed here: [Supported conditions for Outlook 2013 or later for displaying Policy Tips](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips#outlook-2013-and-later-supports-showing-policy-tips-for-only-some-conditions)</span></span>

<span data-ttu-id="cc18c-118">Para obtener más información sobre las sugerencias de directivas de DLP, vea: [Show Policy Tips for DLP Policies](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips)</span><span class="sxs-lookup"><span data-stu-id="cc18c-118">For additional information on DLP policy tips, see: [Show policy tips for DLP Policies](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips)</span></span>
  