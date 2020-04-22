---
title: Contra correo electrónico no deseado-5.7.23
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3156"
- "9001196"
ms.openlocfilehash: 307b738c40c620d057e68eff7d218c8c9b5eb665
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43676514"
---
# <a name="fix-email-delivery-issues-for-error-code-5723"></a><span data-ttu-id="180c5-102">Corregir problemas de entrega de correo electrónico para el código de error 5.7.23</span><span class="sxs-lookup"><span data-stu-id="180c5-102">Fix email delivery issues for error code 5.7.23</span></span>

<span data-ttu-id="180c5-103">Compruebe el registro DNS de SPF de su dominio en un SPF o un comprobador de registros DNS disponible públicamente en la Web.</span><span class="sxs-lookup"><span data-stu-id="180c5-103">Verify the SPF DNS record for your domain at a publicly available SPF or DNS record checker on the web.</span></span>

<span data-ttu-id="180c5-104">Compruebe que Microsoft no identificó el mensaje saliente como correo no deseado y se enrutó a través del [grupo de entrega de alto riesgo](https://docs.microsoft.com/office365/SecurityCompliance/high-risk-delivery-pool-for-outbound-messages).</span><span class="sxs-lookup"><span data-stu-id="180c5-104">Verify that the outbound message wasn't identified as spam by Microsoft and routed through the [High Risk Delivery Pool](https://docs.microsoft.com/office365/SecurityCompliance/high-risk-delivery-pool-for-outbound-messages).</span></span> <span data-ttu-id="180c5-105">Los mensajes del grupo de entrega de alto riesgo no pasarán las comprobaciones de SPF y, por lo tanto, no serán aceptados por la organización de correo electrónico de destino.</span><span class="sxs-lookup"><span data-stu-id="180c5-105">Messages in the High Risk Delivery Pool won't pass SPF checks, and therefore won't be accepted by the destination email organization.</span></span>

<span data-ttu-id="180c5-106">Si el problema persiste, es posible que deba ponerse en contacto con el administrador del host de correo al que está intentando enviar correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="180c5-106">If the problem persists, you may need to contact the admin of the mail host to which you are attempting to send email.</span></span> <span data-ttu-id="180c5-107">Tome nota del error externo detallado disponible en el mensaje de devolución.</span><span class="sxs-lookup"><span data-stu-id="180c5-107">Make note of the detailed external error available in the bounce message.</span></span> <span data-ttu-id="180c5-108">Es posible que el soporte técnico de Microsoft no pueda ayudarle más.</span><span class="sxs-lookup"><span data-stu-id="180c5-108">Microsoft support may not be able to assist further.</span></span>
