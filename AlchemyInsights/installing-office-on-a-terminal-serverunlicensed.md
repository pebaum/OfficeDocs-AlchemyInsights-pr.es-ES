---
title: Instalación de Office en Terminal Server sin licencia
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "917"
- "2000020"
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: 51d1a66fdf9774bbe58bfdbe89317bc93834be09
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/25/2019
ms.locfileid: "37205426"
---
# <a name="installing-office-on-a-terminal-server"></a><span data-ttu-id="332c6-102">Instalación de Office en un servidor Terminal Server</span><span class="sxs-lookup"><span data-stu-id="332c6-102">Installing Office on a Terminal Server</span></span>

<span data-ttu-id="332c6-103">Para implementar Office 365 ProPlus en un servidor Windows con servicios de escritorio remoto (RDS), anteriormente denominado Terminal Services:</span><span class="sxs-lookup"><span data-stu-id="332c6-103">For deploying Office 365 ProPlus on a Windows Server using Remote Desktop Services (RDS), formerly named Terminal Services:</span></span>
  
- <span data-ttu-id="332c6-104">Debe tener un plan de Office 365 que incluya Office 365 ProPlus, como Office 365 Enterprise E3 o Enterprise E5.</span><span class="sxs-lookup"><span data-stu-id="332c6-104">You must have an Office 365 plan that includes Office 365 ProPlus, such as Office 365 Enterprise E3 or Enterprise E5.</span></span> <span data-ttu-id="332c6-105">Los planes de Office 365 Business and Office 365 Business Premium no incluyen Office 365 ProPlus.</span><span class="sxs-lookup"><span data-stu-id="332c6-105">The Office 365 Business and Office 365 Business Premium plans do not include Office 365 ProPlus.</span></span>

