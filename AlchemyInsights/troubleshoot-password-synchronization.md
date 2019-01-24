---
title: Solucionar problemas de sincronización de contraseña
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 1cba32c4-37ce-4ec1-9e58-8d3440b53d57
ms.openlocfilehash: c71fce8621057093d23891c26f7b0285fdc8b9ed
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29491126"
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
    
Para obtener más ayuda de solución de problemas de sincronización de contraseñas, consulte [solucionar problemas sincronización de contraseñas con la sincronización de Azure Connect de AD](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).
  

