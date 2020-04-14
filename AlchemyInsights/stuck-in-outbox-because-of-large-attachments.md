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
ms.openlocfilehash: 4f69de167dc51961fa7cf71b4d73ca7ee3ed4d55
ms.sourcegitcommit: 57fb994ddd3854d06faa67680c971b003b06bf83
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/13/2020
ms.locfileid: "43241269"
---
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a>Corregir mensajes que están atascados en la bandeja de salida

Le recomendamos que empiece por ejecutar el escenario ["tengo problemas para enviar, recibir o encontrar mensajes de correo electrónico"](https://aka.ms/SaRA-OutlookSendReceive) desde la herramienta [Asistente para soporte y recuperación de Microsoft](https://diagnostics.office.com/#/) .

Cuando un mensaje se bloquea en la bandeja de salida, la causa más probable es un dato adjunto grande o la opción "enviar inmediatamente cuando está conectado" no está habilitada.

**Quitar los datos adjuntos grandes**

1. En Outlook, seleccione **enviar y recibir** > **trabajar sin conexión**. 
2. En el panel de navegación, seleccione **bandeja de salida**. Desde aquí, puede: 
    - Elimine el mensaje (selecciónelo y, a continuación, seleccione **eliminar**).
    - Arrastre el mensaje a la carpeta Borradores, haga doble clic en él para abrirlo, quite los datos adjuntos, selecciónelo y, a continuación, seleccione **eliminar**).
3. Si recibe un error que indica que Outlook está intentando transmitir el mensaje, cierre Outlook. La salida puede tardar unos minutos. Si Outlook no se cierra, presione Ctrl + Alt + Supr y seleccione **iniciar el administrador de tareas**. En el administrador de tareas, seleccione la pestaña **procesos** , desplácese hacia abajo hasta Outlook. exe y seleccione **Finalizar proceso**.
4. Una vez que Outlook se cierre, reinícielo y repita los pasos 2 y 3. 
5. Después de quitar los datos adjuntos, haga clic en **enviar y recibir** > **trabajo sin conexión** para continuar trabajando en línea. 

Los mensajes también se atascan en la bandeja de salida cuando hace clic en **Enviar**, pero no está conectado. Haga clic en **enviar y recibir** y mire el botón **trabajar sin conexión** . Si es azul, está desconectado. Haga clic en él para conectarse (el botón se vuelve blanco) y haga clic en **enviar todo**.
 
**Habilitar enviar inmediatamente cuando esté conectado**
 
1. En la pestaña Archivo, haga clic en **Opciones**.

2. En el cuadro de diálogo Opciones de Outlook, haga clic en **avanzadas**.

3. En la sección enviar y recibir, haga clic para habilitar **enviar inmediatamente cuando esté conectado**. Haga clic en **Aceptar**.
 
Para obtener más información, consulte:
- [Vídeo: enviar o eliminar un correo electrónico bloqueado](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [El correo electrónico permanece en la carpeta Bandeja de salida hasta que se inicia manualmente una operación de envío y recepción en Outlook](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)
