---
title: Sincronización UPN deshabilitado
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 2a3489fe-c2a8-4e43-96c2-be4b3c5e978c
ms.openlocfilehash: d00f10688ec775c22d60a9089e291c265ada46f1
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29491130"
---
# <a name="upn-sync-disabled"></a><span data-ttu-id="e7a8c-102">Sincronización UPN deshabilitado</span><span class="sxs-lookup"><span data-stu-id="e7a8c-102">UPN sync disabled</span></span>

<span data-ttu-id="e7a8c-103">Si inicia la sincronización con Azure AD antes del 30 de marzo de 2016, ejecute el siguiente cmdlet de PowerShell de Azure AD para habilitar la coincidencia suave de UPN para su organización sólo:</span><span class="sxs-lookup"><span data-stu-id="e7a8c-103">If you started syncing to Azure AD before March 30, 2016, run the following Azure AD PowerShell cmdlet to enable UPN soft match for your organization only:</span></span>
  
 <span data-ttu-id="e7a8c-104">**Set-MsolDirSyncFeature-EnableSoftMatchOnUpn la característica-Habilitar $True**</span><span class="sxs-lookup"><span data-stu-id="e7a8c-104">**Set-MsolDirSyncFeature -Feature EnableSoftMatchOnUpn -Enable $True**</span></span>
  
<span data-ttu-id="e7a8c-105">Coincidencia UPN suave automáticamente está activado para las organizaciones que inicia la sincronización con Azure AD en o después del 30 de marzo de 2016.</span><span class="sxs-lookup"><span data-stu-id="e7a8c-105">UPN soft match is automatically turned on for organizations that started syncing to Azure AD on or after March 30, 2016.</span></span>
  
<span data-ttu-id="e7a8c-106">Para obtener más información acerca de cómo habilitar la coincidencia suave en UPN y otras características de sincronización, consulte [características del servicio de sincronización de Azure Connect de AD](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).</span><span class="sxs-lookup"><span data-stu-id="e7a8c-106">To learn more about enabling soft match on UPN and other sync features, please see [Azure AD Connect sync service features](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).</span></span>
  

