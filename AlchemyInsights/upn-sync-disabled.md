---
title: Sincronización UPN deshabilitada
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 2a3489fe-c2a8-4e43-96c2-be4b3c5e978c
ms.openlocfilehash: 2a03ac64d92c07b523b015850251b33c58bb76f8
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/22/2019
ms.locfileid: "30767264"
---
# <a name="upn-sync-disabled"></a><span data-ttu-id="b7468-102">Sincronización UPN deshabilitada</span><span class="sxs-lookup"><span data-stu-id="b7468-102">UPN sync disabled</span></span>

<span data-ttu-id="b7468-103">Si empezó a sincronizar con Azure AD antes del 30 de marzo de 2016, ejecute el siguiente cmdlet de Azure AD PowerShell para habilitar la coincidencia simplificada de UPN para su organización solo:</span><span class="sxs-lookup"><span data-stu-id="b7468-103">If you started syncing to Azure AD before March 30, 2016, run the following Azure AD PowerShell cmdlet to enable UPN soft match for your organization only:</span></span>
  
 <span data-ttu-id="b7468-104">**Set-MsolDirSyncFeature-Feature EnableSoftMatchOnUpn-enAble $True**</span><span class="sxs-lookup"><span data-stu-id="b7468-104">**Set-MsolDirSyncFeature -Feature EnableSoftMatchOnUpn -Enable $True**</span></span>
  
<span data-ttu-id="b7468-105">La coincidencia Soft de UPN se activa automáticamente para las organizaciones que comenzaron a sincronizarse con Azure AD a partir del 30 de marzo de 2016.</span><span class="sxs-lookup"><span data-stu-id="b7468-105">UPN soft match is automatically turned on for organizations that started syncing to Azure AD on or after March 30, 2016.</span></span>
  
<span data-ttu-id="b7468-106">Para obtener más información acerca de cómo habilitar la coincidencia flexible en UPN y otras características de sincronización, consulte [características del servicio de sincronización de Azure ad Connect](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).</span><span class="sxs-lookup"><span data-stu-id="b7468-106">To learn more about enabling soft match on UPN and other sync features, please see [Azure AD Connect sync service features](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).</span></span>
  

