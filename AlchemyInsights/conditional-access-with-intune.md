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
# <a name="conditional-access-with-intune"></a><span data-ttu-id="81021-102">Acceso condicional con Intune</span><span class="sxs-lookup"><span data-stu-id="81021-102">Conditional Access with Intune</span></span>

<span data-ttu-id="81021-103">El uso de **acceso condicional** con Intune requiere 3 pasos:</span><span class="sxs-lookup"><span data-stu-id="81021-103">Using **Conditional Access** with Intune requires 3 steps:</span></span> 
  
- <span data-ttu-id="81021-104">Cree una **Directiva de acceso condicional** que defina los recursos que se van a proteger y las condiciones que deben cumplirse para obtener acceso a esos recursos.</span><span class="sxs-lookup"><span data-stu-id="81021-104">Create a **Conditional Access Policy** that defines what resources are being protected, and what conditions need to be met to access those resources.</span></span> <span data-ttu-id="81021-105">Por ejemplo, un dispositivo debe ser compatible antes de obtener acceso al correo electrónico corporativo.</span><span class="sxs-lookup"><span data-stu-id="81021-105">For example, a device must be compliant before accessing corporate email.</span></span> 
    
- <span data-ttu-id="81021-106">Cree una **Directiva de cumplimiento** para definir la configuración que se debe cumplir antes de que el dispositivo se considere conforme.</span><span class="sxs-lookup"><span data-stu-id="81021-106">Create a **Compliance Policy** to define settings that must be met before the device is considered compliant.</span></span> <span data-ttu-id="81021-107">Por ejemplo, un dispositivo debe tener un PIN de al menos 6 dígitos antes de que se considere compatible.</span><span class="sxs-lookup"><span data-stu-id="81021-107">For example, a device must have a pin of at least 6 digits before it is considered compliant.</span></span> 
    
- <span data-ttu-id="81021-108">Garantizar que las directivas de **cumplimiento** y **las directivas de acceso condicional** estén dirigidas a los grupos de usuarios deseados.</span><span class="sxs-lookup"><span data-stu-id="81021-108">Ensuring both **Compliance Policies** and **Conditional Access Policies** are targeted to the desired groups of users.</span></span> <span data-ttu-id="81021-109">Esto puede requerir la creación de grupos específicos de usuarios en Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="81021-109">This may require creating specific groups of users in Azure Active Directory.</span></span> 
    
<span data-ttu-id="81021-110">Más información:</span><span class="sxs-lookup"><span data-stu-id="81021-110">Read more:</span></span>
  
- [<span data-ttu-id="81021-111">Procedimientos recomendados de acceso condicional</span><span class="sxs-lookup"><span data-stu-id="81021-111">Conditional Access best practices</span></span>](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [<span data-ttu-id="81021-112">Introducción al acceso condicional</span><span class="sxs-lookup"><span data-stu-id="81021-112">Getting started with Conditional Access </span></span>](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    

