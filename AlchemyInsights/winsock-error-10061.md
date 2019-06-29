---
title: 1554 error de Winsock 10061
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 12/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1554"
- "9000079"
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: e82e90b670235848105636fb2039ed60d3b93c67
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/28/2019
ms.locfileid: "35364930"
---
# <a name="winsock-error-10061"></a><span data-ttu-id="d5383-102">Error de Winsock 10061</span><span class="sxs-lookup"><span data-stu-id="d5383-102">Winsock error 10061</span></span>

<span data-ttu-id="d5383-103">Este código de error significa que Office 365 no pudo establecer un socket TCP (conexión) con el host de destino.</span><span class="sxs-lookup"><span data-stu-id="d5383-103">This error code means that Office 365 couldn't establish a TCP socket (connection) with the target host.</span></span> <span data-ttu-id="d5383-104">La causa más probable de este error es un problema con la configuración del firewall.</span><span class="sxs-lookup"><span data-stu-id="d5383-104">The most likely cause of this error is a problem with your firewall configuration.</span></span> <span data-ttu-id="d5383-105">Para solucionar el problema, compruebe estas opciones:</span><span class="sxs-lookup"><span data-stu-id="d5383-105">To fix the problem, check these settings:</span></span>

- <span data-ttu-id="d5383-106">Compruebe la configuración del firewall con la información de las [direcciones URL y los intervalos de direcciones IP de Office 365](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span><span class="sxs-lookup"><span data-stu-id="d5383-106">Verify your firewall configuration with the information in [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span></span>

- <span data-ttu-id="d5383-107">Si el error es específico de Exchange Online Protection (EOP), debería haber notificado previamente a un cambio en las [direcciones IP de Exchange Online Protection](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="d5383-107">If the error is specific to Exchange Online Protection (EOP), you should have been previously notified to a change to the [Exchange Online Protection IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>

- <span data-ttu-id="d5383-108">Compruebe que el proveedor de servicios de Internet (ISP) no está bloqueando el puerto.</span><span class="sxs-lookup"><span data-stu-id="d5383-108">Verify that your Internet Service Provider (ISP) isn't blocking the port.</span></span>

- <span data-ttu-id="d5383-109">Compruebe la configuración del host inteligente y del servidor de destino en los conectores.</span><span class="sxs-lookup"><span data-stu-id="d5383-109">Verify the smart host and target server settings in your connectors.</span></span>

<span data-ttu-id="d5383-110">Tenga en cuenta que Office 365 \*\* no bloquea las conexiones entrantes de esta manera.</span><span class="sxs-lookup"><span data-stu-id="d5383-110">Note that Office 365 doesn't block *incoming* connections in this manner.</span></span>
