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
ms.openlocfilehash: eafd31e91340b41b7948fb1fe62889731b816d9a
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/18/2019
ms.locfileid: "36737206"
---
# <a name="adfs-federation-certificate-expiring"></a>Expiración del certificado de Federación de ADFS

Para resolver este problema, siga estos pasos:
  
1. Instale el módulo Microsoft Azure Active Directory para Windows PowerShell en el equipo (si el módulo no está instalado ya). Para ello, vaya a [administrar Azure ad con Windows PowerShell](https://aka.ms/aadposh).

2. Siga los pasos descritos en la sección "escenario 1: el certificado de firma de tokens de AD FS ha expirado" del [mensaje "se ha producido un problema al obtener acceso al sitio" de AD FS cuando un usuario federado inicia sesión en Office 365, Azure o Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).

3. Siga los pasos descritos en [actualizar o reparar la configuración de un dominio federado en Office 365, Azure o Intune](https://docs.microsoft.com/office365/troubleshoot/security/update-federated-domain-office-365).

    Para obtener más información sobre la renovación de certificados de Federación, consulte [renovar certificados de Federación para Office 365 y Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).
