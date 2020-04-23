---
title: Uno de los certificados del servicio de Federación local va a expirar
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
ms.assetid: 172084b7-68a1-42a5-944d-2e871eaa2972
ms.openlocfilehash: dafa344ec649002900e98a5e183b3e5f759707e1
ms.sourcegitcommit: 6a3748f5c05693ca0c19a829287cb8f30635940c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43785320"
---
# <a name="one-of-your-on-premises-federation-service-certificates-is-expiring"></a><span data-ttu-id="81284-102">Uno de los certificados del servicio de Federación local va a expirar</span><span class="sxs-lookup"><span data-stu-id="81284-102">One of your on-premises Federation Service Certificates is expiring</span></span>

<span data-ttu-id="81284-103">Para resolver este problema, siga estos pasos:</span><span class="sxs-lookup"><span data-stu-id="81284-103">To resolve this issue, follow these steps:</span></span>
  
- <span data-ttu-id="81284-104">Instale el módulo Microsoft Azure Active Directory para Windows PowerShell en el equipo (si el módulo no está instalado ya).</span><span class="sxs-lookup"><span data-stu-id="81284-104">Install the Microsoft Azure Active Directory Module for Windows PowerShell on the computer (if the module isn't already installed).</span></span> <span data-ttu-id="81284-105">Para ello, vaya a [Azure Active Directory PowerShell para Graph](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)</span><span class="sxs-lookup"><span data-stu-id="81284-105">To do this, go to [Azure Active Directory PowerShell for Graph ](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)</span></span>
    
- <span data-ttu-id="81284-106">Siga los pasos que se indican en la sección "escenario 1: el certificado de firma de tokens de AD FS ha expirado" del [mensaje "se ha producido un problema al obtener acceso al sitio" de AD FS cuando un usuario federado inicia sesión en Microsoft 365, Azure o Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span><span class="sxs-lookup"><span data-stu-id="81284-106">Follow the steps in the "Scenario 1: The AD FS token-signing certificate expired" section of ["There was a problem accessing the site" error from AD FS when a federated user signs in to Microsoft 365, Azure, or Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span></span>
    
- <span data-ttu-id="81284-107">Siga los pasos [que se indican en cómo actualizar o reparar la configuración de un dominio federado en Microsoft 365, Azure o Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span><span class="sxs-lookup"><span data-stu-id="81284-107">Follow the steps in [How to update or repair the settings of a federated domain in Microsoft 365, Azure, or Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span></span>
    
<span data-ttu-id="81284-108">Para obtener más información acerca de la renovación de certificados de Federación, consulte [renovación de certificados para O365 y Azure ad](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span><span class="sxs-lookup"><span data-stu-id="81284-108">For more information about renewing Federation certificates, see [Certificate renewal for O365 and Azure AD](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span></span>
  

