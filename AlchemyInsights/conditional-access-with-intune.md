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
ms.openlocfilehash: 3b50bc96a879017b62e42e1849f72e68408a0d9d
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/30/2019
ms.locfileid: "29662344"
---
# <a name="conditional-access-with-intune"></a><span data-ttu-id="d8670-102">Acceso condicional con Intune</span><span class="sxs-lookup"><span data-stu-id="d8670-102">Conditional Access with Intune</span></span>

<span data-ttu-id="d8670-103">Uso de **Acceso condicional** con Intune requiere 3 pasos:</span><span class="sxs-lookup"><span data-stu-id="d8670-103">Using **Conditional Access** with Intune requires 3 steps:</span></span> 
  
- <span data-ttu-id="d8670-p101">Crear una **Directiva de acceso condicional** que define qué recursos están protegidos y qué condiciones deben cumplirse para obtener acceso a dichos recursos. Por ejemplo, un dispositivo debe ser compatible con antes de obtener acceso a correo electrónico corporativo.</span><span class="sxs-lookup"><span data-stu-id="d8670-p101">Create a **Conditional Access Policy** that defines what resources are being protected, and what conditions need to be met to access those resources. For example, a device must be compliant before accessing corporate email.</span></span> 
    
- <span data-ttu-id="d8670-p102">Crear una **Directiva de cumplimiento** para definir la configuración que se debe cumplir antes de que el dispositivo se considera compatible. Por ejemplo, un dispositivo debe tener un pin de al menos 6 dígitos antes de que se considera compatible.</span><span class="sxs-lookup"><span data-stu-id="d8670-p102">Create a **Compliance Policy** to define settings that must be met before the device is considered compliant. For example, a device must have a pin of at least 6 digits before it is considered compliant.</span></span> 
    
- <span data-ttu-id="d8670-p103">Garantizar el **Cumplimiento de directivas** y **Las directivas de acceso condicional** destinados a los grupos de usuarios que desee. Esto puede requerir la creación de grupos de usuarios específicos en Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="d8670-p103">Ensuring both **Compliance Policies** and **Conditional Access Policies** are targeted to the desired groups of users. This may require creating specific groups of users in Azure Active Directory.</span></span> 
    
<span data-ttu-id="d8670-110">Obtenga más información:</span><span class="sxs-lookup"><span data-stu-id="d8670-110">Read more:</span></span>
  
- [<span data-ttu-id="d8670-111">Prácticas recomendadas de acceso condicionales</span><span class="sxs-lookup"><span data-stu-id="d8670-111">Conditional Access best practices</span></span>](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [<span data-ttu-id="d8670-112">Introducción al acceso condicional</span><span class="sxs-lookup"><span data-stu-id="d8670-112">Getting started with Conditional Access </span></span>](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    

