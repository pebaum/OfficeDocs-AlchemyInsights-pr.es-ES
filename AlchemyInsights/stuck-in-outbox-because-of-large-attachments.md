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
- "9002385"
- "4645"
ms.openlocfilehash: 35fe9ae76ca77faa43796b288af09be8525cb6df
ms.sourcegitcommit: 929f8accdca2b8e5be170e0fc8edd527581453d4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/12/2020
ms.locfileid: "43232647"
---
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a>Corregir mensajes que están atascados en la bandeja de salida

Le recomendamos que empiece por ejecutar el escenario ["tengo problemas para enviar, recibir o encontrar mensajes de correo electrónico"](https://aka.ms/SaRA-OutlookSendReceive) desde la herramienta [Asistente para soporte y recuperación de Microsoft](https://diagnostics.office.com/#/) en el equipo afectado.

Cuando un mensaje se bloquea en la bandeja de salida, la causa más probable es un dato adjunto grande o la opción "enviar inmediatamente cuando está conectado" no está habilitada.

**Quitar los datos adjuntos grandes**

1. Haga clic en **enviar y recibir** > **trabajo sin conexión**. 
2. En el panel de navegación, haga clic en **bandeja de salida**. Desde aquí, puede: 
    - Elimine el mensaje. Solo tiene que seleccionarlo y hacer clic en **eliminar**.
    - Arrastre el mensaje a la **carpeta Borradores**, haga doble clic en él para abrir el mensaje y elimine los datos adjuntos (haga clic en él y haga clic en **eliminar**).
3. Si un error indica que Outlook está intentando transmitir el mensaje, cierre Outlook. La salida puede tardar unos minutos. Si Outlook no se cierra, presione **Ctrl + Alt + Supr** y haga clic en **iniciar el administrador de tareas**. En el administrador de tareas, seleccione la pestaña **procesos** , desplácese hacia abajo hasta Outlook. exe y haga clic en **Finalizar proceso**.
4. Una vez que Outlook se cierre, reinicie Outlook y repita los pasos 2-3. 
5. Después de quitar los datos adjuntos, haga clic en **enviar y recibir** > **trabajar sin conexión** para anular la selección del botón y reanudar el trabajo en línea. 

Los mensajes también se atascan en la bandeja de salida cuando hace clic en **Enviar**, pero no está conectado. Haga clic en **enviar y recibir** y mire el botón **trabajar sin conexión** . Si es azul, está desconectado. Haga clic en él para conectarse (el botón se vuelve blanco) y haga clic en **enviar todo**.
 
**Habilitar enviar inmediatamente cuando esté conectado**
 
1. En la pestaña Archivo, haga clic en **Opciones**.

2. En el cuadro de diálogo Opciones de Outlook, haga clic en **avanzadas**.

3. En la sección enviar y recibir, haga clic para habilitar **enviar inmediatamente cuando esté conectado**. Haga clic en **Aceptar**.
 
Para obtener más información, consulte:
- [Vídeo: enviar o eliminar un correo electrónico bloqueado](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [El correo electrónico permanece en la carpeta Bandeja de salida hasta que se inicia manualmente una operación de envío y recepción en Outlook](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)
