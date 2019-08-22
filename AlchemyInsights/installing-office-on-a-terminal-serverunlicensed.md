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
ms.openlocfilehash: edac051840594f13b22ccd83f5cd6e3da5f84cbc
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36498432"
---
# <a name="installing-office-on-a-terminal-server"></a>Instalación de Office en un servidor Terminal Server

Para implementar Office 365 ProPlus en un servidor Windows con servicios de escritorio remoto (RDS), anteriormente denominado Terminal Services:
  
- Debe tener un plan de Office 365 que incluya Office 365 ProPlus, como Office 365 Enterprise E3 o Enterprise E5. Los planes de Office 365 Business and Office 365 Business Premium no incluyen Office 365 ProPlus.

- Debe habilitar la [activación en equipos](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus)compartidos.

Si desea instalar Office 365 ProPlus en RDS desde el portal de Office 365, ***que usa la configuración de instalación predeterminada***, siga estos pasos:
  
1. Compruebe qué plan de Office 365 tiene. [Obtenga información sobre cómo](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)

2. Si es necesario, cambie a un plan de Office 365 diferente. [Obtenga información sobre cómo](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)

3. Si Office ya está instalado en el servidor RDS con otros planes de Office 365, desinstálelo. Por ejemplo, vaya a control panel \> desinstalar un programa. Desinstale con el [Asistente para soporte y recuperación de Microsoft](https://aka.ms/SARA-OfficeUninstall-Alchemy) si está teniendo problemas.

4. En el servidor RDS, inicie sesión en el portal de Office 365 con su cuenta de administrador e [instale Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).

5. Una vez instalado Office, ***no abra ni inicie sesión*** en ninguna de las aplicaciones de Office.

6. En el servidor RDS, habilite la activación en equipos compartidos editando el registro siguiendo estos pasos:

1. Haga clic con el botón derecho en el botón Windows en la esquina inferior izquierda de la pantalla y seleccione Ejecutar. En el cuadro Abrir, escriba **regedit**y, a continuación, seleccione Aceptar.

2. Seleccione Sí cuando se le pregunte si desea permitir que el editor del registro realice cambios en el dispositivo.

3. En el editor del registro, agregue un valor de cadena de **SharedComputerLicensing** con un valor de 1 en HKEY_LOCAL_MACHINE\Software\Microsoft \Office\ClickToRun\Configuration.

7. En el servidor RDS, ***inicie sesión como usuario final*** y [Compruebe que la activación en equipos compartidos está habilitada para Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).

Para obtener más información sobre requisitos previos, instrucciones de instalación e instrucciones sobre instalaciones personalizadas mediante la herramienta de implementación de Office, consulte [deploy office 365 ProPlus by Using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).
  
Para corregir los errores relacionados con la activación en equipos compartidos, consulte [solucionar problemas con la activación en equipos compartidos para Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).
  