---
title: Cambiar el sitio raíz clásico por un sitio moderno
ms.author: efrene
author: efrene
ms.date: 8/6/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: ''
ms.custom:
- "9000687"
- "2579"
ms.openlocfilehash: bd477d90ab7e6737aafffc57d931aad2bd0351e8
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2019
ms.locfileid: "36749277"
---
# <a name="swap-your-classic-root-site-with-a-modern-site"></a><span data-ttu-id="373ed-102">Cambiar el sitio raíz clásico por un sitio moderno</span><span class="sxs-lookup"><span data-stu-id="373ed-102">Swap your Classic root site with a Modern site</span></span>

<span data-ttu-id="373ed-103">Si el entorno se configuró antes del 2019 de abril, puede cambiar el sitio raíz a un sitio moderno mediante PowerShell de Microsoft:</span><span class="sxs-lookup"><span data-stu-id="373ed-103">If your environment was set up before April 2019, you can change your root site to a modern site by using Microsoft PowerShell:</span></span>

- <span data-ttu-id="373ed-104">Si tiene un sitio diferente que desea usar como sitio raíz, puede reemplazar [(intercambiar) el sitio raíz](https://docs.microsoft.com/sharepoint/modern-root-site) con él.</span><span class="sxs-lookup"><span data-stu-id="373ed-104">If you have a different site that you want to use as your root site, you can replace [(swap) the root site](https://docs.microsoft.com/sharepoint/modern-root-site) with it.</span></span> 
    - <span data-ttu-id="373ed-105">Use [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) para intercambiar la ubicación de un sitio con otro sitio mientras archiva el sitio original.</span><span class="sxs-lookup"><span data-stu-id="373ed-105">Use [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) to swap the location of a site with another site while archiving the original site.</span></span> <span data-ttu-id="373ed-106">Disponible tanto para el sitio de grupo (no conectado a un grupo) como para el sitio de comunicación.</span><span class="sxs-lookup"><span data-stu-id="373ed-106">Available for both Team Site (not connected to a group) and Communication Site.</span></span> 

- <span data-ttu-id="373ed-107">Se presentarán funciones adicionales próximamente que le permitirán seguir usando el contenido en el sitio, pero convertir el sitio existente en un sitio de comunicación.</span><span class="sxs-lookup"><span data-stu-id="373ed-107">Additional capabilities will be introduced soon that will allow you to keep using the content on the site, but convert the existing site to a communication site.</span></span> 
>[!Important]
><span data-ttu-id="373ed-108">Estas funciones se implementarán gradualmente.</span><span class="sxs-lookup"><span data-stu-id="373ed-108">These capabilities will be rolled out gradually.</span></span> <span data-ttu-id="373ed-109">Continúe con la comprobación del centro de mensajes de Office 365 para obtener actualizaciones.</span><span class="sxs-lookup"><span data-stu-id="373ed-109">Continue to check the Office 365 Message Center for updates.</span></span> 

## <a name="known-issues-with-swapping-sites"></a><span data-ttu-id="373ed-110">Problemas conocidos con el intercambio de sitios</span><span class="sxs-lookup"><span data-stu-id="373ed-110">Known issues with swapping sites</span></span>

- <span data-ttu-id="373ed-111">El sitio de destino puede devolver un error "no se encontró" (HTTP 404) durante un breve período de tiempo.</span><span class="sxs-lookup"><span data-stu-id="373ed-111">The target site may return a "not found" (HTTP 404) error for a short period of time.</span></span>
- <span data-ttu-id="373ed-112">Será necesario volver a rastrear el contenido para actualizar el índice de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="373ed-112">Content will need to be recrawled to update the search index.</span></span> <span data-ttu-id="373ed-113">No es necesario ningún paso manual; esto se realizará automáticamente.</span><span class="sxs-lookup"><span data-stu-id="373ed-113">There is no manual step required - this will be done automatically.</span></span>
- <span data-ttu-id="373ed-114">Todo lo que dependa de los vínculos "estáticos" (como los archivos de OneNote y la sincronización de archivos) deberá corregirse manualmente.</span><span class="sxs-lookup"><span data-stu-id="373ed-114">Anything dependent on "static" links (such as File Sync and OneNote files) will need to be manually corrected.</span></span>
- <span data-ttu-id="373ed-115">Si el sitio de origen era un sitio de noticias de la organización, actualice la dirección URL.</span><span class="sxs-lookup"><span data-stu-id="373ed-115">If the source site was an organizational news site, update the URL.</span></span><span data-ttu-id="373ed-116">Obtenga una lista de todos los sitios de noticias de la organización.</span><span class="sxs-lookup"><span data-stu-id="373ed-116"> Get a list of all organizational news sites.</span></span>
- <span data-ttu-id="373ed-117">Es posible que sea necesario validar los sitios de Project Server para asegurarse de que siguen asociados correctamente.</span><span class="sxs-lookup"><span data-stu-id="373ed-117">Project Server sites may need to be validated to ensure that they are still associated correctly.</span></span>





