---
title: Simulador de ataque de 2681 en Office 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2681"
ms.assetid: ''
ms.openlocfilehash: 07d7622c00074f7bd0d567185824db448f1eeef3
ms.sourcegitcommit: 7232b48bcd8bb9867d52a2f055a46ce76a58b8da
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/27/2019
ms.locfileid: "37305348"
---
# <a name="attack-simulator-in-office-365"></a>Simulador de ataques en Office 365

- ¿Falta el simulador de ataque? El simulador de ataque requiere el **plan 2 de la protección contra amenazas avanzada de office 365 (ATP plan 2)** u **Office 365 Enterprise E5**. El simulador de ataques **no** se incluye en el plan 1 de la protección contra amenazas avanzada de Office 365 (ATP plan 1), Office 365 Enterprise E3 o cualquier suscripción a Office 365 Business.

- La cuenta que use para iniciar ataques simulados requiere permisos de administrador global o de administrador de seguridad y autenticación multifactor (MFA). Para obtener más información acerca de los requisitos de los simuladores de ataques, vea [este tema](https://docs.microsoft.com/office365/securitycompliance/attack-simulator#before-you-begin).

- Aspectos importantes que debe conocer sobre las simulaciones de ataque de **fuerza de contraseña** :

  - Si la cuenta de destino tiene MFA habilitado y la contraseña se ha adivinado correctamente, la cuenta no se mostrará como comprometida (el segundo factor de autenticación será incompleto).

  - El archivo de contraseña no puede tener más de 10 MB. Use una contraseña por línea e incluya una línea en blanco (retorno de carro) después de la última contraseña de la lista.

- Aspectos importantes que debe conocer sobre las simulaciones de conexión de **"Spear phishing"** :

  - Por diseño, no puede proporcionar un valor personalizado para la **dirección URL del servidor de inicio de sesión de suplantación de identidad**.

  - Si un destinatario usa el [complemento habilitar el mensaje de informe](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) para informar del mensaje como suplantación de identidad (phishing), es posible que no reciba alertas del mensaje (ya que se trata de un ataque simulado).

- Informes: una vez completado el ataque simulado, puede hacer clic en detalles de los **ataques** para ver el informe.

- Para obtener instrucciones detalladas y nuevas características en el simulador de ataques, vea [simulador de ataques en Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).
