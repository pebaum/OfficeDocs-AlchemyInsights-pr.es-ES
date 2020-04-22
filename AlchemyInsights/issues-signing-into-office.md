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
- "2574"
ms.openlocfilehash: 695d449a876c22ff441da2367ef67aaea470eb66
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43763018"
---
# <a name="issues-signing-in-to-office-apps"></a>Problemas al iniciar sesión en las aplicaciones de Office

Para solucionar los problemas de inicio de sesión con las aplicaciones de Office, pruebe lo siguiente:

- Quite todas las cuentas de trabajo, excepto la cuenta afectada, mediante la configuración de Windows > **acceso a la oficina o a la escuela**.
- [Borre las credenciales de Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) con el administrador de credenciales de Windows.<br/>
    **Nota:** Las rutas del registro para Office 2016 han cambiado a 16,0. (Por ejemplo: \Software\Microsoft\Office\16.0\Common\Identity\)
- Abra una aplicación de Office y elija la opción**Cerrar sesión**de la**cuenta** > de **archivo** > . A continuación, inicie sesión con una cuenta de usuario con una licencia válida. Para obtener información más detallada, consulte [Cuentas en Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).
- Para Mac, consulte [No se puede iniciar sesión en una aplicación de Office 2016 para Mac](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).
- Si se producen errores al conectar con Microsoft 365 mediante Office 2013, habilite la autenticación moderna para el cliente de Office.

Para obtener más información, vea:
- [No puede iniciar sesión en Microsoft 365, Azure o Intune](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-365-azure-intune)
- [Problemas de conexión en el inicio de sesión después de actualizar a Office 2016 compilación 16.0.7967 en Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016)
- ["Lo sentimos, otra cuenta de su organización ya ha iniciado sesión en este equipo" en Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in)
- [Solucionar problemas de inicio de sesión con la autenticación moderna de Office al usar ADFS](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-issue-with-modern-auth)