---
title: Listas grandes de SharePoint
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 2/12/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "407"
- "530001"
ms.assetid: ee07bf74-7aeb-4c47-8f5d-f496d6c09d79
ms.openlocfilehash: 222ad554de0d94dcfd4e34e9a2c6aa8ab4e6f81f
ms.sourcegitcommit: d7e1b097d3866782f508527c797426dc56c6ba17
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/14/2019
ms.locfileid: "37488534"
---
# <a name="work-with-large-lists-and-libraries-in-sharepoint"></a>Trabajar con listas y bibliotecas de gran tamaño en SharePoint

Las listas y bibliotecas de SharePoint pueden contener hasta 30 millones elementos, pero cuando tienen más de 5.000 elementos, es posible que vea un error de umbral de vista de lista cuando intente trabajar con ellos. Este umbral está en su ubicación para mantener el rendimiento del servicio. No se puede cambiar. Para evitar tener que golpear este umbral:

**Usar moderna**

Las vistas que muestran muchos elementos funcionan mejor en la experiencia moderna. [Use la experiencia moderna](https://support.office.com/article/66dac24b-4177-4775-bf50-3d267318caa9) para evitar errores que pueda ver en la experiencia clásica.

**Agregar índices**

Cuando filtra u ordena por una columna que no tiene un índice, es posible que vea un mensaje de error. [Agregue un índice](https://support.office.com/article/f3f00554-b7dc-44d1-a2ed-d477eac463b0) manualmente desde **configuración** de la lista en el menú configuración y, a continuación, **columnas indizadas**.

**Editar la vista de lista**

Si se produce un error al trabajar con una lista de gran tamaño, [modifique la vista de la lista](https://support.office.com/article/15916903-e79a-423f-b4e2-02d37e1ff372).

Los siguientes cuatro cambios eliminarán los errores de umbral de vista de lista. Realice los cuatro cambios para quitar todos los errores. Si sigue recibiendo errores, compruebe [administrar listas y bibliotecas de gran tamaño](https://support.office.com/article/B8588DAE-9387-48C2-9248-C24122F07C59).

1. Seleccione **ninguno** de **la primera clasificación por la columna** y **, a continuación, ordene por la columna**.
2. Seleccione **ninguno** en **el primer grupo de la columna** y **, a continuación, en agrupar por la columna**.
3. Seleccione **ninguna** en todas las columnas de la sección **totales** .
4. Anule la selección de todas menos una columna para mostrar en la sección **columnas** .

