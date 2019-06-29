---
title: Solucionar problemas relacionados con la inscripción de dispositivos Android en Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d0269461-20a8-4c9e-83b2-8fcf608dc0a5
ms.custom:
- "787"
- "6200002"
ms.openlocfilehash: 9cdfda0d7dd45af260f46738cbc85aac46f53960
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/28/2019
ms.locfileid: "35367306"
---
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a>Solucionar problemas relacionados con la inscripción de dispositivos Android en Microsoft Intune

Revise los recursos que se enumeran a continuación para resolver su problema ahora.
  
Algunos problemas comunes y los pasos de la solución:
  
 **Error de dispositivo no cifrado en el portal de la empresa:** Las versiones más recientes de Android, en especial a partir de la versión 7.0, requieren un código de acceso de inicio para asegurarse de que el dispositivo está totalmente cifrado. Las soluciones comunes son habilitar un PIN de inicio o cifrar completamente el dispositivo. Revise [este documento](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) para obtener más información.
  
 Los **dispositivos no pueden protegerse con el servicio de Intune o mostrarse como "incorrecto" en la consola de administración de Intune:** Es posible que algunos dispositivos de Samsung 4,4 y 5,5 no protejan el servicio. Hay tres posibles soluciones a este problema:
  
1. Abra manualmente la aplicación del portal de empresa de Intune, que iniciará automáticamente una sincronización del dispositivo.

2. Actualice el dispositivo a Android 6,0 o posterior.

3. Deshabilite el administrador inteligente de Samsung para administrar el portal de empresa de Intune. Revise [este documento](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) para obtener más información sobre estos problemas y sus soluciones.

 **Tipo de licencia de usuario no válido** o **nombre de usuario no reconocido error:** el usuario debe tener asignado una licencia de Intune o EMS. Revise estos documentos para asignar una licencia mediante: Centro de administración de Office o portal de Azure.
  
Recursos adicionales para ayudar a resolver el problema:
  
1. Use el [portal de solución de problemas](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) de Intune para diagnosticar y resolver errores comunes de inscripción. Revise [este documento](https://docs.microsoft.com/intune/help-desk-operators) para obtener más información.

2. Revise [este documento](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) para obtener una lista de errores comunes que impiden la inscripción y las resoluciones a cada uno.

3. [Obtenga información sobre cómo inscribir dispositivos Android en Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).
