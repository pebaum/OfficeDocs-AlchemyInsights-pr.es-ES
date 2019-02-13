---
title: Restringir el acceso de SharePoint o OneDrive
ms.author: mikeplum
author: MikePlumleyMSFT
ms.date: 8/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: e0fbec6eb269a173664e2b9a1efe6eefb527b96f
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29905165"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a><span data-ttu-id="ace81-102">Restringir el acceso de SharePoint o OneDrive</span><span class="sxs-lookup"><span data-stu-id="ace81-102">Restrict access in SharePoint or OneDrive</span></span>

<span data-ttu-id="ace81-p101">En SharePoint y OneDrive, restringir el acceso a elementos, como archivos, carpetas y listas mediante la concesión de acceso sólo a los grupos o las personas que desea que tengan acceso. De forma predeterminada, los permisos de SharePoint se heredan de más arriba en la jerarquía. Por lo que un archivo hereda sus permisos de la carpeta, que hereda sus permisos de la biblioteca, que hereda sus permisos del sitio.</span><span class="sxs-lookup"><span data-stu-id="ace81-p101">In SharePoint and OneDrive, you restrict access to items like files, folders, and lists by granting access only to groups or individuals you want to have access. By default, permissions in SharePoint are inherited from higher up in the hierarchy. So a file inherits its permissions from the folder, which inherits its permissions from the library, which inherits its permissions from the site.</span></span>
  
<span data-ttu-id="ace81-p102">Puede compartir en un nivel superior (como al compartir un sitio completo) y, a continuación, interrumpir la herencia si no desea compartir todos los elementos en el sitio. Sin embargo, no se recomienda esto ya que permite mantener los permisos más complejos y confusos en el futuro. Aquí es lo que podría hacer en su lugar:</span><span class="sxs-lookup"><span data-stu-id="ace81-p102">You can share at a higher level (such as by sharing an entire site) and then break inheritance if you don't want to share all the items on the site. However, we don't recommend this because it makes maintaining the permissions more complex and confusing in the future. Here's what you could do instead:</span></span>
  
- <span data-ttu-id="ace81-109">Si, por ejemplo, desea compartir todo el contenido de una carpeta, salvo un solo archivo, mueva ese archivo a una nueva ubicación que no está compartida.</span><span class="sxs-lookup"><span data-stu-id="ace81-109">If, for example, you want to share all the contents of a folder except for one file in it, move that file to a new location that isn't shared.</span></span>
    
- <span data-ttu-id="ace81-110">Si tiene dos subcarpetas en una carpeta y desea compartir una subcarpeta con los grupos A y B y permitir sólo el grupo A acceso a la subcarpeta de segundo, comparta la carpeta principal con un grupo y agregar grupo B a la primera subcarpeta.</span><span class="sxs-lookup"><span data-stu-id="ace81-110">If you have two subfolders in a folder, and you want to share one subfolder with groups A and B and allow only group A access to the second subfolder, share the parent folder with group A and add group B to the first subfolder.</span></span>
    
[<span data-ttu-id="ace81-111">Dejar de compartir un archivo o carpeta</span><span class="sxs-lookup"><span data-stu-id="ace81-111">Stop sharing a file or folder </span></span>](https://go.microsoft.com/fwlink/?linkid=2008861)
  

