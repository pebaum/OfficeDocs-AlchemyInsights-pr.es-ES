---
title: igual que el nombre de archivo es mejor
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 4/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: 37398436435fb72cb5c8dca2d0798b86a0c8ccc9
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/22/2019
ms.locfileid: "30762081"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a><span data-ttu-id="870a0-102">Falta el encabezado de Alchemy H1, H2's no funciona.</span><span class="sxs-lookup"><span data-stu-id="870a0-102">Required Alchemy Header H1, H2's dont work.</span></span>
<span data-ttu-id="870a0-103">Procedimientos recomendados y directrices para la creación de Alchemy:</span><span class="sxs-lookup"><span data-stu-id="870a0-103">Best Practices and guidelines for Alchemy authoring:</span></span>

1. <span data-ttu-id="870a0-104">**No anide información de Alchemy en las carpetas**: esto interrumpirá la estructura de la dirección URL.</span><span class="sxs-lookup"><span data-stu-id="870a0-104">**Do not nest Alchemy Insights in folders**- this will break the url structure.</span></span> <span data-ttu-id="870a0-105">Estamos intentando solucionar esto.</span><span class="sxs-lookup"><span data-stu-id="870a0-105">We're looking into fixing this.</span></span>
1. <span data-ttu-id="870a0-106">Los archivos de la carpeta **AlchemyInsights** deben tener nombres de archivo en minúsculas con guiones para espacios en blanco por ejemplo.</span><span class="sxs-lookup"><span data-stu-id="870a0-106">Files in the **AlchemyInsights** folder should have lowercase filenames with hyphens for spaces ex.</span></span> <span data-ttu-id="870a0-107">***procedimiento de habilitación: retención por juicio***.</span><span class="sxs-lookup"><span data-stu-id="870a0-107">***how-to-enable-litigation-hold***.</span></span>
    1. <span data-ttu-id="870a0-108">Incluya el identificador de la regla o el identificador del cubo del [portal de socios de Alchemy](https://alchemyportal.azurewebsites.net) en el campo ms. Custom.</span><span class="sxs-lookup"><span data-stu-id="870a0-108">Include the Rule ID or bucket ID from the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) in the ms.custom field.</span></span> <span data-ttu-id="870a0-109">precio.</span><span class="sxs-lookup"><span data-stu-id="870a0-109">ex.</span></span> <span data-ttu-id="870a0-110">***MS. Custom: 100021***</span><span class="sxs-lookup"><span data-stu-id="870a0-110">***ms.custom: 100021***</span></span>
1. <span data-ttu-id="870a0-111">Use el resto de los metadatos en la parte superior de este archivo como plantilla.</span><span class="sxs-lookup"><span data-stu-id="870a0-111">Use the rest of the metadata at the top of this file as your template.</span></span>
1. <span data-ttu-id="870a0-112">En el [portal de socios de Alchemy](https://alchemyportal.azurewebsites.net), desplácese hacia abajo hasta la sección título de la **visión del cliente** y úsela como punto de partida para su título H1 para la visión.</span><span class="sxs-lookup"><span data-stu-id="870a0-112">In the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net), navigate down to the section **Customer Insight Title:** and use that as a starting point for your H1 title for the insight.</span></span> 
    > [!NOTE]
    > <span data-ttu-id="870a0-113">La información de Alchemy solo debe tener un solo H1 en la parte superior o se interrumpirá en producción.</span><span class="sxs-lookup"><span data-stu-id="870a0-113">Alchemy Insights MUST have only a single H1 at the top or they will break in production.</span></span> <span data-ttu-id="870a0-114">H2s no representarlas, use **negrita** u otras convenciones para indicar secciones independientes.</span><span class="sxs-lookup"><span data-stu-id="870a0-114">H2s dont render either so use **bold** or other conventions to signify separate sections.</span></span>
1. <span data-ttu-id="870a0-115">A continuación, rellene el texto del cuerpo con el borrador de material en la sección información del cliente de la página de la regla de Alchemy.</span><span class="sxs-lookup"><span data-stu-id="870a0-115">Next, fill in the body text using the draft material in the Customer Insights section of the Alchemy Rule page</span></span>
    1. <span data-ttu-id="870a0-116">Las listas con viñetas están bien</span><span class="sxs-lookup"><span data-stu-id="870a0-116">Bulleted lists are fine</span></span>
    1. <span data-ttu-id="870a0-117">También las listas numeradas</span><span class="sxs-lookup"><span data-stu-id="870a0-117">Numbered lists too</span></span>
    1. <span data-ttu-id="870a0-118">**Negrita** y *cursiva* son a-OK</span><span class="sxs-lookup"><span data-stu-id="870a0-118">**Bold** and *italic* are a-ok</span></span>
    1. <span data-ttu-id="870a0-119">Los vínculos siempre deben ser **"vínculos a Web"/external** o **vínculos profundos a elementos**de la interfaz de usuario, no a vínculos internos.</span><span class="sxs-lookup"><span data-stu-id="870a0-119">Links should always be either **"links to web"/external** OR **deep-links to UI elements**, not internal links.</span></span>
    1. <span data-ttu-id="870a0-120">Las imágenes no son compatibles oficialmente en este momento, pero se encuentra en la guía básica.</span><span class="sxs-lookup"><span data-stu-id="870a0-120">Pictures are not officially supported at this time, but it's on the roadmap.</span></span>

<span data-ttu-id="870a0-121">Y esto ya es un poco demasiado largo.</span><span class="sxs-lookup"><span data-stu-id="870a0-121">And this is really already a bit too long.</span></span> <span data-ttu-id="870a0-122">El procedimiento recomendado es de unos 400 caracteres---------------------------------</span><span class="sxs-lookup"><span data-stu-id="870a0-122">Best practice is about 400 characters ---------------------------------</span></span>

<span data-ttu-id="870a0-123">Una vez que el contenido esté listo, extráigalo a la rama activa.</span><span class="sxs-lookup"><span data-stu-id="870a0-123">Once your content is ready, pull it to the live branch.</span></span> <span data-ttu-id="870a0-124">A continuación, vaya al [portal de socios de Alchemy](https://alchemyportal.azurewebsites.net) y escriba el nombre de archivo en el campo URL.</span><span class="sxs-lookup"><span data-stu-id="870a0-124">Then, go to the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) and enter the filename into the url field.</span></span> <span data-ttu-id="870a0-125">M</span><span class="sxs-lookup"><span data-stu-id="870a0-125">M</span></span>