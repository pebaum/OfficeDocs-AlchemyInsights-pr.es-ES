---
title: Solucionar problemas relacionados con la inscripción de dispositivos Windows en Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 20e9bd42-2db0-4dd7-b480-966571494dd9
ms.custom:
- "784"
- "6200002"
ms.openlocfilehash: be66135b80f32f78266ef2b6a7b3f5b30e24d5fc
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36559678"
---
# <a name="troubleshoot-issues-with-enrolling-windows-devices-in-microsoft-intune"></a>Solucionar problemas relacionados con la inscripción de dispositivos Windows en Microsoft Intune

Revise los recursos que se enumeran a continuación para resolver su problema ahora.
  
Algunos mensajes de error comunes y pasos de resolución:
  
 **El software no se puede instalar, 0x80cf4017:** El certificado de cuenta ha expirado. Vuelva a descargar el paquete de software cliente de PC en la consola de administración de Intune. Consulte esta documentación para obtener más información.
  
 **Código de error 0x801c0003:** El error puede producirse en las siguientes situaciones:
  
1. El usuario tiene más dispositivos inscritos que el límite del dispositivo. Revise estos documentos para [quitar un dispositivo](https://docs.microsoft.com/intune/devices-wipe) o [cambiar el límite del dispositivo](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).

2. "Los usuarios pueden unir dispositivos a Azure AD" se establece en "none". Establézcalo en todos o seleccione usuarios. Consulte [esta documentación](https://docs.microsoft.com/azure/active-directory/device-management-azure-portal#configure-device-settings) para obtener más información.

3. El dispositivo ya está inscrito por otro usuario. Si ese es el caso, quite el dispositivo de la consola de Azure Intune o elimine la inscripción del dispositivo manualmente antes de volver a intentarlo.

4. El dispositivo es Windows 10 Home. Solo las SKU de Windows 10 Pro, Education y Enterprise pueden unirse a Azure Active Directory.

Recursos adicionales para ayudar a resolver el problema:
  
1. Use el [portal de solución de problemas](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) de Intune para diagnosticar y resolver errores comunes de inscripción. Revise [este documento](https://docs.microsoft.com/intune/help-desk-operators) para obtener más información.

2. Revise estos documentos para obtener una lista de errores comunes que impiden la inscripción y las resoluciones a cada uno: [Guía de solución de problemas](https://support.microsoft.com/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) y documento de solución de [problemas](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).

[Obtenga información sobre cómo inscribir dispositivos Windows en Microsoft Intune](https://docs.microsoft.com/intune/windows-enroll).
