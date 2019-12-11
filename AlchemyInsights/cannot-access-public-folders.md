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
ms.openlocfilehash: a9305b175e1ca0b992c014a73705447d67e037bc
ms.sourcegitcommit: cbbd46fa9a32873c5446d9fd5a532cea0300b795
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/10/2019
ms.locfileid: "39959511"
---
# <a name="outlook-cannot-connect-to-public-folders"></a>Outlook no puede conectarse a las carpetas públicas

Si el acceso a la carpeta pública no funciona con pocos usuarios, pruebe lo siguiente:

Conéctese a la PowerShell EXO y configure DefaultPublicFolderMailbox en la cuenta de usuario con problemas para que sea igual a una en una cuenta de usuario que funcione.

Ejemplo:

Get-Mailbox WorkingUser | DefaultPublicFolderMailbox ft, EffectivePublicFolderMailbox

Set-Mailbox ProblemUser-DefaultPublicFolderMailbox \<valor del comando anterior>

Espere al menos una hora para que el cambio surta efecto.