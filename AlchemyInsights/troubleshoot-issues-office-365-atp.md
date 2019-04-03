---
title: Solución de problemas con la protección contra amenazas avanzada de Office 365 (ATP)
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/01/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Admin_O365
ms.custom: 3100021
ms.openlocfilehash: dbdfe2ddcc4afd4477f66ffd060ddb7093af8fd6
ms.sourcegitcommit: 601aec31e6556286fe5e0fd62827a037cbb6fe17
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/02/2019
ms.locfileid: "31031104"
---
# <a name="troubleshoot-issues-with-office-365-atp"></a><span data-ttu-id="6f81c-102">Solucionar problemas con Office 365 ATP</span><span class="sxs-lookup"><span data-stu-id="6f81c-102">Troubleshoot issues with Office 365 ATP</span></span>

- <span data-ttu-id="6f81c-103">¿Hay retrasos **en la entrega de mensajes de correo electrónico**?</span><span class="sxs-lookup"><span data-stu-id="6f81c-103">**Notice delays with email message delivery**?</span></span> <span data-ttu-id="6f81c-104">Pruebe a usar la opción de entrega dinámica para las directivas de datos adJuntos seguros de ATP.</span><span class="sxs-lookup"><span data-stu-id="6f81c-104">Try using the Dynamic Delivery option for your ATP Safe Attachments policies.</span></span> <span data-ttu-id="6f81c-105">Esto evitará los retrasos en la entrega de mensajes de correo electrónico al proteger a los destinatarios de archivos malintencionados.</span><span class="sxs-lookup"><span data-stu-id="6f81c-105">This will avoid email message delivery delays while protecting recipients from malicious files.</span></span>
- <span data-ttu-id="6f81c-106">**¿Desea informar de falsos positivos o falsos negativos**?</span><span class="sxs-lookup"><span data-stu-id="6f81c-106">**Do you want to report false positives or false negatives**?</span></span> <span data-ttu-id="6f81c-107">Use este vínculo para enviar el archivo para su análisis:[https://microsoft.com/wdsi/filesubmission](https://microsoft.com/wdsi/filesubmission)</span><span class="sxs-lookup"><span data-stu-id="6f81c-107">Use this link to submit your file for analysis: [https://microsoft.com/wdsi/filesubmission](https://microsoft.com/wdsi/filesubmission)</span></span>
- <span data-ttu-id="6f81c-108">**¿Sabía que puede habilitar la protección de vínculos seguros de ATP para el correo electrónico que se envía entre las personas de su organización**?</span><span class="sxs-lookup"><span data-stu-id="6f81c-108">**Did you know that you can enable ATP Safe Links protection for email sent between people in your organization**?</span></span> <span data-ttu-id="6f81c-109">Siga estos pasos:</span><span class="sxs-lookup"><span data-stu-id="6f81c-109">Follow these steps:</span></span>
    1. <span data-ttu-id="6f81c-110">Vaya a https://protection.office.come inicie sesión.</span><span class="sxs-lookup"><span data-stu-id="6f81c-110">Go to https://protection.office.com, and sign in.</span></span>
    2. <span data-ttu-id="6f81c-111">Vaya a**vínculos seguros**de la**Directiva** > de **Administración** > de amenazas.</span><span class="sxs-lookup"><span data-stu-id="6f81c-111">Go to **Threat management** > **Policy** > **Safe Links**.</span></span>
    3. <span data-ttu-id="6f81c-112">En **directivas que se aplican a destinatarios específicos**, edite (o agregue) una directiva.</span><span class="sxs-lookup"><span data-stu-id="6f81c-112">Under **Policies that apply to specific recipients**, edit (or add) a policy.</span></span>
    4. <span data-ttu-id="6f81c-113">Seleccione **aplicar vínculos seguros a los mensajes enviados dentro de la organización**.</span><span class="sxs-lookup"><span data-stu-id="6f81c-113">Select **Apply safe links to messages sent within the organization**.</span></span>
    5. <span data-ttu-id="6f81c-114">Guarde la Directiva y espere unos 30 minutos para que los cambios funcionen en el centro de proceso de información.</span><span class="sxs-lookup"><span data-stu-id="6f81c-114">Save your policy, and allow about 30 minutes for your changes to work their way through your datacenter.</span></span>
- <span data-ttu-id="6f81c-115">Para obtener más ayuda con ATP, consulte [Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp).</span><span class="sxs-lookup"><span data-stu-id="6f81c-115">To get more help with ATP, see [Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp).</span></span>