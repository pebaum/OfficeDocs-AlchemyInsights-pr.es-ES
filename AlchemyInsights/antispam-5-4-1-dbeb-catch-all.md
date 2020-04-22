---
title: Correo no deseado 5.4.1 DBEB catch-all
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001209"
- "3167"
ms.openlocfilehash: ad0f4c691a5e06306dbb408f4d66a4e00609e4d5
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43707928"
---
# <a name="fix-delivery-issues-for-error-code-550-541-relay-access-denied"></a><span data-ttu-id="8213a-102">Corregir problemas de entrega para el código de error 550 5.4.1 acceso de retransmisión denegado</span><span class="sxs-lookup"><span data-stu-id="8213a-102">Fix delivery issues for error code 550 5.4.1 Relay Access Denied</span></span>

<span data-ttu-id="8213a-103">Este problema se produce cuando [se comprueba si una dirección de correo electrónico es válida para evitar que se bouncebacks](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-directory-based-edge-blocking) al entrar en la red de Microsoft.</span><span class="sxs-lookup"><span data-stu-id="8213a-103">This problem occurs when [checking to see if an email address is valid to prevent bouncebacks](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-directory-based-edge-blocking) when entering the Microsoft network.</span></span> <span data-ttu-id="8213a-104">Pruebe a hacer lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="8213a-104">Try the following:</span></span>

1. <span data-ttu-id="8213a-105">Determine si el problema es específico de un dominio completo o de una sola dirección de correo electrónico:</span><span class="sxs-lookup"><span data-stu-id="8213a-105">Determine whether the problem is specific to an entire domain or a single email address:</span></span>
    - <span data-ttu-id="8213a-106">Dominio completo: a veces, es necesario sincronizar el dominio; Pruebe a [configurar el dominio como interno y, a continuación, de nuevo a autoritario](https://docs.microsoft.com/exchange/mail-flow-best-practices/manage-accepted-domains/manage-accepted-domains).</span><span class="sxs-lookup"><span data-stu-id="8213a-106">Entire domain: Sometimes the domain needs to be synchronized; try [setting the domain to Internal and then back to Authoritative](https://docs.microsoft.com/exchange/mail-flow-best-practices/manage-accepted-domains/manage-accepted-domains).</span></span>
    - <span data-ttu-id="8213a-107">Dirección de correo electrónico única: a veces, la dirección debe sincronizarse; cambiar la dirección del proxy SMTP y, a continuación, cambiarla de nuevo puede resultarle útil.</span><span class="sxs-lookup"><span data-stu-id="8213a-107">Single email address: Sometimes the address needs to be synchronized; changing the smtp proxy address and then changing it back can help.</span></span>
2. <span data-ttu-id="8213a-108">Determine si el problema es específico de un grupo o una carpeta pública.</span><span class="sxs-lookup"><span data-stu-id="8213a-108">Determine whether the problem is specific to a group or public folder.</span></span> <span data-ttu-id="8213a-109">Para algunos tipos de objetos, es posible que los objetos deban crearse manualmente en Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="8213a-109">For some object types, the objects may need to be manually created in Azure Active Directory.</span></span>

<span data-ttu-id="8213a-110">Si necesita ayuda adicional, abra una incidencia de soporte técnico y especifique el ámbito del problema (incluido el tipo de objeto al que va a enviar) para que podamos ayudarle mejor.</span><span class="sxs-lookup"><span data-stu-id="8213a-110">If you need additional help, please open a support ticket and specify the scope of the issue (including the type of object you're sending to) so we can assist you better.</span></span>