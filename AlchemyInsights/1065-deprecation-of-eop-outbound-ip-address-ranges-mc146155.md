---
title: RangesMC146155 de dirección IP saliente de 1065 degradación de elevación de privilegios
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 9/28/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: bd41784e-8002-428d-bc19-25671cfd34e8
ms.openlocfilehash: 2b4b2e2341f45e2d37713d72a2e0d34fa1a9a7cc
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29934901"
---
# <a name="deprecation-of-eop-outbound-ip-address-ranges"></a><span data-ttu-id="b2e29-102">Tipo de proyectos de intervalos de direcciones IP salientes de elevación de privilegios</span><span class="sxs-lookup"><span data-stu-id="b2e29-102">Deprecation of EOP outbound IP address ranges</span></span>

<span data-ttu-id="b2e29-p101">Hemos detectado un posible problema con la organización que (si no se corrige por el 26 de octubre de 2018) podría interrumpir el flujo de correo a su local o a destinos externos. Como anteriormente comunicados, para simplificar la administración de intervalo de direcciones IP, nos estamos consolidación de los intervalos de direcciones IP de Exchange Online Protection (EOP) que se usan para enviar y recibir correo electrónico fuera de Office 365. Nuestro análisis indica que uno o varios de los orígenes de correo electrónico externa o destinos que ha configurado en los conectores de flujo de correo no se aceptación conexiones desde el IP dirección rangos se muestra [aquí](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="b2e29-p101">We've detected a potential issue with your organization that (if not corrected by October 26th, 2018) might break mail flow to your on-premises or external destinations. As previously communicated, to simplify IP address range management, we're consolidating the Exchange Online Protection (EOP) IP address ranges that are used to send and receive email outside of Office 365. Our analysis indicates that one or more of the external email sources or destinations that you've configured in mail flow connectors aren't accepting connections from the IP address ranges shown [here](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>
  
<span data-ttu-id="b2e29-106">Actuar antes de 26 de octubre para asegurarse de que estos orígenes y destinos aceptará conexiones a y desde todos los [publicado las direcciones IP de elevación de privilegios](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="b2e29-106">Act before October 26th to ensure these sources and destinations will accept connections to and from all [published EOP IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>
  
<span data-ttu-id="b2e29-107">Para obtener más información acerca de este cambio, consulte que centro de mensajes de entradas de [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620)o [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274).</span><span class="sxs-lookup"><span data-stu-id="b2e29-107">For more information about this change, please see Message Center posts [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620), or [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274).</span></span>
  
 <span data-ttu-id="b2e29-p102">**Nota**: si anteriormente usó publicación IP o una dirección URL a través de HTML, XML y RSS para obtener actualizaciones extremo, también debe migrar a los nuevos servicios web para la automatización de estos tipos de actualizaciones. Para obtener más información, vea [categorías de extremo de Office 365 y dirección IP de Office 365 y servicio web de dirección URL](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).</span><span class="sxs-lookup"><span data-stu-id="b2e29-p102">**Note**: If you previously used IP or URL publishing via HTML, XML, and RSS for endpoint updates, you also should migrate to the new web services for automating these types of updates. For more information, see [Office 365 endpoint categories and Office 365 IP Address and URL web service](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).</span></span>
  
