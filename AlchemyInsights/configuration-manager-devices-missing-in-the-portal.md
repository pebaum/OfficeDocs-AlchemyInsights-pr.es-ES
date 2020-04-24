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
# <a name="configuration-manager-devices-missing-in-the-portal"></a><span data-ttu-id="2b7e4-102">Faltan dispositivos de Configuration Manager en el portal</span><span class="sxs-lookup"><span data-stu-id="2b7e4-102">Configuration Manager devices missing in the portal</span></span>

<span data-ttu-id="2b7e4-103">Para que funcione la sincronización de dispositivos, debe poder accederse a los [puntos de conexión de Internet necesarios](https://docs.microsoft.com/configmgr/tenant-attach/device-sync-actions#internet-endpoints) desde el servidor local que hospeda el rol de punto de conexión de servicio.</span><span class="sxs-lookup"><span data-stu-id="2b7e4-103">For device sync to work, [required internet endpoints](https://docs.microsoft.com/configmgr/tenant-attach/device-sync-actions#internet-endpoints) must be reachable from the on-premise server hosting the Service Connection Point role.</span></span> <span data-ttu-id="2b7e4-104">Para solucionar problemas de sincronización de dispositivos, revise el archivo **CMGatewaySyncUploadWorker.log** que encontrará en el punto de conexión de servicio.</span><span class="sxs-lookup"><span data-stu-id="2b7e4-104">To troubleshoot device sync, please review the **CMGatewaySyncUploadWorker.log** located on the service connection point.</span></span>

<span data-ttu-id="2b7e4-105">Obtenga más información sobre la [asociación de inquilinos en Microsoft Endpoint Manager](https://docs.microsoft.com/configmgr/tenant-attach/).</span><span class="sxs-lookup"><span data-stu-id="2b7e4-105">Learn more about [Tenant attach in Microsoft Endpoint Manager](https://docs.microsoft.com/configmgr/tenant-attach/).</span></span>
