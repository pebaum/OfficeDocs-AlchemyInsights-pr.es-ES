---
title: Sincronización UPN deshabilitada
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 2a3489fe-c2a8-4e43-96c2-be4b3c5e978c
ms.openlocfilehash: 33bc7e30d41ff70e2ce55d946202acf45dbcb0f2
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43726121"
---
# <a name="upn-sync-disabled"></a><span data-ttu-id="073be-102">Sincronización UPN deshabilitada</span><span class="sxs-lookup"><span data-stu-id="073be-102">UPN sync disabled</span></span>

<span data-ttu-id="073be-103">Si empezó a sincronizar con Azure AD antes del 30 de marzo de 2016, ejecute el siguiente cmdlet de Azure AD PowerShell para habilitar la coincidencia simplificada de UPN para su organización solo:</span><span class="sxs-lookup"><span data-stu-id="073be-103">If you started syncing to Azure AD before March 30, 2016, run the following Azure AD PowerShell cmdlet to enable UPN soft match for your organization only:</span></span>
  
 <span data-ttu-id="073be-104">**Set-MsolDirSyncFeature-Feature EnableSoftMatchOnUpn-enable $True**</span><span class="sxs-lookup"><span data-stu-id="073be-104">**Set-MsolDirSyncFeature -Feature EnableSoftMatchOnUpn -Enable $True**</span></span>
  
<span data-ttu-id="073be-105">La coincidencia Soft de UPN se activa automáticamente para las organizaciones que comenzaron a sincronizarse con Azure AD a partir del 30 de marzo de 2016.</span><span class="sxs-lookup"><span data-stu-id="073be-105">UPN soft match is automatically turned on for organizations that started syncing to Azure AD on or after March 30, 2016.</span></span>
  
<span data-ttu-id="073be-106">Para obtener más información acerca de cómo habilitar la coincidencia flexible en UPN y otras características de sincronización, consulte [características del servicio de sincronización de Azure ad Connect](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).</span><span class="sxs-lookup"><span data-stu-id="073be-106">To learn more about enabling soft match on UPN and other sync features, please see [Azure AD Connect sync service features](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).</span></span>
  

