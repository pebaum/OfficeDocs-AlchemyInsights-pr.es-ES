---
title: Restringir SharePoint Online al modo clásico
ms.author: kirks
author: Techwriter40
ms.date: 3/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6e99da1c-e61d-40ba-855e-1a8f346e42fd
ms.openlocfilehash: 6a7c0497243ef7425917f54815e61f1244838c54
ms.sourcegitcommit: b14aa00b42ce4ca9d7dc3aa1fd57e66eae115447
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/28/2019
ms.locfileid: "30953361"
---
# <a name="restrict-sharepoint-online-to-classic-mode"></a><span data-ttu-id="74733-102">Restringir SharePoint Online al modo clásico</span><span class="sxs-lookup"><span data-stu-id="74733-102">Restrict SharePoint Online to classic mode</span></span>

<span data-ttu-id="74733-103">Algunas organizaciones todavía necesitan la experiencia de modo clásico.</span><span class="sxs-lookup"><span data-stu-id="74733-103">Some organizations still require the Classic mode experience.</span></span> <span data-ttu-id="74733-104">Aunque no hay planes para quitar el modo clásico en un nivel granular, a partir del 1 de abril de 2019, ya no será posible restringir una organización completa (inquilino) al modo clásico para listas y bibliotecas.</span><span class="sxs-lookup"><span data-stu-id="74733-104">While there are no plans to remove classic mode at a granular level, starting April 1,2019, it will no longer be possible to restrict an entire organization (tenant) to classic mode for lists and libraries.</span></span>

<span data-ttu-id="74733-105">El administrador tendrá las siguientes opciones para administrar listas y bibliotecas individuales en modo clásico mediante modificadores de exclusión granulares que proporcionamos en los siguientes niveles:</span><span class="sxs-lookup"><span data-stu-id="74733-105">The admin will have the following options to manage individual lists and libraries in classic mode using granular opt-out switches that we provide at the following levels:</span></span>

<span data-ttu-id="74733-106">--colección de sitios--site--List--Library</span><span class="sxs-lookup"><span data-stu-id="74733-106">-- site collection -- site -- list -- library</span></span>

<span data-ttu-id="74733-107">Además, las listas que usan determinadas características y personalizaciones que no son compatibles con Modern seguirán cambiando automáticamente al modo clásico.</span><span class="sxs-lookup"><span data-stu-id="74733-107">Additionally, lists that use certain features and customizations that are not supported by modern will still be automatically switched to classic mode.</span></span>

<span data-ttu-id="74733-108">Después del 1 de abril, las listas y bibliotecas que están en modo clásico como resultado de la cancelación de inquilino se administrarán automáticamente en el nivel de sitio y de lista.</span><span class="sxs-lookup"><span data-stu-id="74733-108">After April 1, lists and libraries that are in classic mode as a result of tenant opt-out will automatically be managed at the site level and list level.</span></span>

<span data-ttu-id="74733-109">Si necesita el modo clásico, vea aquí más información aquí y las instrucciones de PowerShell de PnP, que describe las opciones y las herramientas que puede usar hoy para prepararse para la eliminación del nivel de inquilino en el 1 de abril.</span><span class="sxs-lookup"><span data-stu-id="74733-109">If you require classic mode please see more information here and PnP Powershell instruction here that describes options and tools you can use today to prepare for the removal of the tenant level opt-out on April 1.</span></span>
