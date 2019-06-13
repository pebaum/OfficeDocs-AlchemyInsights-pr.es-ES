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
ms.openlocfilehash: b7a3805d30cac44781adbbb00c0f0ed3496ff17b
ms.sourcegitcommit: a9be2e396022382e92cf40c0d0d82f2f59c2e259
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/12/2019
ms.locfileid: "34883608"
---
# <a name="access-denied-when-viewing-a-workflow"></a><span data-ttu-id="dc972-102">Acceso denegado al ver un flujo de trabajo</span><span class="sxs-lookup"><span data-stu-id="dc972-102">Access denied when viewing a Workflow</span></span>

<span data-ttu-id="dc972-103">Los flujos de trabajo de SharePoint 2013 que intentan enviar un correo electrónico a un grupo de SharePoint pueden producir un error con un mensaje de error "acceso denegado" si la pertenencia del grupo de SharePoint no está establecida en todos.</span><span class="sxs-lookup"><span data-stu-id="dc972-103">SharePoint 2013 Workflows that attempt to send an email to a SharePoint group can fail with an "Access Denied" error message if the membership of the SharePoint group is not set to Everyone.</span></span>
  
 <span data-ttu-id="dc972-104">**Para solucionar este problema, siga estos pasos:**</span><span class="sxs-lookup"><span data-stu-id="dc972-104">**To resolve this issue, do these steps:**</span></span>
  
 1. <span data-ttu-id="dc972-105">Permitir a todos los usuarios ver los miembros del grupo de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="dc972-105">Allow everybody to see the members of the SharePoint group.</span></span>
  
 2. <span data-ttu-id="dc972-106">Quite el grupo de SharePoint de la línea para o CC del correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="dc972-106">Remove the SharePoint group from the To or CC line of the email.</span></span>
  
 3. <span data-ttu-id="dc972-107">Agregue explícitamente los usuarios a la línea para o CC si no se puede cambiar la visibilidad de la pertenencia al grupo de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="dc972-107">Explicitly add the users to the To or CC line if the membership visibility cannot be changed for SharePoint group.</span></span>
  
<span data-ttu-id="dc972-108">Para ver más detalles, consulte [http no autorizado a/_vti_bin/Client.SVC/SP.Utilities.Utility.sendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="dc972-108">To view more details please refer to [HTTP Unauthorized to /_vti_bin/client.svc/sp.utilities.utility.SendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span></span>
  