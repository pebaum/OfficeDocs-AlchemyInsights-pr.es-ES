---
title: Uno de los certificados del servicio de Federación local va a expirar
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 172084b7-68a1-42a5-944d-2e871eaa2972
ms.openlocfilehash: 00cbc77cb178d59a3115e44874a16f506e4408c6
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36543582"
---
# <a name="one-of-your-on-premises-federation-service-certificates-is-expiring"></a>Uno de los certificados del servicio de Federación local va a expirar

Para resolver este problema, siga estos pasos:
  
- Instale el módulo Microsoft Azure Active Directory para Windows PowerShell en el equipo (si el módulo no está instalado ya). Para ello, vaya a [Azure Active Directory PowerShell para Graph](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)
    
- Siga los pasos descritos en la sección "escenario 1: el certificado de firma de tokens de AD FS ha expirado" del [mensaje "se ha producido un problema al obtener acceso al sitio" de AD FS cuando un usuario federado inicia sesión en Office 365, Azure o Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).
    
- Siga los pasos que se indican en t[Cómo actualizar o reparar la configuración de un dominio federado en Office 365, Azure o Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).
    
Para obtener más información acerca de la renovación de certificados de Federación, consulte [renovación de certificados para O365 y Azure ad](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).
  

