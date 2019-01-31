---
title: Solución de problemas de inscripción de dispositivos de Windows en Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 20e9bd42-2db0-4dd7-b480-966571494dd9
ms.openlocfilehash: 8c5e7cc502d016ad658383685523dc240dfb4dc6
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/30/2019
ms.locfileid: "29661580"
---
# <a name="troubleshoot-issues-with-enrolling-windows-devices-in-microsoft-intune"></a>Solución de problemas de inscripción de dispositivos de Windows en Microsoft Intune

Revise los recursos enumerados a continuación para resolver el problema ahora. 
  
Algunos mensajes de error comunes y los pasos de la solución:
  
 **No se puede instalar el software, 0x80cf4017:** El certificado de cuenta ha caducado. Vuelva a descargar el paquete de software de cliente de PC en la consola de administración Intune. Revise esta documentación para obtener más información. 
  
 **Código de error 0x801c0003:** El error puede producirse en los siguientes escenarios: 
  
1. El usuario tiene más dispositivos inscritos que el límite de dispositivos. Revise estos documentos para [quitar un dispositivo](https://docs.microsoft.com/intune/devices-wipe) o [cambiar el límite de dispositivos](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).
    
2. "Los usuarios pueden unirse a dispositivos a Azure AD" se establece en "none". Establecido en all o seleccione los usuarios. Revise [esta documentación](https://docs.microsoft.com/azure/active-directory/device-management-azure-portal#configure-device-settings) para obtener más información. 
    
3. El dispositivo ya está inscrito por otro usuario. Si ese es el caso, quite el dispositivo desde la consola de Azure Intune o manualmente anular inscripción el dispositivo antes de intentar de nuevo.
    
4. El dispositivo es 10 Windows Home. Sólo 10 para profesionales de Windows, la educación y las SKU de empresa pueden unir a Azure Active Directory.
    
Recursos adicionales para ayudar a resolver el problema:
  
1. Usar [Intune Portal de solución de problemas](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) para diagnosticar y resolver los errores comunes de inscripción. Revise [este documento](https://docs.microsoft.com/intune/help-desk-operators) para obtener más detalles. 
    
2. Revise estos documentos para obtener una lista de errores comunes que impiden la inscripción y resoluciones a cada uno: [Guía de solución de problemas](https://support.microsoft.com/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) y [solución de problemas doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).
    
[Obtenga información sobre cómo inscribirse los dispositivos de Windows en Microsoft Intune](https://docs.microsoft.com/intune/windows-enroll).
  

