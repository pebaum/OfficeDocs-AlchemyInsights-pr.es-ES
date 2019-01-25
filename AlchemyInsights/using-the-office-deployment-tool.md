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
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29490923"
---
# <a name="using-the-office-deployment-tool-odt"></a><span data-ttu-id="25fb3-102">Using the Office Deployment Tool (ODT)</span><span class="sxs-lookup"><span data-stu-id="25fb3-102">Using the Office Deployment Tool (ODT)</span></span>

<span data-ttu-id="25fb3-p101">Use la herramienta de implementación de Office (ODT) para implementar Office 365 versiones de Office. La herramienta de implementación de Office (setup.exe) se ejecuta desde la línea de comandos y un archivo XML de configuración se utiliza para determinar qué valores de configuración que se debe aplicar al implementar Office.</span><span class="sxs-lookup"><span data-stu-id="25fb3-p101">You use the Office Deployment Tool (ODT) to deploy Office 365 versions of Office. The Office Deployment Tool (setup.exe) is run from the command line and uses a configuration XML file to determine what settings to apply when deploying Office.</span></span>
  
1. <span data-ttu-id="25fb3-105">Descargue la versión más reciente de la herramienta de implementación de Office desde el [Centro de descarga de Microsoft](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span><span class="sxs-lookup"><span data-stu-id="25fb3-105">Download the latest version of the Office Deployment Tool from the [Microsoft Download Center](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span></span>
    
2. <span data-ttu-id="25fb3-p102">Usar la [Herramienta de personalización de Office (OCT)](https://config.office.com) para seleccionar las preferencias de implementación y crear el archivo XML de configuración. Exportar el archivo de configuración y colóquelo localmente en la misma carpeta donde reside el setup.exe.</span><span class="sxs-lookup"><span data-stu-id="25fb3-p102">Use the [Office Customization Tool (OCT)](https://config.office.com) to select your deployment preferences and create the configuration XML file. Export the configuration file and place it locally on the same folder where the setup.exe resides.</span></span> 
    
    <span data-ttu-id="25fb3-p103">**Nota:** Instalación de Office con frecuencia se producen problemas debido a mal configurado o los archivos de configuración de un formato incorrecto. Para evitar estos problemas, se recomienda que use la herramienta de personalización de Office para crear el archivo de configuración. También puede importar archivos de configuración existente a la herramienta de personalización de Office.</span><span class="sxs-lookup"><span data-stu-id="25fb3-p103">**Note:** Office installation issues commonly occur due to misconfigured or malformatted configuration files. To avoid such issues, we recommend that you use the Office Customization Tool to create the configuration file. You can also import existing configuration files into the Office Customization Tool.</span></span> 
    
3. <span data-ttu-id="25fb3-p104">Desde un símbolo del sistema con privilegios elevados, cambie a la ubicación donde reside setup.exe y ejecutar la herramienta de implementación de Office en modo de descarga y especificar el archivo de configuración que acaba de guardar. En este ejemplo, el archivo de configuración se denomina Configuration.xml:</span><span class="sxs-lookup"><span data-stu-id="25fb3-p104">From an elevated command prompt, switch to the location where setup.exe resides and run the Office Deployment Tool in download mode and specify the configuration file you just saved. In this example, the configuration file is named Configuration.xml:</span></span>
    
  ```
  setup.exe /download Configuration.xml  
  ```

4. <span data-ttu-id="25fb3-113">Ejecute la herramienta de implementación de Office en el modo de configurar y especificar el archivo de configuración.</span><span class="sxs-lookup"><span data-stu-id="25fb3-113">Run the Office Deployment Tool in configure mode and specify the configuration file.</span></span>
    
  ```
  setup.exe /configure Configuration.xml
  ```

    <span data-ttu-id="25fb3-114">**Nota:** Debe ejecutar este paso desde el equipo cliente en el que desea instalar Office y debe tener permisos de administrador local en dicho equipo.</span><span class="sxs-lookup"><span data-stu-id="25fb3-114">**Note:** You must run this step from the client computer on which you want to install Office and you must have local administrator permissions on that computer.</span></span> 
    
<span data-ttu-id="25fb3-p105">Para obtener más información acerca de cómo utilizar la herramienta de implementación de Office para los escenarios de implementación de Office 365 ProPlus, consulte [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool). Para obtener más información acerca de cómo usar la herramienta de personalización de Office, vea [Introducción a la herramienta de personalización de Office](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).</span><span class="sxs-lookup"><span data-stu-id="25fb3-p105">To learn more about using Office Deployment Tool for your Office 365 ProPlus deployment scenarios, see [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool). For more details on how to use the Office Customization Tool, see [Overview of the Office Customization Tool](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).</span></span>
  

