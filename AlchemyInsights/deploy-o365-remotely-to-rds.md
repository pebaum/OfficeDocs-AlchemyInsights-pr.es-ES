---
title: Implementación de Office 365 ProPlus para uso compartido en RDS, Terminal Server o VDI
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 12/9/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001419"
- "3411"
ms.openlocfilehash: 2312cca9ebf5dad1322bc98335cef6a6bc81f03e
ms.sourcegitcommit: cbbd46fa9a32873c5446d9fd5a532cea0300b795
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/10/2019
ms.locfileid: "39959476"
---
# <a name="deploying-office-365-proplus-for-shared-use-on-rds-terminal-server-or-vdi"></a>Implementación de Office 365 ProPlus para uso compartido en RDS, Terminal Server o VDI

Para implementar Office 365 ProPlus con servicios de escritorio remoto (RDS), anteriormente denominado Terminal Services:
- Debe disponer de un plan de 365 para el plan de negocio de Microsoft y Office 365 que incluya Office 365 ProPlus, como Office 365 Enterprise E3 o Enterprise E5.
   > [!NOTE] 
   > Los planes de Office 365 Business and Office 365 Business Premium no incluyen Office 365 ProPlus.
- Debe habilitar la [activación en equipos compartidos](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).

> [!NOTE]
> También puede descargar y ejecutar el [Asistente para soporte y recuperación de Microsoft](https://aka.ms/SaRA_OfficeSCA_M365Portal) para instalar Office 365 ProPlus en el modo de activación en equipos compartidos.

Para obtener más información sobre requisitos previos, instrucciones de instalación e instrucciones sobre instalaciones personalizadas mediante la herramienta de implementación de Office, consulte [deploy office 365 ProPlus by Using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).

Para corregir errores relacionados con la activación en equipos compartidos:
- Vea [solucionar problemas relacionados con la activación en equipos compartidos para Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).
- Consulte [restablecer el estado de activación de Office 365 ProPlus](https://go.microsoft.com/fwlink/?linkid=2109218).

Si desea instalar Office 365 ProPlus en RDS desde el centro de administración de Microsoft 365, ***que usa la configuración de instalación predeterminada***, siga estos pasos:

1.  Compruebe qué plan de Office 365 tiene. [Obtenga más información](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have).
2.  Si es necesario, cambie a un plan de Office 365 diferente. [Obtenga más información](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan).
3.  Si Office ya está instalado en el servidor RDS con otros planes de Office 365, desinstálelo. Por ejemplo, vaya a **control panel** > **desinstalar un programa**. Desinstale con el [Asistente para soporte y recuperación de Microsoft](https://aka.ms/SARA-OfficeUninstall-Alchemy) si está teniendo problemas.
4.  En el servidor de RDS, inicie sesión en el centro de administración de Microsoft 365 con su cuenta de administrador e [instale Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).
5.  Una vez instalado Office, ***no abra ni inicie sesión*** en ninguna de las aplicaciones de Office.
6.  En el servidor RDS, habilite la activación en equipos compartidos editando el registro siguiendo estos pasos:
   1. Haga clic con el botón derecho en el botón Windows en la esquina inferior izquierda de la pantalla y seleccione **Ejecutar**. En el cuadro Abrir, escriba **regedit**y, a continuación, seleccione **Aceptar**.
   2. Seleccione **sí** cuando se le pregunte si desea permitir que el editor del registro realice cambios en el dispositivo.
   3. En el editor del registro, agregue un valor de cadena de **SharedComputerLicensing** con un valor de 1 en HKEY_LOCAL_MACHINE \Software\Microsoft \Office\ClickToRun\Configuration.
   4. En el servidor RDS, ***inicie sesión como usuario final*** y [Compruebe que la activación en equipos compartidos está habilitada para Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).

