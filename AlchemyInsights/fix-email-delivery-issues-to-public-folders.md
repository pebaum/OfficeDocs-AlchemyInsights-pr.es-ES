---
title: Corregir problemas de entrega de correo electrónico en carpetas públicas habilitadas para correo
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1956"
- "3500007"
ms.assetid: ''
ms.openlocfilehash: e261fe60843555fa45927b0a6b36e1ccf79fb028
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716369"
---
# <a name="fix-email-delivery-issues-to-mail-enabled-public-folders"></a>Corregir problemas de entrega de correo electrónico en carpetas públicas habilitadas para correo

Si los remitentes externos no pueden enviar mensajes a sus carpetas públicas habilitadas para correo y los remitentes reciben el siguiente error: **no se encontró (550 5.4.1)**, compruebe que el dominio de correo electrónico de la carpeta pública esté configurado como un dominio de retransmisión interna en lugar de un dominio autoritativo:

1. Abra el [centro de administración de Exchange (EAC)](https://docs.microsoft.com/Exchange/exchange-admin-center).

2. Vaya a **Mail flow** \> **dominios aceptados**de flujo de correo, seleccione el dominio aceptado y, a continuación, haga clic en **Editar**.

3. En la página de propiedades que se abre, si el tipo de dominio está configurado como **autoritativo**, cambie el valor a **retransmisión interna** y, a continuación, haga clic en **Guardar**.

Si los remitentes externos reciben el error **que no tiene permiso (550 5.7.13)**, ejecute el siguiente comando en [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) para ver los permisos de los usuarios anónimos en la carpeta pública:

`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous`Por ejemplo, `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous`.

Para permitir que los usuarios externos envíen correo electrónico a esta carpeta pública, agregue el derecho de acceso CreateItems al usuario anónimo. Por ejemplo, `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.
