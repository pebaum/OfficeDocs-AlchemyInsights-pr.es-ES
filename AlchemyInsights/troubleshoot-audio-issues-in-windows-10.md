---
title: Solucionar problemas de audio en Windows 10
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3476"
- "9001463"
ms.openlocfilehash: 46b23f97c2e682258224dc95e7a76b1201991828
ms.sourcegitcommit: 802537a54ef8bde1bdd758ee9a60b6c19d37d6e1
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/19/2019
ms.locfileid: "40796395"
---
# <a name="troubleshooting-audio-problems-in-windows-10"></a><span data-ttu-id="f1236-102">Solución de problemas de audio en Windows 10</span><span class="sxs-lookup"><span data-stu-id="f1236-102">Troubleshooting audio problems in Windows 10</span></span>

<span data-ttu-id="f1236-103">**Ejecutar el solucionador de problemas de audio**</span><span class="sxs-lookup"><span data-stu-id="f1236-103">**Run the audio troubleshooter**</span></span>

<span data-ttu-id="f1236-104">Es posible que el solucionador de problemas de audio pueda corregir los problemas de audio automáticamente:</span><span class="sxs-lookup"><span data-stu-id="f1236-104">The audio troubleshooter might be able to fix the audio problems automatically:</span></span> 

1. <span data-ttu-id="f1236-105">Seleccione **Inicio**, escriba **solución de problemas**y, a continuación, seleccione **solución de problemas** en la lista de resultados.</span><span class="sxs-lookup"><span data-stu-id="f1236-105">Select **Start**, type **troubleshoot**, and then select **Troubleshoot** from the list of results.</span></span> 
2. <span data-ttu-id="f1236-106">Seleccionar **reproducir audio** > **ejecute el solucionador de problemas**.</span><span class="sxs-lookup"><span data-stu-id="f1236-106">Select **Playing Audio** > **Run the troubleshooter**.</span></span>

<span data-ttu-id="f1236-107">**Comprobar los cables, el volumen, los altavoces y los auriculares**</span><span class="sxs-lookup"><span data-stu-id="f1236-107">**Check cables, volume, speakers, and headphones**</span></span>

- <span data-ttu-id="f1236-108">Comprueba las conexiones de altavoces y auriculares para ver si hay cables sueltos y asegúrate de que estén conectados a la clavija correcta.</span><span class="sxs-lookup"><span data-stu-id="f1236-108">Check your speaker and headphone connections for loose cables, and make sure they're connected to the correct jack.</span></span>
- <span data-ttu-id="f1236-109">Compruebe los niveles de energía y volumen e intente subir todos los controles de volumen.</span><span class="sxs-lookup"><span data-stu-id="f1236-109">Check your power and volume levels, and try turning all the volume controls up.</span></span>
- <span data-ttu-id="f1236-110">Algunos altavoces y aplicaciones tienen sus propios controles de volumen y es posible que debas comprobar todos ellos para asegurarse de que se encuentran en los niveles correctos.</span><span class="sxs-lookup"><span data-stu-id="f1236-110">Some speakers and apps have their own volume controls, and you might have to check them all to make sure they're at the right levels.</span></span>
- <span data-ttu-id="f1236-111">Intente conectarse usando un puerto USB diferente.</span><span class="sxs-lookup"><span data-stu-id="f1236-111">Try connecting using a different USB port.</span></span>
- <span data-ttu-id="f1236-112">**Nota:** Recuerde que es posible que los altavoces no funcionen cuando los auriculares estén conectados.</span><span class="sxs-lookup"><span data-stu-id="f1236-112">**Note:** Remember that your speakers may not work when headphones are plugged in.</span></span>

<span data-ttu-id="f1236-113">**Comprobar el administrador de dispositivos**</span><span class="sxs-lookup"><span data-stu-id="f1236-113">**Check Device Manager**</span></span>

<span data-ttu-id="f1236-114">Para asegurarse de que los controladores están actualizados:</span><span class="sxs-lookup"><span data-stu-id="f1236-114">To make sure the drivers are up to date:</span></span>

- <span data-ttu-id="f1236-115">Seleccione **Inicio**, escriba **Administrador de dispositivos**y, a continuación, seleccione **Administrador de dispositivos** en la lista de resultados.</span><span class="sxs-lookup"><span data-stu-id="f1236-115">Select **Start**, type **Device Manager**, and then select **Device Manager** from the list of results.</span></span>

