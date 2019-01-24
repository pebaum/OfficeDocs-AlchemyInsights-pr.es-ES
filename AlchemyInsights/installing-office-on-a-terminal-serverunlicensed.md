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
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29491197"
---
# <a name="installing-office-on-a-terminal-server"></a>Instalar Office en un servidor de Terminal Server

Para la implementación de Office 365 ProPlus en un servidor de Windows mediante los servicios de escritorio remoto (RDS), anteriormente denominado Terminal Services:
  
- Debe tener un plan de Office 365 que incluye Office 365 ProPlus, como Office 365 Enterprise E3 o E5 de la empresa. Los planes de negocio de Office 365 y Office 365 Business Premium no incluir Office 365 ProPlus.
    
- Debe habilitar la [activación de equipo compartido](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).
    
Si desea instalar Office 365 ProPlus en RDS desde el portal de Office 365, ** *que usa la configuración de la instalación predeterminada* **, siga estos pasos: 
  
1. Compruebe qué plan de Office 365 tiene. [Obtenga información sobre cómo](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)
    
2. Si la intención es necesario, cambie a un diferentes de Office 365. [Obtenga información sobre cómo](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)
    
3. Si Office ya está instalado en el servidor RDS con otros planes de Office 365, desinstálelo. Por ejemplo, yendo al Panel de Control \> desinstalar un programa. Desinstalar mediante [el Asistente de recuperación y de soporte técnico de Microsoft](https://aka.ms/SARA-OfficeUninstall-Alchemy) si se está ejecutando en problemas. 
    
4. En el servidor RDS, inicie sesión el portal de Office 365 con su cuenta de administrador e [instale Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).
    
5. Después de instalar Office, ** *no abra ni iniciar sesión en* ** a las aplicaciones de Office. 
    
6. En el servidor RDS, habilitar la activación de equipo compartido mediante la edición del registro, siga estos pasos:
    
1. Haga clic en el botón de Windows en la esquina inferior izquierda de la pantalla y seleccione Ejecutar. En el cuadro Abrir, escriba **regedit**y, a continuación, seleccione Aceptar. 
    
2. Seleccione Sí cuando se le solicite para permitir que al Editor del registro para realizar cambios en su dispositivo.
    
3. En el Editor del registro, agregue un valor de cadena de **SharedComputerLicensing** con una configuración de 1 bajo HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration. 
    
7. En el servidor RDS, ** *iniciar sesión como un usuario final* ** y [Compruebe que la activación del equipo compartido está habilitada para Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).
    
Para obtener más detalles sobre los requisitos previos, instrucciones de instalación y orientación sobre las instalaciones personalizadas mediante el uso de la herramienta de implementación de Office, vea [Implementar Office 365 ProPlus mediante el uso de servicios de escritorio remoto](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).
  
Para corregir errores relacionados con la activación del equipo compartido, consulte [solucionar problemas con la activación de equipo compartido para Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).
  

