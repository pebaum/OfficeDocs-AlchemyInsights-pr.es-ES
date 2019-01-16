---
title: Con la herramienta de implementación de Office
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 7ff7cc06-76d0-468f-bd66-3f2760750d04
ms.openlocfilehash: b4ade0f21794a8986aa7a37d783da5fa289488fc
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28314143"
---
# <a name="using-the-office-deployment-tool-odt"></a>Using the Office Deployment Tool (ODT)

Use la herramienta de implementación de Office (ODT) para implementar Office 365 versiones de Office. La herramienta de implementación de Office (setup.exe) se ejecuta desde la línea de comandos y un archivo XML de configuración se utiliza para determinar qué valores de configuración que se debe aplicar al implementar Office.
  
1. Descargue la versión más reciente de la herramienta de implementación de Office desde el [Centro de descarga de Microsoft](http://go.microsoft.com/fwlink/p/?LinkID=626065).
    
2. Usar la [Herramienta de personalización de Office (OCT)](https://config.office.com) para seleccionar las preferencias de implementación y crear el archivo XML de configuración. Exportar el archivo de configuración y colóquelo localmente en la misma carpeta donde reside el setup.exe. 
    
    **Nota:** Instalación de Office con frecuencia se producen problemas debido a mal configurado o los archivos de configuración de un formato incorrecto. Para evitar estos problemas, se recomienda que use la herramienta de personalización de Office para crear el archivo de configuración. También puede importar archivos de configuración existente a la herramienta de personalización de Office. 
    
3. Desde un símbolo del sistema con privilegios elevados, cambie a la ubicación donde reside setup.exe y ejecutar la herramienta de implementación de Office en modo de descarga y especificar el archivo de configuración que acaba de guardar. En este ejemplo, el archivo de configuración se denomina Configuration.xml:
    
  ```
  setup.exe /download Configuration.xml  
  ```

4. Ejecute la herramienta de implementación de Office en el modo de configurar y especificar el archivo de configuración.
    
  ```
  setup.exe /configure Configuration.xml
  ```

    **Nota:** Debe ejecutar este paso desde el equipo cliente en el que desea instalar Office y debe tener permisos de administrador local en dicho equipo. 
    
Para obtener más información acerca de cómo utilizar la herramienta de implementación de Office para los escenarios de implementación de Office 365 ProPlus, consulte [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool). Para obtener más información acerca de cómo usar la herramienta de personalización de Office, vea [Introducción a la herramienta de personalización de Office](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).
  

