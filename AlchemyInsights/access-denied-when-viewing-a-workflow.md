---
title: Acceso denegado al ver un flujo de trabajo
ms.author: kirks
author: Techwriter40
ms.date: 11/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: 53bd9285e49e220f880eea21923f261302003127
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36495840"
---
# <a name="access-denied-when-viewing-a-workflow"></a>Acceso denegado al ver un flujo de trabajo

Los flujos de trabajo de SharePoint 2013 que intentan enviar un correo electrónico a un grupo de SharePoint pueden producir un error con un mensaje de error "acceso denegado" si la pertenencia del grupo de SharePoint no está establecida en todos.
  
 **Para solucionar este problema, siga estos pasos:**
  
 1. Permitir a todos los usuarios ver los miembros del grupo de SharePoint.
  
 2. Quite el grupo de SharePoint de la línea para o CC del correo electrónico.
  
 3. Agregue explícitamente los usuarios a la línea para o CC si no se puede cambiar la visibilidad de la pertenencia al grupo de SharePoint.
  
Para ver más detalles, consulte [http no autorizado a/_vti_bin/Client.SVC/SP.Utilities.Utility.sendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).
  