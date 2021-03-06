---
title: Problema de solución de problemas-el usuario no se encuentra en el directorio
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.openlocfilehash: 3b863c5e9962dd29ca2ed41d113041d74830f615
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43702755"
---
# <a name="troubleshoot-issue---user-not-found-in-directory"></a>Problema de solución de problemas-el usuario no se encuentra en el directorio

Si los usuarios reciben el mensaje de error "no se encuentra el usuario" en el directorio, vuelva a intentarlo donde el tipo de problema es usuario no está en el directorio.

Puede completar los siguientes pasos para solucionar el problema.

- Asegúrese de que la cuenta que aceptó la invitación por correo electrónico es la misma cuenta que se usa para iniciar sesión más adelante. Asegúrese de que el usuario usa la misma cuenta para aceptar la invitación e inicie sesión en el sitio. 

Para obtener más información, vea [Cómo administrar los alias</a> de su cuenta de Microsoft para administrar el inicio de sesión de Microsoft 365](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases). 

- Busque en cada sitio o sitios en los que el usuario recibe el error. 

Agregue "/_layouts/15/People.aspx/membershipgroupid = 0" (dentro de las comillas dobles) al final de la dirección URL del sitio. 

Ejemplo: https://< "Contoso" >. sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.

- Seleccione el usuario de la lista.

- Haga clic en **quitar permisos de usuario** de la cinta. 
-  Vuelva a agregar el usuario y a enviar la invitación al usuario.

