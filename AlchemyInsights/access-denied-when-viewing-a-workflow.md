---
title: Acceso denegado al ver un flujo de trabajo
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: c576bf88225582f2577e0b59506a7482cf9f38d5
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43687347"
---
# <a name="access-denied-when-viewing-a-workflow"></a>Acceso denegado al ver un flujo de trabajo

Los flujos de trabajo de SharePoint 2013 que intentan enviar un correo electrónico a un grupo de SharePoint pueden producir un error con un mensaje de error "acceso denegado" si la pertenencia del grupo de SharePoint no está establecida en todos.
  
 **Para solucionar este problema, siga estos pasos:**
  
 1. Permitir a todos los usuarios ver los miembros del grupo de SharePoint.
  
 2. Quite el grupo de SharePoint de la línea para o CC del correo electrónico.
  
 3. Agregue explícitamente los usuarios a la línea para o CC si no se puede cambiar la visibilidad de la pertenencia al grupo de SharePoint.
  
Para ver más detalles, consulte [http no autorizado a/_vti_bin/Client.SVC/SP.Utilities.Utility.sendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).
  