---
title: Código de error 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Si recibe un error durante la activación de Office 2013 en las implementaciones de servicios de escritorio remoto (RDS), considere la posibilidad de habilitar ADAL mediante la edición del registro.
ms.openlocfilehash: 89f9270169e13fd7706f7826c624ef8ae4d47b3f
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29499399"
---
<span data-ttu-id="75ff4-103">Si recibe un error durante la activación de Office 2013 en las implementaciones de servicios de escritorio remoto (RDS), considere la posibilidad de habilitar ADAL mediante la edición del registro.</span><span class="sxs-lookup"><span data-stu-id="75ff4-103">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span> 
  
|<span data-ttu-id="75ff4-104">**Clave del registro**</span><span class="sxs-lookup"><span data-stu-id="75ff4-104">**Registry key**</span></span>|<span data-ttu-id="75ff4-105">**Tipo**</span><span class="sxs-lookup"><span data-stu-id="75ff4-105">**Type**</span></span>|<span data-ttu-id="75ff4-106">**Valor**</span><span class="sxs-lookup"><span data-stu-id="75ff4-106">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="75ff4-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span><span class="sxs-lookup"><span data-stu-id="75ff4-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="75ff4-108">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="75ff4-108">REG_DWORD</span></span>  <br/> |<span data-ttu-id="75ff4-109">^1</span><span class="sxs-lookup"><span data-stu-id="75ff4-109">1</span></span>  <br/> |
   
<span data-ttu-id="75ff4-110">Para obtener más información, vea [Habilitar moderno Authentication for Office 2013 en dispositivos de Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span><span class="sxs-lookup"><span data-stu-id="75ff4-110">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="75ff4-p101">ADAL está habilitada de forma predeterminada en Office 365 ProPlus y Office 2016. > servicios de escritorio remoto (RDS) se denominaba anteriormente Terminal Services.</span><span class="sxs-lookup"><span data-stu-id="75ff4-p101">ADAL is enabled by default in Office 365 ProPlus and Office 2016. >  Remote Desktop Services (RDS) was previously named Terminal Services.</span></span> 
  

