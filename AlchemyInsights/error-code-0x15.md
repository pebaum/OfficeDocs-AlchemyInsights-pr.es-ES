---
title: Código de error 0x15
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "919"
- "2000022"
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Si recibe un error al activar Office 2013 en implementaciones de servicios de escritorio remoto (RDS), considere la posibilidad de habilitar ADAL editando el registro.
ms.openlocfilehash: 566d63cbe37d295b3546b9d7d5b14dfc8e8fe0ec
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43703155"
---
# <a name="error-while-activation-office-2013-on-remote-desktop-services"></a><span data-ttu-id="d7680-103">Error al activar Office 2013 en servicios de escritorio remoto</span><span class="sxs-lookup"><span data-stu-id="d7680-103">Error while activation Office 2013 on Remote Desktop Services</span></span>

<span data-ttu-id="d7680-104">Si recibe un error al activar Office 2013 en implementaciones de servicios de escritorio remoto (RDS), considere la posibilidad de habilitar ADAL editando el registro.</span><span class="sxs-lookup"><span data-stu-id="d7680-104">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span>
  
|<span data-ttu-id="d7680-105">**Clave del registro**</span><span class="sxs-lookup"><span data-stu-id="d7680-105">**Registry key**</span></span>|<span data-ttu-id="d7680-106">**Tipo**</span><span class="sxs-lookup"><span data-stu-id="d7680-106">**Type**</span></span>|<span data-ttu-id="d7680-107">**Valor**</span><span class="sxs-lookup"><span data-stu-id="d7680-107">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="d7680-108">HKEY_CURRENT_USER \Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span><span class="sxs-lookup"><span data-stu-id="d7680-108">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="d7680-109">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="d7680-109">REG_DWORD</span></span>  <br/> |<span data-ttu-id="d7680-110">1</span><span class="sxs-lookup"><span data-stu-id="d7680-110">1</span></span>  <br/> |

<span data-ttu-id="d7680-111">Para obtener más información, consulte [Habilitar la autenticación moderna para Office 2013 en dispositivos Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span><span class="sxs-lookup"><span data-stu-id="d7680-111">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="d7680-112">ADAL está habilitado de forma predeterminada en las aplicaciones de Microsoft 365 para empresas y Office 2016.</span><span class="sxs-lookup"><span data-stu-id="d7680-112">ADAL is enabled by default in Microsoft 365 Apps for enterprise and Office 2016.</span></span> <span data-ttu-id="d7680-113">Servicios de escritorio remoto (RDS) se llamaba Terminal Services.</span><span class="sxs-lookup"><span data-stu-id="d7680-113">Remote Desktop Services (RDS) was previously named Terminal Services.</span></span>
  