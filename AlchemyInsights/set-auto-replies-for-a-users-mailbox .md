---
title: Establecer respuestas automáticas para un buzón de correo
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000761"
- "3514"
ms.openlocfilehash: e3cc01298c10fd3ba21327a7fb5cc5396d0ad74d
ms.sourcegitcommit: 23e5b94f1758bfe202008384e300b81816975375
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/14/2020
ms.locfileid: "43506649"
---
# <a name="set-auto-replies-for-a-users-mailbox"></a>Establecer respuestas automáticas para un buzón de correo

**Método 1**

1. Iniciar sesión en el portal de Office 365

2. Vaya a **Usuarios > Usuarios activos** (o **Grupos > Buzones compartidos** si configura esto en un buzón compartido).

3. Seleccione un usuario que tenga un buzón de Microsoft Exchange.

4. En el menú emergente de la derecha, vaya a **Configuración de correo > Respuestas automáticas** (si se trata de un buzón compartido, haga clic en **Respuestas automáticas** en la parte emergente).

**Método 2**

1. Inicie sesión en el portal de administración de Office 365 con las credenciales de administrador.

2. Expanda **Centros de administración** y, luego, haga clic en **Exchange**.

3. Haga clic en la imagen de la esquina superior derecha, luego en **Otro usuario** y, a continuación, seleccione el buzón de usuario que quiere cambiar.

4. En el lado izquierdo, seleccione **Opciones**, haga clic en **Organizar correo electrónico** y, a continuación, haga clic en **Respuestas automáticas.**

**Método 3**

Ejecute los siguientes cmdlet en Exchange Online PowerShell:

PowerShellCopy

    Set-MailboxAutoReplyConfiguration

Para obtener más información sobre este cmdlet, consulte [Set-MailboxAutoReplyConfiguration](https://docs.microsoft.com/powershell/module/exchange/mailboxes/set-mailboxautoreplyconfiguration).
