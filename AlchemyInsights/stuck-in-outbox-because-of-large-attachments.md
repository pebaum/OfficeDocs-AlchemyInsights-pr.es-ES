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
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a><span data-ttu-id="7603b-102">Corregir mensajes que están atascados en la bandeja de salida</span><span class="sxs-lookup"><span data-stu-id="7603b-102">Fix messages that are stuck in the Outbox</span></span>

<span data-ttu-id="7603b-103">Le recomendamos que empiece por ejecutar el escenario ["tengo problemas para enviar, recibir o encontrar mensajes de correo electrónico"](https://aka.ms/SaRA-OutlookSendReceive) desde la herramienta [Asistente para soporte y recuperación de Microsoft](https://diagnostics.office.com/#/) .</span><span class="sxs-lookup"><span data-stu-id="7603b-103">We recommend that you start by running the scenario ["I’m having problems sending, receiving, or finding email messages"](https://aka.ms/SaRA-OutlookSendReceive) from the [Microsoft Support and Recovery Assistant](https://diagnostics.office.com/#/) tool.</span></span>

<span data-ttu-id="7603b-104">Cuando un mensaje se bloquea en la bandeja de salida, las causas más probables son:</span><span class="sxs-lookup"><span data-stu-id="7603b-104">When a message gets stuck in your Outbox, the most likely causes are:</span></span>
- <span data-ttu-id="7603b-105">Datos adjuntos de gran tamaño.</span><span class="sxs-lookup"><span data-stu-id="7603b-105">Large attachments.</span></span>
- <span data-ttu-id="7603b-106">La opción **enviar inmediatamente cuando esté conectado** no está habilitada.</span><span class="sxs-lookup"><span data-stu-id="7603b-106">The **Send immediately when connected** option is not enabled.</span></span>

<span data-ttu-id="7603b-107">Para quitar datos adjuntos grandes:</span><span class="sxs-lookup"><span data-stu-id="7603b-107">To remove large attachments:</span></span> 

1. <span data-ttu-id="7603b-108">En Outlook, seleccione **enviar y recibir** > **trabajar sin conexión**.</span><span class="sxs-lookup"><span data-stu-id="7603b-108">In Outlook, select **Send / Receive** > **Work Offline**.</span></span> 
2. <span data-ttu-id="7603b-109">En el panel de navegación, seleccione **bandeja de salida**.</span><span class="sxs-lookup"><span data-stu-id="7603b-109">In the navigation pane, select **Outbox**.</span></span> <span data-ttu-id="7603b-110">Desde aquí, puede:</span><span class="sxs-lookup"><span data-stu-id="7603b-110">From here, you can:</span></span> 
    - <span data-ttu-id="7603b-111">Elimine el mensaje (selecciónelo y, a continuación, seleccione **eliminar**).</span><span class="sxs-lookup"><span data-stu-id="7603b-111">Delete the message (select it and then select **Delete**).</span></span>
    - <span data-ttu-id="7603b-112">Arrastre el mensaje a la carpeta Borradores, haga doble clic en él para abrirlo, quite los datos adjuntos, selecciónelo y, a continuación, seleccione **eliminar**).</span><span class="sxs-lookup"><span data-stu-id="7603b-112">Drag the message to your Drafts folder, double-click to open it, and remove the attachment select it and then select **Delete**).</span></span>
