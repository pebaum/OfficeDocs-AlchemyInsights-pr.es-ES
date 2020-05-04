---
title: Implementación de Microsoft 365 apps for Enterprise para uso compartido en RDS, Terminal Server o VDI
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001419"
- "3411"
ms.openlocfilehash: 51512b29f8d37ce6c39ece5bb704cb01e88e463d
ms.sourcegitcommit: 7e06d9ec1dd462cbd882f088c997d012a032f04d
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/04/2020
ms.locfileid: "44010271"
---
# <a name="deploying-microsoft-365-apps-for-enterprise-for-shared-use-on-rds-terminal-server-or-vdi"></a>Implementación de Microsoft 365 apps for Enterprise para uso compartido en RDS, Terminal Server o VDI

Para implementar las aplicaciones de Microsoft 365 para empresas con servicios de escritorio remoto (RDS), anteriormente denominados Terminal Services:
- Debe disponer de un plan para el plan de 365 o un plan de Office 365 que incluya las aplicaciones de Microsoft 365 para la empresa, como Office 365 Enterprise E3 o Enterprise E5.
   > [!NOTE] 
   > Los planes estándar de Microsoft 365 apps for Business y Microsoft 365 Business Premium no incluyen Microsoft 365 apps for Enterprise.
- Debe habilitar la [activación en equipos compartidos](https://docs.microsoft.com/DeployOffice/overview-shared-computer-activation).

> [!NOTE]
> También puede descargar y ejecutar el [Asistente para soporte y recuperación de Microsoft](https://aka.ms/SaRA_OfficeSCA_M365Portal) para instalar las aplicaciones de Microsoft 365 para empresas en el modo de activación en equipos compartidos.

Para obtener más información sobre requisitos previos, instrucciones de instalación e instrucciones sobre instalaciones personalizadas mediante la herramienta de implementación de Office, consulte [deploy Microsoft 365 apps for Enterprise by Using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-microsoft-365-apps-remote-desktop-services).

Para corregir errores relacionados con la activación en equipos compartidos:
- Vea [solucionar problemas relacionados con la activación en equipos compartidos para aplicaciones de Microsoft 365 para empresas](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation).
- Vea [Restablecer el estado de activación de las aplicaciones de Microsoft 365 para empresas](https://go.microsoft.com/fwlink/?linkid=2109218).

Si desea instalar las aplicaciones de Microsoft 365 para empresas en RDS desde el centro de administración de Microsoft 365, ***que usa la configuración de instalación predeterminada***, siga estos pasos:

1.    Compruebe qué suscripción tiene. [Obtenga más información](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have).
2.    Si es necesario, cambie a una suscripción diferente. [Obtenga más información](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan).
3.    Si Office ya está instalado en el servidor RDS con otras suscripciones de Microsoft, desinstálelo. Por ejemplo, vaya a **control panel** > **desinstalar un programa**. Desinstale con el [Asistente para soporte y recuperación de Microsoft](https://aka.ms/SARA-OfficeUninstall-Alchemy) si está teniendo problemas.
4.    En el servidor de RDS, inicie sesión en el centro de administración de Microsoft 365 con su cuenta de administrador e [Instale las aplicaciones de microsoft 365 para la empresa](https://portal.office.com/OLS/MySoftware.aspx).
5.    Una vez instalado Office, ***no abra ni inicie sesión*** en ninguna de las aplicaciones de Office.
6.    En el servidor RDS, habilite la activación en equipos compartidos editando el registro siguiendo estos pasos:
   1. Haga clic con el botón derecho en el botón Windows en la esquina inferior izquierda de la pantalla y seleccione **Ejecutar**. En el cuadro Abrir, escriba **regedit**y, a continuación, seleccione **Aceptar**.
   2. Seleccione **sí** cuando se le pregunte si desea permitir que el editor del registro realice cambios en el dispositivo.
   3. En el editor del registro, agregue un valor de cadena de **SharedComputerLicensing** con un valor de 1 en HKEY_LOCAL_MACHINE \Software\Microsoft \Office\ClickToRun\Configuration.
   4. En el servidor RDS, ***inicie sesión como usuario final*** y [Compruebe que la activación en equipos compartidos está habilitada para las aplicaciones de Microsoft 365 para empresas](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation#verify-that-activation-for-microsoft-365-apps-succeeded).

