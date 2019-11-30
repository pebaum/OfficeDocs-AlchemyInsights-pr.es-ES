---
title: Solución de aplicaciones de Office no se pudo encontrar el mensaje asociado de licencias de Office
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3421"
- "9001426"
ms.openlocfilehash: 1820cdb83a1adf36b4e7d0898ecdf8097eb6f0f3
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/27/2019
ms.locfileid: "39627935"
---
# <a name="fixing-the-office-apps-couldnt-find-office-licenses-associated-message"></a>Corrección del mensaje "no se pudieron encontrar las licencias de Office asociadas" en las aplicaciones de Office

Si recibe este mensaje, pruebe lo siguiente:

1. Compruebe el firewall, el software antivirus y la configuración de proxy para confirmar que no están bloqueando el acceso a Internet a las aplicaciones de Office. Consulte [Office 365 URL e intervalos de direcciones IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).
2. Quite y [reasigne la licencia de Office](https://docs.microsoft.com/office365/admin/manage/assign-licenses-to-users) para el usuario afectado. 
3. Abra una aplicación de Office y [cierre la sesión](https://support.office.com/article/5a20dc11-47e9-4b6f-945d-478cb6d92071) de las cuentas de usuario existentes.
4. Vaya a configuración de Windows **>** > cuentas de**correo &** cuentas y quite todas las cuentas de trabajo excepto la cuenta afectada.
5. Vaya a configuración de Windows > **cuentas** > **tienen acceso a trabajo o escuela**y desconectan todas las cuentas de trabajo, excepto la cuenta afectada.
6. Restablezca el estado de activación de Office. [Obtenga más información](https://docs.microsoft.com/office365/troubleshoot/activation/reset-office-365-proplus-activation-state).
7. [Inicie sesión](https://support.office.com/article/628ea040-f265-49de-b986-be09c3ebf8a9) con la cuenta de usuario afectada.

Para obtener soluciones adicionales para la solución de problemas, consulte [errores de activación y de producto sin licencia en Office](https://support.office.com/Article/0d23d3c0-c19c-4b2f-9845-5344fedc4380).