---
title: Uso de la herramienta de implementación de Office
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "918"
- "2000022"
ms.assetid: 7ff7cc06-76d0-468f-bd66-3f2760750d04
ms.openlocfilehash: 874bb7883bca4f062e85963a6828a771cd2dad9b
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36531592"
---
# <a name="using-the-office-deployment-tool-odt"></a><span data-ttu-id="1bbd4-102">Uso de la herramienta de implementación de Office (ODT)</span><span class="sxs-lookup"><span data-stu-id="1bbd4-102">Using the Office Deployment Tool (ODT)</span></span>

<span data-ttu-id="1bbd4-103">Use la herramienta de implementación de Office (ODT) para implementar versiones de Office 365 de Office.</span><span class="sxs-lookup"><span data-stu-id="1bbd4-103">You use the Office Deployment Tool (ODT) to deploy Office 365 versions of Office.</span></span> <span data-ttu-id="1bbd4-104">La herramienta de implementación de Office (Setup. exe) se ejecuta desde la línea de comandos y usa un archivo de configuración XML para determinar qué configuración aplicar al implementar Office.</span><span class="sxs-lookup"><span data-stu-id="1bbd4-104">The Office Deployment Tool (setup.exe) is run from the command line and uses a configuration XML file to determine what settings to apply when deploying Office.</span></span>
  
1. <span data-ttu-id="1bbd4-105">Descargue la versión más reciente de la herramienta de implementación de Office del [centro de descarga de Microsoft](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span><span class="sxs-lookup"><span data-stu-id="1bbd4-105">Download the latest version of the Office Deployment Tool from the [Microsoft Download Center](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span></span>

2. <span data-ttu-id="1bbd4-106">Use la [herramienta de personalización de Office (Oct)](https://config.office.com) para seleccionar sus preferencias de implementación y crear el archivo XML de configuración.</span><span class="sxs-lookup"><span data-stu-id="1bbd4-106">Use the [Office Customization Tool (OCT)](https://config.office.com) to select your deployment preferences and create the configuration XML file.</span></span> <span data-ttu-id="1bbd4-107">Exporte el archivo de configuración y colóquelo localmente en la misma carpeta en la que se encuentra Setup. exe.</span><span class="sxs-lookup"><span data-stu-id="1bbd4-107">Export the configuration file and place it locally on the same folder where the setup.exe resides.</span></span>

    <span data-ttu-id="1bbd4-108">**Nota:** Los problemas de instalación de Office se producen normalmente debido a archivos de configuración mal configurados o con formato incorrecto.</span><span class="sxs-lookup"><span data-stu-id="1bbd4-108">**Note:** Office installation issues commonly occur due to misconfigured or malformatted configuration files.</span></span> <span data-ttu-id="1bbd4-109">Para evitar estos problemas, le recomendamos que use la herramienta de personalización de Office para crear el archivo de configuración.</span><span class="sxs-lookup"><span data-stu-id="1bbd4-109">To avoid such issues, we recommend that you use the Office Customization Tool to create the configuration file.</span></span> <span data-ttu-id="1bbd4-110">También puede importar los archivos de configuración existentes en la herramienta de personalización de Office.</span><span class="sxs-lookup"><span data-stu-id="1bbd4-110">You can also import existing configuration files into the Office Customization Tool.</span></span>

3. <span data-ttu-id="1bbd4-111">Desde un símbolo del sistema con privilegios elevados, cambie a la ubicación en la que reside Setup. exe y ejecute la herramienta de implementación de Office en el modo de descarga y especifique el archivo de configuración que acaba de guardar.</span><span class="sxs-lookup"><span data-stu-id="1bbd4-111">From an elevated command prompt, switch to the location where setup.exe resides and run the Office Deployment Tool in download mode and specify the configuration file you just saved.</span></span> <span data-ttu-id="1bbd4-112">En este ejemplo, el archivo de configuración se denomina Configuration. xml:</span><span class="sxs-lookup"><span data-stu-id="1bbd4-112">In this example, the configuration file is named Configuration.xml:</span></span>
    
  ```
  setup.exe /download Configuration.xml  
  ```

4. <span data-ttu-id="1bbd4-113">Ejecute la herramienta de implementación de Office en el modo de configuración y especifique el archivo de configuración.</span><span class="sxs-lookup"><span data-stu-id="1bbd4-113">Run the Office Deployment Tool in configure mode and specify the configuration file.</span></span>
    
  ```
  setup.exe /configure Configuration.xml
  ```

    <span data-ttu-id="1bbd4-114">**Nota:** Debe ejecutar este paso desde el equipo cliente en el que desea instalar Office y debe tener permisos de administrador local en ese equipo.</span><span class="sxs-lookup"><span data-stu-id="1bbd4-114">**Note:** You must run this step from the client computer on which you want to install Office and you must have local administrator permissions on that computer.</span></span>

<span data-ttu-id="1bbd4-115">Para obtener más información sobre el uso de la herramienta de implementación de Office para los escenarios de implementación de Office 365 ProPlus, vea [información general sobre la herramienta de implementación de Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="1bbd4-115">To learn more about using Office Deployment Tool for your Office 365 ProPlus deployment scenarios, see [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span> <span data-ttu-id="1bbd4-116">Para obtener más información sobre cómo usar la herramienta de personalización de Office, vea [información general sobre la herramienta de personalización de Office](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).</span><span class="sxs-lookup"><span data-stu-id="1bbd4-116">For more details on how to use the Office Customization Tool, see [Overview of the Office Customization Tool](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).</span></span>
