---
title: Recuperar o reemplazar un mensaje de correo electrónico
ms.author: daeite
author: daeite
manager: joallard
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1860"
- "9000260"
ms.assetid: ''
ms.openlocfilehash: e541620a499b02a7206579ffcc505ceb4e632a4c
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43742772"
---
# <a name="recall-or-replace-an-email-message-in-microsoft-365"></a>Recuperar o reemplazar un mensaje de correo electrónico en Microsoft 365

- Solo puede **recuperar los mensajes que se envían a las personas de su organización**. Si el mensaje se envió a una dirección de gmail, por ejemplo, no puede recuperarlo.
- Solo puede **recuperar mensajes enviados desde Outlook 2016 para el equipo**. Si un usuario envía un mensaje con Outlook para Mac o Outlook en la web, no puede recuperarlo.
- Si es administrador, puede **recuperar mensajes en nombre de los usuarios con PowerShell**. No puede recuperar mensajes del centro de administración. Desplácese hacia abajo hasta "buscar y eliminar mensajes de correo electrónico de la organización" para obtener más información.

**Recuperar o reemplazar un mensaje de correo electrónico enviado**

1. En el panel de carpetas de la izquierda de la ventana de Outlook, elija la carpeta elementos enviados.
2. Abra el mensaje que desea recuperar. Debe hacer doble clic para abrir el mensaje. La selección del mensaje para que aparezca en el panel de lectura no le permitirá recuperar el mensaje.
3. En la pestaña mensaje, seleccione **acciones** > **recuperar este mensaje**.
4. Elija **eliminar copias no leídas de este mensaje** o **eliminar copias no leídas y reemplazarlas por un nuevo mensaje**y, a continuación, seleccione **Aceptar**.
5. Si va a enviar un mensaje de reemplazo, Redacte el mensaje y, a continuación, seleccione **Enviar**.
6. El éxito o el fracaso de una recuperación de mensajes depende de la configuración de los destinatarios en Outlook.

Para obtener más información, incluido cómo comprobar la recuperación, vea [recuperar o reemplazar un mensaje de correo electrónico enviado](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).

***Buscar y eliminar mensajes de correo electrónico de la organización*** Para buscar y eliminar mensajes de correo electrónico en su organización, es más fácil si es un administrador global. Si no es un administrador global, su cuenta debe agregarse al grupo de roles eDiscovery Manager o al rol de administración de búsqueda de cumplimiento. Para eliminar mensajes, debe unirse al grupo de funciones de administración de la organización o al rol de administración de búsqueda y depuración. Los permisos para estos roles se asignan en el [centro de seguridad & cumplimiento](https://protection.office.com/).

1. [Cree una búsqueda de contenido](https://docs.microsoft.com/office365/securitycompliance/content-search) para buscar el mensaje que se va a eliminar.
2. [Conectarse a PowerShell del Centro de seguridad y cumplimiento](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps). 

Si está usando MFA, consulte [conectarse a Microsoft 365 security & el centro de cumplimiento de PowerShell con autenticación multifactor](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps). 
