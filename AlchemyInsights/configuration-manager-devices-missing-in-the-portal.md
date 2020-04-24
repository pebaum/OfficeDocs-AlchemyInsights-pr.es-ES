---
title: Faltan dispositivos de Configuration Manager en el portal
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001495"
- "4384"
ms.openlocfilehash: 7a11ad3c6970be2c52a7cf0696bd3810b9bd665a
ms.sourcegitcommit: 89ae9e8b36d1980f89f07b016fff0ec48f96b620
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2020
ms.locfileid: "43790234"
---
# <a name="configuration-manager-devices-missing-in-the-portal"></a>Faltan dispositivos de Configuration Manager en el portal

Para que funcione la sincronización de dispositivos, debe poder accederse a los [puntos de conexión de Internet necesarios](https://docs.microsoft.com/configmgr/tenant-attach/device-sync-actions#internet-endpoints) desde el servidor local que hospeda el rol de punto de conexión de servicio. Para solucionar problemas de sincronización de dispositivos, revise el archivo **CMGatewaySyncUploadWorker.log** que encontrará en el punto de conexión de servicio.

Obtenga más información sobre la [asociación de inquilinos en Microsoft Endpoint Manager](https://docs.microsoft.com/configmgr/tenant-attach/).
