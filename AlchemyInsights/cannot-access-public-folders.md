---
title: No se puede tener acceso a las carpetas públicas
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3462"
ms.openlocfilehash: a579b89b68bfb8432adfe64b155803eda2c3b086
ms.sourcegitcommit: a3b42ee05224846327d353b48a8c67dab724f6eb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/21/2020
ms.locfileid: "42891766"
---
# <a name="outlook-cannot-connect-to-public-folders"></a>Outlook no puede conectarse a las carpetas públicas

Si el acceso a la carpeta pública no funciona para algunos usuarios, intente lo siguiente:

Conéctese a EXO PowerShell y configure el parámetro DefaultPublicFolderMailbox en la cuenta de usuario problemática para que cumpla el parámetro en una cuenta de usuario que funcione.

Ejemplo:

Get-Mailbox WorkingUser | DefaultPublicFolderMailbox ft, EffectivePublicFolderMailbox

Set-Mailbox ProblemUser-DefaultPublicFolderMailbox \<valor del comando anterior>

Espere al menos una hora para que el cambio surta efecto.

Si el problema persiste, siga [este procedimiento](https://aka.ms/pfcte) para solucionar problemas de acceso a carpetas públicas con Outlook.