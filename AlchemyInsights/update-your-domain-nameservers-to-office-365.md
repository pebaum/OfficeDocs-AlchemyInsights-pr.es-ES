---
title: Actualizar los servidores DNS de dominio a Office 365
ms.author: v-crytho
author: CrystalThomasMS
ms.date: 5/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 5d38b331-a0e8-4937-8bda-4f8f715e1976
ms.custom:
- "6"
- "14"
ms.openlocfilehash: 23d49c734148739ede0d5e5b53430a42b606c831
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2019
ms.locfileid: "36742204"
---
# <a name="update-your-domain-nameservers-to-office-365"></a><span data-ttu-id="ed3b5-102">Actualizar los servidores DNS de dominio a Office 365</span><span class="sxs-lookup"><span data-stu-id="ed3b5-102">Update your domain nameservers to Office 365</span></span>

<span data-ttu-id="ed3b5-103">Nota: Los cambios de Nameserver a veces pueden tardar hasta 48 horas en propagarse.</span><span class="sxs-lookup"><span data-stu-id="ed3b5-103">Note: Nameserver changes can sometimes take up to 48 hours to propagate.</span></span>
  
<span data-ttu-id="ed3b5-p101">Para configurar su dominio en Office 365, los servidores DNS en su registrador deben actualizarse. Cree o edite los registros del servidor DNS en el registrador de dominios.</span><span class="sxs-lookup"><span data-stu-id="ed3b5-p101">To set up your domain in Office 365, the nameservers at your registrar need to be updated. Create or edit your nameserver records at your domain registrar.</span></span>
  
1. <span data-ttu-id="ed3b5-106">Vaya al sitio web del registrador de dominios y busque el área donde puede modificar los servidores DNS.</span><span class="sxs-lookup"><span data-stu-id="ed3b5-106">Go to your domain registrar's website and find the area where you can edit the nameservers.</span></span>

2. <span data-ttu-id="ed3b5-107">Cree edite dos registros de servidores DNS para que coincidan con estos valores:</span><span class="sxs-lookup"><span data-stu-id="ed3b5-107">Create or edit two nameserver records to match these values:</span></span>

  - <span data-ttu-id="ed3b5-108">ns1.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="ed3b5-108">ns1.bdm.microsoftonline.com</span></span>

  - <span data-ttu-id="ed3b5-109">ns2.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="ed3b5-109">ns2.bdm.microsoftonline.com</span></span>

3. <span data-ttu-id="ed3b5-110">Guarde los cambios.</span><span class="sxs-lookup"><span data-stu-id="ed3b5-110">Save changes.</span></span>

<span data-ttu-id="ed3b5-111">También encontrará instrucciones detalladas en este artículo: [Cambiar los servidores DNS para configurar Office 365 con cualquier registrador de dominio](https://docs.microsoft.com/office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span><span class="sxs-lookup"><span data-stu-id="ed3b5-111">You can also find detailed instructions in this article: [Change nameservers to set up Office 365 with any domain registrar](https://docs.microsoft.com/office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span></span>
  