---
title: 'Problema de activación: no se puede conectar ahora'
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3408"
- "9001423"
ms.openlocfilehash: 84e3a7700558ad8a5fad5b7ded6354fe8736e0f7
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/27/2019
ms.locfileid: "39628259"
---
# <a name="fixing-the-office-apps-we-are-unable-to-connect-right-now-message"></a>Corrección del mensaje "no se puede conectar ahora de las aplicaciones de Office"

Si recibe este mensaje, pruebe lo siguiente:

1. Compruebe el firewall, el software antivirus y la configuración de proxy para confirmar que no están bloqueando el acceso a Internet a las aplicaciones de Office. Consulte [Office 365 URL e intervalos de direcciones IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).

2. Vaya a **Inicio** > **Ejecutar**y, a continuación, escriba **Services. msc**. Asegúrese de que se están ejecutando todos los servicios siguientes:
    - Configuración automática de dispositivos conectados a la red
    - Servicio de lista de redes
    - Reconocimiento de ubicación de red
    - Registro de eventos de Windows

Si uno de estos servicios no se está ejecutando, intente iniciarlo. Si tiene un problema para iniciar el servicio, ejecute el siguiente comando abriendo un símbolo del sistema con permisos elevados:

**SFC/scannow**

Una vez finalizado este comando, reinicie el equipo.

Para obtener información detallada, consulte ["lo sentimos, no podemos conectarnos a su cuenta. Intente de nuevo más tarde "al activar Office desde Office 365](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).