- <span data-ttu-id="332c6-106">Debe habilitar la [activación en equipos compartidos](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span><span class="sxs-lookup"><span data-stu-id="332c6-106">You need to enable [shared computer activation](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span></span>

<span data-ttu-id="332c6-107">Si desea instalar Office 365 ProPlus en RDS desde el centro de administración de Microsoft 365, ***que usa la configuración de instalación predeterminada***, siga estos pasos.</span><span class="sxs-lookup"><span data-stu-id="332c6-107">If you want to install Office 365 ProPlus on RDS from the Microsoft 365 admin center, ***which uses default installation settings***, use the following steps.</span></span>

> [!TIP]
> <span data-ttu-id="332c6-108">También puede descargar y ejecutar el [Asistente para soporte y recuperación de Microsoft](https://aka.ms/SaRA_OfficeSCA_M365Portal) para instalar Office 365 ProPlus en el modo de activación en equipos compartidos.</span><span class="sxs-lookup"><span data-stu-id="332c6-108">You can also download and run the [Microsoft Support and Recovery Assistant](https://aka.ms/SaRA_OfficeSCA_M365Portal) to install Office 365 ProPlus in shared computer activation mode.</span></span>
  
1. <span data-ttu-id="332c6-109">Compruebe qué plan de Office 365 tiene.</span><span class="sxs-lookup"><span data-stu-id="332c6-109">Check what Office 365 plan you have.</span></span> [<span data-ttu-id="332c6-110">Obtenga información sobre cómo</span><span class="sxs-lookup"><span data-stu-id="332c6-110">Learn how</span></span>](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)

2. <span data-ttu-id="332c6-111">Si es necesario, cambie a un plan de Office 365 diferente.</span><span class="sxs-lookup"><span data-stu-id="332c6-111">If necessary, switch to a different Office 365 plan.</span></span> [<span data-ttu-id="332c6-112">Obtenga información sobre cómo</span><span class="sxs-lookup"><span data-stu-id="332c6-112">Learn how</span></span>](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)

3. <span data-ttu-id="332c6-113">Si Office ya está instalado en el servidor RDS con otros planes de Office 365, desinstálelo.</span><span class="sxs-lookup"><span data-stu-id="332c6-113">If Office is already installed on the RDS server using any other Office 365 plans, uninstall it.</span></span> <span data-ttu-id="332c6-114">Por ejemplo, vaya a control panel \> desinstalar un programa.</span><span class="sxs-lookup"><span data-stu-id="332c6-114">For example, by going to Control Panel \> Uninstall a program.</span></span> <span data-ttu-id="332c6-115">Desinstale con el [Asistente para soporte y recuperación de Microsoft](https://aka.ms/SARA-OfficeUninstall-Alchemy) si está teniendo problemas.</span><span class="sxs-lookup"><span data-stu-id="332c6-115">Uninstall using [Microsoft Support and Recovery Assistant](https://aka.ms/SARA-OfficeUninstall-Alchemy) if you're running into issues.</span></span>

4. <span data-ttu-id="332c6-116">En el servidor de RDS, inicie sesión en el centro de administración de Microsoft 365 con su cuenta de administrador e [instale Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span><span class="sxs-lookup"><span data-stu-id="332c6-116">On the RDS server, sign in to the Microsoft 365 admin center with your administrator account and [install Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span></span>

5. <span data-ttu-id="332c6-117">Una vez instalado Office, ***no abra ni inicie sesión*** en ninguna de las aplicaciones de Office.</span><span class="sxs-lookup"><span data-stu-id="332c6-117">After Office is installed, ***don't open or sign in*** to any Office applications.</span></span>

6. <span data-ttu-id="332c6-118">En el servidor RDS, habilite la activación en equipos compartidos editando el registro siguiendo estos pasos:</span><span class="sxs-lookup"><span data-stu-id="332c6-118">On the RDS server, enable shared computer activation by editing the registry by following these steps:</span></span>

1. <span data-ttu-id="332c6-119">Haga clic con el botón derecho en el botón Windows en la esquina inferior izquierda de la pantalla y seleccione Ejecutar.</span><span class="sxs-lookup"><span data-stu-id="332c6-119">Right-click the Windows button in the lower left-hand corner of your screen and select Run.</span></span> <span data-ttu-id="332c6-120">En el cuadro Abrir, escriba **regedit**y, a continuación, seleccione Aceptar.</span><span class="sxs-lookup"><span data-stu-id="332c6-120">In the Open box, type **regedit**, and then select OK.</span></span>

2. <span data-ttu-id="332c6-121">Seleccione Sí cuando se le pregunte si desea permitir que el editor del registro realice cambios en el dispositivo.</span><span class="sxs-lookup"><span data-stu-id="332c6-121">Select Yes when prompted to allow Registry Editor to make changes to your device.</span></span>

3. <span data-ttu-id="332c6-122">En el editor del registro, agregue un valor de cadena de **SharedComputerLicensing** con un valor de 1 en HKEY_LOCAL_MACHINE\Software\Microsoft \Office\ClickToRun\Configuration.</span><span class="sxs-lookup"><span data-stu-id="332c6-122">In the Registry Editor, add a string value of **SharedComputerLicensing** with a setting of 1 under HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span></span>

7. <span data-ttu-id="332c6-123">En el servidor RDS, ***inicie sesión como usuario final*** y [Compruebe que la activación en equipos compartidos está habilitada para Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span><span class="sxs-lookup"><span data-stu-id="332c6-123">On the RDS server, ***sign in as an end user*** and [verify that shared computer activation is enabled for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span></span>

<span data-ttu-id="332c6-124">Para obtener más información sobre requisitos previos, instrucciones de instalación e instrucciones sobre instalaciones personalizadas mediante la herramienta de implementación de Office, consulte [deploy office 365 ProPlus by Using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span><span class="sxs-lookup"><span data-stu-id="332c6-124">For more details on prerequisites, setup instructions and guidance on customized installations by using the Office Deployment Tool, please see [Deploy Office 365 ProPlus by using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span></span>
  
<span data-ttu-id="332c6-125">Para corregir los errores relacionados con la activación en equipos compartidos, consulte [solucionar problemas con la activación en equipos compartidos para Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span><span class="sxs-lookup"><span data-stu-id="332c6-125">To fix errors related to shared computer activation, please see [Troubleshoot issues with shared computer activation for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span></span>
  