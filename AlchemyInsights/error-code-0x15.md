---
title: Código de error 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Si recibe un error al activar Office 2013 en implementaciones de servicios de escritorio remoto (RDS), considere la posibilidad de habilitar ADAL editando el registro.
ms.openlocfilehash: 6d4076ecb5c6ee3c3cf4c4610ad4aa29ab477d8a
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "32402756"
---
<span data-ttu-id="96bb9-103">Si recibe un error al activar Office 2013 en implementaciones de servicios de escritorio remoto (RDS), considere la posibilidad de habilitar ADAL editando el registro.</span><span class="sxs-lookup"><span data-stu-id="96bb9-103">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span> 
  
|<span data-ttu-id="96bb9-104">**Clave del registro**</span><span class="sxs-lookup"><span data-stu-id="96bb9-104">**Registry key**</span></span>|<span data-ttu-id="96bb9-105">**Tipo**</span><span class="sxs-lookup"><span data-stu-id="96bb9-105">**Type**</span></span>|<span data-ttu-id="96bb9-106">**Valor**</span><span class="sxs-lookup"><span data-stu-id="96bb9-106">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="96bb9-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span><span class="sxs-lookup"><span data-stu-id="96bb9-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="96bb9-108">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="96bb9-108">REG_DWORD</span></span>  <br/> |<span data-ttu-id="96bb9-109">1 </span><span class="sxs-lookup"><span data-stu-id="96bb9-109">1</span></span>  <br/> |
   
<span data-ttu-id="96bb9-110">Para obtener más información, consulte [Habilitar la autenticación moderna para Office 2013 en dispositivos Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span><span class="sxs-lookup"><span data-stu-id="96bb9-110">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="96bb9-111">ADAL está habilitado de forma predeterminada en Office 365 proPlus y Office 2016.</span><span class="sxs-lookup"><span data-stu-id="96bb9-111">ADAL is enabled by default in Office 365 ProPlus and Office 2016.</span></span> <span data-ttu-id="96bb9-112">> servicios de escritorio remoto (RDS) se llamaba Terminal Services.</span><span class="sxs-lookup"><span data-stu-id="96bb9-112">>  Remote Desktop Services (RDS) was previously named Terminal Services.</span></span> 
  

