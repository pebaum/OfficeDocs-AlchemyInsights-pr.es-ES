---
title: Restringir el acceso a SharePoint o OneDrive
ms.author: mikeplum
author: MikePlumleyMSFT
ms.date: 8/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: e5458226fe33bd5cb3da1f608fb113b888fbfd16
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36551468"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a>Restringir el acceso a SharePoint o OneDrive

En SharePoint y OneDrive, se restringe el acceso a elementos como archivos, carpetas y listas al conceder acceso solo a los grupos o usuarios a los que desea tener acceso. De forma predeterminada, los permisos de SharePoint se heredan de un nivel superior en la jerarquía. Por lo tanto, un archivo hereda sus permisos de la carpeta, que hereda sus permisos de la biblioteca, que hereda sus permisos del sitio.
  
Puede compartir a un nivel superior (por ejemplo, compartiendo un sitio completo) y, a continuación, interrumpir la herencia si no desea compartir todos los elementos del sitio. Sin embargo, no lo recomendamos porque hace que el mantenimiento de los permisos sea más complejo y confuso en el futuro. Esto es lo que puede hacer en su lugar:
  
- Si, por ejemplo, desea compartir todo el contenido de una carpeta excepto un archivo de la misma, mueva ese archivo a una nueva ubicación que no esté compartida.
    
- Si tiene dos subcarpetas en una carpeta y desea compartir una subcarpeta con los grupos A y B y permitir que sólo el grupo tenga acceso a la segunda subcarpeta, comparta la carpeta principal con el grupo A y agregue el grupo B a la primera subcarpeta.
    
[Dejar de compartir un archivo o una carpeta](https://go.microsoft.com/fwlink/?linkid=2008861)
  

