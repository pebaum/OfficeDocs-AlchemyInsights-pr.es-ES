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
# <a name="installing-office-on-a-terminal-server"></a>Instalación de Office en un servidor Terminal Server

Para implementar Microsoft 365 apps for Enterprise en un servidor Windows con servicios de escritorio remoto (RDS), anteriormente denominado Terminal Services:
  
- Debe tener una suscripción a Microsoft 365 que incluya aplicaciones de Microsoft 365 para la empresa, como Office 365 Enterprise E3 o Enterprise E5. Los planes de Microsoft 365 apps for Business y Microsoft 365 para empresas Premium no incluyen las aplicaciones de Microsoft 365 para empresas.

- Debe habilitar la [activación en equipos compartidos](https://docs.microsoft.com/DeployOffice/overview-shared-computer-activation).

Si desea instalar las aplicaciones de Microsoft 365 para empresas en RDS desde el centro de administración de Microsoft 365, ***que usa la configuración de instalación predeterminada***, siga estos pasos.

> [!TIP]
> También puede descargar y ejecutar el [Asistente para soporte y recuperación de Microsoft](https://aka.ms/SaRA_OfficeSCA_M365Portal) para instalar las aplicaciones de Microsoft 365 para empresas en el modo de activación en equipos compartidos.
  
1. Compruebe qué suscripción de Microsoft 365 tiene. [Obtenga información sobre cómo](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)

2. Si es necesario, cambie a una suscripción de Microsoft 365 diferente. [Obtenga información sobre cómo](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)

3. Si Office ya está instalado en el servidor RDS con otras suscripciones de Microsoft 365, desinstálelo. Por ejemplo, vaya a control panel \> desinstalar un programa. Desinstale con el [Asistente para soporte y recuperación de Microsoft](https://aka.ms/SARA-OfficeUninstall-Alchemy) si está teniendo problemas.

4. En el servidor de RDS, inicie sesión en el centro de administración de Microsoft 365 con su cuenta de administrador e [Instale las aplicaciones de microsoft 365 para la empresa](https://portal.office.com/OLS/MySoftware.aspx).

5. Una vez instalado Office, ***no abra ni inicie sesión*** en ninguna de las aplicaciones de Office.

6. En el servidor RDS, habilite la activación en equipos compartidos editando el registro siguiendo estos pasos:

1. Haga clic con el botón derecho en el botón Windows en la esquina inferior izquierda de la pantalla y seleccione Ejecutar. En el cuadro Abrir, escriba **regedit**y, a continuación, seleccione Aceptar.

2. Seleccione Sí cuando se le pregunte si desea permitir que el editor del registro realice cambios en el dispositivo.

3. En el editor del registro, agregue un valor de cadena de **SharedComputerLicensing** con un valor de 1 en HKEY_LOCAL_MACHINE \Software\Microsoft \Office\ClickToRun\Configuration.

7. En el servidor RDS, ***inicie sesión como usuario final*** y [Compruebe que la activación en equipos compartidos está habilitada para las aplicaciones de Microsoft 365 para empresas](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation#verify-that-activation-for-microsoft-365-apps-succeeded).

Para obtener más información sobre requisitos previos, instrucciones de instalación e instrucciones sobre instalaciones personalizadas mediante la herramienta de implementación de Office, consulte [deploy Microsoft 365 apps for Enterprise by Using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-microsoft-365-apps-remote-desktop-services).
  
Para corregir errores relacionados con la activación en equipos compartidos, vea [solucionar problemas de activación en equipos compartidos para aplicaciones de Microsoft 365 para empresas](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation).
  