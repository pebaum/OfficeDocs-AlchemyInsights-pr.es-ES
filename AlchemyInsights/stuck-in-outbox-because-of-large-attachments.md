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
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a><span data-ttu-id="28cac-102">Corregir mensajes que están atascados en la bandeja de salida</span><span class="sxs-lookup"><span data-stu-id="28cac-102">Fix messages that are stuck in the Outbox</span></span>

<span data-ttu-id="28cac-103">Le recomendamos que empiece por ejecutar el escenario ["tengo problemas para enviar, recibir o encontrar mensajes de correo electrónico"](https://aka.ms/SaRA-OutlookSendReceive) desde la herramienta [Asistente para soporte y recuperación de Microsoft](https://diagnostics.office.com/#/) .</span><span class="sxs-lookup"><span data-stu-id="28cac-103">We recommend that you start by running the scenario ["I'm having problems sending, receiving, or finding email messages"](https://aka.ms/SaRA-OutlookSendReceive) from the [Microsoft Support and Recovery Assistant](https://diagnostics.office.com/#/) tool.</span></span>

<span data-ttu-id="28cac-104">Cuando un mensaje se bloquea en la bandeja de salida, la causa más probable es un dato adjunto grande o la opción "enviar inmediatamente cuando está conectado" no está habilitada.</span><span class="sxs-lookup"><span data-stu-id="28cac-104">When a message gets stuck in your Outbox, the most likely cause is a large attachment or the option "Send immediately when connected" is not enabled.</span></span>

<span data-ttu-id="28cac-105">**Quitar los datos adjuntos grandes**</span><span class="sxs-lookup"><span data-stu-id="28cac-105">**Remove the large attachment**</span></span>

1. <span data-ttu-id="28cac-106">En Outlook, seleccione **enviar y recibir** > **trabajar sin conexión**.</span><span class="sxs-lookup"><span data-stu-id="28cac-106">In Outlook, select **Send / Receive** > **Work Offline**.</span></span> 
2. <span data-ttu-id="28cac-107">En el panel de navegación, seleccione **bandeja de salida**.</span><span class="sxs-lookup"><span data-stu-id="28cac-107">In the navigation pane, select **Outbox**.</span></span> <span data-ttu-id="28cac-108">Desde aquí, puede:</span><span class="sxs-lookup"><span data-stu-id="28cac-108">From here, you can:</span></span> 
    - <span data-ttu-id="28cac-109">Elimine el mensaje (selecciónelo y, a continuación, seleccione **eliminar**).</span><span class="sxs-lookup"><span data-stu-id="28cac-109">Delete the message (select it and then select **Delete**).</span></span>
    - <span data-ttu-id="28cac-110">Arrastre el mensaje a la carpeta Borradores, haga doble clic en él para abrirlo, quite los datos adjuntos, selecciónelo y, a continuación, seleccione **eliminar**).</span><span class="sxs-lookup"><span data-stu-id="28cac-110">Drag the message to your Drafts folder, double-click to open it, and remove the attachment select it and then select **Delete**).</span></span>
