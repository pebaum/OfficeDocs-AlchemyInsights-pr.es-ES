---
title: Preguntas sobre el uso de la herramienta de implementación de Office (ODT)
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/26/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: 604fc200517316de6e0194bd64e6eb3039cfa61b
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2019
ms.locfileid: "36553557"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a>Preguntas sobre el uso de la herramienta de implementación de Office (ODT)

Descargue la Herramienta de implementación de Office desde el [Centro de descarga de Microsoft](http://go.microsoft.com/fwlink/p/?LinkID=626065).
  
Después de descargar el archivo autoextraíble, ejecútelo para extraer el archivo ejecutable de la Herramienta de implementación de Office (setup.exe) y un archivo de configuración de ejemplo (configuration.xml).
  
 **Para excluir o quitar productos de Office 365 ProPlus de los equipos cliente:**
  
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
  

