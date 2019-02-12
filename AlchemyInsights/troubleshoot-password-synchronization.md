---
title: Solucionar problemas de sincronización de contraseña
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 1cba32c4-37ce-4ec1-9e58-8d3440b53d57
ms.openlocfilehash: d346cf97fb2fd08a9132904517192d8728ffa941
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29924713"
---
# <a name="troubleshoot-password-synchronization"></a>Solucionar problemas de sincronización de contraseña

Para solucionar los problemas que no las contraseñas se sincronizada con Azure Connect AD versión 1.1.614.0 o posterior:
  
1. Abra una nueva sesión de Windows PowerShell en el servidor de Azure de AD de conectar con la opción **Ejecutar como administrador** . 
    
2. Ejecute **Set-ExecutionPolicy RemoteSigned** o **Set-ExecutionPolicy sin restricciones**. 
    
3. Iniciar al Asistente para la conexión de Azure AD.
    
4. Navegue hasta el ** tareas adicionales ** página, seleccione ** Troubleshoot ** y haga clic en **siguiente**. 
    
5. En la página de solución de problemas, haga clic en el menú de **Inicio para iniciar la solución de problemas** en PowerShell. 
    
6. En el menú principal, seleccione **Solución de problemas de sincronización de contraseña**. 
    
7. En el menú sub, seleccione **la sincronización de contraseña no funciona en absoluto**. 
    
 **Comprender los resultados de la tarea de solución de problemas**
  
La tarea de solución de problemas realiza las siguientes comprobaciones:
  
- Valida que la característica de sincronización de contraseña está habilitada para el inquilino de Azure AD.
    
- Valida que el servidor de Azure Connect AD no está en modo de ensayo.
    
- Para cada conector de Active Directory de local existente al (que corresponde a un bosque de Active Directory existente):
    
- 
  - Valida que está habilitada la característica de sincronización de contraseña.
    
  - Busca los eventos de latido de sincronización de contraseña en los registros de eventos de aplicación de Windows.
    
  - Para cada dominio de Active Directory en el conector de Active Directory local:
    
  - Valida que el dominio está accesible desde el servidor de Azure Connect de AD.
    
  - Valida que las cuentas de servicios de dominio de Active Directory (AD DS) utilizadas por el conector de Active Directory local tiene el nombre de usuario correcto, contraseña y permisos necesarios para la sincronización de contraseña.
    
Para obtener más ayuda de solución de problemas de sincronización de contraseñas, consulte [solucionar problemas sincronización de contraseñas con la sincronización de Azure Connect de AD](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).
  

