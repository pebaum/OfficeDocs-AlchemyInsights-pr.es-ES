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
ms.custom:
- "1835"
- "1889"
- "9000225"
ms.openlocfilehash: e7ecfd8c2f1a532355bfb8c2c0a846fc0d6e88b1
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36551576"
---
# <a name="restrict-sharepoint-online-to-classic-mode"></a><span data-ttu-id="16a92-102">Restringir SharePoint Online al modo clásico</span><span class="sxs-lookup"><span data-stu-id="16a92-102">Restrict SharePoint Online to classic mode</span></span>

<span data-ttu-id="16a92-103">Algunas organizaciones todavía necesitan la experiencia de modo clásico.</span><span class="sxs-lookup"><span data-stu-id="16a92-103">Some organizations still require the Classic mode experience.</span></span> <span data-ttu-id="16a92-104">Aunque no hay planes para quitar el modo clásico en un nivel granular, ya no es posible restringir una organización completa (inquilino) al modo clásico para listas y bibliotecas.</span><span class="sxs-lookup"><span data-stu-id="16a92-104">While there are no plans to remove classic mode at a granular level, it is no longer possible to restrict an entire organization (tenant) to classic mode for lists and libraries.</span></span>

<span data-ttu-id="16a92-105">El administrador tendrá las siguientes opciones para administrar listas y bibliotecas individuales en modo clásico mediante modificadores de exclusión granulares que proporcionamos en los siguientes niveles:</span><span class="sxs-lookup"><span data-stu-id="16a92-105">The admin will have the following options to manage individual lists and libraries in classic mode using granular opt-out switches that we provide at the following levels:</span></span>

- <span data-ttu-id="16a92-106">colección de sitios</span><span class="sxs-lookup"><span data-stu-id="16a92-106">site collection</span></span>
- <span data-ttu-id="16a92-107">emplaza</span><span class="sxs-lookup"><span data-stu-id="16a92-107">site</span></span>
- <span data-ttu-id="16a92-108">lista</span><span class="sxs-lookup"><span data-stu-id="16a92-108">list</span></span>
- <span data-ttu-id="16a92-109">Biblioteca</span><span class="sxs-lookup"><span data-stu-id="16a92-109">library</span></span>

<span data-ttu-id="16a92-110">Además, las listas que usan determinadas características y personalizaciones que no son compatibles con Modern seguirán cambiando automáticamente al modo clásico.</span><span class="sxs-lookup"><span data-stu-id="16a92-110">Additionally, lists that use certain features and customizations that are not supported by modern will still be automatically switched to classic mode.</span></span>

<span data-ttu-id="16a92-111">A partir del 1 de abril de 2019, el proceso para deshabilitar el nivel de inquilino no participar en la lista y las bibliotecas modernas se iniciará y continuará hasta el 31 de mayo de 2019.</span><span class="sxs-lookup"><span data-stu-id="16a92-111">Beginning April 1, 2019, the process to disable the tenant level opt out of modern list and libraries will start and continue through May 31, 2019.</span></span>  <span data-ttu-id="16a92-112">Las listas y bibliotecas que se encuentran en modo clásico como resultado de la cancelación de inquilino se desplazarán automáticamente a moderna.</span><span class="sxs-lookup"><span data-stu-id="16a92-112">The lists and libraries that are in classic mode as a result of tenant opt-out will automatically be shifted to modern.</span></span>

<span data-ttu-id="16a92-113">Si necesita el modo clásico, vea [aquí](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries-optout) más información [aquí](https://techcommunity.microsoft.com/t5/Microsoft-SharePoint-Blog/Delivering-SharePoint-modern-experiences/ba-p/315023) y instrucciones de PowerShell PNP que describe las opciones y las herramientas que puede usar hoy para usar la experiencia de modo clásico.</span><span class="sxs-lookup"><span data-stu-id="16a92-113">If you require classic mode please see more information [here](https://techcommunity.microsoft.com/t5/Microsoft-SharePoint-Blog/Delivering-SharePoint-modern-experiences/ba-p/315023) and PnP Powershell instruction [here](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries-optout) that describes options and tools you can use today to use the classic mode experience.</span></span>
