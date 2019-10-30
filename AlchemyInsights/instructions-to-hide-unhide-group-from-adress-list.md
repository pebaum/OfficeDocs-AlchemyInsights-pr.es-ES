---
title: Instrucciones para ocultar o mostrar un grupo de la lista de direcciones
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "3161"
ms.openlocfilehash: d0e0285701f1a5f308bdc682abaddf5cc2d34120
ms.sourcegitcommit: defe2c412567b596fa8c3ab52111bde712ebb314
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/29/2019
ms.locfileid: "37768954"
---
# <a name="hide-office-365-group-from-address-list-gal"></a><span data-ttu-id="3702c-102">Ocultar grupo de Office 365 de la lista de direcciones (GAL)</span><span class="sxs-lookup"><span data-stu-id="3702c-102">Hide Office 365 group from address list (GAL)</span></span>

<span data-ttu-id="3702c-103">Para ocultar un grupo de Office 365 de las listas de direcciones (GAL) de los clientes de Exchange (como Outlook o OWA), use el comando siguiente en el shell EXO:</span><span class="sxs-lookup"><span data-stu-id="3702c-103">To hide an Office 365 group from address lists (GAL) of Exchange clients (such as Outlook or OWA), use the following command in EXO shell:</span></span>

`Set-UnifiedGroup -Identity GroupName -HiddenFromAddressListsEnabled:$true`

<span data-ttu-id="3702c-104">Para ocultar el grupo de Office 365 para que no sea visible para los clientes de Exchange, use el comando siguiente en el shell EXO:</span><span class="sxs-lookup"><span data-stu-id="3702c-104">To hide the Office 365 group from being visible to Exchange clients, use the following command in EXO shell:</span></span>

`Set-unifiedGroup -Identity GroupName -HiddenFromExchangeClientsEnabled:$true
Check this article for detailed instructions`

