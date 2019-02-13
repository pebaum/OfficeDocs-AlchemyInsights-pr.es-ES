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
ms.openlocfilehash: 2e778bf4fbdb766700fb24b3405b4ddce89253f7
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29935971"
---
# <a name="conditional-access-with-intune"></a>Acceso condicional con Intune

Uso de **Acceso condicional** con Intune requiere 3 pasos: 
  
- Crear una **Directiva de acceso condicional** que define qué recursos están protegidos y qué condiciones deben cumplirse para obtener acceso a dichos recursos. Por ejemplo, un dispositivo debe ser compatible con antes de obtener acceso a correo electrónico corporativo. 
    
- Crear una **Directiva de cumplimiento** para definir la configuración que se debe cumplir antes de que el dispositivo se considera compatible. Por ejemplo, un dispositivo debe tener un pin de al menos 6 dígitos antes de que se considera compatible. 
    
- Garantizar el **Cumplimiento de directivas** y **Las directivas de acceso condicional** destinados a los grupos de usuarios que desee. Esto puede requerir la creación de grupos de usuarios específicos en Azure Active Directory. 
    
Obtenga más información:
  
- [Prácticas recomendadas de acceso condicionales](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [Introducción al acceso condicional](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    

