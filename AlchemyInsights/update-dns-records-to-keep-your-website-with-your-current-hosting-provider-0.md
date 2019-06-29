---
title: Actualizar registros DNS para conservar su sitio web con su proveedor de hospedaje actual
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "42"
- "43"
- "100002"
ms.assetid: 48251355-7383-4fdc-a1e1-9dc2c85a8d29
ms.openlocfilehash: 62f49038cf541c2185ed6a60c6cb58fe2889342d
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/28/2019
ms.locfileid: "35353194"
---
# <a name="update-dns-records-to-keep-your-website-with-your-current-hosting-provider"></a>Actualizar registros DNS para conservar su sitio web con su proveedor de hospedaje actual

1. En la página [Dominios](https://portal.office.com/adminportal/home#/Domains), en la lista de dominios, seleccione el que use para su sitio web y, después, **Configuración de DNS** en el panel de administración.

2. Seleccione **Nuevo registro personalizado** y escriba lo siguiente:

  - Como **Tipo DNS**, escriba " **D (Dirección)** ".

  - Como **Nombre de host o alias**, escriba " **@** ".

  - Como **Dirección IP**, escriba la dirección IP estática en la que se hospeda actualmente su sitio web (por ejemplo: 172.16.140.1).

    Esta dirección IP debe ser  *estática*  , no puede ser  *dinámica*  . Consulte al proveedor donde se hospeda el sitio web para asegurarse de que puede obtener una dirección IP estática para su sitio web público.

3. Seleccione **Guardar**.

Además, puede crear un registro CNAME para ayudar a los clientes a encontrar su sitio web.
  
1. Seleccione **Nuevo registro personalizado** y escriba lo siguiente:

  - Como **Tipo DNS**, escriba " **CNAME (Alias)** ".

  - Como **Nombre de host o alias**, escriba " **www** ".

  - Como **Dirección de destino**, escriba el FQDN (nombre de dominio completo) de su sitio web (por ejemplo, contoso.com).

2. Haga clic en **Guardar**.