3. <span data-ttu-id="28cac-111">Si recibe un error que indica que Outlook está intentando transmitir el mensaje, cierre Outlook.</span><span class="sxs-lookup"><span data-stu-id="28cac-111">If you receive an error that says Outlook is trying to transmit the message, close Outlook.</span></span> <span data-ttu-id="28cac-112">La salida puede tardar unos minutos.</span><span class="sxs-lookup"><span data-stu-id="28cac-112">It may take a few moments to exit.</span></span> <span data-ttu-id="28cac-113">Si Outlook no se cierra, presione Ctrl + Alt + Supr y seleccione **iniciar el administrador de tareas**.</span><span class="sxs-lookup"><span data-stu-id="28cac-113">If Outlook doesn't close, press Ctrl+Alt+Delete and select **Start Task Manager**.</span></span> <span data-ttu-id="28cac-114">En el administrador de tareas, seleccione la pestaña **procesos** , desplácese hacia abajo hasta Outlook. exe y seleccione **Finalizar proceso**.</span><span class="sxs-lookup"><span data-stu-id="28cac-114">In Task Manager, select the **Processes** tab, scroll down to outlook.exe, and select **End Process**.</span></span>
4. <span data-ttu-id="28cac-115">Una vez que Outlook se cierre, reinícielo y repita los pasos 2 y 3.</span><span class="sxs-lookup"><span data-stu-id="28cac-115">After Outlook closes, restart it and repeat steps 2 and 3.</span></span> 
5. <span data-ttu-id="28cac-116">Después de quitar los datos adjuntos, haga clic en **enviar y recibir** > **trabajo sin conexión** para continuar trabajando en línea.</span><span class="sxs-lookup"><span data-stu-id="28cac-116">After you remove the attachment, click **Send / Receive** > **Work Offline** to resume working online.</span></span> 

<span data-ttu-id="28cac-117">Los mensajes también se atascan en la bandeja de salida cuando hace clic en **Enviar**, pero no está conectado.</span><span class="sxs-lookup"><span data-stu-id="28cac-117">Messages also get stuck in the Outbox when you click **Send**, but you are not connected.</span></span> <span data-ttu-id="28cac-118">Haga clic en **enviar y recibir** y mire el botón **trabajar sin conexión** .</span><span class="sxs-lookup"><span data-stu-id="28cac-118">Click **Send / Receive** and look at the **Work Offline** button.</span></span> <span data-ttu-id="28cac-119">Si es azul, está desconectado.</span><span class="sxs-lookup"><span data-stu-id="28cac-119">If it's blue, you're disconnected.</span></span> <span data-ttu-id="28cac-120">Haga clic en él para conectarse (el botón se vuelve blanco) y haga clic en **enviar todo**.</span><span class="sxs-lookup"><span data-stu-id="28cac-120">Click it to connect (the button turns white) and click **Send All**.</span></span>
 
<span data-ttu-id="28cac-121">**Habilitar enviar inmediatamente cuando esté conectado**</span><span class="sxs-lookup"><span data-stu-id="28cac-121">**Enable Send immediately when connected**</span></span>
 
1. <span data-ttu-id="28cac-122">En la pestaña Archivo, haga clic en **Opciones**.</span><span class="sxs-lookup"><span data-stu-id="28cac-122">On the File tab, click **Options**.</span></span>

2. <span data-ttu-id="28cac-123">En el cuadro de diálogo Opciones de Outlook, haga clic en **avanzadas**.</span><span class="sxs-lookup"><span data-stu-id="28cac-123">In the Outlook Options dialog box, click **Advanced**.</span></span>

3. <span data-ttu-id="28cac-124">En la sección enviar y recibir, haga clic para habilitar **enviar inmediatamente cuando esté conectado**.</span><span class="sxs-lookup"><span data-stu-id="28cac-124">In the Send and receive section, click to enable **Send immediately when connected**.</span></span> <span data-ttu-id="28cac-125">Haga clic en **Aceptar**.</span><span class="sxs-lookup"><span data-stu-id="28cac-125">Click **OK**.</span></span>
 
<span data-ttu-id="28cac-126">Para obtener más información, consulte:</span><span class="sxs-lookup"><span data-stu-id="28cac-126">For full details, see:</span></span>
- [<span data-ttu-id="28cac-127">Vídeo: enviar o eliminar un correo electrónico bloqueado</span><span class="sxs-lookup"><span data-stu-id="28cac-127">Video: Send or delete a stuck email</span></span>](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [<span data-ttu-id="28cac-128">El correo electrónico permanece en la carpeta Bandeja de salida hasta que se inicia manualmente una operación de envío y recepción en Outlook</span><span class="sxs-lookup"><span data-stu-id="28cac-128">Email stays in the Outbox folder until you manually initiate a send/receive operation in Outlook</span></span>](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)
