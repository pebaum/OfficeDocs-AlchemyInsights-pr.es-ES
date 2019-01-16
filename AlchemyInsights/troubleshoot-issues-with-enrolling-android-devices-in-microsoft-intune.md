---
title: Solución de problemas con dispositivos Android en Microsoft Intune se inscriben
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: d0269461-20a8-4c9e-83b2-8fcf608dc0a5
ms.openlocfilehash: 2f4fc434128ebe7323f0b8c08aec3be82112bbda
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28314549"
---
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a>Solución de problemas con dispositivos Android en Microsoft Intune se inscriben

Revise los recursos enumerados a continuación para resolver el problema ahora.
  
Algunos problemas comunes y los pasos de la solución:
  
 **Dispositivo no cifrado error en el Portal de empresa:** Las versiones más recientes de Android, especialmente comenzando con v7.0, requieren un código de acceso de inicio para asegurarse de que su dispositivo está totalmente cifrado. Soluciones comunes son habilitar un pin de inicio o totalmente cifrar el dispositivo. Revise [este documento](https://docs.microsoft.com/en-us/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) para obtener más información. 
  
 **Producirá un error en los dispositivos comprobar con el servicio Intune o mostrar como "Negativa" en la consola de administración Intune:** Algunos 4.4 Samsung y 5.5 dispositivos no pueden comprobar en el servicio. Existen 3 soluciones posibles a este problema: 
  
1. Abrir manualmente la aplicación de Portal de empresa Intune, que iniciará automáticamente una sincronización de dispositivo.
    
2. Actualizar el dispositivo para Android 6.0 o superior.
    
3. Deshabilitar a Samsung inteligentes administrador desde administración del Portal de la compañía Intune. Revise [este documento](https://docs.microsoft.com/en-us/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) para obtener más información sobre estos problemas y soluciones. 
    
 **Tipo de licencia de usuario válido** o **error de nombre de usuario no reconocido:** el usuario debe asignarse una licencia Intune o EMS. Revise estos documentos para asignar una licencia a través de: portal de centro de administración de Office o de Azure. 
  
Recursos adicionales para ayudar a resolver el problema:
  
1. Usar [Intune Portal de solución de problemas](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) para diagnosticar y resolver los errores comunes de inscripción. Revise [este documento](https://docs.microsoft.com/en-us/intune/help-desk-operators) para obtener más detalles. 
    
2. Revise [este documento](https://docs.microsoft.com/en-us/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) para obtener una lista de errores comunes que impiden la inscripción y resoluciones a cada uno. 
    
3. [Obtenga información sobre cómo inscribirse dispositivos Android en Intune de Microsoft](https://docs.microsoft.com/en-us/intune/android-enroll).
    

