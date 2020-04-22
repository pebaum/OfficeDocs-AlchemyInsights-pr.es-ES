---
title: 1048 5.7.750 servicio no disponible. El cliente bloqueó el envío de dominios no registrados
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 8cf6d70b-9a78-4f04-ac59-7ffcf44ffd22
ms.custom:
- "1048"
- "3100026"
ms.openlocfilehash: 48b9c2de27f8d7f52215c3a3d547bdf746a3a4cd
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43676730"
---
# <a name="57750-client-blocked-from-sending-from-unregistered-domain"></a><span data-ttu-id="d1cb7-103">5.7.750: se bloqueó el envío de un dominio no registrado</span><span class="sxs-lookup"><span data-stu-id="d1cb7-103">5.7.750 Client blocked from sending from unregistered domain</span></span>

<span data-ttu-id="d1cb7-104">El error se produce cuando se envía un gran volumen de mensajes desde dominios no aprovisionados en el espacio empresarial (agregados como dominios aceptados y validados).</span><span class="sxs-lookup"><span data-stu-id="d1cb7-104">The error occurs when a large volume of messages are sent from domains that aren't provisioned in your tenant (added as accepted domains and validated).</span></span>

<span data-ttu-id="d1cb7-105">Para evitar este error, puede usar un conector de flujo de correo basado en certificados donde el dominio del certificado sea un dominio aprovisionado o puede aprovisionar todos los dominios de envío.</span><span class="sxs-lookup"><span data-stu-id="d1cb7-105">To avoid this error, you can use a certificate-based mail flow connector where the certificate's domain is a provisioned domain, or you can provision all sending domains.</span></span>
