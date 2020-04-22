---
title: Solución de problemas de la protección contra amenazas avanzada de Office 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1039
ms.assetid: ''
ms.openlocfilehash: c90c8e9cb23cba93883cc1148fcbca77c9e92408
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43732419"
---
# <a name="troubleshooting-office-365-advanced-threat-protection"></a><span data-ttu-id="86a78-102">Solución de problemas de la protección contra amenazas avanzada de Office 365</span><span class="sxs-lookup"><span data-stu-id="86a78-102">Troubleshooting Office 365 Advanced Threat Protection</span></span>

- <span data-ttu-id="86a78-103">¿Observa retrasos en la entrega de mensajes?</span><span class="sxs-lookup"><span data-stu-id="86a78-103">Do you notice delays in message delivery?</span></span> <span data-ttu-id="86a78-104">Use la opción de [entrega dinámica](https://docs.microsoft.com/office365/securitycompliance/dynamic-delivery-and-previewing) en la Directiva de datos adjuntos seguros de ATP.</span><span class="sxs-lookup"><span data-stu-id="86a78-104">Use the [Dynamic Delivery](https://docs.microsoft.com/office365/securitycompliance/dynamic-delivery-and-previewing) option in your ATP Safe Attachments policy.</span></span> <span data-ttu-id="86a78-105">Esto ayudará a evitar los retrasos en los mensajes al proteger a los destinatarios de archivos malintencionados.</span><span class="sxs-lookup"><span data-stu-id="86a78-105">This will help avoid message delays while protecting recipients from malicious files.</span></span>

- <span data-ttu-id="86a78-106">¿Desea informar de falsos positivos o falsos negativos a Microsoft?</span><span class="sxs-lookup"><span data-stu-id="86a78-106">Do you want to report false positives or false negatives to Microsoft?</span></span> <span data-ttu-id="86a78-107">Use este [vínculo](https://www.microsoft.com/wdsi/filesubmission/) para enviar archivos para su análisis.</span><span class="sxs-lookup"><span data-stu-id="86a78-107">Use this [link](https://www.microsoft.com/wdsi/filesubmission/) to submit files for analysis.</span></span>

- <span data-ttu-id="86a78-108">¿Sabía que puede habilitar la protección de vínculos seguros para el correo electrónico interno que se envía entre los destinatarios de la organización?</span><span class="sxs-lookup"><span data-stu-id="86a78-108">Did you know that you can enable Safe Links protection for internal email sent between recipients within your organization?</span></span> <span data-ttu-id="86a78-109">Siga estos pasos:</span><span class="sxs-lookup"><span data-stu-id="86a78-109">Follow these steps:</span></span>

  1. <span data-ttu-id="86a78-110">Vaya a [https://protection.office.com](https://protection.office.com) e inicie sesión con una cuenta de administrador global o de administrador de seguridad.</span><span class="sxs-lookup"><span data-stu-id="86a78-110">Go to [https://protection.office.com](https://protection.office.com) and sign in with a global administrator or security administrator account.</span></span>

  2. <span data-ttu-id="86a78-111">En el panel de navegación izquierdo, en **Administración de amenazas**, elija **vínculos seguros**de **Directiva** \> .</span><span class="sxs-lookup"><span data-stu-id="86a78-111">In the left navigation pane under **Threat management**, choose **Policy** \> **Safe Links**.</span></span>

  3. <span data-ttu-id="86a78-112">En la sección **directivas que se aplican a toda la organización** , seleccione la Directiva y haga clic en **Editar**.</span><span class="sxs-lookup"><span data-stu-id="86a78-112">In the **Policies that apply to the entire organization** section, select the policy and click **Edit**.</span></span>

  4. <span data-ttu-id="86a78-113">En **configuración**, habilite **aplicar vínculos seguros a los mensajes enviados dentro de la organización**.</span><span class="sxs-lookup"><span data-stu-id="86a78-113">Under **Settings**, enable **Apply safe links to messages sent within the organization**.</span></span>
