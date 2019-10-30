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
# <a name="hide-office-365-group-from-address-list-gal"></a>Ocultar grupo de Office 365 de la lista de direcciones (GAL)

Para ocultar un grupo de Office 365 de las listas de direcciones (GAL) de los clientes de Exchange (como Outlook o OWA), use el comando siguiente en el shell EXO:

`Set-UnifiedGroup -Identity GroupName -HiddenFromAddressListsEnabled:$true`

Para ocultar el grupo de Office 365 para que no sea visible para los clientes de Exchange, use el comando siguiente en el shell EXO:

`Set-unifiedGroup -Identity GroupName -HiddenFromExchangeClientsEnabled:$true
Check this article for detailed instructions`

