---
title: Acceso condicional con Intune
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: c9c47d71b2da3840504d5b28c7c9e067b4c05fa5
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43706038"
---
# <a name="conditional-access-with-intune"></a>Acceso condicional con Intune

El uso de **acceso condicional** con Intune requiere 3 pasos: 
  
- Cree una **Directiva de acceso condicional** que defina los recursos que se van a proteger y las condiciones que deben cumplirse para obtener acceso a esos recursos. Por ejemplo, un dispositivo debe ser compatible antes de obtener acceso al correo electrónico corporativo. 
    
- Cree una **Directiva de cumplimiento** para definir la configuración que se debe cumplir antes de que el dispositivo se considere conforme. Por ejemplo, un dispositivo debe tener un PIN de al menos 6 dígitos antes de que se considere compatible. 
    
- Garantizar que las directivas de **cumplimiento** y **las directivas de acceso condicional** estén dirigidas a los grupos de usuarios deseados. Esto puede requerir la creación de grupos específicos de usuarios en Azure Active Directory. 
    
Más información:
  
- [Procedimientos recomendados de acceso condicional](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [Introducción al acceso condicional](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    

