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
ms.openlocfilehash: 4ffe8d77dad7db5fd5806fe879cf4934e5ca7c4a
ms.sourcegitcommit: 89ae9e8b36d1980f89f07b016fff0ec48f96b620
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2020
ms.locfileid: "43788899"
---
# <a name="set-auto-replies-for-a-users-mailbox"></a>Establecer respuestas automáticas para un buzón de correo

**Método 1**

1. Iniciar sesión en el Portal de Microsoft 365.

2. Vaya a **Usuarios > Usuarios activos** (o **Grupos > Buzones compartidos** si configura esto en un buzón compartido).

3. Seleccione un usuario que tenga un buzón de Microsoft Exchange.

4. En el menú emergente de la derecha, vaya a **Configuración de correo > Respuestas automáticas** (si se trata de un buzón compartido, haga clic en **Respuestas automáticas** en la parte emergente).

**Método 2**

1. Iniciar sesión en el Portal de administración de Microsoft 365 con las credenciales de administrador.

2. Expanda **Centros de administración** y, luego, haga clic en **Exchange**.

3. Haga clic en la imagen de la esquina superior derecha, luego en **Otro usuario** y, a continuación, seleccione el buzón de usuario que quiere cambiar.

4. En el lado izquierdo, seleccione **Opciones**, haga clic en **Organizar correo electrónico** y, a continuación, haga clic en **Respuestas automáticas.**

**Método 3**

Ejecute los siguientes cmdlet en Exchange Online PowerShell:

PowerShellCopy

```
    Set-MailboxAutoReplyConfiguration
```

Para obtener más información sobre este cmdlet, consulte [Set-MailboxAutoReplyConfiguration](https://docs.microsoft.com/powershell/module/exchange/mailboxes/set-mailboxautoreplyconfiguration).
