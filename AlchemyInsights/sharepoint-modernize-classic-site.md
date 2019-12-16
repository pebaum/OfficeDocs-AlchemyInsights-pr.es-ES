---
title: Sitio moderno como sitio raíz
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid:
- "9000153"
- "1692"
ms.openlocfilehash: 3c48cb2dc172ac55e4517e1f84282396ca845c5a
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/15/2019
ms.locfileid: "40051478"
---
# <a name="modernize-your-classic-sharepoint-site"></a><span data-ttu-id="f3669-102">Modernizar el sitio clásico de SharePoint</span><span class="sxs-lookup"><span data-stu-id="f3669-102">Modernize your classic SharePoint site</span></span>

<span data-ttu-id="f3669-103">Para cambiar a una interfaz de usuario moderna, debe centrarse en lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="f3669-103">To make the switch to a modern user interface, you need to focus on the following:</span></span>

- <span data-ttu-id="f3669-104">Transición de las **listas y bibliotecas** para usar la interfaz de usuario moderna (también denominada experiencia moderna de listas y bibliotecas).</span><span class="sxs-lookup"><span data-stu-id="f3669-104">Transitioning your **lists and libraries** to use the modern user interface (also referred to as the modern list and library experience).</span></span>
- <span data-ttu-id="f3669-105">Transformar las páginas del **sitio** de las páginas de elementos Web y wiki clásicas en páginas modernas del lado cliente.</span><span class="sxs-lookup"><span data-stu-id="f3669-105">Transforming your **site pages** from classic wiki and web part pages into modern client-side pages.</span></span>
- <span data-ttu-id="f3669-106">Crear **sitios modernos** (sitio de grupo o sitio de comunicación).</span><span class="sxs-lookup"><span data-stu-id="f3669-106">Creating **modern sites** (Team site or Communication Site).</span></span>

<span data-ttu-id="f3669-107">Modernice su experiencia por:</span><span class="sxs-lookup"><span data-stu-id="f3669-107">Modernize your experience by:</span></span>
- <span data-ttu-id="f3669-108">[Habilite listas y bibliotecas para que se muestren en la interfaz de usuario moderna](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries) reemplazando las personalizaciones, quitando las columnas incompatibles de las vistas usadas o, como último recurso, moviendo los datos a un tipo de lista de interfaz de usuario moderna compatible.</span><span class="sxs-lookup"><span data-stu-id="f3669-108">[Enabling lists and libraries to show in the modern user interface](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries) by replacing customizations, removing incompatible columns from the used views, or (as a last resort) moving data into a modern user interface-compatible list type.</span></span>
- <span data-ttu-id="f3669-109">[Conectar el sitio a un grupo de Office 365](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group), que proporciona al sitio una página principal moderna y permite que el sitio use, por ejemplo, un buzón o Microsoft Planner.</span><span class="sxs-lookup"><span data-stu-id="f3669-109">[Connecting your site to an Office 365 group](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group), which gives your site a modern home page and enables your site to use, for example, a mailbox or Microsoft Planner.</span></span> <span data-ttu-id="f3669-110">Esto le permite usar una versión moderna de un calendario y una lista de tareas.</span><span class="sxs-lookup"><span data-stu-id="f3669-110">This enables you to use a modern version of a calendar and task list.</span></span>
- <span data-ttu-id="f3669-111">La [creación de páginas modernas](https://support.office.com/article/create-and-use-modern-pages-on-a-sharepoint-site-b3d46deb-27a6-4b1e-87b8-df851e503dec)es una excelente forma de compartir ideas con imágenes, documentos de Excel, Word y PowerPoint, vídeo y mucho más.</span><span class="sxs-lookup"><span data-stu-id="f3669-111">[Creating modern pages](https://support.office.com/article/create-and-use-modern-pages-on-a-sharepoint-site-b3d46deb-27a6-4b1e-87b8-df851e503dec), is a great way to share ideas using images, Excel, Word and PowerPoint documents, video, and more.</span></span>
- <span data-ttu-id="f3669-112">[Cree páginas modernas del lado cliente](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-site-pages) y configúrelas para que sean "similares" a las principales páginas wiki y de elementos web clásicas.</span><span class="sxs-lookup"><span data-stu-id="f3669-112">[Creating modern client-side pages](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-site-pages) and configuring these to be "similar" to your key classic wiki and web part pages.</span></span> <span data-ttu-id="f3669-113">La transformación de página mediante programación debe realizarse para las páginas principales de los sitios, ya que, al transformar todas las páginas, se usan muchos recursos y, a menudo, no es necesario.</span><span class="sxs-lookup"><span data-stu-id="f3669-113">Programmatic page transformation should be done for the key pages of your sites, as transforming all pages is resource-intensive and often not needed.</span></span> <span data-ttu-id="f3669-114">Para ayudar con esta clasificación, el analizador de modernización de SharePoint le proporcionará información de uso de las páginas wiki y elementos web actuales.</span><span class="sxs-lookup"><span data-stu-id="f3669-114">To assist in this triage, the SharePoint Modernization scanner can give you usage information about the current wiki and web part pages.</span></span>
- <span data-ttu-id="f3669-115">[Crear sitios modernos](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).</span><span class="sxs-lookup"><span data-stu-id="f3669-115">[Creating modern sites](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).</span></span> <span data-ttu-id="f3669-116">¿Debo crear un sitio de grupo o de comunicación?</span><span class="sxs-lookup"><span data-stu-id="f3669-116">Should I create a team site or a communication site?</span></span>

<span data-ttu-id="f3669-117">Información adicional:</span><span class="sxs-lookup"><span data-stu-id="f3669-117">Additional Info:</span></span> 
- <span data-ttu-id="f3669-118">Para obtener una introducción paso a paso sobre la modernización de los sitios de SharePoint clásicos a la experiencia moderna, vea [modernizar los sitios de SharePoint clásicos](https://docs.microsoft.com/sharepoint/dev/transform/modernize-classic-sites).</span><span class="sxs-lookup"><span data-stu-id="f3669-118">For a step-by-step overview of modernizing your classic SharePoint Sites to the modern experience, see [Modernize your classic SharePoint Sites](https://docs.microsoft.com/sharepoint/dev/transform/modernize-classic-sites).</span></span>
- <span data-ttu-id="f3669-119">Consulte la guía de la [experiencia moderna](https://docs.microsoft.com/sharepoint/guide-to-sharepoint-modern-experience).</span><span class="sxs-lookup"><span data-stu-id="f3669-119">See a guide to [Modern Experience](https://docs.microsoft.com/sharepoint/guide-to-sharepoint-modern-experience).</span></span>
- <span data-ttu-id="f3669-120">Vea [experiencias clásicas y modernas de SharePoint](https://support.office.com/article/sharepoint-classic-and-modern-experiences-5725c103-505d-4a6e-9350-300d3ec7d73f).</span><span class="sxs-lookup"><span data-stu-id="f3669-120">See [SharePoint Classic and Modern experiences](https://support.office.com/article/sharepoint-classic-and-modern-experiences-5725c103-505d-4a6e-9350-300d3ec7d73f).</span></span> 




