---
title: Uno de los certificados de servicio de federación local va a expirar
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
ms.assetid: 172084b7-68a1-42a5-944d-2e871eaa2972
ms.openlocfilehash: 9e2e1a1dd2993b2a02b4405db8a707b23ff4af16
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/30/2019
ms.locfileid: "29658924"
---
# <a name="one-of-your-on-premises-federation-service-certificates-is-expiring"></a><span data-ttu-id="db08b-102">Uno de los certificados de servicio de federación local va a expirar</span><span class="sxs-lookup"><span data-stu-id="db08b-102">One of your on-premises Federation Service Certificates is expiring</span></span>

<span data-ttu-id="db08b-103">Para resolver este problema, siga estos pasos:</span><span class="sxs-lookup"><span data-stu-id="db08b-103">To resolve this issue, follow these steps:</span></span>
  
- <span data-ttu-id="db08b-p101">Instale el Microsoft Azure Active Directory módulo para Windows PowerShell en el equipo (si el módulo ya no está instalado). Para ello, vaya a [Azure Active Directory PowerShell para gráfico](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)</span><span class="sxs-lookup"><span data-stu-id="db08b-p101">Install the Microsoft Azure Active Directory Module for Windows PowerShell on the computer (if the module isn't already installed). To do this, go to [Azure Active Directory PowerShell for Graph ](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)</span></span>
    
- <span data-ttu-id="db08b-106">Siga los pasos descritos en la "escenario 1: el certificado de firma de tokens de AD FS caducado" sección de [error "Se ha producido un problema al obtener acceso el sitio" desde AD FS cuando un usuario federado inicia sesión en Office 365, Azure o Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span><span class="sxs-lookup"><span data-stu-id="db08b-106">Follow the steps in the "Scenario 1: The AD FS token-signing certificate expired" section of ["There was a problem accessing the site" error from AD FS when a federated user signs in to Office 365, Azure, or Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span></span>
    
- <span data-ttu-id="db08b-107">Siga los pasos descritos en[cómo actualizar o reparar la configuración de un dominio federado en Office 365, Azure o Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3)t.</span><span class="sxs-lookup"><span data-stu-id="db08b-107">Follow the steps in t[How to update or repair the settings of a federated domain in Office 365, Azure, or Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span></span>
    
<span data-ttu-id="db08b-108">Para obtener más información acerca de cómo renovar certificados de federación, vea [renovación de certificados para Office 365 y Azure AD](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span><span class="sxs-lookup"><span data-stu-id="db08b-108">For more information about renewing Federation certificates, see [Certificate renewal for O365 and Azure AD](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span></span>
  

