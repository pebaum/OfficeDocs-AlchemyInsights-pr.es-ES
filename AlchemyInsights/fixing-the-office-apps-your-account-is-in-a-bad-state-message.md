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
ms.openlocfilehash: e591c56dd207a5bcb3979be3f66052121100b162
ms.sourcegitcommit: 2572c4e5a981d5f3f556835061c568cfd08b78da
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/27/2019
ms.locfileid: "41969825"
---
# <a name="fixing-the-office-apps-your-account-is-in-a-bad-state-error"></a>Error al reparar las aplicaciones de Office "la cuenta está en mal estado"

Para solucionar este error, pruebe las siguientes opciones en el equipo afectado:

- Abra una aplicación de Office, **** > seleccione Cerrar sesión en la**cuenta** > **de archivo de todas las cuentas**. Inicie sesión de nuevo con una cuenta de usuario con una licencia válida. Para obtener información detallada, consulte [accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).
- [Borre las credenciales de Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) con el administrador de credenciales de Windows.<br>
  **Nota:** Las rutas del registro para Office 2016 han cambiado a 16,0. Por ejemplo, \Software\Microsoft\Office\16.0\Common\Identity\
- En el equipo afectado, establezca EnableADAL = 0 mediante los pasos siguientes:  
     1. Haga clic con el botón derecho en el botón Windows y seleccione **Ejecutar**. En el cuadro **abrir** , escriba **regedit**y, a continuación, seleccione **Aceptar**.
     2. Seleccione **sí** cuando se le pregunte si desea permitir que el editor del registro realice cambios en el dispositivo.
    3. En el editor del registro, agregue un valor DWORD de EnableADAL con un valor de 0 en HKEY_CURRENT_USER \Software\Microsoft\Office\16.0\Common\Identity.
- Si el error se produce al conectar con Office 365 mediante Office 2013, [habilite la autenticación moderna](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication) para el cliente de Office.

Para obtener más información, vea [cómo solucionar problemas de aplicaciones que no son de explorador que no pueden iniciar sesión en Office 365, Azure o Intune](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1).

