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
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a><span data-ttu-id="0cf96-102">Preguntas sobre el uso de la herramienta de implementación de Office (ODT)</span><span class="sxs-lookup"><span data-stu-id="0cf96-102">Questions about how to use the Office Deployment Tool (ODT)</span></span>

<span data-ttu-id="0cf96-103">Descargue la Herramienta de implementación de Office desde el [Centro de descarga de Microsoft](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span><span class="sxs-lookup"><span data-stu-id="0cf96-103">Download the Office Deployment Tool from the [Microsoft Download Center](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span></span>
  
<span data-ttu-id="0cf96-104">Después de descargar el archivo autoextraíble, ejecútelo para extraer el archivo ejecutable de la Herramienta de implementación de Office (setup.exe) y un archivo de configuración de ejemplo (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="0cf96-104">After downloading the file, run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span>
  
 <span data-ttu-id="0cf96-105">**Para excluir o quitar productos de Office 365 ProPlus de los equipos cliente:**</span><span class="sxs-lookup"><span data-stu-id="0cf96-105">**To exclude or remove Office 365 ProPlus products from client computers:**</span></span>
  
<span data-ttu-id="0cf96-p101">Al instalar Office 365 ProPlus, puede excluir determinados productos. Para ello, siga los pasos de instalación de Office con la ODT, pero incluya el elemento ExcludeApp en el archivo de configuración. Por ejemplo, este archivo de configuración instala todos los productos de Office 365 ProPlus excepto Publisher:</span><span class="sxs-lookup"><span data-stu-id="0cf96-p101">When installing Office 365 ProPlus, you can exclude specific products. To do so, follow the steps for installing Office with the ODT, but include the ExcludeApp element in your configuration file. For example, this configuration file installs all the Office 365 ProPlus products except Publisher:</span></span>
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[<span data-ttu-id="0cf96-109">Información general sobre la Herramienta de implementación de Office</span><span class="sxs-lookup"><span data-stu-id="0cf96-109">Overview of the Office Deployment Tool</span></span>](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)
  

