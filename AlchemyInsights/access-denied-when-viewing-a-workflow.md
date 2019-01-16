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
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28313540"
---
# <a name="access-denied-when-viewing-a-workflow"></a><span data-ttu-id="2c0de-102">Acceso denegado al ver un flujo de trabajo</span><span class="sxs-lookup"><span data-stu-id="2c0de-102">Access denied when viewing a Workflow</span></span>

<span data-ttu-id="2c0de-103">Los flujos de trabajo de 2013 de SharePoint que intenta enviar un correo electrónico a un grupo de SharePoint puede producirse un error con un mensaje de error "Acceso denegado" Si no se establece la pertenencia al grupo de SharePoint para todos los usuarios.</span><span class="sxs-lookup"><span data-stu-id="2c0de-103">SharePoint 2013 Workflows that attempt to send an email to a SharePoint group can fail with an "Access Denied" error message if the membership of the SharePoint group is not set to Everyone.</span></span>
  
 <span data-ttu-id="2c0de-104">**Para resolver este problema, siga estos pasos:**</span><span class="sxs-lookup"><span data-stu-id="2c0de-104">**To resolve this issue, do these steps:**</span></span>
  
 1. <span data-ttu-id="2c0de-105">Permitir que cualquier persona ver a los miembros del grupo de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="2c0de-105">Allow everybody to see the members of the SharePoint group.</span></span> 
  
 2. <span data-ttu-id="2c0de-106">Quitar el grupo de SharePoint para o CC línea del correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="2c0de-106">Remove the SharePoint group from the To or CC line of the email.</span></span> 
  
 3. <span data-ttu-id="2c0de-107">Agregue explícitamente los usuarios a para o CC de línea si no se puede cambiar la visibilidad de la pertenencia al grupo de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="2c0de-107">Explicitly add the users to the To or CC line if the membership visibility cannot be changed for SharePoint group.</span></span> 
  
<span data-ttu-id="2c0de-108">Para ver más detalles, consulte [HTTP no autorizado a /_vti_bin/client.svc/sp.utilities.utility.SendEmail ](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="2c0de-108">To view more details please refer to [HTTP Unauthorized to /_vti_bin/client.svc/sp.utilities.utility.SendEmail ](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span></span>
  