3. <span data-ttu-id="7603b-113">Si recibe un error que indica que Outlook está intentando transmitir el mensaje, cierre Outlook.</span><span class="sxs-lookup"><span data-stu-id="7603b-113">If you receive an error that says Outlook is trying to transmit the message, close Outlook.</span></span> <span data-ttu-id="7603b-114">La salida puede tardar unos minutos.</span><span class="sxs-lookup"><span data-stu-id="7603b-114">It may take a few moments to exit.</span></span> <span data-ttu-id="7603b-115">Si Outlook no se cierra, presione Ctrl + Alt + Supr y seleccione **iniciar el administrador de tareas**.</span><span class="sxs-lookup"><span data-stu-id="7603b-115">If Outlook doesn’t close, press Ctrl+Alt+Delete and select **Start Task Manager**.</span></span> <span data-ttu-id="7603b-116">En el administrador de tareas, seleccione la pestaña **procesos** , desplácese hacia abajo hasta Outlook. exe y seleccione **Finalizar proceso**.</span><span class="sxs-lookup"><span data-stu-id="7603b-116">In Task Manager, select the **Processes** tab, scroll down to outlook.exe, and select **End Process**.</span></span>
4. <span data-ttu-id="7603b-117">Una vez que Outlook se cierre, reinícielo y repita los pasos 2 y 3.</span><span class="sxs-lookup"><span data-stu-id="7603b-117">After Outlook closes, restart it and repeat steps 2 and 3.</span></span> 
5. <span data-ttu-id="7603b-118">Después de quitar los datos adjuntos, haga clic en **enviar y recibir** > **trabajo sin conexión** para continuar trabajando en línea.</span><span class="sxs-lookup"><span data-stu-id="7603b-118">After you remove the attachment, click **Send / Receive** > **Work Offline** to resume working online.</span></span> 

<span data-ttu-id="7603b-119">Los mensajes también se atascan en la bandeja de salida cuando hace clic en **Enviar**, pero no está conectado.</span><span class="sxs-lookup"><span data-stu-id="7603b-119">Messages also get stuck in the Outbox when you click **Send**, but you are not connected.</span></span> <span data-ttu-id="7603b-120">Haga clic en **enviar y recibir** y mire el botón **trabajar sin conexión** .</span><span class="sxs-lookup"><span data-stu-id="7603b-120">Click **Send / Receive** and look at the **Work Offline** button.</span></span> <span data-ttu-id="7603b-121">Si es azul, está desconectado.</span><span class="sxs-lookup"><span data-stu-id="7603b-121">If it's blue, you're disconnected.</span></span> <span data-ttu-id="7603b-122">Seleccione esta opción para conectarse (el botón se vuelve blanco) y haga clic en **enviar todo**.</span><span class="sxs-lookup"><span data-stu-id="7603b-122">Select it to connect (the button turns white) and click **Send All**.</span></span>
 
<span data-ttu-id="7603b-123">Para habilitar **enviar inmediatamente cuando está conectado**:</span><span class="sxs-lookup"><span data-stu-id="7603b-123">To enable **Send immediately when connected**:</span></span>
 
- <span data-ttu-id="7603b-124">Seleccione \*\*\*\* > \*\*\*\* opciones >  de archivo**avanzadas**.</span><span class="sxs-lookup"><span data-stu-id="7603b-124">Select **File** > **Options** >  **Advanced**.</span></span>
<span data-ttu-id="7603b-125">En la sección **enviar y recibir** , seleccione **enviar inmediatamente cuando esté conectado**y, después, haga clic en **Aceptar**.</span><span class="sxs-lookup"><span data-stu-id="7603b-125">In the **Send and receive** section, select **Send immediately when connected**, and then choose **OK**.</span></span>
 
<span data-ttu-id="7603b-126">Para obtener detalles completos, consulte:</span><span class="sxs-lookup"><span data-stu-id="7603b-126">For full details see:</span></span>
- [<span data-ttu-id="7603b-127">Vídeo: enviar o eliminar un correo electrónico bloqueado</span><span class="sxs-lookup"><span data-stu-id="7603b-127">Video: Send or delete a stuck email</span></span>](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [<span data-ttu-id="7603b-128">El correo electrónico permanece en la carpeta Bandeja de salida hasta que se inicia manualmente una operación de envío y recepción en Outlook</span><span class="sxs-lookup"><span data-stu-id="7603b-128">Email stays in the Outbox folder until you manually initiate a send/receive operation in Outlook</span></span>](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)
