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
ms.openlocfilehash: 89a4dd910d43d70e849be19d5f88e281f6d19834
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28313471"
---
# <a name="one-of-your-on-premises-federation-service-certificates-is-expiring"></a>Uno de los certificados de servicio de federación local va a expirar

Para resolver este problema, siga estos pasos:
  
- Instale el Microsoft Azure Active Directory módulo para Windows PowerShell en el equipo (si el módulo ya no está instalado). Para ello, vaya a [Azure Active Directory PowerShell para gráfico](https://docs.microsoft.com/en-us/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)
    
- Siga los pasos descritos en la "escenario 1: el certificado de firma de tokens de AD FS caducado" sección de [error "Se ha producido un problema al obtener acceso el sitio" desde AD FS cuando un usuario federado inicia sesión en Office 365, Azure o Intune](https://support.microsoft.com/en-us/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).
    
- Siga los pasos descritos en[cómo actualizar o reparar la configuración de un dominio federado en Office 365, Azure o Intune](https://support.microsoft.com/en-us/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3)t.
    
Para obtener más información acerca de cómo renovar certificados de federación, vea [renovación de certificados para Office 365 y Azure AD](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect-o365-certs).
  

