---
title: Error de Winsock 1554 10061
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: 9331a6c2b6e92a66fb97daf7dc5655ec320cba0f
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29903130"
---
# <a name="winsock-error-10061"></a><span data-ttu-id="b7eaf-102">Error de Winsock 10061</span><span class="sxs-lookup"><span data-stu-id="b7eaf-102">Winsock error 10061</span></span>

<span data-ttu-id="b7eaf-p101">Este código de error significa que Office 365 no se ha podido establecer un Sockets TCP (conexión) con el host de destino. La causa más probable de este error es un problema con la configuración del firewall. Para solucionar el problema, compruebe estas opciones:</span><span class="sxs-lookup"><span data-stu-id="b7eaf-p101">This error code means that Office 365 couldn't establish a TCP socket (connection) with the target host. The most likely cause of this error is a problem with your firewall configuration. To fix the problem, check these settings:</span></span>
  
- <span data-ttu-id="b7eaf-106">Compruebe la configuración del servidor de seguridad con la información de [las direcciones URL de Office 365 y los intervalos de direcciones IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span><span class="sxs-lookup"><span data-stu-id="b7eaf-106">Verify your firewall configuration with the information in [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span></span>
    
- <span data-ttu-id="b7eaf-107">Si el error es específico para Exchange Online Protection (EOP), debe han sido previamente notificados a un cambio en las [direcciones IP de protección en línea de Exchange](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="b7eaf-107">If the error is specific to Exchange Online Protection (EOP), you should have been previously notified to a change to the [Exchange Online Protection IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>
    
- <span data-ttu-id="b7eaf-108">Compruebe que su proveedor de servicios de Internet (ISP) no esté bloqueando el puerto.</span><span class="sxs-lookup"><span data-stu-id="b7eaf-108">Verify that your Internet Service Provider (ISP) isn't blocking the port.</span></span>
    
- <span data-ttu-id="b7eaf-109">Compruebe la configuración del servidor host y de destino inteligente en los conectores.</span><span class="sxs-lookup"><span data-stu-id="b7eaf-109">Verify the smart host and target server settings in your connectors.</span></span>
    
<span data-ttu-id="b7eaf-110">Tenga en cuenta que Office 365 no bloquea las conexiones *entrantes* de esta manera.</span><span class="sxs-lookup"><span data-stu-id="b7eaf-110">Note that Office 365 doesn't block  *incoming*  connections in this manner.</span></span> 
  

