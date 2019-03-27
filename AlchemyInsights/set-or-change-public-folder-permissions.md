---
title: Establecimiento o cambio de permisos de carpetas públicas
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 8/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cffdf9bf-34ce-40f6-a69e-d02f17d9caef
ms.openlocfilehash: d1554e8a63455f3549044e526183c0e8709f2631
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/22/2019
ms.locfileid: "30767301"
---
# <a name="permissions-and-public-folders"></a>Permisos y carpetas públicas

Puede cambiar los permisos de las carpetas públicas con Outlook, el centro de administración de Exchange (EAC) o PowerShell:
  
- Para obtener instrucciones de Outlook, [haga clic aquí](https://support.office.com/article/Set-or-change-permissions-for-a-public-folder-b2e0440c-7873-48ec-9ff2-b1a20b723005.aspx).
    
- Para EAC, consulte [este artículo](https://technet.microsoft.com/library/jj651147%28v=exchg.150%29.aspx.aspx#Anchor_1) para obtener instrucciones. Puede hacer clic [aquí](https://support.office.com/article/ https://outlook.office365.com/ecp/.aspx) para ir a EAC. 
    
- Para PowerShell, consulte [este artículo](https://technet.microsoft.com/library/bb124743%28v=exchg.160%29.aspx.aspx) para obtener instrucciones sobre cómo usar el cmdlet sharepointsync Add-PublicFolderClientPermission. Si necesita instrucciones para conectarse a Exchange PowerShell, haga clic [aquí](https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx.aspx).
    
Si **los usuarios externos no pueden enviar correos electrónicos a una carpeta pública habilitada para correo**, la razón podría ser que faltan los permisos necesarios para la entrega de correo electrónico externa en la carpeta pública. Para solucionarlo, use las instrucciones de Outlook [aquí](https://technet.microsoft.com/library/aa997560%28v=exchg.150%29.aspx.aspx#Anchor_1)o las instrucciones de PowerShell que se [enumeran aquí](https://support.microsoft.com/help/2984402/-5.7.1-smtp-550-5.7.1-resolver.rst.authrequired-nondelivery-report-when-external-users-try-to-send-mail-to-mail-enabled-public-folders-in-office-365.aspx).
  

