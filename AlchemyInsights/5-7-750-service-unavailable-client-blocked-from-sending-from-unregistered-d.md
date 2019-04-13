---
title: 1048 5.7.750 servicio no disponible. El cliente bloqueó el envío de dominios no registrados
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 9/28/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 8cf6d70b-9a78-4f04-ac59-7ffcf44ffd22
ms.custom: 1048
ms.openlocfilehash: 06be6babc524ae0d8065355218426c695f49be66
ms.sourcegitcommit: 1a4b8fa9e38a95ca811085af516edb81caf2018c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/13/2019
ms.locfileid: "31856637"
---
# <a name="57750-client-blocked-from-sending-from-unregistered-domain"></a><span data-ttu-id="2c46e-103">el cliente de 5.7.750 bloqueó el envío desde un dominio no registrado</span><span class="sxs-lookup"><span data-stu-id="2c46e-103">5.7.750 Client blocked from sending from unregistered domain</span></span>

<span data-ttu-id="2c46e-104">El error se produce cuando se envía un gran volumen de mensajes desde dominios que no se aprovisionan en Office 365 (que se agregan como dominios aceptados y se validan).</span><span class="sxs-lookup"><span data-stu-id="2c46e-104">The error occurs when a large volume of messages are sent from domains that aren't provisioned in Office 365 (added as accepted domains and validated).</span></span>

<span data-ttu-id="2c46e-105">Para evitar este error, puede usar un conector de flujo de correo basado en certificados donde el dominio del certificado sea un dominio aprovisionado o puede aprovisionar todos los dominios de envío.</span><span class="sxs-lookup"><span data-stu-id="2c46e-105">To avoid this error, you can use a certificate-based mail flow connector where the certificate's domain is a provisioned domain, or you can provision all sending domains.</span></span>
