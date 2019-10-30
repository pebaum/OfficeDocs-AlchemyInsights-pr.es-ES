---
title: Herramienta de exportación de exhibición de documentos electrónicos
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "263"
- "928"
- "1100001"
- "3100022"
ms.assetid: b16d310d-1134-4959-be68-d1c0ad463930
ms.openlocfilehash: 7e2964ef0a44ddf421e4aae007acbdbda196e20f
ms.sourcegitcommit: defe2c412567b596fa8c3ab52111bde712ebb314
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/29/2019
ms.locfileid: "37769320"
---
# <a name="cant-install-or-run-the-ediscovery-export-tool"></a>¿No puede instalar ni ejecutar la herramienta de exportación de exhibición de documentos electrónicos?

Si no puede instalar ni ejecutar la herramienta de exportación de Office 365 eDiscovery para descargar los resultados de la búsqueda, compruebe lo siguiente:
  
- El equipo que está usando cumple estos requisitos previos:

  - Versiones de 32 o 64 bits de Windows 7 y versiones posteriores

  - Microsoft .NET Framework 4,7

  - Un explorador compatible:

  - Microsoft Edge

    O bien

  - Internet Explorer 10 y versiones posteriores

    No se admiten otros exploradores, como Google Chrome y Mozilla Firefox.

- Su organización puede conectarse al extremo en Azure, que es ** \*. BLOB.Core.Windows.net** (el carácter comodín representa un identificador único para su trabajo de exportación).

- Tiene asignada la función exportar en el centro de seguridad &amp; y cumplimiento de Office 365. De forma predeterminada, este rol solo se asigna al grupo de roles eDiscovery Manager. Consulte [asignar permisos de exhibición](https://docs.microsoft.com/office365/securitycompliance/assign-ediscovery-permissions)de documentos electrónicos.

Para obtener más información, vea [exportar resultados](https://docs.microsoft.com/office365/securitycompliance/export-search-results)de la búsqueda de contenido.
  