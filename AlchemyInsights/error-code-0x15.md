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
ms.openlocfilehash: 4ef2943e5a529368fa2c614e4431cf180924fbb8
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36527071"
---
# <a name="error-while-activation-office-2013-on-remote-desktop-services"></a><span data-ttu-id="1de63-103">Error al activar Office 2013 en servicios de escritorio remoto</span><span class="sxs-lookup"><span data-stu-id="1de63-103">Error while activation Office 2013 on Remote Desktop Services</span></span>

<span data-ttu-id="1de63-104">Si recibe un error al activar Office 2013 en implementaciones de servicios de escritorio remoto (RDS), considere la posibilidad de habilitar ADAL editando el registro.</span><span class="sxs-lookup"><span data-stu-id="1de63-104">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span>
  
|<span data-ttu-id="1de63-105">**Clave del registro**</span><span class="sxs-lookup"><span data-stu-id="1de63-105">**Registry key**</span></span>|<span data-ttu-id="1de63-106">**Type**</span><span class="sxs-lookup"><span data-stu-id="1de63-106">**Type**</span></span>|<span data-ttu-id="1de63-107">**Value**</span><span class="sxs-lookup"><span data-stu-id="1de63-107">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="1de63-108">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span><span class="sxs-lookup"><span data-stu-id="1de63-108">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="1de63-109">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="1de63-109">REG_DWORD</span></span>  <br/> |<span data-ttu-id="1de63-110">1 </span><span class="sxs-lookup"><span data-stu-id="1de63-110">1</span></span>  <br/> |

<span data-ttu-id="1de63-111">Para obtener más información, consulte [Habilitar la autenticación moderna para Office 2013 en dispositivos Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span><span class="sxs-lookup"><span data-stu-id="1de63-111">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="1de63-112">ADAL está habilitado de forma predeterminada en Office 365 ProPlus y Office 2016.</span><span class="sxs-lookup"><span data-stu-id="1de63-112">ADAL is enabled by default in Office 365 ProPlus and Office 2016.</span></span> <span data-ttu-id="1de63-113">Servicios de escritorio remoto (RDS) se llamaba Terminal Services.</span><span class="sxs-lookup"><span data-stu-id="1de63-113">Remote Desktop Services (RDS) was previously named Terminal Services.</span></span>
  