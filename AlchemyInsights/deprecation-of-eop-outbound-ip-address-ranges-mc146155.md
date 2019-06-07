---
title: 1065 desuso de la dirección IP saliente de EOP rangesMC146155
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 9/28/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1065
ms.assetid: bd41784e-8002-428d-bc19-25671cfd34e8
ms.openlocfilehash: 9860845dea444847833d4c5cd01d49ea93473778
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/07/2019
ms.locfileid: "34752972"
---
# <a name="deprecation-of-eop-outbound-ip-address-ranges"></a><span data-ttu-id="fa8d8-102">Desuso de los intervalos de direcciones IP salientes de EOP</span><span class="sxs-lookup"><span data-stu-id="fa8d8-102">Deprecation of EOP outbound IP address ranges</span></span>

<span data-ttu-id="fa8d8-103">Hemos detectado un posible problema con su organización que (si no se ha corregido antes del 26 de octubre de 2018) podría romper el flujo de correo a sus destinos locales o externos.</span><span class="sxs-lookup"><span data-stu-id="fa8d8-103">We've detected a potential issue with your organization that (if not corrected by October 26th, 2018) might break mail flow to your on-premises or external destinations.</span></span> <span data-ttu-id="fa8d8-104">Como se comunicó anteriormente, para simplificar la administración del intervalo de direcciones IP, estamos consolidando los intervalos de direcciones IP de Exchange Online Protection (EOP) que se usan para enviar y recibir correo electrónico fuera de Office 365.</span><span class="sxs-lookup"><span data-stu-id="fa8d8-104">As previously communicated, to simplify IP address range management, we're consolidating the Exchange Online Protection (EOP) IP address ranges that are used to send and receive email outside of Office 365.</span></span> <span data-ttu-id="fa8d8-105">Nuestro análisis indica que uno o varios de los orígenes de correo electrónico externos o destinos que ha configurado en conectores de flujo de correo no aceptan conexiones de los intervalos de direcciones IP que se muestran [aquí](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="fa8d8-105">Our analysis indicates that one or more of the external email sources or destinations that you've configured in mail flow connectors aren't accepting connections from the IP address ranges shown [here](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>

<span data-ttu-id="fa8d8-106">Act antes del 26 de octubre para garantizar que estos orígenes y destinos acepten conexiones a y desde todas [las direcciones IP de EOP publicadas](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="fa8d8-106">Act before October 26th to ensure these sources and destinations will accept connections to and from all [published EOP IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>

<span data-ttu-id="fa8d8-107">Para obtener más información acerca de este cambio, consulte publicaciones del centro de mensajes [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620)o [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274).</span><span class="sxs-lookup"><span data-stu-id="fa8d8-107">For more information about this change, please see Message Center posts [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620), or [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274).</span></span>

<span data-ttu-id="fa8d8-108">**Nota**: si anteriormente usó la publicación de direcciones IP o URL a través de HTML, XML y RSS para las actualizaciones de extremos, deberá migrar también a los nuevos servicios web para automatizar estos tipos de actualizaciones.</span><span class="sxs-lookup"><span data-stu-id="fa8d8-108">**Note**: If you previously used IP or URL publishing via HTML, XML, and RSS for endpoint updates, you also should migrate to the new web services for automating these types of updates.</span></span> <span data-ttu-id="fa8d8-109">Para obtener más información, vea [categorías de puntos de conexión de office 365 y servicio Web de direcciones IP y URL de office 365](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).</span><span class="sxs-lookup"><span data-stu-id="fa8d8-109">For more information, see [Office 365 endpoint categories and Office 365 IP Address and URL web service](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).</span></span>
