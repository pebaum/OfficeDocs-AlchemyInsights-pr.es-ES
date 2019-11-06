---
title: 2609-retención-o-eDiscovery-Hold
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2609"
- "9000048"
ms.openlocfilehash: 85c41995545efd8e1526d9f7dce4a23929f85be5
ms.sourcegitcommit: 24e8248b0f061a76af50bf566d7a13fc24d29d99
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/05/2019
ms.locfileid: "37994098"
---
# <a name="unable-to-delete-items-in-sharepoint-online-or-onedrive-for-business"></a><span data-ttu-id="035ca-102">No se pueden eliminar elementos en SharePoint Online o OneDrive para la empresa</span><span class="sxs-lookup"><span data-stu-id="035ca-102">Unable to delete items in SharePoint Online or OneDrive for Business</span></span>

<span data-ttu-id="035ca-103">Es posible que usted o sus usuarios no puedan eliminar elementos en SharePoint Online o OneDrive para la empresa porque una directiva de retención, una etiqueta de retención o una retención de exhibición de documentos electrónicos se aplican a un sitio de SharePoint de OneDrive o a un elemento específico.</span><span class="sxs-lookup"><span data-stu-id="035ca-103">You or your users may be unable to delete items in SharePoint Online or OneDrive for Business because a retention policy, retention label, or eDiscovery hold is applied to a SharePoint of OneDrive site or to a specific item.</span></span> <span data-ttu-id="035ca-104">Esto incluye no poder eliminar un documento, una versión de documento, una carpeta, una biblioteca de documentos, una lista, una aplicación, un sitio o una colección de sitios.</span><span class="sxs-lookup"><span data-stu-id="035ca-104">This includes being unable to delete a document, a document version, a folder, a document library, a list, an app, a site, or a site collection.</span></span> <span data-ttu-id="035ca-105">A continuación se muestran algunos ejemplos de los mensajes de error que puede recibir si intenta eliminar un elemento que se conserva:</span><span class="sxs-lookup"><span data-stu-id="035ca-105">Here are some examples of the error messages you may received if you try to delete an item that is being retained:</span></span>

- <span data-ttu-id="035ca-106">"Este sitio no se puede eliminar porque está incluido en una directiva de retención o retención de exhibición de documentos electrónicos"</span><span class="sxs-lookup"><span data-stu-id="035ca-106">"This site cannot be deleted because it is included in an eDiscovery hold or retention policy"</span></span>
- <span data-ttu-id="035ca-107">"Este sitio tiene una directiva de cumplimiento establecida para la eliminación de bloques"</span><span class="sxs-lookup"><span data-stu-id="035ca-107">"This site has a compliance policy set to block deletion"</span></span>
- <span data-ttu-id="035ca-108">"Una directiva de cumplimiento bloquea actualmente esta eliminación de sitio"</span><span class="sxs-lookup"><span data-stu-id="035ca-108">"A compliance policy is currently blocking this site deletion"</span></span>
- <span data-ttu-id="035ca-109">"Esta colección de sitios no se puede eliminar porque contiene sitios incluidos en una retención de exhibición de documentos electrónicos o una directiva de retención"</span><span class="sxs-lookup"><span data-stu-id="035ca-109">"This site collection can’t be deleted because it contains sites that are included in an eDiscovery hold or retention policy"</span></span>
- <span data-ttu-id="035ca-110">"Tiene que eliminar todos los elementos de esta carpeta antes de eliminar la carpeta"</span><span class="sxs-lookup"><span data-stu-id="035ca-110">"You have to delete all the items in this folder before you delete the folder"</span></span>
- <span data-ttu-id="035ca-111">"No se pueden eliminar las versiones de este elemento porque está en retención o Directiva de retención"</span><span class="sxs-lookup"><span data-stu-id="035ca-111">"Versions of this item cannot be deleted because it is on hold or retention policy"</span></span>
- <span data-ttu-id="035ca-112">"El elemento no se puede eliminar mientras está en espera"</span><span class="sxs-lookup"><span data-stu-id="035ca-112">"Item cannot be deleted while on hold"</span></span>
- <span data-ttu-id="035ca-113">"La etiqueta que se aplica a este elemento impide que se edite o elimine"</span><span class="sxs-lookup"><span data-stu-id="035ca-113">"The label that's applied to this item prevents it from being edited or deleted"</span></span>
- <span data-ttu-id="035ca-114">"No se puede eliminar la lista cuando está en retención o en una directiva de retención"</span><span class="sxs-lookup"><span data-stu-id="035ca-114">"List cannot be deleted while on hold or retention policy"</span></span>
- <span data-ttu-id="035ca-115">"No se puede eliminar la lista si está bloqueada o si se le ha aplicado una directiva de retención"</span><span class="sxs-lookup"><span data-stu-id="035ca-115">"The list cannot be deleted if it is blocked or if a retention policy is applied to it"</span></span>

