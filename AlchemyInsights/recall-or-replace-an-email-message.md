---
title: Recuperar o reemplazar un mensaje de correo electrónico
ms.author: daeite
author: daeite
manager: joallard
ms.date: 05/15/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1860"
- "9000260"
ms.assetid: ''
ms.openlocfilehash: 170fbd632f0289a45d9497ac26fbe7f90cf88318
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/28/2019
ms.locfileid: "35356614"
---
# <a name="recall-or-replace-an-email-message"></a>Recuperar o reemplazar un mensaje de correo electrónico

- Solo puede **recuperar los mensajes que se envían a las personas de su organización**. Si el mensaje se envió a una dirección de gmail, por ejemplo, no puede recuperarlo.
- Solo puede **recuperar mensajes enviados desde Outlook 2016 para el equipo**. Si un usuario envía un mensaje con Outlook para Mac o Outlook en la web, no puede recuperarlo.
- Si es administrador, puede **recuperar mensajes en nombre de los usuarios con PowerShell**. No puede recuperar mensajes del centro de administración. Desplácese hacia abajo hasta "buscar y eliminar mensajes de correo electrónico de la organización" para obtener más información.

***Recuperar o reemplazar un mensaje de correo electrónico enviado***

1. En el panel de carpetas de la izquierda de la ventana de Outlook, elija la carpeta elementos enviados.
2. Abra el mensaje que desea recuperar. Debe hacer doble clic para abrir el mensaje. La selección del mensaje para que aparezca en el panel de lectura no le permitirá recuperar el mensaje.
3. En la pestaña mensaje, seleccione **acciones** > **recuperar este mensaje**.
4. Elija **eliminar copias no leídas de este mensaje** o **eliminar copias no leídas y reemplazarlas por un nuevo mensaje**y, a continuación, seleccione **Aceptar**.
5. Si va a enviar un mensaje de reemplazo, Redacte el mensaje y, a continuación, seleccione **Enviar**.
6. El éxito o el fracaso de una recuperación de mensajes depende de la configuración de los destinatarios en Outlook.

Para obtener más información, incluido cómo comprobar la recuperación, vea [recuperar o reemplazar un mensaje de correo electrónico enviado](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).

***Buscar y eliminar mensajes de correo electrónico de la organización*** Para buscar y eliminar mensajes de correo electrónico en su organización, es más fácil si es un administrador global. Si no es un administrador global, su cuenta debe agregarse al grupo de roles eDiscovery Manager o al rol de administración de búsqueda de cumplimiento. Para eliminar mensajes, debe unirse al grupo de funciones de administración de la organización o al rol de administración de búsqueda y depuración. Los permisos para estos roles se asignan en el [centro de seguridad & cumplimiento](https://protection.office.com/).

1. [Cree una búsqueda de contenido](https://docs.microsoft.com/office365/securitycompliance/content-search) para buscar el mensaje que se va a eliminar.
2. [Conéctese al centro de seguridad & PowerShell del centro de cumplimiento](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps). 

Si está usando MFA, consulte [conectarse a Office 365 Security & cumplimiento del centro de cumplimiento de PowerShell con multi-factor Authentication](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps). 
