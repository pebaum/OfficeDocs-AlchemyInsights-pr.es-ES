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
# <a name="work-with-large-lists-and-libraries-in-sharepoint"></a><span data-ttu-id="baaef-102">Trabajar con listas y bibliotecas de gran tamaño en SharePoint</span><span class="sxs-lookup"><span data-stu-id="baaef-102">Work with large lists and libraries in SharePoint</span></span>

<span data-ttu-id="baaef-103">Las listas y bibliotecas de SharePoint pueden contener hasta 30 millones elementos, pero cuando tienen más de 5.000 elementos, es posible que vea un error de umbral de vista de lista cuando intente trabajar con ellos.</span><span class="sxs-lookup"><span data-stu-id="baaef-103">SharePoint lists and libraries can contain up to 30 million items, but when they have more than 5,000 items, you might see a List View Threshold error when you try to work with them.</span></span> <span data-ttu-id="baaef-104">Este umbral está en su ubicación para mantener el rendimiento del servicio.</span><span class="sxs-lookup"><span data-stu-id="baaef-104">This threshold is in place to maintain performance of the service.</span></span> <span data-ttu-id="baaef-105">No se puede cambiar.</span><span class="sxs-lookup"><span data-stu-id="baaef-105">It can't be changed.</span></span> <span data-ttu-id="baaef-106">Para evitar tener que golpear este umbral:</span><span class="sxs-lookup"><span data-stu-id="baaef-106">To avoid hitting this threshold:</span></span>

<span data-ttu-id="baaef-107">**Usar moderna**</span><span class="sxs-lookup"><span data-stu-id="baaef-107">**Use modern**</span></span>

<span data-ttu-id="baaef-108">Las vistas que muestran muchos elementos funcionan mejor en la experiencia moderna.</span><span class="sxs-lookup"><span data-stu-id="baaef-108">Views showing many items work best in the modern experience.</span></span> <span data-ttu-id="baaef-109">[Use la experiencia moderna](https://support.office.com/article/66dac24b-4177-4775-bf50-3d267318caa9) para evitar errores que pueda ver en la experiencia clásica.</span><span class="sxs-lookup"><span data-stu-id="baaef-109">[Use the modern experience](https://support.office.com/article/66dac24b-4177-4775-bf50-3d267318caa9) to avoid errors you might see in the classic experience.</span></span>

<span data-ttu-id="baaef-110">**Agregar índices**</span><span class="sxs-lookup"><span data-stu-id="baaef-110">**Add indexes**</span></span>

<span data-ttu-id="baaef-111">Cuando filtra u ordena por una columna que no tiene un índice, es posible que vea un mensaje de error.</span><span class="sxs-lookup"><span data-stu-id="baaef-111">When you filter or sort by a column that doesn't have an index, you might see an error message.</span></span> <span data-ttu-id="baaef-112">[Agregue un índice](https://support.office.com/article/f3f00554-b7dc-44d1-a2ed-d477eac463b0) manualmente desde **configuración** de la lista en el menú configuración y, a continuación, **columnas indizadas**.</span><span class="sxs-lookup"><span data-stu-id="baaef-112">[Add an index](https://support.office.com/article/f3f00554-b7dc-44d1-a2ed-d477eac463b0) manually from **List Settings** in the settings menu, then **Indexed Columns**.</span></span>

<span data-ttu-id="baaef-113">**Editar la vista de lista**</span><span class="sxs-lookup"><span data-stu-id="baaef-113">**Edit the list view**</span></span>

<span data-ttu-id="baaef-114">Si se produce un error al trabajar con una lista de gran tamaño, [modifique la vista de la lista](https://support.office.com/article/15916903-e79a-423f-b4e2-02d37e1ff372).</span><span class="sxs-lookup"><span data-stu-id="baaef-114">If an error occurs when working with a large list, [edit your list view](https://support.office.com/article/15916903-e79a-423f-b4e2-02d37e1ff372).</span></span>

<span data-ttu-id="baaef-115">Los siguientes cuatro cambios eliminarán los errores de umbral de vista de lista.</span><span class="sxs-lookup"><span data-stu-id="baaef-115">The following four changes will remove list view threshold errors.</span></span> <span data-ttu-id="baaef-116">Realice los cuatro cambios para quitar todos los errores.</span><span class="sxs-lookup"><span data-stu-id="baaef-116">Make all four changes to remove all errors.</span></span> <span data-ttu-id="baaef-117">Si sigue recibiendo errores, compruebe [administrar listas y bibliotecas de gran tamaño](https://support.office.com/article/B8588DAE-9387-48C2-9248-C24122F07C59).</span><span class="sxs-lookup"><span data-stu-id="baaef-117">If you are still getting errors, check [Manage large lists and libraries](https://support.office.com/article/B8588DAE-9387-48C2-9248-C24122F07C59).</span></span>

1. <span data-ttu-id="baaef-118">Seleccione **ninguno** de **la primera clasificación por la columna** y **, a continuación, ordene por la columna**.</span><span class="sxs-lookup"><span data-stu-id="baaef-118">Select **None** from both **First sort by the column** and **Then sort by the column**.</span></span>
2. <span data-ttu-id="baaef-119">Seleccione **ninguno** en **el primer grupo de la columna** y **, a continuación, en agrupar por la columna**.</span><span class="sxs-lookup"><span data-stu-id="baaef-119">Select **None** from both **First group by the column** and **Then group by the column**.</span></span>
3. <span data-ttu-id="baaef-120">Seleccione **ninguna** en todas las columnas de la sección **totales** .</span><span class="sxs-lookup"><span data-stu-id="baaef-120">Select **None** for all columns in the **Totals** section.</span></span>
4. <span data-ttu-id="baaef-121">Anule la selección de todas menos una columna para mostrar en la sección **columnas** .</span><span class="sxs-lookup"><span data-stu-id="baaef-121">Deselect all but one column for display from the **Columns** section.</span></span>

