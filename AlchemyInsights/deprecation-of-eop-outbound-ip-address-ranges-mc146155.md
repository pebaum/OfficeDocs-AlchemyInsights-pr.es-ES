---
title: 1065 desuso de la dirección IP saliente de EOP rangesMC146155
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 9/28/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1065
ms.assetid: bd41784e-8002-428d-bc19-25671cfd34e8
ms.openlocfilehash: 17beb1722142d94ea05b67ce5ed1f20f8b11375c
ms.sourcegitcommit: 1a4b8fa9e38a95ca811085af516edb81caf2018c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/13/2019
ms.locfileid: "31858113"
---
# <a name="deprecation-of-eop-outbound-ip-address-ranges"></a>Desuso de los intervalos de direcciones IP salientes de EOP

Hemos detectado un posible problema con su organización que (si no se ha corregido antes del 26 de octubre de 2018) podría romper el flujo de correo a sus destinos locales o externos. Como se comunicó anteriormente, para simplificar la administración del intervalo de direcciones IP, estamos consolidando los intervalos de direcciones IP de Exchange Online Protection (EOP) que se usan para enviar y recibir correo electrónico fuera de Office 365. Nuestro análisis indica que uno o varios de los orígenes de correo electrónico externos o destinos que ha configurado en conectores de flujo de correo no aceptan conexiones de los intervalos de direcciones IP que se muestran [aquí](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).

Act antes del 26 de octubre para garantizar que estos orígenes y destinos acepten conexiones a y desde todas [las direcciones IP de EOP publicadas](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).

Para obtener más información acerca de este cambio, consulte publicaciones del centro de mensajes [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620)o [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274).

**Nota**: si anteriormente usó la publicación de direcciones IP o URL a través de HTML, XML y RSS para las actualizaciones de extremos, deberá migrar también a los nuevos servicios web para automatizar estos tipos de actualizaciones. Para obtener más información, vea [categorías de puntos de conexión de office 365 y servicio Web de direcciones IP y URL de office 365](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).
