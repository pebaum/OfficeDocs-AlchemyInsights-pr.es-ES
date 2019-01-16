---
title: Solución de problemas con dispositivos iOS en Microsoft Intune se inscriben
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: d717bcc9-1cc1-44f6-b5e6-c1bc059c1973
ms.openlocfilehash: 663ff9b101494be781095ca550a4ed3deedca175
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28314481"
---
# <a name="troubleshoot-issues-with-enrolling-ios-devices-in-microsoft-intune"></a><span data-ttu-id="c9a1b-102">Solución de problemas con dispositivos iOS en Microsoft Intune se inscriben</span><span class="sxs-lookup"><span data-stu-id="c9a1b-102">Troubleshoot issues with enrolling iOS devices in Microsoft Intune</span></span>

<span data-ttu-id="c9a1b-103">Revise los recursos enumerados a continuación para resolver el problema ahora.</span><span class="sxs-lookup"><span data-stu-id="c9a1b-103">Review the resources listed below to resolve your issue now.</span></span> 
  
<span data-ttu-id="c9a1b-104">Algunos mensajes de error comunes y los pasos de la solución:</span><span class="sxs-lookup"><span data-stu-id="c9a1b-104">Some common error messages and resolution steps:</span></span>
  
- <span data-ttu-id="c9a1b-p101">**Cap dispositivo alcanzado** El usuario tiene más dispositivos inscritos que el límite de dispositivos. Revise estos documentos para [quitar un dispositivo](https://docs.microsoft.com/en-us/intune/devices-wipe) o [cambiar el límite de dispositivos](https://docs.microsoft.com/en-us/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span><span class="sxs-lookup"><span data-stu-id="c9a1b-p101">**Device Cap Reached** The user has more devices enrolled than the device limit. Review these documents to [remove a device](https://docs.microsoft.com/en-us/intune/devices-wipe) or [change the device limit](https://docs.microsoft.com/en-us/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span></span>
    
- <span data-ttu-id="c9a1b-p102">No se admite **este servicio. Ninguna directiva de inscripción:** servicio de notificación de inserción de Apple (APN) necesita ser configurado o renovar. Revise [este documento](https://docs.microsoft.com/en-us/intune/apple-mdm-push-certificate-get) para obtener instrucciones sobre cómo hacerlo.</span><span class="sxs-lookup"><span data-stu-id="c9a1b-p102">**This Service is not supported. No Enrollment Policy:** Apple Push Notification Service (APNS) needs to be configured or renewed. Review [this document](https://docs.microsoft.com/en-us/intune/apple-mdm-push-certificate-get) for instructions on how to do that.</span></span> 
    
- <span data-ttu-id="c9a1b-p103">**Tipo de licencia de usuario no válido o no reconocida el nombre de usuario:** El usuario debe asignarse una licencia Intune o EMS. Revise estos documentos para asignar una licencia a través de: [Centro de administración de Office](https://docs.microsoft.com/en-us/intune/licenses-assign) o el [portal de Azure](https://docs.microsoft.com/en-us/azure/active-directory/license-users-groups).</span><span class="sxs-lookup"><span data-stu-id="c9a1b-p103">**User License Type Invalid or User Name Not Recognized:** The user needs to be assigned an Intune or EMS license. Review these documents to assign a license through: [Office Admin Center](https://docs.microsoft.com/en-us/intune/licenses-assign) or [Azure portal](https://docs.microsoft.com/en-us/azure/active-directory/license-users-groups).</span></span>
    
<span data-ttu-id="c9a1b-111">Recursos adicionales para ayudar a resolver el problema:</span><span class="sxs-lookup"><span data-stu-id="c9a1b-111">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="c9a1b-p104">Usar [Intune Portal de solución de problemas](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) para diagnosticar y resolver los errores comunes de inscripción. Revise [este documento](https://docs.microsoft.com/en-us/intune/help-desk-operators) para obtener más detalles.</span><span class="sxs-lookup"><span data-stu-id="c9a1b-p104">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures. Review [this document](https://docs.microsoft.com/en-us/intune/help-desk-operators) for more details.</span></span> 
    
2. <span data-ttu-id="c9a1b-114">Revise estos documentos para obtener una lista de errores comunes que impiden la inscripción y resoluciones a cada uno: [Guía de solución de problemas](https://support.microsoft.com/en-us/help/4039809/troubleshooting-ios-device-enrollment-in-intune) y [solución de problemas doc](https://docs.microsoft.com/en-us/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span><span class="sxs-lookup"><span data-stu-id="c9a1b-114">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/en-us/help/4039809/troubleshooting-ios-device-enrollment-in-intune) and [Troubleshooting doc](https://docs.microsoft.com/en-us/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span></span>
    
3. <span data-ttu-id="c9a1b-115">[Obtenga información sobre cómo inscribirse dispositivos iOS en Intune de Microsoft](https://docs.microsoft.com/en-us/intune/ios-enroll).</span><span class="sxs-lookup"><span data-stu-id="c9a1b-115">[Learn how to enroll iOS devices in Microsoft Intune](https://docs.microsoft.com/en-us/intune/ios-enroll).</span></span>
    

