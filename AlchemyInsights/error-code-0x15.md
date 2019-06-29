---
title: Código de error 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "919"
- "2000022"
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Si recibe un error al activar Office 2013 en implementaciones de servicios de escritorio remoto (RDS), considere la posibilidad de habilitar ADAL editando el registro.
ms.openlocfilehash: e2249d8ebbd2313c64dda5656a3243fa76d97a9a
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/28/2019
ms.locfileid: "35388262"
---
<span data-ttu-id="77c2d-103">Si recibe un error al activar Office 2013 en implementaciones de servicios de escritorio remoto (RDS), considere la posibilidad de habilitar ADAL editando el registro.</span><span class="sxs-lookup"><span data-stu-id="77c2d-103">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span>
  
|<span data-ttu-id="77c2d-104">**Clave del registro**</span><span class="sxs-lookup"><span data-stu-id="77c2d-104">**Registry key**</span></span>|<span data-ttu-id="77c2d-105">**Type**</span><span class="sxs-lookup"><span data-stu-id="77c2d-105">**Type**</span></span>|<span data-ttu-id="77c2d-106">**Value**</span><span class="sxs-lookup"><span data-stu-id="77c2d-106">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="77c2d-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span><span class="sxs-lookup"><span data-stu-id="77c2d-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="77c2d-108">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="77c2d-108">REG_DWORD</span></span>  <br/> |<span data-ttu-id="77c2d-109">1 </span><span class="sxs-lookup"><span data-stu-id="77c2d-109">1</span></span>  <br/> |

<span data-ttu-id="77c2d-110">Para obtener más información, consulte [Habilitar la autenticación moderna para Office 2013 en dispositivos Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span><span class="sxs-lookup"><span data-stu-id="77c2d-110">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="77c2d-111">ADAL está habilitado de forma predeterminada en Office 365 ProPlus y Office 2016.</span><span class="sxs-lookup"><span data-stu-id="77c2d-111">ADAL is enabled by default in Office 365 ProPlus and Office 2016.</span></span> <span data-ttu-id="77c2d-112">> servicios de escritorio remoto (RDS) se llamaba Terminal Services.</span><span class="sxs-lookup"><span data-stu-id="77c2d-112">>  Remote Desktop Services (RDS) was previously named Terminal Services.</span></span>
  