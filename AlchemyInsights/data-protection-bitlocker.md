---
title: Dataprotection-BitLocker
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1802"
- "9000220"
ms.openlocfilehash: c23a2a2bde240900119382a9c1185a6e02520149
ms.sourcegitcommit: 123e9fe46e99719dd271e75a66555861e968f4a2
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/30/2019
ms.locfileid: "40908726"
---
# <a name="enabling-bitlocker-encryption-with-intune"></a>Habilitación del cifrado de BitLocker con Intune

 La Directiva de la protección de extremos de Intune se puede usar para configurar las opciones de cifrado de BitLocker para dispositivos Windows. Para obtener más información, consulte [configuración de Windows 10 (y versiones posteriores) para proteger los dispositivos con Intune](https://docs.microsoft.com/intune/endpoint-protection-windows-10#windows-encryption).
 
Debe tener en cuenta que muchos dispositivos nuevos que ejecutan Windows 10 admiten el cifrado de BitLocker automático, que se desencadena sin la aplicación de la Directiva de MDM. Esto puede afectar a la aplicación de la Directiva si se configuran opciones no predeterminadas. Consulte las siguientes preguntas frecuentes para obtener más información.
 
Para obtener información sobre cómo solucionar problemas de BitLocker, vea [solucionar problemas de las directivas de BitLocker en Microsoft Intune](https://docs.microsoft.com/intune/protect/troubleshoot-bitlocker-policies).
 
 
**Preguntas más frecuentes**

 P: ¿Qué ediciones de Windows admiten el cifrado de dispositivos con la Directiva de Endpoint Protection?<br>
 A: la configuración de la Directiva de la protección de extremos de Intune se implementa con el [CSP de BitLocker](https://docs.microsoft.com/windows/client-management/mdm/bitlocker-csp). No todas las ediciones o compilaciones de Windows admiten el CSP de BitLocker. <br><br>
      En este momento, se admiten las siguientes ediciones de Windows: Enterprise, Education, Mobile, Mobile Enterprise y Professional (compilación 1809 y posteriores).
 
P: Si ya se ha cifrado un dispositivo con BitLocker mediante la configuración predeterminada del sistema operativo para el método de cifrado y la seguridad de cifrado (XTS-AES-128), se aplicará una directiva con una configuración diferente para activar de nuevo el cifrado de la unidad con la nueva configuración.<br>
R: No. Para aplicar la nueva configuración de cifrado, primero debe descifrarse la unidad.<br><br>
**Nota:** Para los dispositivos que se inscriben con AutoPilot, el cifrado automático que se produciría durante la OOBE no se desencadena hasta que se evalúe la Directiva de Intune, lo que permite usar la configuración basada en directivas en lugar de los valores predeterminados del sistema operativo.
 
P: Si un dispositivo está cifrado como resultado de la aplicación de la Directiva de Intune, ¿se descifrará cuando se quite la Directiva?<br>
A: la eliminación de la Directiva relacionada con el cifrado no produce el descifrado de las unidades configuradas.
 
P: ¿por qué la Directiva de cumplimiento de Intune muestra que el dispositivo no tiene BitLocker habilitado, aunque es?<br>
A: el valor "BitLocker Enabled" de la Directiva de cumplimiento de Intune usa el cliente de atestación de estado del dispositivo Windows (DHA). Este cliente solo mide el estado del dispositivo durante el arranque. Por lo tanto, si un dispositivo no se ha reiniciado desde que se completó el cifrado de BitLocker, el servicio de cliente de DHA no informará de BitLocker como activo.
 
 