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
# <a name="upn-sync-disabled"></a>Sincronización UPN deshabilitado

Si inicia la sincronización con Azure AD antes del 30 de marzo de 2016, ejecute el siguiente cmdlet de PowerShell de Azure AD para habilitar la coincidencia suave de UPN para su organización sólo:
  
 **Set-MsolDirSyncFeature-EnableSoftMatchOnUpn la característica-Habilitar $True**
  
Coincidencia UPN suave automáticamente está activado para las organizaciones que inicia la sincronización con Azure AD en o después del 30 de marzo de 2016.
  
Para obtener más información acerca de cómo habilitar la coincidencia suave en UPN y otras características de sincronización, consulte [características del servicio de sincronización de Azure Connect de AD](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).
  

