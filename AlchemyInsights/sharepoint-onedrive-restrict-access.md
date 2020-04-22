---
title: Restringir el acceso a SharePoint o OneDrive
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: 39aa8cd6e649eca4a1e196eeb589a825364d0977
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43692782"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a>Restringir el acceso a SharePoint o OneDrive

Hay muchas formas de restringir el acceso a los servicios de SharePoint Online/OneDrive. Estos varios métodos de restricción de acceso se describen a continuación. 

**Restricción de permisos**

En SharePoint Online y OneDrive para la empresa, se restringe el acceso a elementos como sitios, archivos y carpetas mediante la concesión solo de acceso a los grupos o usuarios que deben tener acceso.

- [Personalización de permisos para una lista o biblioteca de SharePoint](https://support.office.com/article/Customize-permissions-for-a-SharePoint-list-or-library-02d770f3-59eb-4910-a608-5f84cc297782)

- [Personalizar permisos del sitio de SharePoint](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions)

- [Cambiar permisos en una subcarpeta](https://support.office.com/article/Change-the-permissions-on-a-subfolder-5427BD7C-F20A-4F75-8CF2-5359DD45A1A6)

- [Control de acceso desde dispositivos no administrados](https://docs.microsoft.com/sharepoint/control-access-from-unmanaged-devices)

Como administrador global o de SharePoint, puede bloquear o limitar el acceso a contenido de SharePoint y OneDrive desde dispositivos no administrados (no compatibles con AD híbrido o compatibles con Intune).

**Restricción de ubicación de red**

Como administrador de ti, puede controlar el acceso a los recursos de SharePoint y OneDrive en función de las ubicaciones de red definidas en las que confíe. Esto también se conoce como directiva basada en la ubicación. Para obtener más información, vea [controlar el acceso a los datos de SharePoint Online y OneDrive en función de la ubicación de la red](https://docs.microsoft.com/sharepoint/control-access-based-on-network-location) .

**Restricción de bloqueo del sitio** 

En SharePoint Online tiene la posibilidad de bloquear una colección de sitios, por lo que nadie tiene acceso. Esto se establece a través de PowerShell y el [Shell de administración de SharePoint Online](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) con la propiedad [set-SPOSite](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) -LockState.

**Restringir a los usuarios la creación de sitios o subsitios**

Como administrador de SharePoint o administrador global, puede permitir a los usuarios crear y administrar sus propios sitios de SharePoint, determinar el tipo de sitios que pueden crear y especificar la ubicación de los sitios. Para obtener más información, vea [administrar la creación de sitios en SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation) .

