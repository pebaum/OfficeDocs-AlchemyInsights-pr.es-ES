---
title: Restringir el acceso de SharePoint o OneDrive
ms.author: mikeplum
author: MikePlumleyMSFT
ms.date: 8/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: b6be074ed5f7e83f8196ca3fe90252673896569f
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28314090"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a>Restringir el acceso de SharePoint o OneDrive

En SharePoint y OneDrive, restringir el acceso a elementos, como archivos, carpetas y listas mediante la concesión de acceso sólo a los grupos o las personas que desea que tengan acceso. De forma predeterminada, los permisos de SharePoint se heredan de más arriba en la jerarquía. Por lo que un archivo hereda sus permisos de la carpeta, que hereda sus permisos de la biblioteca, que hereda sus permisos del sitio.
  
Puede compartir en un nivel superior (como al compartir un sitio completo) y, a continuación, interrumpir la herencia si no desea compartir todos los elementos en el sitio. Sin embargo, no se recomienda esto ya que permite mantener los permisos más complejos y confusos en el futuro. Aquí es lo que podría hacer en su lugar:
  
- Si, por ejemplo, desea compartir todo el contenido de una carpeta, salvo un solo archivo, mueva ese archivo a una nueva ubicación que no está compartida.
    
- Si tiene dos subcarpetas en una carpeta y desea compartir una subcarpeta con los grupos A y B y permitir sólo el grupo A acceso a la subcarpeta de segundo, comparta la carpeta principal con un grupo y agregar grupo B a la primera subcarpeta.
    
[Dejar de compartir un archivo o carpeta](https://go.microsoft.com/fwlink/?linkid=2008861)
  

