---
title: 'lo mismo que el nombre de archivo es mejor [regla #-descripción]'
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 4/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: 278a26f4b986a85e33442baef690d3bb44462ace
ms.sourcegitcommit: 32355b76d45b730a069575efeec708149d4aeaa3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/01/2019
ms.locfileid: "29697147"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a><span data-ttu-id="d4569-102">Requiere Alchemy encabezado H1, H2 no funcionan.</span><span class="sxs-lookup"><span data-stu-id="d4569-102">Required Alchemy Header H1, H2's dont work.</span></span>
<span data-ttu-id="d4569-103">Procedimientos recomendados e instrucciones para la creación de Alchemy:</span><span class="sxs-lookup"><span data-stu-id="d4569-103">Best Practices and guidelines for Alchemy authoring:</span></span>

1. <span data-ttu-id="d4569-p101">**No anidar Alchemy conocimientos en las carpetas**- esto, interrumpirá la estructura de la dirección url. Buscamos en corregir esto.</span><span class="sxs-lookup"><span data-stu-id="d4569-p101">**Do not nest Alchemy Insights in folders**- this will break the url structure. We're looking into fixing this.</span></span>
1. <span data-ttu-id="d4569-106">Los archivos en la carpeta **AlchemyInsights** deben tener el identificador de la regla y el nombre de la regla desde el [portal de socios de Alchemy](https://alchemyportal.azurewebsites.net) en el nombre de archivo.</span><span class="sxs-lookup"><span data-stu-id="d4569-106">Files in the **AlchemyInsights** folder should have Rule ID and Rule Name from the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) in the filename.</span></span>
    1. <span data-ttu-id="d4569-p102">***976-How-to-enable-litigation-hold*** ex.</span><span class="sxs-lookup"><span data-stu-id="d4569-p102">ex. ***976-How-to-enable-litigation-hold***</span></span>
1. <span data-ttu-id="d4569-p103">Usar los metadatos en la parte superior de este archivo como plantilla. Se necesita nada más.</span><span class="sxs-lookup"><span data-stu-id="d4569-p103">Use the metadata at the top of this file as your template. Nothing else is required.</span></span>
1. <span data-ttu-id="d4569-111">En el [portal de socios de Alchemy](https://alchemyportal.azurewebsites.net), desplácese hacia abajo hasta la sección **cliente Insight título:** y el uso que, como un inicio, elija su título H1 para la perspectiva.</span><span class="sxs-lookup"><span data-stu-id="d4569-111">In the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net), navigate down to the section **Customer Insight Title:** and use that as a starting point for your H1 title for the insight.</span></span> 
    > [!NOTE]
    > <span data-ttu-id="d4569-p104">Alchemy perspectivas debe tener solo un único H1 en la parte superior o dividirá en producción. H2s no representar uso de es así **negrita** u otras convenciones para indicar las secciones independientes.</span><span class="sxs-lookup"><span data-stu-id="d4569-p104">Alchemy Insights MUST have only a single H1 at the top or they will break in production. H2s dont render either so use **bold** or other conventions to signify separate sections.</span></span>
1. <span data-ttu-id="d4569-114">A continuación, rellene el texto del cuerpo con el material de borrador en la sección de la perspectiva del cliente de la página Alchemy regla</span><span class="sxs-lookup"><span data-stu-id="d4569-114">Next, fill in the body text using the draft material in the Customer Insights section of the Alchemy Rule page</span></span>
    1. <span data-ttu-id="d4569-115">Las listas con viñetas son no pasa nada</span><span class="sxs-lookup"><span data-stu-id="d4569-115">Bulleted lists are fine</span></span>
    1. <span data-ttu-id="d4569-116">Listas numeradas demasiado</span><span class="sxs-lookup"><span data-stu-id="d4569-116">Numbered lists too</span></span>
    1. <span data-ttu-id="d4569-117">**Negrita** y *cursiva* son a-ok</span><span class="sxs-lookup"><span data-stu-id="d4569-117">**Bold** and *italic* are a-ok</span></span>
    1. <span data-ttu-id="d4569-118">Vínculos siempre deben ser una **"vínculos al sitio web" / externo** OR **profundo-vínculos a elementos de la interfaz de usuario**, los vínculos no internos.</span><span class="sxs-lookup"><span data-stu-id="d4569-118">Links should always be either **"links to web"/external** OR **deep-links to UI elements**, not internal links.</span></span>

<span data-ttu-id="d4569-p105">Y esto realmente ya es un poco demasiado largo. Procedimiento recomendado es de aproximadamente 400 caracteres---</span><span class="sxs-lookup"><span data-stu-id="d4569-p105">And this is really already a bit too long. Best practice is about 400 characters ---------------------------------</span></span>

<span data-ttu-id="d4569-p106">Una vez que el contenido esté listo, extraer a la rama live. A continuación, vaya al [portal de socios de Alchemy](https://alchemyportal.azurewebsites.net) y escriba el nombre de archivo en el campo de dirección url. Asegúrese de que sus conocimientos revisan y se publican dice "Sí" y, a continuación, haga clic en regla de actualización. **(El aspecto será mejor aspecto en la nueva versión del portal - lanzará pronto.)** 
 ![campo de dirección url](media/for-content-team.PNG)</span><span class="sxs-lookup"><span data-stu-id="d4569-p106">Once your content is ready, pull it to the live branch. Then, go to the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) and enter the filename into the url field. Make sure Insight reviewed and published says "yes" and then click Update Rule. **(This will look prettier in the new version of the portal - releasing soon.)**
![url field](media/for-content-team.PNG)</span></span>

