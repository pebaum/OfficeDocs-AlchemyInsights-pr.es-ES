---
title: Solo lectura para el mensaje de mantenimiento al intentar usar SharePoint o OneDrive
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "127"
- "128"
ms.assetid: de7b6877-f3f9-4402-8072-c73783aaccaa
ms.openlocfilehash: 02cf1aa7abae365a3d317af9e785648d1c1517e1
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/15/2019
ms.locfileid: "40051298"
---
# <a name="read-only-for-maintenance-message-when-attempting-to-use-sharepoint-or-onedrive"></a>Solo lectura para el mensaje de mantenimiento al intentar usar SharePoint o OneDrive

Los usuarios pueden recibir un mensaje **de solo lectura para** el mensaje de mantenimiento al intentar usar SharePoint o OneDrive para uno de los siguientes escenarios. 

-   Una actividad de mantenimiento planificado o activo.  Para buscarlos, navegue hasta el [centro de mensajes](https://portal.office.com/adminportal/home#/messagecenter).
-   Un incidente de servicio activo de alta prioridad que pueda estar ocurriendo. Compruebe si hay algún asesor o incidente desplazándose al [Estado del servicio](https://portal.office.com/adminportal/home#/servicehealth).
-   Un escenario de recuperación de recuperación automática secundaria que podría estar ocurriendo debido a eventos inesperados en los servidores que pueden durar menos de 30 minutos o más. 
    
    No existen publicaciones de estado del servicio o del centro de mensajes para estas recuperaciones menores, pero debe volver a ser normal muy pronto.

En muy pocas ocasiones observamos que uno de los tres escenarios enumerados anteriormente ha sido la causa y que se ha restaurado el servicio, pero la memoria caché del explorador de usuarios no se ha borrado.

Intente borrar la memoria caché del explorador antes de navegar al sitio.

1. En el explorador de Microsoft Edge, selecciona **configuración**y, a continuación, haz clic en **privacidad y seguridad**.
2. En **borrar la búsqueda**, seleccione **elegir lo que desea borrar**.
3. Seleccione **cookies y datos del sitio web guardados**y seleccione **Borrar**.

>[!Note] 
> Estos pasos pueden variar cuando se usan otros exploradores como Mozilla Firefox o Google Chrome.

>[!Note] 
> Otra opción sería abrir el sitio de SharePoint o OneDrive en una nueva ventana de InPrivate.