---
title: Atascado en la bandeja de salida debido a datos adjuntos grandes
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2713"
- "9000768"
ms.openlocfilehash: d5fb20fcc146be67c5a04de0640ed4efd625311a
ms.sourcegitcommit: 8004ee243b5c68ff9532224a2e6c69dda0abbd0b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/10/2019
ms.locfileid: "37441322"
---
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a>Corregir mensajes que están atascados en la bandeja de salida

Le recomendamos que empiece por ejecutar el escenario ["tengo problemas para enviar, recibir o encontrar mensajes de correo electrónico"](https://aka.ms/SaRA-OutlookSendReceive) desde la herramienta [Asistente para soporte y recuperación de Microsoft](https://diagnostics.office.com/#/) .

Cuando un mensaje se bloquea en la bandeja de salida, las causas más probables son:
- Datos adjuntos de gran tamaño.
- La opción **enviar inmediatamente cuando esté conectado** no está habilitada.

Para quitar datos adjuntos grandes: 

1. En Outlook, seleccione **enviar y recibir** > **trabajar sin conexión**. 
2. En el panel de navegación, seleccione **bandeja de salida**. Desde aquí, puede: 
    - Elimine el mensaje (selecciónelo y, a continuación, seleccione **eliminar**).
    - Arrastre el mensaje a la carpeta Borradores, haga doble clic en él para abrirlo, quite los datos adjuntos, selecciónelo y, a continuación, seleccione **eliminar**).
3. Si recibe un error que indica que Outlook está intentando transmitir el mensaje, cierre Outlook. La salida puede tardar unos minutos. Si Outlook no se cierra, presione Ctrl + Alt + Supr y seleccione **iniciar el administrador de tareas**. En el administrador de tareas, seleccione la pestaña **procesos** , desplácese hacia abajo hasta Outlook. exe y seleccione **Finalizar proceso**.
4. Una vez que Outlook se cierre, reinícielo y repita los pasos 2 y 3. 
5. Después de quitar los datos adjuntos, haga clic en **enviar y recibir** > **trabajo sin conexión** para continuar trabajando en línea. 

Los mensajes también se atascan en la bandeja de salida cuando hace clic en **Enviar**, pero no está conectado. Haga clic en **enviar y recibir** y mire el botón **trabajar sin conexión** . Si es azul, está desconectado. Seleccione esta opción para conectarse (el botón se vuelve blanco) y haga clic en **enviar todo**.
 
Para habilitar **enviar inmediatamente cuando está conectado**:
 
- Seleccione **** > **** opciones >  de archivo**avanzadas**.
En la sección **enviar y recibir** , seleccione **enviar inmediatamente cuando esté conectado**y, después, haga clic en **Aceptar**.
 
Para obtener detalles completos, consulte:
- [Vídeo: enviar o eliminar un correo electrónico bloqueado](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [El correo electrónico permanece en la carpeta Bandeja de salida hasta que se inicia manualmente una operación de envío y recepción en Outlook](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)
