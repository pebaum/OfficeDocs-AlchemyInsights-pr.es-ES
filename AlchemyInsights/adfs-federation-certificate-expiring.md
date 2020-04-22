---
title: Expiración del certificado de Federación de ADFS
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "645"
- "1300012"
ms.assetid: 26a7eebb-1424-4ddc-a123-af1cc94bc40f
ms.openlocfilehash: 14e7da6220dfa96edca5d9ec5c32e003480a9eaf
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43710424"
---
# <a name="adfs-federation-certificate-expiring"></a><span data-ttu-id="5b5b9-102">Expiración del certificado de Federación de ADFS</span><span class="sxs-lookup"><span data-stu-id="5b5b9-102">ADFS Federation Certificate Expiring</span></span>

<span data-ttu-id="5b5b9-103">Para resolver este problema, siga estos pasos:</span><span class="sxs-lookup"><span data-stu-id="5b5b9-103">To resolve this issue, follow these steps:</span></span>
  
1. <span data-ttu-id="5b5b9-104">Instale el módulo Microsoft Azure Active Directory para Windows PowerShell en el equipo (si el módulo no está instalado ya).</span><span class="sxs-lookup"><span data-stu-id="5b5b9-104">Install the Microsoft Azure Active Directory Module for Windows PowerShell on the computer (if the module isn't already installed).</span></span> <span data-ttu-id="5b5b9-105">Para ello, vaya a [administrar Azure ad con Windows PowerShell](https://aka.ms/aadposh).</span><span class="sxs-lookup"><span data-stu-id="5b5b9-105">To do this, go to [Manage Azure AD using Windows PowerShell](https://aka.ms/aadposh).</span></span>

2. <span data-ttu-id="5b5b9-106">Siga los pasos que se indican en la sección "escenario 1: el certificado de firma de tokens de AD FS ha expirado" del [mensaje "se ha producido un problema al obtener acceso al sitio" de AD FS cuando un usuario federado inicia sesión en Microsoft 365, Azure o Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span><span class="sxs-lookup"><span data-stu-id="5b5b9-106">Follow the steps in the "Scenario 1: The AD FS token-signing certificate expired" section of ["There was a problem accessing the site" error from AD FS when a federated user signs in to Microsoft 365, Azure, or Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span></span>

3. <span data-ttu-id="5b5b9-107">Siga los pasos descritos en [actualizar o reparar la configuración de un dominio federado en Microsoft, Azure o Intune](https://docs.microsoft.com/office365/troubleshoot/security/update-federated-domain-office-365).</span><span class="sxs-lookup"><span data-stu-id="5b5b9-107">Follow the steps in [Update or repair the settings of a federated domain in Microsoft, Azure, or Intune](https://docs.microsoft.com/office365/troubleshoot/security/update-federated-domain-office-365).</span></span>

    <span data-ttu-id="5b5b9-108">Para obtener más información sobre la renovación de certificados de Federación, consulte [renovar certificados de Federación para Microsoft 365 y Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span><span class="sxs-lookup"><span data-stu-id="5b5b9-108">To learn more about renewing Federation certificates, see [Renew federation certificates for Microsoft 365 and Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span></span>
