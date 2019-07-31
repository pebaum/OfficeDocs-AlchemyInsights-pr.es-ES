---
title: Problemas al iniciar sesión en las aplicaciones de Office
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000571"
- "2556"
ms.openlocfilehash: 08bb0a94066f071f2ba0e9c54378f0d479191496
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938351"
---
# <a name="blank-sign-in-screen-in-office-apps"></a>Pantalla de inicio de sesión en blanco en las aplicaciones de Office

Para solucionar este problema, pruebe lo siguiente:
- Instale las actualizaciones más recientes para [Windows](https://support.microsoft.com/help/4027667/windows-10-update) y [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).
- Restablecer opciones de Internet Explorer: vaya a **herramientas** > **Opciones** > de Internet**avanzada** > **restablecer configuración de Internet Explorer** (tenga en cuenta que perderá la configuración personalizada) y, a continuación, intente iniciar sesión de nuevo en Office.
- Deshabilite la protección de aplicaciones de Windows Defender (WDAG) o cualquier programa de firewall o antivirus similar:
    1. En el panel de control, vaya a **programas**y, a continuación, elija **activar o desactivar las características de Windows**.
    2. Si la protección de aplicaciones de Windows Defender está habilitada, prueba a deshabilitarla.<br/>
    **Nota:** Es posible que deba reiniciar el equipo.
- Asegúrese de que el [complemento WAM](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-1) Microsoft. AAD. BrokerPlugin AAD no está bloqueado por ninguna aplicación o programa de firewall o antivirus.
- [Borre las credenciales de Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) con el administrador de credenciales de Windows.<br/>
    **Nota:** Las rutas del registro para Office 2016 han cambiado a 16,0. (Por ejemplo: \Software\Microsoft\Office\16.0\Common\Identity\)

Para obtener más información, vea [problemas de conexión en el inicio de sesión después de actualizar a Office 2016 Build 16.0.7967 en Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).