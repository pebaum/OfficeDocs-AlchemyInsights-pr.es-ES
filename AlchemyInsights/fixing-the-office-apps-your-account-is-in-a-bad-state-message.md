---
title: Corrección de las aplicaciones de Office la cuenta está en un mensaje de estado incorrecto
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2558"
- "9000571"
ms.openlocfilehash: b28865ff1da434a254c9051183074be35cdd0252
ms.sourcegitcommit: 9b2b162ad651e2c3d9d0c746f67a78334592f076
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/17/2020
ms.locfileid: "43547979"
---
# <a name="fixing-the-office-apps-your-account-is-in-a-bad-state-error"></a>Error al reparar las aplicaciones de Office "la cuenta está en mal estado"

Para solucionar este error, pruebe las siguientes opciones en el equipo afectado:

- Abra una aplicación de Office, **File** > seleccione Cerrar sesión en la**cuenta** > **de archivo de todas las cuentas**. Inicie sesión de nuevo con una cuenta de usuario con una licencia válida. Para obtener información más detallada, consulte [Cuentas en Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).
- [Borre las credenciales de Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) con el administrador de credenciales de Windows.<br>
  **Nota:** Las rutas del registro para Office 2016 han cambiado a 16,0. Por ejemplo, \Software\Microsoft\Office\16.0\Common\Identity\
- Si el error se produce al conectar con Office 365 mediante Office 2013, [habilite la autenticación moderna](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication) para el cliente de Office.

Para obtener más información, vea [cómo solucionar problemas de aplicaciones que no son de explorador que no pueden iniciar sesión en Office 365, Azure o Intune](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1).

