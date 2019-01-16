---
title: Acceso condicional con Intune
ms.author: pebaum
author: pebaum
ms.date: 10/11/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: 59f1aefaeec3d655b2388b00e7d58a8c2338504b
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28313400"
---
# <a name="conditional-access-with-intune"></a>Acceso condicional con Intune

Uso de **Acceso condicional** con Intune requiere 3 pasos: 
  
- Crear una **Directiva de acceso condicional** que define qué recursos están protegidos y qué condiciones deben cumplirse para obtener acceso a dichos recursos. Por ejemplo, un dispositivo debe ser compatible con antes de obtener acceso a correo electrónico corporativo. 
    
- Crear una **Directiva de cumplimiento** para definir la configuración que se debe cumplir antes de que el dispositivo se considera compatible. Por ejemplo, un dispositivo debe tener un pin de al menos 6 dígitos antes de que se considera compatible. 
    
- Garantizar el **Cumplimiento de directivas** y **Las directivas de acceso condicional** destinados a los grupos de usuarios que desee. Esto puede requerir la creación de grupos de usuarios específicos en Azure Active Directory. 
    
Obtenga más información:
  
- [Prácticas recomendadas de acceso condicionales](https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/best-practices)
    
- [Introducción al acceso condicional](https://docs.microsoft.com/en-us/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    

