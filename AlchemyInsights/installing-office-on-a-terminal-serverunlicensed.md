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
ms.openlocfilehash: 6e952513679c9ac66f8de2b43d6d243cf17ff789
ms.sourcegitcommit: 7e06d9ec1dd462cbd882f088c997d012a032f04d
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/04/2020
ms.locfileid: "44010631"
---
# <a name="installing-office-on-a-terminal-server"></a><span data-ttu-id="78758-102">Instalación de Office en un servidor Terminal Server</span><span class="sxs-lookup"><span data-stu-id="78758-102">Installing Office on a Terminal Server</span></span>

<span data-ttu-id="78758-103">Para implementar Microsoft 365 apps for Enterprise en un servidor Windows con servicios de escritorio remoto (RDS), anteriormente denominado Terminal Services:</span><span class="sxs-lookup"><span data-stu-id="78758-103">For deploying Microsoft 365 Apps for enterprise on a Windows Server using Remote Desktop Services (RDS), formerly named Terminal Services:</span></span>
  
- <span data-ttu-id="78758-104">Debe tener una suscripción a Microsoft 365 que incluya aplicaciones de Microsoft 365 para la empresa, como Office 365 Enterprise E3 o Enterprise E5.</span><span class="sxs-lookup"><span data-stu-id="78758-104">You must have a Microsoft 365 subscription that includes Microsoft 365 Apps for enterprise, such as Office 365 Enterprise E3 or Enterprise E5.</span></span> <span data-ttu-id="78758-105">Los planes de Microsoft 365 apps for Business y Microsoft 365 para empresas Premium no incluyen las aplicaciones de Microsoft 365 para empresas.</span><span class="sxs-lookup"><span data-stu-id="78758-105">The Microsoft 365 Apps for business and Microsoft 365 Apps for business Premium plans do not include Microsoft 365 Apps for enterprise.</span></span>

