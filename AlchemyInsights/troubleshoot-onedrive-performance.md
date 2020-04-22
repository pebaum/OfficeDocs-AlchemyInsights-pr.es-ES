---
title: Solucionar problemas de rendimiento de OneDrive
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1977"
- "9000343"
ms.openlocfilehash: 197a84c5f69f9e58460925049345263743fe78ee
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43733215"
---
# <a name="troubleshoot-onedrive-performance"></a><span data-ttu-id="3b28b-102">Solucionar problemas de rendimiento de OneDrive</span><span class="sxs-lookup"><span data-stu-id="3b28b-102">Troubleshoot OneDrive performance</span></span>

<span data-ttu-id="3b28b-103">Si está experimentando una sincronización más lenta que la esperada o problemas de rendimiento similares con OneDrive:</span><span class="sxs-lookup"><span data-stu-id="3b28b-103">If you’re experiencing a slower than expected sync, or similar performance issues with OneDrive:</span></span>

- <span data-ttu-id="3b28b-104">Confirme que no hay problemas conocidos al usar el [Panel de estado del servicio](https://portal.office.com/adminportal/home?ref=/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="3b28b-104">Confirm there are no known issues using the [Service Health Dashboard](https://portal.office.com/adminportal/home?ref=/servicehealth).</span></span>

- <span data-ttu-id="3b28b-105">[Habilite los archivos a petición](https://support.office.com/article/save-disk-space-with-onedrive-files-on-demand-for-windows-10-0e6860d3-d9f3-4971-b321-7092438fb38e) para poder acceder a todos los archivos en OneDrive sin tener que descargarlos todos y usar espacio de almacenamiento en el dispositivo.</span><span class="sxs-lookup"><span data-stu-id="3b28b-105">[Enable Files On Demand](https://support.office.com/article/save-disk-space-with-onedrive-files-on-demand-for-windows-10-0e6860d3-d9f3-4971-b321-7092438fb38e) so that you can access all your files in OneDrive without having to download all of them and use storage space on your device.</span></span>

- <span data-ttu-id="3b28b-106">[Revise los procedimientos recomendados](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance) para la planeación y el rendimiento de la red.</span><span class="sxs-lookup"><span data-stu-id="3b28b-106">[Review best practices](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance) for network planning and performance.</span></span>

- <span data-ttu-id="3b28b-107">[Maximice la velocidad de carga y descarga](https://support.office.com/article/maximize-upload-and-download-speed-8eeadfb8-501f-406d-997b-98ab6ff67f43), especialmente si está sincronizando un dispositivo por primera vez.</span><span class="sxs-lookup"><span data-stu-id="3b28b-107">[Maximize upload and download speed](https://support.office.com/article/maximize-upload-and-download-speed-8eeadfb8-501f-406d-997b-98ab6ff67f43), especially if you’re syncing a device for the first time.</span></span>

- <span data-ttu-id="3b28b-108">Si está sincronizando una biblioteca con más de 100.000 elementos, puede parecer que la sincronización de OneDrive se ha bloqueado durante mucho tiempo, o el estado muestra el procesamiento de 0KB de xMB ".</span><span class="sxs-lookup"><span data-stu-id="3b28b-108">If you’re syncing a library with more than 100,000 items, OneDrive sync may seem stuck for a long time, or the status shows Processing 0KB of xMB."</span></span> <span data-ttu-id="3b28b-109">[Obtenga más información sobre cómo sincronizar más de 100.000 archivos](https://support.office.com/article/invalid-file-names-and-file-types-in-onedrive-onedrive-for-business-and-sharepoint-64883a5d-228e-48f5-b3d2-eb39e07630fa) , así como el [límite admitido por OneDrive de 300.000 archivos](https://support.office.com/article/invalid-file-names-and-file-types-in-onedrive-onedrive-for-business-and-sharepoint-64883a5d-228e-48f5-b3d2-eb39e07630fa).</span><span class="sxs-lookup"><span data-stu-id="3b28b-109">[Learn more about syncing more than 100,000 files](https://support.office.com/article/invalid-file-names-and-file-types-in-onedrive-onedrive-for-business-and-sharepoint-64883a5d-228e-48f5-b3d2-eb39e07630fa) as well as [OneDrive’s supported limit of 300,000 files](https://support.office.com/article/invalid-file-names-and-file-types-in-onedrive-onedrive-for-business-and-sharepoint-64883a5d-228e-48f5-b3d2-eb39e07630fa).</span></span>

- <span data-ttu-id="3b28b-p102">Cuando un usuario supera los límites de uso, SharePoint Online las limitaciones de las solicitudes sucesivas de esa cuenta de usuario durante un breve período. Se limita a todas las acciones de usuario mientras el acelerador está activada.</span><span class="sxs-lookup"><span data-stu-id="3b28b-p102">When a user exceeds usage limits, SharePoint Online throttles any further requests from that user account for a short period. All user actions are throttled while the throttle is in effect.</span></span>
