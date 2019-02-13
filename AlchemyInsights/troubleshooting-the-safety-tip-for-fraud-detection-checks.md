---
title: Solución de problemas de la sugerencia de seguridad para la detección de loterías comprueba
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 1/9/2019
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 96ebe3c5-66ea-4662-98b7-052c2181c2f3
ms.openlocfilehash: 98627edcd2b685673dda8a8a18821eddf9b64bc1
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29936377"
---
# <a name="troubleshooting-the-safety-tip-for-fraud-detection-checks"></a><span data-ttu-id="37482-102">Solución de problemas de la sugerencia de seguridad para la detección de loterías comprueba</span><span class="sxs-lookup"><span data-stu-id="37482-102">Troubleshooting the safety tip for fraud detection checks</span></span>



<span data-ttu-id="37482-p101">Si está obteniendo una sugerencia de seguridad dice "el remitente no pudo nuestras comprobaciones de detección de loterías y puede no ser que parecen ser", a continuación, el remitente no se pudo pasar comprobaciones de autenticación con DKIM o SPF. Es el mejor método para resolver este problema para que el remitente autorizar a sí mismos. Si el remitente está enviando en su nombre, debe autorizar a ellos mediante la adición de dirección IP del remitente para su registro SPF.</span><span class="sxs-lookup"><span data-stu-id="37482-p101">If you are getting a safety tip that says "The sender failed our fraud detection checks and may not be who they appear to be", then the sender failed to pass either DKIM or SPF authentication checks. The best method to resolve this is for the sender to authorize themselves. If the sender is sending on your behalf, you need to authorize them by adding the sender's IP address to your SPF record.</span></span>
  
<span data-ttu-id="37482-106">Para obtener más información, vea [solución de problemas de la punta de color rojo seguridad (sospechosos) para la detección de loterías comprueba](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) .</span><span class="sxs-lookup"><span data-stu-id="37482-106">See [Troubleshooting the red (suspicious) safety tip for fraud detection checks](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) for more info.</span></span> 
  
<span data-ttu-id="37482-107">A continuación presentamos algunos otros vínculos que pueden ayudar a:</span><span class="sxs-lookup"><span data-stu-id="37482-107">Here are some other links that can help:</span></span>
  
- [<span data-ttu-id="37482-108">Cómo Office 365 usa el marco de directivas de remitente (SPF) para evitar la suplantación de identidad</span><span class="sxs-lookup"><span data-stu-id="37482-108">How Office 365 uses sender policy framework (SPF) to prevent spoofing</span></span>](https://docs.microsoft.com/office365/SecurityCompliance/how-office-365-uses-spf-to-prevent-spoofing)
    
- [<span data-ttu-id="37482-109">Configurar SPF en Office 365 para ayudar a evitar la suplantación de identidad</span><span class="sxs-lookup"><span data-stu-id="37482-109">Set up SPF in Office 365 to help prevent spoofing</span></span>](https://docs.microsoft.com/office365/SecurityCompliance/set-up-spf-in-office-365-to-help-prevent-spoofing)
    

