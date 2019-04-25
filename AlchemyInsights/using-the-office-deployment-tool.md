---
title: Uso de la herramienta de implementación de Office
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 7ff7cc06-76d0-468f-bd66-3f2760750d04
ms.openlocfilehash: c7e0e96f225030590fdd516eaf3115c93a6335b6
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "32423200"
---
# <a name="using-the-office-deployment-tool-odt"></a>Uso de la herramienta de implementación de Office (ODT)

Use la herramienta de implementación de Office (ODT) para implementar versiones de Office 365 de Office. La herramienta de implementación de Office (Setup. exe) se ejecuta desde la línea de comandos y usa un archivo de configuración XML para determinar qué configuración aplicar al implementar Office.
  
1. Descargue la versión más reciente de la herramienta de implementación de Office del [centro de descarga de Microsoft](http://go.microsoft.com/fwlink/p/?LinkID=626065).
    
2. Use la [herramienta de personalización de Office (Oct)](https://config.office.com) para seleccionar sus preferencias de implementación y crear el archivo XML de configuración. ExPorte el archivo de configuración y colóquelo localmente en la misma carpeta en la que se encuentra Setup. exe. 
    
    **Nota:** Los problemas de instalación de Office se producen normalmente debido a archivos de configuración mal configurados o con formato incorrecto. Para evitar estos problemas, le recomendamos que use la herramienta de personalización de Office para crear el archivo de configuración. También puede importar los archivos de configuración existentes en la herramienta de personalización de Office. 
    
3. Desde un símbolo del sistema con privilegios elevados, cambie a la ubicación en la que reside Setup. exe y ejecute la herramienta de implementación de Office en el modo de descarga y especifique el archivo de configuración que acaba de guardar. En este ejemplo, el archivo de configuración se denomina Configuration. xml:
    
  ```
  setup.exe /download Configuration.xml  
  ```

4. Ejecute la herramienta de implementación de Office en el modo de configuración y especifique el archivo de configuración.
    
  ```
  setup.exe /configure Configuration.xml
  ```

    **Nota:** Debe ejecutar este paso desde el equipo cliente en el que desea instalar Office y debe tener permisos de administrador local en ese equipo. 
    
Para obtener más información sobre el uso de la herramienta de implementación de Office para los escenarios de implementación de Office 365 proPlus, vea [información general sobre la herramienta de implementación de Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool). Para obtener más información sobre cómo usar la herramienta de personalización de Office, vea [información general sobre la herramienta de personalización de Office](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).
  

