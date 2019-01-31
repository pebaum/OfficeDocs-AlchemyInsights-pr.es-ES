---
title: Federación de ADFS certificado a expirar
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/8/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 26a7eebb-1424-4ddc-a123-af1cc94bc40f
ms.openlocfilehash: 6170265dac1eebe8fa1acf766d2eb8d6b0a5908b
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/30/2019
ms.locfileid: "29662380"
---
# <a name="adfs-federation-certificate-expiring"></a><span data-ttu-id="0fc2c-102">Federación de ADFS certificado a expirar</span><span class="sxs-lookup"><span data-stu-id="0fc2c-102">ADFS Federation Certificate Expiring</span></span>

<span data-ttu-id="0fc2c-103">Para resolver este problema, siga estos pasos:</span><span class="sxs-lookup"><span data-stu-id="0fc2c-103">To resolve this issue, follow these steps:</span></span>
  
1. <span data-ttu-id="0fc2c-p101">Instale el Microsoft Azure Active Directory módulo para Windows PowerShell en el equipo (si el módulo ya no está instalado). Para ello, vaya a [administrar Windows Azure con Windows PowerShell](https://aka.ms/aadposh).</span><span class="sxs-lookup"><span data-stu-id="0fc2c-p101">Install the Microsoft Azure Active Directory Module for Windows PowerShell on the computer (if the module isn't already installed). To do this, go to [Manage Azure AD using Windows PowerShell](https://aka.ms/aadposh).</span></span>
    
2. <span data-ttu-id="0fc2c-106">Siga los pasos descritos en la "escenario 1: el certificado de firma de tokens de AD FS caducado" sección de [error "Se ha producido un problema al obtener acceso el sitio" desde AD FS cuando un usuario federado inicia sesión en Office 365, Azure o Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span><span class="sxs-lookup"><span data-stu-id="0fc2c-106">Follow the steps in the "Scenario 1: The AD FS token-signing certificate expired" section of ["There was a problem accessing the site" error from AD FS when a federated user signs in to Office 365, Azure, or Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span></span>
    
3. <span data-ttu-id="0fc2c-107">Siga los pasos descritos en [cómo actualizar o reparar la configuración de un dominio federado en Office 365, Azure o Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span><span class="sxs-lookup"><span data-stu-id="0fc2c-107">Follow the steps in [How to update or repair the settings of a federated domain in Office 365, Azure, or Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span></span>
    
    <span data-ttu-id="0fc2c-108">Para obtener más información acerca de cómo renovar certificados de federación, vea [renovar los certificados de federación de Office 365 y Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span><span class="sxs-lookup"><span data-stu-id="0fc2c-108">To learn more about renewing Federation certificates, see [Renew federation certificates for Office 365 and Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span></span>
    

