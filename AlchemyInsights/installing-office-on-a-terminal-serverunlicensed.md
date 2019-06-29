---
title: Instalación de Office en Terminal Server sin licencia
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "917"
- "2000020"
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: 6fc4bd5f6971ca833084a6a8ad6c25b3fdafb8dc
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/28/2019
ms.locfileid: "35381746"
---
# <a name="installing-office-on-a-terminal-server"></a><span data-ttu-id="496ac-102">Instalación de Office en un servidor Terminal Server</span><span class="sxs-lookup"><span data-stu-id="496ac-102">Installing Office on a Terminal Server</span></span>

<span data-ttu-id="496ac-103">Para implementar Office 365 ProPlus en un servidor Windows con servicios de escritorio remoto (RDS), anteriormente denominado Terminal Services:</span><span class="sxs-lookup"><span data-stu-id="496ac-103">For deploying Office 365 ProPlus on a Windows Server using Remote Desktop Services (RDS), formerly named Terminal Services:</span></span>
  
- <span data-ttu-id="496ac-104">Debe tener un plan de Office 365 que incluya Office 365 ProPlus, como Office 365 Enterprise E3 o Enterprise E5.</span><span class="sxs-lookup"><span data-stu-id="496ac-104">You must have an Office 365 plan that includes Office 365 ProPlus, such as Office 365 Enterprise E3 or Enterprise E5.</span></span> <span data-ttu-id="496ac-105">Los planes de Office 365 Business and Office 365 Business Premium no incluyen Office 365 ProPlus.</span><span class="sxs-lookup"><span data-stu-id="496ac-105">The Office 365 Business and Office 365 Business Premium plans do not include Office 365 ProPlus.</span></span>

- <span data-ttu-id="496ac-106">Debe habilitar la [activación en equipos](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus)compartidos.</span><span class="sxs-lookup"><span data-stu-id="496ac-106">You need to enable [shared computer activation](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span></span>

<span data-ttu-id="496ac-107">Si desea instalar Office 365 ProPlus en RDS desde el portal de Office 365, \* \* *que usa la configuración de instalación predeterminada* \* \*, siga estos pasos:</span><span class="sxs-lookup"><span data-stu-id="496ac-107">If you want to install Office 365 ProPlus on RDS from the Office 365 portal, \*\* *which uses default installation settings* \*\*, follow these steps:</span></span>
  
1. <span data-ttu-id="496ac-108">Compruebe qué plan de Office 365 tiene.</span><span class="sxs-lookup"><span data-stu-id="496ac-108">Check what Office 365 plan you have.</span></span> [<span data-ttu-id="496ac-109">Obtenga información sobre cómo</span><span class="sxs-lookup"><span data-stu-id="496ac-109">Learn how</span></span>](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)

2. <span data-ttu-id="496ac-110">Si es necesario, cambie a un plan de Office 365 diferente.</span><span class="sxs-lookup"><span data-stu-id="496ac-110">If necessary, switch to a different Office 365 plan.</span></span> [<span data-ttu-id="496ac-111">Obtenga información sobre cómo</span><span class="sxs-lookup"><span data-stu-id="496ac-111">Learn how</span></span>](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)

3. <span data-ttu-id="496ac-112">Si Office ya está instalado en el servidor RDS con otros planes de Office 365, desinstálelo.</span><span class="sxs-lookup"><span data-stu-id="496ac-112">If Office is already installed on the RDS server using any other Office 365 plans, uninstall it.</span></span> <span data-ttu-id="496ac-113">Por ejemplo, vaya a control panel \> desinstalar un programa.</span><span class="sxs-lookup"><span data-stu-id="496ac-113">For example, by going to Control Panel \> Uninstall a program.</span></span> <span data-ttu-id="496ac-114">Desinstale con el [Asistente para soporte y recuperación de Microsoft](https://aka.ms/SARA-OfficeUninstall-Alchemy) si está teniendo problemas.</span><span class="sxs-lookup"><span data-stu-id="496ac-114">Uninstall using [Microsoft Support and Recovery Assistant](https://aka.ms/SARA-OfficeUninstall-Alchemy) if you're running into issues.</span></span>

4. <span data-ttu-id="496ac-115">En el servidor RDS, inicie sesión en el portal de Office 365 con su cuenta de administrador e [instale Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span><span class="sxs-lookup"><span data-stu-id="496ac-115">On the RDS server, sign in to the Office 365 portal with your administrator account and [install Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span></span>

5. <span data-ttu-id="496ac-116">Una vez instalado Office, \* \* *no abra ni inicie sesión* \* \* en ninguna de las aplicaciones de Office.</span><span class="sxs-lookup"><span data-stu-id="496ac-116">After Office is installed, \*\* *don't open or sign in* \*\* to any Office applications.</span></span>

6. <span data-ttu-id="496ac-117">En el servidor RDS, habilite la activación en equipos compartidos editando el registro siguiendo estos pasos:</span><span class="sxs-lookup"><span data-stu-id="496ac-117">On the RDS server, enable shared computer activation by editing the registry by following these steps:</span></span>

1. <span data-ttu-id="496ac-118">Haga clic con el botón derecho en el botón Windows en la esquina inferior izquierda de la pantalla y seleccione Ejecutar.</span><span class="sxs-lookup"><span data-stu-id="496ac-118">Right-click the Windows button in the lower left-hand corner of your screen and select Run.</span></span> <span data-ttu-id="496ac-119">En el cuadro Abrir, escriba **regedit**y, a continuación, seleccione Aceptar.</span><span class="sxs-lookup"><span data-stu-id="496ac-119">In the Open box, type **regedit**, and then select OK.</span></span>

2. <span data-ttu-id="496ac-120">Seleccione Sí cuando se le pregunte si desea permitir que el editor del registro realice cambios en el dispositivo.</span><span class="sxs-lookup"><span data-stu-id="496ac-120">Select Yes when prompted to allow Registry Editor to make changes to your device.</span></span>

3. <span data-ttu-id="496ac-121">En el editor del registro, agregue un valor de cadena de **SharedComputerLicensing** con un valor de 1 en HKEY_LOCAL_MACHINE\Software\Microsoft \Office\ClickToRun\Configuration.</span><span class="sxs-lookup"><span data-stu-id="496ac-121">In the Registry Editor, add a string value of **SharedComputerLicensing** with a setting of 1 under HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span></span>

7. <span data-ttu-id="496ac-122">En el servidor RDS, \* \* *inicie sesión como usuario final* \* \* y [Compruebe que la activación en equipos compartidos está habilitada para Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span><span class="sxs-lookup"><span data-stu-id="496ac-122">On the RDS server, \*\* *sign in as an end user* \*\* and [verify that shared computer activation is enabled for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span></span>

<span data-ttu-id="496ac-123">Para obtener más información sobre requisitos previos, instrucciones de instalación e instrucciones sobre instalaciones personalizadas mediante la herramienta de implementación de Office, consulte [deploy office 365 ProPlus by Using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span><span class="sxs-lookup"><span data-stu-id="496ac-123">For more details on prerequisites, setup instructions and guidance on customized installations by using the Office Deployment Tool, please see [Deploy Office 365 ProPlus by using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span></span>
  
<span data-ttu-id="496ac-124">Para corregir los errores relacionados con la activación en equipos compartidos, consulte [solucionar problemas con la activación en equipos compartidos para Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span><span class="sxs-lookup"><span data-stu-id="496ac-124">To fix errors related to shared computer activation, please see [Troubleshoot issues with shared computer activation for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span></span>
  