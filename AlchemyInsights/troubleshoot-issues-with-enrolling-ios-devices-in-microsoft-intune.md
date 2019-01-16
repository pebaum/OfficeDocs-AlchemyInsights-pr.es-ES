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
# <a name="troubleshoot-issues-with-enrolling-ios-devices-in-microsoft-intune"></a>Solución de problemas con dispositivos iOS en Microsoft Intune se inscriben

Revise los recursos enumerados a continuación para resolver el problema ahora. 
  
Algunos mensajes de error comunes y los pasos de la solución:
  
- **Cap dispositivo alcanzado** El usuario tiene más dispositivos inscritos que el límite de dispositivos. Revise estos documentos para [quitar un dispositivo](https://docs.microsoft.com/en-us/intune/devices-wipe) o [cambiar el límite de dispositivos](https://docs.microsoft.com/en-us/intune/enrollment-restrictions-set#set-device-limit-restrictions).
    
- No se admite **este servicio. Ninguna directiva de inscripción:** servicio de notificación de inserción de Apple (APN) necesita ser configurado o renovar. Revise [este documento](https://docs.microsoft.com/en-us/intune/apple-mdm-push-certificate-get) para obtener instrucciones sobre cómo hacerlo. 
    
- **Tipo de licencia de usuario no válido o no reconocida el nombre de usuario:** El usuario debe asignarse una licencia Intune o EMS. Revise estos documentos para asignar una licencia a través de: [Centro de administración de Office](https://docs.microsoft.com/en-us/intune/licenses-assign) o el [portal de Azure](https://docs.microsoft.com/en-us/azure/active-directory/license-users-groups).
    
Recursos adicionales para ayudar a resolver el problema:
  
1. Usar [Intune Portal de solución de problemas](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) para diagnosticar y resolver los errores comunes de inscripción. Revise [este documento](https://docs.microsoft.com/en-us/intune/help-desk-operators) para obtener más detalles. 
    
2. Revise estos documentos para obtener una lista de errores comunes que impiden la inscripción y resoluciones a cada uno: [Guía de solución de problemas](https://support.microsoft.com/en-us/help/4039809/troubleshooting-ios-device-enrollment-in-intune) y [solución de problemas doc](https://docs.microsoft.com/en-us/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).
    
3. [Obtenga información sobre cómo inscribirse dispositivos iOS en Intune de Microsoft](https://docs.microsoft.com/en-us/intune/ios-enroll).
    

