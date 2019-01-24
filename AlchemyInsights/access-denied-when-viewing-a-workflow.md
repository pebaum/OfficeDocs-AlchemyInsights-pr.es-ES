---
title: Acceso denegado al ver un flujo de trabajo
ms.author: kirks
author: Techwriter40
ms.date: 11/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: cced887b03876eef527e0166a5a3c9be4b553029
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29491122"
---
# <a name="access-denied-when-viewing-a-workflow"></a>Acceso denegado al ver un flujo de trabajo

Los flujos de trabajo de 2013 de SharePoint que intenta enviar un correo electrónico a un grupo de SharePoint puede producirse un error con un mensaje de error "Acceso denegado" Si no se establece la pertenencia al grupo de SharePoint para todos los usuarios.
  
 **Para resolver este problema, siga estos pasos:**
  
 1. Permitir que cualquier persona ver a los miembros del grupo de SharePoint. 
  
 2. Quitar el grupo de SharePoint para o CC línea del correo electrónico. 
  
 3. Agregue explícitamente los usuarios a para o CC de línea si no se puede cambiar la visibilidad de la pertenencia al grupo de SharePoint. 
  
Para ver más detalles, consulte [HTTP no autorizado a /_vti_bin/client.svc/sp.utilities.utility.SendEmail ](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).
  

