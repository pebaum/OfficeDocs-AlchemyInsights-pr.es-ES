---
title: Escritorio de Outlook recuperar o reemplazar un mensaje de correo electrónico
ms.author: daeite
author: daeite
manager: joallard
ms.date: 3/13/2019
ms.audience: Admin
ms.topic: article
ms.custom: 9000260
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.openlocfilehash: 3d3a6c253317137b7069a978b907c97d61bf7313
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36496128"
---
# <a name="recall-or-replace-an-outlook-email-message"></a>Recuperar o reemplazar un mensaje de correo electrónico de Outlook

- Como administrador, puede **recuperar mensajes en nombre de los usuarios mediante PowerShell**. No puede recuperar mensajes del centro de administración.
- Solo puede **recuperar los mensajes que se envían a las personas de su organización**. Si el mensaje se envió a una dirección de gmail, por ejemplo, no puede recuperarlo.
- Solo puede **recuperar los mensajes enviados desde Outlook 2016 en el equipo PC**. Si un usuario envía un mensaje con Outlook para Mac o Outlook en la web, no puede recuperarlo.

Para recuperar o reemplazar un mensaje de correo electrónico:

1. En el panel de carpetas en la parte izquierda de la ventana de Outlook, seleccione la carpeta elementos enviados.
1. Haga doble clic en el mensaje que desea recuperar para abrirlo.
1. Seleccione la pestaña **mensaje** y, a continuación, seleccione **acciones** > **recuperar este mensaje**.
1. Seleccione **eliminar copias no leídas de este mensaje** o **eliminar copias no leídas y reemplazarlas con un nuevo mensaje**y, a continuación, seleccione **Aceptar**.
1. Si va a enviar un mensaje de reemplazo, Redacte el mensaje y, a continuación, seleccione **Enviar**.
1. El éxito o el fracaso de una recuperación de mensajes depende de la configuración del destinatario en Outlook. Para conocer los pasos para comprobar la recuperación, consulte [este artículo](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).

Buscar y eliminar mensajes de correo electrónico de la organización

- Si no es un administrador global, la cuenta debe agregarse a la función Administrador de eDiscovery o la función administración de búsqueda de cumplimiento para buscar mensajes. Para eliminar mensajes, debe unirse al grupo de funciones de administración de la organización o al rol de administración de búsqueda y depuración. Los permisos para estos roles se asignan en el [centro de seguridad y cumplimiento](https://go.microsoft.com/fwlink/?linkid=2083731).
- [Cree una búsqueda de contenido](https://docs.microsoft.com/office365/securitycompliance/content-search) para buscar el mensaje que se va a eliminar.
- [Conéctese a PowerShell del centro de seguridad y cumplimiento](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).

Si está usando la autenticación multifactor, consulte [conectarse a PowerShell del centro de seguridad y cumplimiento de Office 365 con la autenticación multifactor](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).