---
title: Sitio moderno como sitio raíz
ms.author: efrene
author: efrene
ms.audience: ITPro
ms.topic: article
ms.date: 8/7/2019
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000265"
- "1874"
ms.openlocfilehash: 2f75f1e60af06da47fe846e84bbb370dd60084e9
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36543870"
---
# <a name="modern-site-as-root-site"></a><span data-ttu-id="434ed-102">Sitio moderno como sitio raíz</span><span class="sxs-lookup"><span data-stu-id="434ed-102">Modern site as root site</span></span>

<span data-ttu-id="434ed-103">Hemos empezado a distribuir una nueva característica que le permitirá intercambiar el sitio de raíz del sitio clásico con un sitio moderno.</span><span class="sxs-lookup"><span data-stu-id="434ed-103">We have begun to rollout a new feature that will allow you to swap your classic site root site with a modern site.</span></span> <span data-ttu-id="434ed-104">Use [Invoke-SPSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) para intercambiar la ubicación de un sitio con otro sitio mientras archiva el sitio original.</span><span class="sxs-lookup"><span data-stu-id="434ed-104">Use [Invoke-SPSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) to swap the location of a site with another site while archiving the original site.</span></span> <span data-ttu-id="434ed-105">Disponible tanto para el sitio de grupo (no conectado a un grupo) como para el sitio de comunicación.</span><span class="sxs-lookup"><span data-stu-id="434ed-105">Available for both Team Site (not connected to a group) and Communication Site.</span></span> 

>[!Important]
> <span data-ttu-id="434ed-106">No elimine el sitio raíz clásico para crear un sitio de comunicación moderno.</span><span class="sxs-lookup"><span data-stu-id="434ed-106">Do not delete your classic root site to create a modern Communication Site.</span></span> <span data-ttu-id="434ed-107">No es compatible con Microsoft.</span><span class="sxs-lookup"><span data-stu-id="434ed-107">This is not supported by Microsoft.</span></span> <span data-ttu-id="434ed-108">La eliminación del sitio raíz hará que todos los sitios de SharePoint de la organización sean inaccesibles para todos los usuarios, hasta que restaure el sitio o cree un sitio nuevo en la misma dirección URL.</span><span class="sxs-lookup"><span data-stu-id="434ed-108">Deleting the root site will make all SharePoint sites in your organization inaccessible to all users, until you restore the site or create a new site at the same URL.</span></span> <span data-ttu-id="434ed-109">Se comunicará esta característica a través del centro de mensajes.</span><span class="sxs-lookup"><span data-stu-id="434ed-109">We’ll be communicating this feature via the message center.</span></span> <span data-ttu-id="434ed-110">Es de esperar que la característica se active en su espacio empresarial en breve.</span><span class="sxs-lookup"><span data-stu-id="434ed-110">You should expect the feature to be turned on in your tenant shortly.</span></span>

## <a name="known-issues-with-swapping-sites"></a><span data-ttu-id="434ed-111">Problemas conocidos con el intercambio de sitios</span><span class="sxs-lookup"><span data-stu-id="434ed-111">Known issues with swapping sites</span></span>
- <span data-ttu-id="434ed-112">El sitio de destino puede devolver un error "no se encontró" (HTTP 404) durante un breve período de tiempo.</span><span class="sxs-lookup"><span data-stu-id="434ed-112">The target site may return a "not found" (HTTP 404) error for a short period of time.</span></span>
- <span data-ttu-id="434ed-113">Será necesario volver a rastrear el contenido para actualizar el índice de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="434ed-113">Content will need to be recrawled to update the search index.</span></span> <span data-ttu-id="434ed-114">No se requiere ningún paso manual aquí, esto se realizará automáticamente.</span><span class="sxs-lookup"><span data-stu-id="434ed-114">There is no manual step required here, this will be done automatically.</span></span>
- <span data-ttu-id="434ed-115">Todo lo que dependa de los vínculos "estáticos" (como los archivos de OneNote y la sincronización de archivos) deberá corregirse manualmente.</span><span class="sxs-lookup"><span data-stu-id="434ed-115">Anything dependent on "static" links (such as File Sync and OneNote files) will need to be manually corrected.</span></span>
- <span data-ttu-id="434ed-116">Es posible que sea necesario validar los sitios de Project Server para asegurarse de que siguen asociados correctamente.</span><span class="sxs-lookup"><span data-stu-id="434ed-116">Project Server sites may need to be validated to ensure that they are still associated correctly.</span></span> 
