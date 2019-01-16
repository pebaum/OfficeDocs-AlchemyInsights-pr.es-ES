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
ms.openlocfilehash: c608489be8497233d9d4f87ec53649026b823250
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28313731"
---
# <a name="adfs-federation-certificate-expiring"></a>Federación de ADFS certificado a expirar

Para resolver este problema, siga estos pasos:
  
1. Instale el Microsoft Azure Active Directory módulo para Windows PowerShell en el equipo (si el módulo ya no está instalado). Para ello, vaya a [administrar Windows Azure con Windows PowerShell](https://aka.ms/aadposh).
    
2. Siga los pasos descritos en la "escenario 1: el certificado de firma de tokens de AD FS caducado" sección de [error "Se ha producido un problema al obtener acceso el sitio" desde AD FS cuando un usuario federado inicia sesión en Office 365, Azure o Intune](https://support.microsoft.com/en-us/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).
    
3. Siga los pasos descritos en [cómo actualizar o reparar la configuración de un dominio federado en Office 365, Azure o Intune](https://support.microsoft.com/en-us/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).
    
    Para obtener más información acerca de cómo renovar certificados de federación, vea [renovar los certificados de federación de Office 365 y Azure Active Directory](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect-o365-certs).
    
