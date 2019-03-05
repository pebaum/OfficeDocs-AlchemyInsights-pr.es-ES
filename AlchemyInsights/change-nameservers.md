---
title: Cambiar los servidores DNS
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: d011531a-0951-49c0-af30-40d2e765f381
ms.openlocfilehash: 61c4c5e43a247679bf18fd3861dd98fbe9a7b3eb
ms.sourcegitcommit: f1c96fd3890d4e211f7d6bf73b9105fdaab2e11c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/05/2019
ms.locfileid: "30405340"
---
# <a name="update-your-domain-nameservers-to-office-365"></a><span data-ttu-id="c9469-102">Actualizar los servidores DNS de dominio a Office 365</span><span class="sxs-lookup"><span data-stu-id="c9469-102">Update your domain nameservers to Office 365</span></span>

<span data-ttu-id="c9469-103">Nota: en ocasiones, los cambios de los servidores de nombres pueden tardar hasta 48 horas en propagarse.</span><span class="sxs-lookup"><span data-stu-id="c9469-103">Note: Nameserver changes can sometimes take up to 48 hours to propagate.</span></span>
  
<span data-ttu-id="c9469-p101">Para configurar su dominio en Office 365, los servidores DNS en su registrador deben actualizarse. Cree o edite los registros del servidor DNS en el registrador de dominios.</span><span class="sxs-lookup"><span data-stu-id="c9469-p101">To set up your domain in Office 365, the nameservers at your registrar need to be updated. Create or edit your nameserver records at your domain registrar.</span></span>
  
1. <span data-ttu-id="c9469-106">Vaya al sitio web del registrador de dominios y busque el área donde puede modificar los servidores DNS.</span><span class="sxs-lookup"><span data-stu-id="c9469-106">Go to your domain registrar's website and find the area where you can edit the nameservers.</span></span>
    
2. <span data-ttu-id="c9469-107">Cree edite dos registros de servidores DNS para que coincidan con estos valores:</span><span class="sxs-lookup"><span data-stu-id="c9469-107">Create or edit two nameserver records to match these values:</span></span>
    
  - <span data-ttu-id="c9469-108">ns1.BDM.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="c9469-108">ns1.bdm.microsoftonline.com</span></span>
    
  - <span data-ttu-id="c9469-109">NS2.BDM.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="c9469-109">ns2.bdm.microsoftonline.com</span></span>
    
3. <span data-ttu-id="c9469-110">Guarde los cambios.</span><span class="sxs-lookup"><span data-stu-id="c9469-110">Save changes.</span></span>
    
<span data-ttu-id="c9469-111">También encontrará instrucciones detalladas en este artículo: [Cambiar los servidores DNS para configurar Office 365 con cualquier registrador de dominio](https://support.office.com/article/Change-nameservers-at-any-domain-registrar-to-set-up-Office-365-a8b487a9-2a45-4581-9dc4-5d28a47010a2.aspx)</span><span class="sxs-lookup"><span data-stu-id="c9469-111">You can also find detailed instructions in this article: [Change nameservers to set up Office 365 with any domain registrar](https://support.office.com/article/Change-nameservers-at-any-domain-registrar-to-set-up-Office-365-a8b487a9-2a45-4581-9dc4-5d28a47010a2.aspx)</span></span>
  

