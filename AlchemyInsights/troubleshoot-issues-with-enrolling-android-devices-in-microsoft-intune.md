---
title: Solución de problemas con dispositivos Android en Microsoft Intune se inscriben
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d0269461-20a8-4c9e-83b2-8fcf608dc0a5
ms.openlocfilehash: 0e727bd47a7d549a439e4666fa9dbb8a02e39778
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29939365"
---
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a><span data-ttu-id="020a2-102">Solución de problemas con dispositivos Android en Microsoft Intune se inscriben</span><span class="sxs-lookup"><span data-stu-id="020a2-102">Troubleshoot issues with enrolling Android devices in Microsoft Intune</span></span>

<span data-ttu-id="020a2-103">Revise los recursos enumerados a continuación para resolver el problema ahora.</span><span class="sxs-lookup"><span data-stu-id="020a2-103">Review the resources listed below to resolve your issue now.</span></span>
  
<span data-ttu-id="020a2-104">Algunos problemas comunes y los pasos de la solución:</span><span class="sxs-lookup"><span data-stu-id="020a2-104">Some common issues and resolution steps:</span></span>
  
 <span data-ttu-id="020a2-p101">**Dispositivo no cifrado error en el Portal de empresa:** Las versiones más recientes de Android, especialmente comenzando con v7.0, requieren un código de acceso de inicio para asegurarse de que su dispositivo está totalmente cifrado. Soluciones comunes son habilitar un pin de inicio o totalmente cifrar el dispositivo. Revise [este documento](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="020a2-p101">**Device not Encrypted error in Company Portal:** Newer versions of Android, particularly starting with v7.0, require a startup passcode to make sure that your device is fully encrypted. Common solutions are to enable a startup pin or fully encrypt the device. Review [this document](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) for more information.</span></span> 
  
 <span data-ttu-id="020a2-p102">**Producirá un error en los dispositivos comprobar con el servicio Intune o mostrar como "Negativa" en la consola de administración Intune:** Algunos 4.4 Samsung y 5.5 dispositivos no pueden comprobar en el servicio. Existen 3 soluciones posibles a este problema:</span><span class="sxs-lookup"><span data-stu-id="020a2-p102">**Devices fail to check in with the Intune service or display as "Unhealthy" in the Intune admin console:** Some Samsung 4.4 and 5.5 devices may not check into the service. There are 3 possible solutions to this issue:</span></span> 
  
1. <span data-ttu-id="020a2-110">Abrir manualmente la aplicación de Portal de empresa Intune, que iniciará automáticamente una sincronización de dispositivo.</span><span class="sxs-lookup"><span data-stu-id="020a2-110">Manually open the Intune Company Portal app, which will automatically initiate a device sync.</span></span>
    
2. <span data-ttu-id="020a2-111">Actualizar el dispositivo para Android 6.0 o superior.</span><span class="sxs-lookup"><span data-stu-id="020a2-111">Update the device to Android 6.0 or higher.</span></span>
    
3. <span data-ttu-id="020a2-p103">Deshabilitar a Samsung inteligentes administrador desde administración del Portal de la compañía Intune. Revise [este documento](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) para obtener más información sobre estos problemas y soluciones.</span><span class="sxs-lookup"><span data-stu-id="020a2-p103">Disable Samsung Smart Manager from managing the Intune Company Portal. Review [this document](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) for further details on these issues and resolutions.</span></span> 
    
 <span data-ttu-id="020a2-p104">**Tipo de licencia de usuario válido** o **error de nombre de usuario no reconocido:** el usuario debe asignarse una licencia Intune o EMS. Revise estos documentos para asignar una licencia a través de: portal de centro de administración de Office o de Azure.</span><span class="sxs-lookup"><span data-stu-id="020a2-p104">**User License Type Invalid** or **User Name Not Recognized error:** The user needs to be assigned an Intune or EMS license. Review these documents to assign a license through: Office Admin Center or Azure portal.</span></span> 
  
<span data-ttu-id="020a2-116">Recursos adicionales para ayudar a resolver el problema:</span><span class="sxs-lookup"><span data-stu-id="020a2-116">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="020a2-p105">Usar [Intune Portal de solución de problemas](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) para diagnosticar y resolver los errores comunes de inscripción. Revise [este documento](https://docs.microsoft.com/intune/help-desk-operators) para obtener más detalles.</span><span class="sxs-lookup"><span data-stu-id="020a2-p105">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures. Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span> 
    
2. <span data-ttu-id="020a2-119">Revise [este documento](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) para obtener una lista de errores comunes que impiden la inscripción y resoluciones a cada uno.</span><span class="sxs-lookup"><span data-stu-id="020a2-119">Review [this document](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) for a list of common errors that prevent enrollment and resolutions to each.</span></span> 
    
3. <span data-ttu-id="020a2-120">[Obtenga información sobre cómo inscribirse dispositivos Android en Intune de Microsoft](https://docs.microsoft.com/intune/android-enroll).</span><span class="sxs-lookup"><span data-stu-id="020a2-120">[Learn how to enroll Android devices in Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).</span></span>
    

