---
title: Solucionar problemas de sincronización de contraseñas
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "579"
- "1300006"
ms.assetid: 1cba32c4-37ce-4ec1-9e58-8d3440b53d57
ms.openlocfilehash: edd4f68466296f72c2dc0bafda45e6749d62d942
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43732527"
---
# <a name="troubleshoot-password-synchronization"></a>Solucionar problemas de sincronización de contraseñas

Para solucionar problemas en los que no se ha sincronizado ninguna contraseña con Azure AD Connect versión 1.1.614.0 o posterior:
  
1. Abra una nueva sesión de Windows PowerShell en su servidor de Azure AD Connect con la opción **Ejecutar como administrador** .

2. Ejecute **Set-ExecutionPolicy RemoteSigned** o **Set-ExecutionPolicy Unrestricted**.

3. Inicie el Asistente de Azure AD Connect.

4. Vaya a la página **tareas adicionales** , seleccione **solución de problemas**y, a continuación, haga clic en **siguiente**.

5. En la página solución de problemas, haga clic en **iniciar para iniciar el** menú de solución de problemas en PowerShell.

6. En el menú principal, seleccione **solucionar problemas de sincronización de contraseña**.

7. En el menú secundario, seleccione la **sincronización de contraseña no funciona**.

**Comprender los resultados de la tarea de solución de problemas**
  
La tarea de solución de problemas realiza las comprobaciones siguientes:
  
- Valida que la característica de sincronización de contraseña esté habilitada para el inquilino de Azure AD.

- Valida que el servidor de Azure AD Connect no está en modo de ensayo.

- Para cada conector de Active Directory local existente (que corresponda a un bosque de Active Directory existente):

- 
  - Valida que la característica de sincronización de contraseña esté habilitada.

  - Busca eventos Heartbeat de sincronización de contraseña en los registros de eventos de aplicación de Windows.

  - Para cada dominio de Active Directory en el conector de Active Directory local:

  - Valida que el dominio es accesible desde el servidor de Azure AD Connect.

  - Valida que las cuentas de servicios de dominio de Active Directory (AD DS) que usa el conector de Active Directory local tengan el nombre de usuario, la contraseña y los permisos correctos necesarios para la sincronización de contraseña.

Para obtener más información sobre cómo solucionar problemas de la sincronización de contraseñas, consulte [solucionar problemas de sincronización de contraseña con sincronización de Azure ad Connect](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).
  