- <span data-ttu-id="78758-106">Debe habilitar la [activación en equipos compartidos](https://docs.microsoft.com/DeployOffice/overview-shared-computer-activation).</span><span class="sxs-lookup"><span data-stu-id="78758-106">You need to enable [shared computer activation](https://docs.microsoft.com/DeployOffice/overview-shared-computer-activation).</span></span>

<span data-ttu-id="78758-107">Si desea instalar las aplicaciones de Microsoft 365 para empresas en RDS desde el centro de administración de Microsoft 365, ***que usa la configuración de instalación predeterminada***, siga estos pasos.</span><span class="sxs-lookup"><span data-stu-id="78758-107">If you want to install Microsoft 365 Apps for enterprise on RDS from the Microsoft 365 admin center, ***which uses default installation settings***, use the following steps.</span></span>

> [!TIP]
> <span data-ttu-id="78758-108">También puede descargar y ejecutar el [Asistente para soporte y recuperación de Microsoft](https://aka.ms/SaRA_OfficeSCA_M365Portal) para instalar las aplicaciones de Microsoft 365 para empresas en el modo de activación en equipos compartidos.</span><span class="sxs-lookup"><span data-stu-id="78758-108">You can also download and run the [Microsoft Support and Recovery Assistant](https://aka.ms/SaRA_OfficeSCA_M365Portal) to install Microsoft 365 Apps for enterprise in shared computer activation mode.</span></span>
  
1. <span data-ttu-id="78758-109">Compruebe qué suscripción de Microsoft 365 tiene.</span><span class="sxs-lookup"><span data-stu-id="78758-109">Check what Microsoft 365 subscription you have.</span></span> [<span data-ttu-id="78758-110">Obtenga información sobre cómo</span><span class="sxs-lookup"><span data-stu-id="78758-110">Learn how</span></span>](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)

2. <span data-ttu-id="78758-111">Si es necesario, cambie a una suscripción de Microsoft 365 diferente.</span><span class="sxs-lookup"><span data-stu-id="78758-111">If necessary, switch to a different Microsoft 365 subscription.</span></span> [<span data-ttu-id="78758-112">Obtenga información sobre cómo</span><span class="sxs-lookup"><span data-stu-id="78758-112">Learn how</span></span>](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)

3. <span data-ttu-id="78758-113">Si Office ya está instalado en el servidor RDS con otras suscripciones de Microsoft 365, desinstálelo.</span><span class="sxs-lookup"><span data-stu-id="78758-113">If Office is already installed on the RDS server using any other Microsoft 365 subscriptions, uninstall it.</span></span> <span data-ttu-id="78758-114">Por ejemplo, vaya a control panel \> desinstalar un programa.</span><span class="sxs-lookup"><span data-stu-id="78758-114">For example, by going to Control Panel \> Uninstall a program.</span></span> <span data-ttu-id="78758-115">Desinstale con el [Asistente para soporte y recuperación de Microsoft](https://aka.ms/SARA-OfficeUninstall-Alchemy) si está teniendo problemas.</span><span class="sxs-lookup"><span data-stu-id="78758-115">Uninstall using [Microsoft Support and Recovery Assistant](https://aka.ms/SARA-OfficeUninstall-Alchemy) if you're running into issues.</span></span>

4. <span data-ttu-id="78758-116">En el servidor de RDS, inicie sesión en el centro de administración de Microsoft 365 con su cuenta de administrador e [Instale las aplicaciones de microsoft 365 para la empresa](https://portal.office.com/OLS/MySoftware.aspx).</span><span class="sxs-lookup"><span data-stu-id="78758-116">On the RDS server, sign in to the Microsoft 365 admin center with your administrator account and [install Microsoft 365 Apps for enterprise](https://portal.office.com/OLS/MySoftware.aspx).</span></span>

5. <span data-ttu-id="78758-117">Una vez instalado Office, ***no abra ni inicie sesión*** en ninguna de las aplicaciones de Office.</span><span class="sxs-lookup"><span data-stu-id="78758-117">After Office is installed, ***don't open or sign in*** to any Office applications.</span></span>

6. <span data-ttu-id="78758-118">En el servidor RDS, habilite la activación en equipos compartidos editando el registro siguiendo estos pasos:</span><span class="sxs-lookup"><span data-stu-id="78758-118">On the RDS server, enable shared computer activation by editing the registry by following these steps:</span></span>

1. <span data-ttu-id="78758-119">Haga clic con el botón derecho en el botón Windows en la esquina inferior izquierda de la pantalla y seleccione Ejecutar.</span><span class="sxs-lookup"><span data-stu-id="78758-119">Right-click the Windows button in the lower left-hand corner of your screen and select Run.</span></span> <span data-ttu-id="78758-120">En el cuadro Abrir, escriba **regedit**y, a continuación, seleccione Aceptar.</span><span class="sxs-lookup"><span data-stu-id="78758-120">In the Open box, type **regedit**, and then select OK.</span></span>

2. <span data-ttu-id="78758-121">Seleccione Sí cuando se le pregunte si desea permitir que el editor del registro realice cambios en el dispositivo.</span><span class="sxs-lookup"><span data-stu-id="78758-121">Select Yes when prompted to allow Registry Editor to make changes to your device.</span></span>

3. <span data-ttu-id="78758-122">En el editor del registro, agregue un valor de cadena de **SharedComputerLicensing** con un valor de 1 en HKEY_LOCAL_MACHINE \Software\Microsoft \Office\ClickToRun\Configuration.</span><span class="sxs-lookup"><span data-stu-id="78758-122">In the Registry Editor, add a string value of **SharedComputerLicensing** with a setting of 1 under HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span></span>

7. <span data-ttu-id="78758-123">En el servidor RDS, ***inicie sesión como usuario final*** y [Compruebe que la activación en equipos compartidos está habilitada para las aplicaciones de Microsoft 365 para empresas](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation#verify-that-activation-for-microsoft-365-apps-succeeded).</span><span class="sxs-lookup"><span data-stu-id="78758-123">On the RDS server, ***sign in as an end user*** and [verify that shared computer activation is enabled for Microsoft 365 Apps for enterprise](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation#verify-that-activation-for-microsoft-365-apps-succeeded).</span></span>

<span data-ttu-id="78758-124">Para obtener más información sobre requisitos previos, instrucciones de instalación e instrucciones sobre instalaciones personalizadas mediante la herramienta de implementación de Office, consulte [deploy Microsoft 365 apps for Enterprise by Using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-microsoft-365-apps-remote-desktop-services).</span><span class="sxs-lookup"><span data-stu-id="78758-124">For more details on prerequisites, setup instructions and guidance on customized installations by using the Office Deployment Tool, please see [Deploy Microsoft 365 Apps for enterprise by using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-microsoft-365-apps-remote-desktop-services).</span></span>
  
<span data-ttu-id="78758-125">Para corregir errores relacionados con la activación en equipos compartidos, vea [solucionar problemas de activación en equipos compartidos para aplicaciones de Microsoft 365 para empresas](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation).</span><span class="sxs-lookup"><span data-stu-id="78758-125">To fix errors related to shared computer activation, please see [Troubleshoot issues with shared computer activation for Microsoft 365 Apps for enterprise](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation).</span></span>
  