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
# <a name="upn-sync-disabled"></a>Sincronización UPN deshabilitada

Si empezó a sincronizar con Azure AD antes del 30 de marzo de 2016, ejecute el siguiente cmdlet de Azure AD PowerShell para habilitar la coincidencia simplificada de UPN para su organización solo:
  
 **Set-MsolDirSyncFeature-Feature EnableSoftMatchOnUpn-enAble $True**
  
La coincidencia Soft de UPN se activa automáticamente para las organizaciones que comenzaron a sincronizarse con Azure AD a partir del 30 de marzo de 2016.
  
Para obtener más información acerca de cómo habilitar la coincidencia flexible en UPN y otras características de sincronización, consulte [características del servicio de sincronización de Azure ad Connect](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).
  

