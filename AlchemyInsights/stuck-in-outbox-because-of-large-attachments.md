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
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a><span data-ttu-id="db121-102">Corregir mensajes que están atascados en la bandeja de salida</span><span class="sxs-lookup"><span data-stu-id="db121-102">Fix messages that are stuck in the Outbox</span></span>

<span data-ttu-id="db121-103">Le recomendamos que empiece por ejecutar el escenario ["tengo problemas para enviar, recibir o encontrar mensajes de correo electrónico"](https://aka.ms/SaRA-OutlookSendReceive) desde la herramienta [Asistente para soporte y recuperación de Microsoft](https://diagnostics.office.com/#/) en el equipo afectado.</span><span class="sxs-lookup"><span data-stu-id="db121-103">We recommend that you start by running the scenario ["I'm having problems sending, receiving, or finding email messages"](https://aka.ms/SaRA-OutlookSendReceive) from the [Microsoft Support and Recovery Assistant](https://diagnostics.office.com/#/) tool on the affected machine.</span></span>

<span data-ttu-id="db121-104">Cuando un mensaje se bloquea en la bandeja de salida, la causa más probable es un dato adjunto grande o la opción "enviar inmediatamente cuando está conectado" no está habilitada.</span><span class="sxs-lookup"><span data-stu-id="db121-104">When a message gets stuck in your Outbox, the most likely cause is a large attachment or the option "Send immediately when connected" is not enabled.</span></span>

<span data-ttu-id="db121-105">**Quitar los datos adjuntos grandes**</span><span class="sxs-lookup"><span data-stu-id="db121-105">**Remove the large attachment**</span></span>

1. <span data-ttu-id="db121-106">Haga clic en **enviar y recibir** > **trabajo sin conexión**.</span><span class="sxs-lookup"><span data-stu-id="db121-106">Click **Send / Receive** > **Work Offline**.</span></span> 
2. <span data-ttu-id="db121-107">En el panel de navegación, haga clic en **bandeja de salida**.</span><span class="sxs-lookup"><span data-stu-id="db121-107">In the navigation pane, click **Outbox**.</span></span> <span data-ttu-id="db121-108">Desde aquí, puede:</span><span class="sxs-lookup"><span data-stu-id="db121-108">From here, you can:</span></span> 
    - <span data-ttu-id="db121-109">Elimine el mensaje.</span><span class="sxs-lookup"><span data-stu-id="db121-109">Delete the message.</span></span> <span data-ttu-id="db121-110">Solo tiene que seleccionarlo y hacer clic en **eliminar**.</span><span class="sxs-lookup"><span data-stu-id="db121-110">Just select it and click **Delete**.</span></span>
    - <span data-ttu-id="db121-111">Arrastre el mensaje a la **carpeta Borradores**, haga doble clic en él para abrir el mensaje y elimine los datos adjuntos (haga clic en él y haga clic en **eliminar**).</span><span class="sxs-lookup"><span data-stu-id="db121-111">Drag the message to your **drafts folder**, double-click to open the message, and delete the attachment (click it and click **Delete**).</span></span>
3. <span data-ttu-id="db121-112">Si un error indica que Outlook está intentando transmitir el mensaje, cierre Outlook.</span><span class="sxs-lookup"><span data-stu-id="db121-112">If an error tells you Outlook is trying to transmit the message, close Outlook.</span></span> <span data-ttu-id="db121-113">La salida puede tardar unos minutos.</span><span class="sxs-lookup"><span data-stu-id="db121-113">It may take a few moments to exit.</span></span> <span data-ttu-id="db121-114">Si Outlook no se cierra, presione **Ctrl + Alt + Supr** y haga clic en **iniciar el administrador de tareas**.</span><span class="sxs-lookup"><span data-stu-id="db121-114">If Outlook doesn't close, press **Ctrl+Alt+Delete** and click **Start Task Manager**.</span></span> <span data-ttu-id="db121-115">En el administrador de tareas, seleccione la pestaña **procesos** , desplácese hacia abajo hasta Outlook. exe y haga clic en **Finalizar proceso**.</span><span class="sxs-lookup"><span data-stu-id="db121-115">In Task Manager, select the **Processes** tab, scroll down to outlook.exe, and click **End Process**.</span></span>
4. <span data-ttu-id="db121-116">Una vez que Outlook se cierre, reinicie Outlook y repita los pasos 2-3.</span><span class="sxs-lookup"><span data-stu-id="db121-116">After Outlook closes, restart Outlook and repeat steps 2-3.</span></span> 
5. <span data-ttu-id="db121-117">Después de quitar los datos adjuntos, haga clic en **enviar y recibir** > **trabajar sin conexión** para anular la selección del botón y reanudar el trabajo en línea.</span><span class="sxs-lookup"><span data-stu-id="db121-117">After you remove the attachment, click **Send / Receive** > **Work Offline** to deselect the button and to resume working online.</span></span> 

<span data-ttu-id="db121-118">Los mensajes también se atascan en la bandeja de salida cuando hace clic en **Enviar**, pero no está conectado.</span><span class="sxs-lookup"><span data-stu-id="db121-118">Messages also get stuck in the Outbox when you click **Send**, but you are not connected.</span></span> <span data-ttu-id="db121-119">Haga clic en **enviar y recibir** y mire el botón **trabajar sin conexión** .</span><span class="sxs-lookup"><span data-stu-id="db121-119">Click **Send / Receive** and look at the **Work Offline** button.</span></span> <span data-ttu-id="db121-120">Si es azul, está desconectado.</span><span class="sxs-lookup"><span data-stu-id="db121-120">If it's blue, you're disconnected.</span></span> <span data-ttu-id="db121-121">Haga clic en él para conectarse (el botón se vuelve blanco) y haga clic en **enviar todo**.</span><span class="sxs-lookup"><span data-stu-id="db121-121">Click it to connect (the button turns white) and click **Send All**.</span></span>
 
<span data-ttu-id="db121-122">**Habilitar enviar inmediatamente cuando esté conectado**</span><span class="sxs-lookup"><span data-stu-id="db121-122">**Enable Send immediately when connected**</span></span>
 
1. <span data-ttu-id="db121-123">En la pestaña Archivo, haga clic en **Opciones**.</span><span class="sxs-lookup"><span data-stu-id="db121-123">On the File tab, click **Options**.</span></span>

2. <span data-ttu-id="db121-124">En el cuadro de diálogo Opciones de Outlook, haga clic en **avanzadas**.</span><span class="sxs-lookup"><span data-stu-id="db121-124">In the Outlook Options dialog box, click **Advanced**.</span></span>

3. <span data-ttu-id="db121-125">En la sección enviar y recibir, haga clic para habilitar **enviar inmediatamente cuando esté conectado**.</span><span class="sxs-lookup"><span data-stu-id="db121-125">In the Send and receive section, click to enable **Send immediately when connected**.</span></span> <span data-ttu-id="db121-126">Haga clic en **Aceptar**.</span><span class="sxs-lookup"><span data-stu-id="db121-126">Click **OK**.</span></span>
 
<span data-ttu-id="db121-127">Para obtener más información, consulte:</span><span class="sxs-lookup"><span data-stu-id="db121-127">For full details, see:</span></span>
- [<span data-ttu-id="db121-128">Vídeo: enviar o eliminar un correo electrónico bloqueado</span><span class="sxs-lookup"><span data-stu-id="db121-128">Video: Send or delete a stuck email</span></span>](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [<span data-ttu-id="db121-129">El correo electrónico permanece en la carpeta Bandeja de salida hasta que se inicia manualmente una operación de envío y recepción en Outlook</span><span class="sxs-lookup"><span data-stu-id="db121-129">Email stays in the Outbox folder until you manually initiate a send/receive operation in Outlook</span></span>](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)
