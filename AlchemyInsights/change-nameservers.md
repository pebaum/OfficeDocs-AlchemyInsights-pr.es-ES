---
title: Cambiar NameServers
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "5"
- "14"
ms.openlocfilehash: 572f8befd84f55cb07a3535852a46e735d3ed620
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43706772"
---
# <a name="update-your-domain-nameservers-to-point-to-microsoft"></a><span data-ttu-id="dbb5b-102">Actualizar los servidores de nombre de dominio para que señalen a Microsoft</span><span class="sxs-lookup"><span data-stu-id="dbb5b-102">Update your domain nameservers to point to Microsoft</span></span>

<span data-ttu-id="dbb5b-103">Nota: Los cambios de Nameserver a veces pueden tardar hasta 48 horas en propagarse.</span><span class="sxs-lookup"><span data-stu-id="dbb5b-103">Note: Nameserver changes can sometimes take up to 48 hours to propagate.</span></span>
  
<span data-ttu-id="dbb5b-p101">Para configurar su dominio en Microsoft 365, los servidores DNS en su registrador deben actualizarse. Cree o edite los registros del servidor DNS en el registrador de dominios.</span><span class="sxs-lookup"><span data-stu-id="dbb5b-p101">To set up your domain in Microsoft 365, the nameservers at your registrar need to be updated. Create or edit your nameserver records at your domain registrar.</span></span>
  
1. <span data-ttu-id="dbb5b-106">Vaya al sitio web del registrador de dominios y busque el área donde puede modificar los servidores DNS.</span><span class="sxs-lookup"><span data-stu-id="dbb5b-106">Go to your domain registrar's website and find the area where you can edit the nameservers.</span></span>
  
2. <span data-ttu-id="dbb5b-107">Cree edite dos registros de servidores DNS para que coincidan con estos valores:</span><span class="sxs-lookup"><span data-stu-id="dbb5b-107">Create or edit two nameserver records to match these values:</span></span>

  - <span data-ttu-id="dbb5b-108">ns1.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="dbb5b-108">ns1.bdm.microsoftonline.com</span></span>

  - <span data-ttu-id="dbb5b-109">ns2.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="dbb5b-109">ns2.bdm.microsoftonline.com</span></span>

3. <span data-ttu-id="dbb5b-110">Guarde los cambios.</span><span class="sxs-lookup"><span data-stu-id="dbb5b-110">Save changes.</span></span>

<span data-ttu-id="dbb5b-111">También encontrará instrucciones detalladas en este artículo: [Cambiar los servidores DNS con cualquier registrador de dominio](https://docs.microsoft.com//office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span><span class="sxs-lookup"><span data-stu-id="dbb5b-111">You can also find detailed instructions in this article: [Change nameservers with any domain registrar](https://docs.microsoft.com//office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span></span>
  