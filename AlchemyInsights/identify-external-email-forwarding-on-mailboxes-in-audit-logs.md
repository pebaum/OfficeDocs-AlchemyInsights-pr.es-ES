---
title: Identificar el reenvío externo de correo electrónico en los buzones de registros de auditoría
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1369"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 7defd0902e8c8bebae9c7bfee72c3199cbc1909f
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36539118"
---
# <a name="identify-when-external-email-forwarding-is-configured-on-mailboxes"></a>Identificar cuándo se configura el reenvío externo de correo electrónico en los buzones

Cuando un usuario de Office 365 configura el reenvío externo de correo electrónico en un buzón, la actividad se audita como parte del cmdlet **set-Mailbox** . Puede ver la actividad mediante la búsqueda de registros de auditoría en el centro de seguridad & cumplimiento.

1. Inicie sesión en el [centro de cumplimiento de & de seguridad de Office 365](https://protection.office.com/).

2. Vaya a la página de**búsqueda del registro de auditoría** de **búsqueda** > .

3. Seleccione el intervalo de fechas en los campos **fecha de inicio** y **fecha** de finalización. No es necesario especificar un nombre de usuario. Compruebe que el campo **actividades** está configurado para **Mostrar resultados para todas las actividades**.

4. Haga clic en **Buscar**.

En los resultados, haga clic en **filtrar resultados** y escriba **set-Mailbox** en el cuadro filtro de actividad. Seleccione un registro de auditoría en los resultados. En el control flotante de **detalles** , haga clic en **más información**. Tiene que mirar los detalles de cada registro de auditoría para determinar si la actividad está relacionada con el reenvío de correo electrónico.

- **ObjectId**: el valor de alias del buzón que se modificó.

- **** Parameters: _ForwardingSmtpAddress_ indica la dirección de correo electrónico de destino.

- **Userid**: usuario que configuró el reenvío de correo electrónico en el buzón del campo **objectId** .

Para obtener más información, vea [determinar quién ha configurado el reenvío de correo para un buzón](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-who-set-up-email-forwarding-for-a-mailbox).
