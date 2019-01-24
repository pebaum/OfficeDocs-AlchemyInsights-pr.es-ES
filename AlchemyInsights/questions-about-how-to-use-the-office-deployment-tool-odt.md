---
title: Preguntas acerca de cómo usar la herramienta de implementación de Office (ODT)
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/26/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: c16b7ac7d79794307fa33ed1039305ed5b842cf6
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29491315"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a>Preguntas acerca de cómo usar la herramienta de implementación de Office (ODT)

Descargue la Herramienta de implementación de Office desde el [Centro de descarga de Microsoft](http://go.microsoft.com/fwlink/p/?LinkID=626065).
  
Después de descargar el archivo autoextraíble, ejecútelo para extraer el archivo ejecutable de la Herramienta de implementación de Office (setup.exe) y un archivo de configuración de ejemplo (configuration.xml).
  
 **Para excluir o quitar los productos de Office 365 ProPlus desde los equipos cliente:**
  
Al instalar Office 365 ProPlus, puede excluir determinados productos. Para ello, siga los pasos de instalación de Office con la ODT, pero incluya el elemento ExcludeApp en el archivo de configuración. Por ejemplo, este archivo de configuración instala todos los productos de Office 365 ProPlus excepto Publisher:
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[Información general sobre la Herramienta de implementación de Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)
  

