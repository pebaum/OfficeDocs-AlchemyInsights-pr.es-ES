---
title: Claves de recuperación de BitLocker
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1922"
- "9000220"
ms.openlocfilehash: 4e06e0e43b63836b9e9cf923e554dd474b82c671
ms.sourcegitcommit: 123e9fe46e99719dd271e75a66555861e968f4a2
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/30/2019
ms.locfileid: "40908831"
---
# <a name="accessing-bitlocker-recovery-keys"></a>Obtener acceso a las claves de recuperación de BitLocker

Al configurar la Directiva de la protección de extremos de Intune de configuración de BitLocker, es posible definir si la información de recuperación de BitLocker debe almacenarse en Azure Active Directory.

Si esta configuración está configurada, los datos de recuperación almacenados deben estar visibles para un administrador de Intune como parte de los datos de registro de dispositivo en la hoja dispositivos de Intune de dos maneras:

Dispositivos: dispositivos de Azure AD-> "dispositivo" o dispositivos-> todos los dispositivos-> "dispositivo"-> claves de recuperación

Como alternativa, si hay acceso administrativo al propio dispositivo, se puede ver la clave de recuperación (contraseña) mediante la ejecución del siguiente comando desde un símbolo del sistema con privilegios elevados:

```
manage-bde -protectors c: -get
Example
Volume C: []
All Key Protectors
    TPM:
      ID: {8A5D13D6-7ED9-46C8-A74F-AC3ADF016EC8}
      PCR Validation Profile:
        0, 2, 4, 8, 9, 10, 11
    Numerical Password:
      ID: {DFA26333-XXXX-402C-YYYY-A8C40AF3ZZZZ}
      Password:
        393943-22222-281721-555554-577984-77777-194700-99999
```
Si el dispositivo se cifró antes de la inscripción en Intune, es posible que la clave de recuperación se haya asociado con la "cuenta Microsoft" (MSA) que se usó para iniciar sesión en el dispositivo durante el proceso OOBE. Si este es el caso, el acceso https://onedrive.live.com/recoverykey e inicio de sesión con ese MSA debería mostrar los dispositivos para los que se almacenaron claves de recuperación.
 
Si el dispositivo se cifró como resultado de la configuración mediante una directiva de grupo basada en dominio, la información de recuperación puede almacenarse en Active Directory local.
 

