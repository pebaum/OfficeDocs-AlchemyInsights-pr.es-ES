---
title: Solucionar problemas relacionados con la inscripción de dispositivos iOS en Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d717bcc9-1cc1-44f6-b5e6-c1bc059c1973
ms.openlocfilehash: 664c18daca5d8e0ad4a88f41db3ff0dbced606e5
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43736175"
---
# <a name="troubleshoot-issues-with-enrolling-ios-devices-in-microsoft-intune"></a><span data-ttu-id="8d4a3-102">Solucionar problemas relacionados con la inscripción de dispositivos iOS en Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="8d4a3-102">Troubleshoot issues with enrolling iOS devices in Microsoft Intune</span></span>

<span data-ttu-id="8d4a3-103">Revise los recursos que se enumeran a continuación para resolver su problema ahora.</span><span class="sxs-lookup"><span data-stu-id="8d4a3-103">Review the resources listed below to resolve your issue now.</span></span> 
  
<span data-ttu-id="8d4a3-104">Algunos mensajes de error comunes y pasos de resolución:</span><span class="sxs-lookup"><span data-stu-id="8d4a3-104">Some common error messages and resolution steps:</span></span>
  
- <span data-ttu-id="8d4a3-105">**Límite de dispositivo alcanzado** El usuario tiene más dispositivos inscritos que el límite del dispositivo.</span><span class="sxs-lookup"><span data-stu-id="8d4a3-105">**Device Cap Reached** The user has more devices enrolled than the device limit.</span></span> <span data-ttu-id="8d4a3-106">Revise estos documentos para [quitar un dispositivo](https://docs.microsoft.com/intune/devices-wipe) o [cambiar el límite del dispositivo](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span><span class="sxs-lookup"><span data-stu-id="8d4a3-106">Review these documents to [remove a device](https://docs.microsoft.com/intune/devices-wipe) or [change the device limit](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span></span>
    
- <span data-ttu-id="8d4a3-107">**Este servicio no es compatible. No hay ninguna directiva de inscripción:** el servicio de notificaciones push de Apple (APNS) tiene que configurarse o renovarse.</span><span class="sxs-lookup"><span data-stu-id="8d4a3-107">**This Service is not supported. No Enrollment Policy:** Apple Push Notification Service (APNS) needs to be configured or renewed.</span></span> <span data-ttu-id="8d4a3-108">Revise [este documento](https://docs.microsoft.com/intune/apple-mdm-push-certificate-get) para obtener instrucciones sobre cómo hacerlo.</span><span class="sxs-lookup"><span data-stu-id="8d4a3-108">Review [this document](https://docs.microsoft.com/intune/apple-mdm-push-certificate-get) for instructions on how to do that.</span></span> 
    
- <span data-ttu-id="8d4a3-109">**Tipo de licencia de usuario no válido o nombre de usuario no reconocido:** Al usuario se le debe asignar una licencia de Intune o EMS.</span><span class="sxs-lookup"><span data-stu-id="8d4a3-109">**User License Type Invalid or User Name Not Recognized:** The user needs to be assigned an Intune or EMS license.</span></span> <span data-ttu-id="8d4a3-110">Revise estos documentos para asignar una licencia mediante: [centro de administración de Office](https://docs.microsoft.com/intune/licenses-assign) o [portal de Azure](https://docs.microsoft.com/azure/active-directory/license-users-groups).</span><span class="sxs-lookup"><span data-stu-id="8d4a3-110">Review these documents to assign a license through: [Office Admin Center](https://docs.microsoft.com/intune/licenses-assign) or [Azure portal](https://docs.microsoft.com/azure/active-directory/license-users-groups).</span></span>
    
<span data-ttu-id="8d4a3-111">Recursos adicionales para ayudar a resolver el problema:</span><span class="sxs-lookup"><span data-stu-id="8d4a3-111">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="8d4a3-112">Use el [portal de solución de problemas de Intune](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) para diagnosticar y resolver errores comunes de inscripción.</span><span class="sxs-lookup"><span data-stu-id="8d4a3-112">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures.</span></span> <span data-ttu-id="8d4a3-113">Revise [este documento](https://docs.microsoft.com/intune/help-desk-operators) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="8d4a3-113">Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span> 
    
2. <span data-ttu-id="8d4a3-114">Revise estos documentos para obtener una lista de errores comunes que impiden la inscripción y las resoluciones a cada uno: [Guía de solución de problemas](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) y documento de solución de [problemas](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span><span class="sxs-lookup"><span data-stu-id="8d4a3-114">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) and [Troubleshooting doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span></span>
    
3. <span data-ttu-id="8d4a3-115">[Obtenga información sobre cómo inscribir dispositivos iOS en Microsoft Intune](https://docs.microsoft.com/intune/ios-enroll).</span><span class="sxs-lookup"><span data-stu-id="8d4a3-115">[Learn how to enroll iOS devices in Microsoft Intune](https://docs.microsoft.com/intune/ios-enroll).</span></span>
    

