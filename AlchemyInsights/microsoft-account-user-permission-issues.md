---
title: Crear y usar un buzón compartido
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.openlocfilehash: 1825cfd0a78a29734d0a5128e19acbfba9115d32
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/04/2019
ms.locfileid: "34717363"
---
# <a name="troubleshoot-issue---user-not-found-in-directory"></a>Problema de solución de problemas-el usuario no se encuentra en el directorio

<p>Si los usuarios reciben un mensaje <strong> &ldquo; &hellip;de error&rsquo;, no se puede encontrar el usuario en el directorio. Vuelva a intentarlo&hellip; </strong> donde el tipo de problema <strong> &ldquo;es usuario no está en&rdquo;el directorio.</strong>, puede completar los siguientes pasos para solucionar el problema.</p> <ol> <li>Asegúrese de que la cuenta que aceptó la invitación por correo electrónico es la misma cuenta que se usa para iniciar sesión más adelante. Asegúrese de que el usuario usa la misma cuenta para aceptar la invitación e inicie sesión en el sitio. <br /><br />Para obtener más información, vea <a href="https://support.microsoft.com/en-us/help/12407/microsoft-account-how-to-manage-aliases">Cómo administrar los alias de su cuenta de Microsoft</a> para administrar el inicio de sesión de Office 365. <br /><br /></li> <li>Busque en cada sitio o sitios en los que el usuario recibe el error. <br /><br />a. Agregue <strong> &ldquo;/_layouts/15/People.aspx/membershipgroupid = 0&rdquo; </strong> (entre comillas dobles) al final de la dirección URL del sitio. <br /><br />Ejemplo: https://&lt;contoso&gt;. SharePoint.com/_layouts/15/People.aspx/membershipGroupId=0 <br /><br />b. Seleccione el usuario de la lista. <br /><br />c. Haga clic en <strong>quitar permisos de usuario de la cinta</strong>. <br /><br />d. Vuelva a agregar el usuario y a enviar la invitación al usuario.</li> </ol>

