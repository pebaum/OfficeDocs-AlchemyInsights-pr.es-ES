---
title: 'igual que FILENAME es mejor [RULE #-deScription]'
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 4/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: e248c2ee3cbb9a86f21c1f36be10c893df76ff52
ms.sourcegitcommit: 3070905131e6d8449981231a3551c0bb4ca38ae6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/14/2019
ms.locfileid: "30634521"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a><span data-ttu-id="0887b-102">Falta el encabezado de Alchemy H1, H2's no funciona.</span><span class="sxs-lookup"><span data-stu-id="0887b-102">Required Alchemy Header H1, H2's dont work.</span></span>
<span data-ttu-id="0887b-103">Procedimientos recomendados y directrices para la creación de Alchemy:</span><span class="sxs-lookup"><span data-stu-id="0887b-103">Best Practices and guidelines for Alchemy authoring:</span></span>

1. <span data-ttu-id="0887b-104">**No anide información de Alchemy en las carpetas**: esto interrumpirá la estructura de la dirección URL.</span><span class="sxs-lookup"><span data-stu-id="0887b-104">**Do not nest Alchemy Insights in folders**- this will break the url structure.</span></span> <span data-ttu-id="0887b-105">Estamos intentando solucionar esto.</span><span class="sxs-lookup"><span data-stu-id="0887b-105">We're looking into fixing this.</span></span>
1. <span data-ttu-id="0887b-106">Los archivos de la carpeta **AlchemyInsights** deben tener el identificador de la regla y el nombre de la regla del [portal de socios de Alchemy](https://alchemyportal.azurewebsites.net) en el nombre del archivo.</span><span class="sxs-lookup"><span data-stu-id="0887b-106">Files in the **AlchemyInsights** folder should have Rule ID and Rule Name from the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) in the filename.</span></span>
    1. <span data-ttu-id="0887b-107">precio.</span><span class="sxs-lookup"><span data-stu-id="0887b-107">ex.</span></span> <span data-ttu-id="0887b-108">***976-procedimiento-habilitado: retención en litigios***</span><span class="sxs-lookup"><span data-stu-id="0887b-108">***976-How-to-enable-litigation-hold***</span></span>
1. <span data-ttu-id="0887b-109">Use los metadatos en la parte superior de este archivo como plantilla.</span><span class="sxs-lookup"><span data-stu-id="0887b-109">Use the metadata at the top of this file as your template.</span></span> <span data-ttu-id="0887b-110">No se requiere ninguna otra cosa.</span><span class="sxs-lookup"><span data-stu-id="0887b-110">Nothing else is required.</span></span>
1. <span data-ttu-id="0887b-111">En el [portal de socios de Alchemy](https://alchemyportal.azurewebsites.net), desplácese hacia abajo hasta la sección título de la **visión del cliente** y úsela como punto de partida para su título H1 para la visión.</span><span class="sxs-lookup"><span data-stu-id="0887b-111">In the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net), navigate down to the section **Customer Insight Title:** and use that as a starting point for your H1 title for the insight.</span></span> 
    > [!NOTE]
    > <span data-ttu-id="0887b-112">La información de Alchemy solo debe tener un solo H1 en la parte superior o se interrumpirá en producción.</span><span class="sxs-lookup"><span data-stu-id="0887b-112">Alchemy Insights MUST have only a single H1 at the top or they will break in production.</span></span> <span data-ttu-id="0887b-113">H2s no representarlas, use **negrita** u otras convenciones para indicar secciones independientes.</span><span class="sxs-lookup"><span data-stu-id="0887b-113">H2s dont render either so use **bold** or other conventions to signify separate sections.</span></span>
1. <span data-ttu-id="0887b-114">A continuación, rellene el texto del cuerpo con el borrador de material en la sección información del cliente de la página de la regla de Alchemy.</span><span class="sxs-lookup"><span data-stu-id="0887b-114">Next, fill in the body text using the draft material in the Customer Insights section of the Alchemy Rule page</span></span>
    1. <span data-ttu-id="0887b-115">Las listas con viñetas están bien</span><span class="sxs-lookup"><span data-stu-id="0887b-115">Bulleted lists are fine</span></span>
    1. <span data-ttu-id="0887b-116">También las listas numeradas</span><span class="sxs-lookup"><span data-stu-id="0887b-116">Numbered lists too</span></span>
    1. <span data-ttu-id="0887b-117">**Negrita** y *cursiva* son a-OK</span><span class="sxs-lookup"><span data-stu-id="0887b-117">**Bold** and *italic* are a-ok</span></span>
    1. <span data-ttu-id="0887b-118">Los vínculos siempre deben ser **"vínculos a Web"/external** o **vínculos profundos a elementos**de la interfaz de usuario, no a vínculos internos.</span><span class="sxs-lookup"><span data-stu-id="0887b-118">Links should always be either **"links to web"/external** OR **deep-links to UI elements**, not internal links.</span></span>

<span data-ttu-id="0887b-119">Y esto ya es un poco demasiado largo.</span><span class="sxs-lookup"><span data-stu-id="0887b-119">And this is really already a bit too long.</span></span> <span data-ttu-id="0887b-120">El procedimiento recomendado es de unos 400 caracteres---------------------------------</span><span class="sxs-lookup"><span data-stu-id="0887b-120">Best practice is about 400 characters ---------------------------------</span></span>

<span data-ttu-id="0887b-121">Una vez que el contenido esté listo, extráigalo a la rama activa.</span><span class="sxs-lookup"><span data-stu-id="0887b-121">Once your content is ready, pull it to the live branch.</span></span> <span data-ttu-id="0887b-122">A continuación, vaya al [portal de socios de Alchemy](https://alchemyportal.azurewebsites.net) y escriba el nombre de archivo en el campo URL.</span><span class="sxs-lookup"><span data-stu-id="0887b-122">Then, go to the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) and enter the filename into the url field.</span></span> <span data-ttu-id="0887b-123">Asegúrese de que la información de revisión revisada y publicada dice "sí" y, a continuación, haga clic en actualizar regla.</span><span class="sxs-lookup"><span data-stu-id="0887b-123">Make sure Insight reviewed and published says "yes" and then click Update Rule.</span></span> <span data-ttu-id="0887b-124">**(El aspecto será Prettier en la nueva versión del portal de lanzamiento de próximamente).** 
 ![](media/for-content-team.PNG)</span><span class="sxs-lookup"><span data-stu-id="0887b-124">**(This will look prettier in the new version of the portal - releasing soon.)**
![url field](media/for-content-team.PNG)</span></span>

