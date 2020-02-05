---
title: Retrasos en la recepción de alertas de SharePoint y OneDrive
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 02/04/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "2642"
ms.openlocfilehash: 0bc9f614047e06e8654a9b3ff64e87427f33139f
ms.sourcegitcommit: 317eeed39c7777a922442992d67733726c41d9e1
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/04/2020
ms.locfileid: "41771232"
---
# <a name="delays-in-receiving-sharepoint-and-onedrive-alerts"></a>Retrasos en la recepción de alertas de SharePoint y OneDrive

- Compruebe primero la carpeta de correo no deseado o no deseado en el correo electrónico.
- Si **se retrasan todas las alertas de varios archivos o bibliotecas**, visite el [Panel de estado del servicio](https://nam06.safelinks.protection.outlook.com/?url=https://admin.microsoft.com/AdminPortal/Home%23/servicehealth&data=02%7c01%7cv-todmc%40microsoft.com%7c2cd2037aa7304711d2bc08d741fae254%7c72f988bf86f141af91ab2d7cd011db47%7c1%7c0%7c637050418099632638&sdata=35FUOTleK0Sc0z%2B7N7Vm0tOgXplyeOe3LcIzqRziGXc%3D&reserved=0) para comprobar si hay algún asesor o incidente que pueda estar ocurriendo con SharePoint o Exchange. El problema puede deberse a la capacidad de alerta de SharePoint o a los retrasos en los correos electrónicos a través de Exchange. Además, tenga en cuenta si se está entregando otro correo electrónico (si no es así, es probable que el problema se produzca con retrasos de Exchange).
- Si **no se entrega una alerta individual de un archivo o biblioteca específicos**, intente eliminarla y volver a crearla. Consulte [administrar, ver o eliminar alertas de SharePoint](https://nam06.safelinks.protection.outlook.com/?url=https://support.office.com/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2?ui%3Den-US%26rs%3D%26ad%3DUS%23ID0EAADAAA%3DOnline&data=02%7c01%7cv-todmc%40microsoft.com%7c2cd2037aa7304711d2bc08d741fae254%7c72f988bf86f141af91ab2d7cd011db47%7c1%7c0%7c637050418099632638&sdata=AkE%2BjiG6%2BA59llp2DGcg4uHHUjaUDUnAlK5ax/epn3E%3D&reserved=0) para volver a crear la alerta.

> [!NOTE]
> - No se pueden enviar alertas a un grupo de distribución. Solo se admiten los grupos de seguridad y de O365.
> - No puede personalizar las plantillas de correo electrónico de alerta. Debe usar el flujo de trabajo de Microsoft Flow o SharePoint Designer para conseguirlos.
