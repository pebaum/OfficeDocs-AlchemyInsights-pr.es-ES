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
# <a name="access-denied-when-viewing-a-workflow"></a><span data-ttu-id="c6f14-102">Acceso denegado al ver un flujo de trabajo</span><span class="sxs-lookup"><span data-stu-id="c6f14-102">Access denied when viewing a Workflow</span></span>

<span data-ttu-id="c6f14-103">Los flujos de trabajo de SharePoint 2013 que intentan enviar un correo electrónico a un grupo de SharePoint pueden producir un error con un mensaje de error "acceso denegado" si la pertenencia del grupo de SharePoint no está establecida en todos.</span><span class="sxs-lookup"><span data-stu-id="c6f14-103">SharePoint 2013 Workflows that attempt to send an email to a SharePoint group can fail with an "Access Denied" error message if the membership of the SharePoint group is not set to Everyone.</span></span>
  
 <span data-ttu-id="c6f14-104">**Para solucionar este problema, siga estos pasos:**</span><span class="sxs-lookup"><span data-stu-id="c6f14-104">**To resolve this issue, do these steps:**</span></span>
  
 1. <span data-ttu-id="c6f14-105">Permitir a todos los usuarios ver los miembros del grupo de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="c6f14-105">Allow everybody to see the members of the SharePoint group.</span></span>
  
 2. <span data-ttu-id="c6f14-106">Quite el grupo de SharePoint de la línea para o CC del correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="c6f14-106">Remove the SharePoint group from the To or CC line of the email.</span></span>
  
 3. <span data-ttu-id="c6f14-107">Agregue explícitamente los usuarios a la línea para o CC si no se puede cambiar la visibilidad de la pertenencia al grupo de SharePoint.</span><span class="sxs-lookup"><span data-stu-id="c6f14-107">Explicitly add the users to the To or CC line if the membership visibility cannot be changed for SharePoint group.</span></span>
  
<span data-ttu-id="c6f14-108">Para ver más detalles, consulte [http no autorizado a/_vti_bin/Client.SVC/SP.Utilities.Utility.sendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="c6f14-108">To view more details please refer to [HTTP Unauthorized to /_vti_bin/client.svc/sp.utilities.utility.SendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span></span>
  