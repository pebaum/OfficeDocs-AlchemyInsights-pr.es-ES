---
title: Expiración del certificado de Federación de ADFS
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/8/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "645"
- "1300012"
ms.assetid: 26a7eebb-1424-4ddc-a123-af1cc94bc40f
ms.openlocfilehash: c9922258c2d203cc07c1a1055ffa36c23a756115
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36499908"
---
# <a name="adfs-federation-certificate-expiring"></a><span data-ttu-id="b649c-102">Expiración del certificado de Federación de ADFS</span><span class="sxs-lookup"><span data-stu-id="b649c-102">ADFS Federation Certificate Expiring</span></span>

<span data-ttu-id="b649c-103">Para resolver este problema, siga estos pasos:</span><span class="sxs-lookup"><span data-stu-id="b649c-103">To resolve this issue, follow these steps:</span></span>
  
1. <span data-ttu-id="b649c-104">Instale el módulo Microsoft Azure Active Directory para Windows PowerShell en el equipo (si el módulo no está instalado ya).</span><span class="sxs-lookup"><span data-stu-id="b649c-104">Install the Microsoft Azure Active Directory Module for Windows PowerShell on the computer (if the module isn't already installed).</span></span> <span data-ttu-id="b649c-105">Para ello, vaya a [administrar Azure ad con Windows PowerShell](https://aka.ms/aadposh).</span><span class="sxs-lookup"><span data-stu-id="b649c-105">To do this, go to [Manage Azure AD using Windows PowerShell](https://aka.ms/aadposh).</span></span>

2. <span data-ttu-id="b649c-106">Siga los pasos descritos en la sección "escenario 1: el certificado de firma de tokens de AD FS ha expirado" del [mensaje "se ha producido un problema al obtener acceso al sitio" de AD FS cuando un usuario federado inicia sesión en Office 365, Azure o Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span><span class="sxs-lookup"><span data-stu-id="b649c-106">Follow the steps in the "Scenario 1: The AD FS token-signing certificate expired" section of ["There was a problem accessing the site" error from AD FS when a federated user signs in to Office 365, Azure, or Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span></span>

3. <span data-ttu-id="b649c-107">Siga los pasos [que se indican en cómo actualizar o reparar la configuración de un dominio federado en Office 365, Azure o Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span><span class="sxs-lookup"><span data-stu-id="b649c-107">Follow the steps in [How to update or repair the settings of a federated domain in Office 365, Azure, or Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span></span>

    <span data-ttu-id="b649c-108">Para obtener más información sobre la renovación de certificados de Federación, consulte [renovar certificados de Federación para Office 365 y Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span><span class="sxs-lookup"><span data-stu-id="b649c-108">To learn more about renewing Federation certificates, see [Renew federation certificates for Office 365 and Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span></span>
