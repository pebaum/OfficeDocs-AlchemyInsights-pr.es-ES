---
title: Faltan términos en el almacén de términos de SharePoint Online
ms.author: pebaum
author: pebaum
ms.date: 10/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1243"
- "5200021"
ms.openlocfilehash: 28913b8e57e39d51e8957b7408c19337a119c589
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/15/2019
ms.locfileid: "40053530"
---
# <a name="enabling-bitlocker-encryption-with-intune"></a>Habilitación del cifrado de BitLocker con Intune

La Directiva de Intune Endpoint Protection se puede usar para establecer la configuración de cifrado de Boitlocker para dispositivos Windows como se describe en: Windows10 (y versiones posteriores) configuración para proteger dispositivos con Intune

Debe tener en cuenta que muchos dispositivos nuevos que ejecutan Windows 10 admiten el cifrado de BitLocker automático que se desencadena sin la aplicación de la Directiva de MDM. Esto puede afectar a la aplicación de la Directiva si se configuran las opciones no predeterminadas. Consulte las preguntas más frecuentes para obtener más información.


P  + f p: ¿Qué ediciones de Windows admiten el cifrado de dispositivos con la Directiva de Endpoint Protection?
 A: la configuración de la Directiva de la protección de extremos de Intune se implementa con el CSP de BitLocker.No todas las ediciones ni las compilaciones de Windows admiten el CSP de BitLocker. 
      En este momento, ediciones de Windows: Enterprise; Se admiten educación, móvil, Mobile Enterprise y Professional (desde la compilación 1809 en adelante).




P: Si ya se ha cifrado un dispositivo con BitLocker mediante la configuración predeterminada del sistema operativo para el método de cifrado y la seguridad de cifrado (XTS-AES-128), se aplicará una directiva con una configuración diferente para activar automáticamente el recifrado de la unidad con la nueva configuración.

R: No. Para aplicar la nueva configuración de cifrado es necesario descifrar primero la unidad.

Nota para que los dispositivos se inscriban con la prueba piloto automática, el cifrado automático que se produciría durante la OOBE no se desencadena hasta que se evalúe la Directiva de Intune, lo que permite usar la configuración basada en directivas en lugar de los valores predeterminados del sistema operativo




P si un dispositivo está cifrado como resultado de la aplicación de la Directiva de Intune, ¿se descifrará cuando se elimine la Directiva?

A: la eliminación de la Directiva relacionada con el cifrado no produce el descifrado de las unidades configuradas.




P: ¿por qué la Directiva de cumplimiento de Intune muestra que el dispositivo no tiene "BitLocker habilitado", pero sí?

A: el valor "BitLocker Enabled" de la Directiva de cumplimiento de Intune usa el cliente de atestación de estado del dispositivo Windows (DHA). Este cliente solo mide el estado del dispositivo durante el arranque. Por lo tanto, si un dispositivo no se reinició desde que se completó el cifrado de BitLocker, el servicio de cliente de DHA no informará de BitLocker como activo.