2. <span data-ttu-id="f1236-116">En **dispositivos de sonido, vídeo y juegos**, seleccione la tarjeta de sonido, ábrala, seleccione la pestaña **controlador** y haga clic en **Actualizar controlador**.</span><span class="sxs-lookup"><span data-stu-id="f1236-116">Under **Sound, video, and game controllers**, select your sound card, open it, select the **Driver** tab, and select **Update Driver**.</span></span> 

<span data-ttu-id="f1236-117">**Nota:** Si Windows no encuentra un nuevo controlador, busca uno en el sitio web del fabricante del dispositivo y sigue sus instrucciones.</span><span class="sxs-lookup"><span data-stu-id="f1236-117">**Note:** If Windows doesn't find a new driver, look for one on the device manufacturer's website and follow their instructions.</span></span>

<span data-ttu-id="f1236-118">**Reinstalar el controlador**</span><span class="sxs-lookup"><span data-stu-id="f1236-118">**Reinstall the driver**</span></span>

<span data-ttu-id="f1236-119">Si no puede actualizar mediante el administrador de dispositivos o encontrar un nuevo controlador en el sitio web del fabricante, pruebe estos pasos:</span><span class="sxs-lookup"><span data-stu-id="f1236-119">If you can't update via Device Manager or find a new driver on the manufacturer's website, try these steps:</span></span> 

1. <span data-ttu-id="f1236-120">En el administrador de dispositivos, haga clic con el botón derecho (o mantenga presionado) el controlador de audio y seleccione **desinstalar**.</span><span class="sxs-lookup"><span data-stu-id="f1236-120">In Device Manager, right-click (or press and hold) the audio driver, and select **Uninstall**.</span></span> <span data-ttu-id="f1236-121">Reinicia el dispositivo y Windows intentará reinstalar el controlador.</span><span class="sxs-lookup"><span data-stu-id="f1236-121">Restart your device and Windows will attempt to reinstall the driver.</span></span>

2. <span data-ttu-id="f1236-122">Si no funciona la reinstalación del controlador, prueba a usar el controlador de audio genérico que se incluye con Windows.</span><span class="sxs-lookup"><span data-stu-id="f1236-122">If reinstalling the driver doesn't work, try using the generic audio driver that comes with Windows.</span></span> <span data-ttu-id="f1236-123">En el administrador de dispositivos, haga clic con el botón derecho (o mantenga presionado) el controlador de audio > **actualizar el software** > **de controlador buscar en el equipo para el software** > de controlador**permitirme elegir de una lista de controladores de dispositivo en mi PC**, seleccione **dispositivo de audio de alta definición**, seleccione **siguiente**y siga las instrucciones para instalarlo.</span><span class="sxs-lookup"><span data-stu-id="f1236-123">In Device Manager, right-click (or press and hold) your audio driver > **Update driver software** > **Browse my computer for driver software** > **Let me pick from a list of device drivers on my computer**, select **High Definition Audio Device**, select **Next**, and follow the instructions to install it.</span></span>

<span data-ttu-id="f1236-124">**Establecer el dispositivo predeterminado**</span><span class="sxs-lookup"><span data-stu-id="f1236-124">**Set the default device**</span></span>

<span data-ttu-id="f1236-125">Si te conectas a un dispositivo de audio mediante USB o HDMI, es posible que tengas que establecer ese dispositivo como predeterminado:</span><span class="sxs-lookup"><span data-stu-id="f1236-125">If you're connecting to an audio device using USB or HDMI, you might need to set that device as the default:</span></span> 

1. <span data-ttu-id="f1236-126">Seleccione **Inicio**, escriba **sonido**y, a continuación, seleccione **sonido** o **cambiar sonidos del sistema** de la lista de resultados.</span><span class="sxs-lookup"><span data-stu-id="f1236-126">Select **Start**, type **Sound**, and then select **Sound** or **Change system sounds** from the list of results.</span></span>

2. <span data-ttu-id="f1236-127">En la pestaña **reproducción** , seleccione un dispositivo, seleccione **establecer como predeterminado**y, después, haga clic en **Aceptar**.</span><span class="sxs-lookup"><span data-stu-id="f1236-127">On the **Playback** tab, select a device, select **Set Default**, and then select **OK**.</span></span>

