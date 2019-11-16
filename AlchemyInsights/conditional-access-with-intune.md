---
title: Acceso condicional con Intune
ms.author: pebaum
author: pebaum
ms.date: 10/11/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: e147e7460ee6a786e577a43c0b8355fc27ee367b
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/15/2019
ms.locfileid: "36505011"
---
# <a name="conditional-access-with-intune"></a>Acceso condicional con Intune

El uso de **acceso condicional** con Intune requiere 3 pasos: 
  
- Cree una **Directiva de acceso condicional** que defina los recursos que se van a proteger y las condiciones que deben cumplirse para obtener acceso a esos recursos. Por ejemplo, un dispositivo debe ser compatible antes de obtener acceso al correo electrónico corporativo. 
    
- Cree una **Directiva de cumplimiento** para definir la configuración que se debe cumplir antes de que el dispositivo se considere conforme. Por ejemplo, un dispositivo debe tener un PIN de al menos 6 dígitos antes de que se considere compatible. 
    
- Garantizar que las directivas de **cumplimiento** y **las directivas de acceso condicional** estén dirigidas a los grupos de usuarios deseados. Esto puede requerir la creación de grupos específicos de usuarios en Azure Active Directory. 
    
Más información:
  
- [Procedimientos recomendados de acceso condicional](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [Introducción al acceso condicional](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    