<span data-ttu-id="035ca-116">Para eliminar elementos en uno de estos escenarios, se debe quitar la Directiva de retención, la etiqueta de retención o la retención de exhibición de documentos electrónicos (o se debe excluir un sitio de una directiva de retención).</span><span class="sxs-lookup"><span data-stu-id="035ca-116">To delete items in one of these scenarios, the retention policy, retention label, or eDiscovery hold has to be removed (or a site has to be excluded from a retention policy).</span></span> <span data-ttu-id="035ca-117">Debe deshabilitar o excluir la retención respectiva que está causando este problema.</span><span class="sxs-lookup"><span data-stu-id="035ca-117">You need to either disable or exclude respective hold that's causing this issue.</span></span> <span data-ttu-id="035ca-118">Una vez quitada la retención o la Directiva de retención, el cambio puede tardar hasta 24 horas en surtir efecto.</span><span class="sxs-lookup"><span data-stu-id="035ca-118">After a retention policy or hold is removed, it may take up to 24 hours for the change to take effect.</span></span> 

<span data-ttu-id="035ca-119">Para obtener información sobre las diferentes características de retención y retención que se pueden aplicar a los sitios de SharePoint y a las cuentas de OneDrive, vea uno de los siguientes temas.</span><span class="sxs-lookup"><span data-stu-id="035ca-119">For information about about the different retention and hold features that can be applied to SharePoint sites and OneDrive accounts, see one of the following topics.</span></span>

- [<span data-ttu-id="035ca-120">Información general sobre las directivas de retención</span><span class="sxs-lookup"><span data-stu-id="035ca-120">Overview of retention policies</span></span>](https://docs.microsoft.com/microsoft-365/compliance/retention-policies)

- [<span data-ttu-id="035ca-121">Introducción a las etiquetas de retención</span><span class="sxs-lookup"><span data-stu-id="035ca-121">Overview of retention labels</span></span>](https://docs.microsoft.com/microsoft-365/compliance/labels)

- [<span data-ttu-id="035ca-122">Administrar suspensiones en la exhibición avanzada de documentos electrónicos</span><span class="sxs-lookup"><span data-stu-id="035ca-122">Manage holds in Advanced eDiscovery</span></span>](https://docs.microsoft.com/microsoft-365/compliance/managing-holds)

- [<span data-ttu-id="035ca-123">suspensiones de eDiscovery</span><span class="sxs-lookup"><span data-stu-id="035ca-123">eDiscovery holds</span></span>](https://docs.microsoft.com/microsoft-365/compliance/ediscovery-cases#step-4-place-content-locations-on-hold)

- [<span data-ttu-id="035ca-124">Directivas de cierre y eliminación de sitios heredados</span><span class="sxs-lookup"><span data-stu-id="035ca-124">Legacy site closure and deletion policies</span></span>](https://support.office.com/article/Use-policies-for-site-closure-and-deletion-A8280D82-27FD-48C5-9ADF-8A5431208BA5)
