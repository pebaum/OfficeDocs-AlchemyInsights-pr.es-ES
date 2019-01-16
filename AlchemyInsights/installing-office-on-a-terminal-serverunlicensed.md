---
title: 'Instalar office en un servidor de Terminal: sin licencia'
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: 73d5128b55cae7712c48be9e2d05e558c3ba2e5c
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28314057"
---
# <a name="installing-office-on-a-terminal-server"></a><span data-ttu-id="8b808-102">Instalar Office en un servidor de Terminal Server</span><span class="sxs-lookup"><span data-stu-id="8b808-102">Installing Office on a Terminal Server</span></span>

<span data-ttu-id="8b808-103">Para la implementación de Office 365 ProPlus en un servidor de Windows mediante los servicios de escritorio remoto (RDS), anteriormente denominado Terminal Services:</span><span class="sxs-lookup"><span data-stu-id="8b808-103">For deploying Office 365 ProPlus on a Windows Server using Remote Desktop Services (RDS), formerly named Terminal Services:</span></span>
  
- <span data-ttu-id="8b808-p101">Debe tener un plan de Office 365 que incluye Office 365 ProPlus, como Office 365 Enterprise E3 o E5 de la empresa. Los planes de negocio de Office 365 y Office 365 Business Premium no incluir Office 365 ProPlus.</span><span class="sxs-lookup"><span data-stu-id="8b808-p101">You must have an Office 365 plan that includes Office 365 ProPlus, such as Office 365 Enterprise E3 or Enterprise E5. The Office 365 Business and Office 365 Business Premium plans do not include Office 365 ProPlus.</span></span>
    
- <span data-ttu-id="8b808-106">Debe habilitar la [activación de equipo compartido](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span><span class="sxs-lookup"><span data-stu-id="8b808-106">You need to enable [shared computer activation](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span></span>
    
<span data-ttu-id="8b808-107">Si desea instalar Office 365 ProPlus en RDS desde el portal de Office 365, \*\* *que usa la configuración de la instalación predeterminada* \*\*, siga estos pasos:</span><span class="sxs-lookup"><span data-stu-id="8b808-107">If you want to install Office 365 ProPlus on RDS from the Office 365 portal, \*\* *which uses default installation settings* \*\*, follow these steps:</span></span> 
  
1. <span data-ttu-id="8b808-p102">Compruebe qué plan de Office 365 tiene. [Obtenga información sobre cómo](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)</span><span class="sxs-lookup"><span data-stu-id="8b808-p102">Check what Office 365 plan you have. [Learn how](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)</span></span>
    
2. <span data-ttu-id="8b808-p103">Si la intención es necesario, cambie a un diferentes de Office 365. [Obtenga información sobre cómo](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)</span><span class="sxs-lookup"><span data-stu-id="8b808-p103">If necessary, switch to a different Office 365 plan. [Learn how](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)</span></span>
    
3. <span data-ttu-id="8b808-p104">Si Office ya está instalado en el servidor RDS con otros planes de Office 365, desinstálelo. Por ejemplo, yendo al Panel de Control \> desinstalar un programa. Desinstalar mediante [el Asistente de recuperación y de soporte técnico de Microsoft](https://aka.ms/SARA-OfficeUninstall-Alchemy) si se está ejecutando en problemas.</span><span class="sxs-lookup"><span data-stu-id="8b808-p104">If Office is already installed on the RDS server using any other Office 365 plans, uninstall it. For example, by going to Control Panel \> Uninstall a program. Uninstall using [Microsoft Support and Recovery Assistant](https://aka.ms/SARA-OfficeUninstall-Alchemy) if you're running into issues.</span></span> 
    
4. <span data-ttu-id="8b808-115">En el servidor RDS, inicie sesión el portal de Office 365 con su cuenta de administrador e [instale Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span><span class="sxs-lookup"><span data-stu-id="8b808-115">On the RDS server, sign in to the Office 365 portal with your administrator account and [install Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span></span>
    
5. <span data-ttu-id="8b808-116">Después de instalar Office, \*\* *no abra ni iniciar sesión en* \*\* a las aplicaciones de Office.</span><span class="sxs-lookup"><span data-stu-id="8b808-116">After Office is installed, \*\* *don't open or sign in* \*\* to any Office applications.</span></span> 
    
6. <span data-ttu-id="8b808-117">En el servidor RDS, habilitar la activación de equipo compartido mediante la edición del registro, siga estos pasos:</span><span class="sxs-lookup"><span data-stu-id="8b808-117">On the RDS server, enable shared computer activation by editing the registry by following these steps:</span></span>
    
1. <span data-ttu-id="8b808-p105">Haga clic en el botón de Windows en la esquina inferior izquierda de la pantalla y seleccione Ejecutar. En el cuadro Abrir, escriba **regedit**y, a continuación, seleccione Aceptar.</span><span class="sxs-lookup"><span data-stu-id="8b808-p105">Right-click the Windows button in the lower left-hand corner of your screen and select Run. In the Open box, type **regedit**, and then select OK.</span></span> 
    
2. <span data-ttu-id="8b808-120">Seleccione Sí cuando se le solicite para permitir que al Editor del registro para realizar cambios en su dispositivo.</span><span class="sxs-lookup"><span data-stu-id="8b808-120">Select Yes when prompted to allow Registry Editor to make changes to your device.</span></span>
    
3. <span data-ttu-id="8b808-121">En el Editor del registro, agregue un valor de cadena de **SharedComputerLicensing** con una configuración de 1 bajo HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span><span class="sxs-lookup"><span data-stu-id="8b808-121">In the Registry Editor, add a string value of **SharedComputerLicensing** with a setting of 1 under HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span></span> 
    
7. <span data-ttu-id="8b808-122">En el servidor RDS, \*\* *iniciar sesión como un usuario final* \*\* y [Compruebe que la activación del equipo compartido está habilitada para Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span><span class="sxs-lookup"><span data-stu-id="8b808-122">On the RDS server, \*\* *sign in as an end user* \*\* and [verify that shared computer activation is enabled for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span></span>
    
<span data-ttu-id="8b808-123">Para obtener más detalles sobre los requisitos previos, instrucciones de instalación y orientación sobre las instalaciones personalizadas mediante el uso de la herramienta de implementación de Office, vea [Implementar Office 365 ProPlus mediante el uso de servicios de escritorio remoto](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span><span class="sxs-lookup"><span data-stu-id="8b808-123">For more details on prerequisites, setup instructions and guidance on customized installations by using the Office Deployment Tool, please see [Deploy Office 365 ProPlus by using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span></span>
  
<span data-ttu-id="8b808-124">Para corregir errores relacionados con la activación del equipo compartido, consulte [solucionar problemas con la activación de equipo compartido para Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span><span class="sxs-lookup"><span data-stu-id="8b808-124">To fix errors related to shared computer activation, please see [Troubleshoot issues with shared computer activation for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span></span>
  

