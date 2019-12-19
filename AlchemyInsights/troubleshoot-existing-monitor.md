---
title: Solución de problemas del monitor existente
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3454"
- "9001450"
ms.openlocfilehash: d90baddd01bdf8508bd6289509c8399b8241887a
ms.sourcegitcommit: 42463e8d8869f36225a27388d83d37629c6b149e
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/18/2019
ms.locfileid: "40738585"
---
# <a name="troubleshoot-an-existing-monitor"></a><span data-ttu-id="e6563-102">Solucionar problemas de un monitor existente</span><span class="sxs-lookup"><span data-stu-id="e6563-102">Troubleshoot an existing monitor</span></span>

<span data-ttu-id="e6563-103">Pruebe estas soluciones para solucionar problemas de un monitor.</span><span class="sxs-lookup"><span data-stu-id="e6563-103">Try these solutions to troubleshoot a monitor.</span></span> 

<span data-ttu-id="e6563-104">**Actualizar la pantalla del monitor:**</span><span class="sxs-lookup"><span data-stu-id="e6563-104">**Refresh your monitor's display:**</span></span>

<span data-ttu-id="e6563-105">Presione las siguientes teclas al mismo tiempo: tecla Windows + Ctrl + Mayús + B. Esto actualizará la comunicación con el controlador de gráficos.</span><span class="sxs-lookup"><span data-stu-id="e6563-105">Press the following keys at the same time: Windows Key  + Ctrl + Shift + B. This will refresh communication with your graphics driver.</span></span> <span data-ttu-id="e6563-106">Los monitores parpadearán momentáneamente y regresarán después de unos segundos.</span><span class="sxs-lookup"><span data-stu-id="e6563-106">Your monitors will blink momentarily and come back after a few seconds.</span></span>

<span data-ttu-id="e6563-107">**Solución de problemas de hardware de monitor:**</span><span class="sxs-lookup"><span data-stu-id="e6563-107">**Troubleshoot monitor hardware:**</span></span>

1. <span data-ttu-id="e6563-108">Desconecta el cable que conecta el equipo con el monitor y vuelve a conectarlo.</span><span class="sxs-lookup"><span data-stu-id="e6563-108">Unplug the cable connecting your PC to your monitor, and plug it back in.</span></span>
2. <span data-ttu-id="e6563-109">Desconecte los dispositivos que no sean esenciales de su PC (como adaptadores o muelles).</span><span class="sxs-lookup"><span data-stu-id="e6563-109">Disconnect any non-essential devices from your PC (such as adapters or docks).</span></span>

<span data-ttu-id="e6563-110">**Si ha instalado recientemente una actualización en su PC, puede revertir el controlador de pantalla:**</span><span class="sxs-lookup"><span data-stu-id="e6563-110">**If you recently installed an update on your PC, you can roll back your display driver:**</span></span>

1. <span data-ttu-id="e6563-111">Seleccione **Inicio**, escriba **Administrador de dispositivos**y seleccione el **Administrador de dispositivos** en los resultados.</span><span class="sxs-lookup"><span data-stu-id="e6563-111">Select **Start**, type **device manager**, and select **Device Manager** from the results.</span></span>
2. <span data-ttu-id="e6563-112">Expanda la sección **adaptadores de pantalla** , haga clic con el botón secundario en el adaptador de pantalla mezclar seleccione **propiedades**.</span><span class="sxs-lookup"><span data-stu-id="e6563-112">Expand the **Display adapters** section, right-click your display adapter, ands select **Properties**.</span></span>
3. <span data-ttu-id="e6563-113">Vaya a la ficha **controlador** y seleccione **volver al controlador posterior**.</span><span class="sxs-lookup"><span data-stu-id="e6563-113">Navigate to the **Driver** tab and select **Roll Back Driver**.</span></span> <br>
<span data-ttu-id="e6563-114">Nota: Si esta opción no está disponible o está atenuada, seleccione **no** en las siguientes opciones para ir al paso siguiente.</span><span class="sxs-lookup"><span data-stu-id="e6563-114">Note: If this isn't available or is grayed out, select **No** from the options below to move to the next step.</span></span>
4. <span data-ttu-id="e6563-115">Es posible que tengas que reiniciar el equipo para que estos cambios surtan efecto.</span><span class="sxs-lookup"><span data-stu-id="e6563-115">You may need to restart your PC before these changes take effect.</span></span>

<span data-ttu-id="e6563-116">**Desinstale y vuelva a instalar el controlador de pantalla:**</span><span class="sxs-lookup"><span data-stu-id="e6563-116">**Uninstall and reinstall your display driver:**</span></span>

1. <span data-ttu-id="e6563-117">Seleccione **Inicio**, escriba **Administrador de dispositivos**y seleccione el **Administrador de dispositivos** en los resultados.</span><span class="sxs-lookup"><span data-stu-id="e6563-117">Select **Start**, type **device manager**, and select **Device Manager** from the results.</span></span>
2. <span data-ttu-id="e6563-118">Expanda la sección **adaptadores de pantalla** , haga clic con el botón secundario en el adaptador de pantalla, mezclar seleccione **desinstalar dispositivo**.</span><span class="sxs-lookup"><span data-stu-id="e6563-118">Expand the **Display adapters** section, right-click your display adapter, ands select **Uninstall device**.</span></span> 
3. <span data-ttu-id="e6563-119">Seleccione el cuadro situado junto a **eliminar el software de controlador para este dispositivo** y seleccione **desinstalar**.</span><span class="sxs-lookup"><span data-stu-id="e6563-119">Select the box next to **Delete the driver software for this device** and select **Uninstall**.</span></span><br>
<span data-ttu-id="e6563-120">Nota: es posible que se le pida que reinicie el equipo en esta fase.</span><span class="sxs-lookup"><span data-stu-id="e6563-120">Note: You may be asked to restart your computer at this stage.</span></span> <span data-ttu-id="e6563-121">Asegúrese de anotar las demás instrucciones antes de reiniciar.</span><span class="sxs-lookup"><span data-stu-id="e6563-121">Make sure to write down the remaining instructions before you restart.</span></span>
4. <span data-ttu-id="e6563-122">Vuelva a abrir el administrador de dispositivos.</span><span class="sxs-lookup"><span data-stu-id="e6563-122">Open Device Manager again.</span></span>
5. <span data-ttu-id="e6563-123">Expanda la sección **adaptadores de pantalla** , haga clic con el botón secundario en el adaptador de pantalla y seleccione **Actualizar controlador**.</span><span class="sxs-lookup"><span data-stu-id="e6563-123">Expand the **Display adapters** section, right-click on your display adapter, and select **Update Driver**.</span></span>
6. <span data-ttu-id="e6563-124">Seleccione **Buscar software de controlador de actualización automáticamente** y siga las instrucciones de instalación.</span><span class="sxs-lookup"><span data-stu-id="e6563-124">Select **Search automatically for update driver software** and follow the installation instructions.</span></span>