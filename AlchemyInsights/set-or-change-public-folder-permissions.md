---
title: Establecer o cambiar los permisos de carpetas públicas
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 8/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: cffdf9bf-34ce-40f6-a69e-d02f17d9caef
ms.openlocfilehash: e4e98ba3e7dff2bd86be4667d7262c9544f9c9cb
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29899225"
---
# <a name="permissions-and-public-folders"></a>Los permisos y las carpetas públicas

Puede cambiar los permisos en las carpetas públicas con Outlook, el centro de administración de Exchange (EAC), o PowerShell:
  
- Para obtener instrucciones Outlook, [haga clic aquí](https://support.office.com/article/Set-or-change-permissions-for-a-public-folder-b2e0440c-7873-48ec-9ff2-b1a20b723005.aspx).
    
- Para CEF, consulte [este artículo](https://technet.microsoft.com/library/jj651147%28v=exchg.150%29.aspx.aspx#Anchor_1) para obtener instrucciones. Puede hacer clic [aquí](https://support.office.com/article/ https://outlook.office365.com/ecp/.aspx) para desplazarse al CEF. 
    
- Para Powershell, consulte [este artículo](https://technet.microsoft.com/library/bb124743%28v=exchg.160%29.aspx.aspx) para obtener instrucciones sobre cómo utilizar el cmdlet Add-PublicFolderClientPermission. Si necesita instrucciones para conectarse a Exchange Powershell, haga clic en [aquí](https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx.aspx).
    
Si **los usuarios externos no pueden enviar mensajes de correo electrónico a una carpeta pública habilitada para correo**, la razón es posible que se que la carpeta pública falta los permisos necesarios para la entrega de correo electrónico externa. Puede corregirlo mediante las instrucciones de Outlook [aquí](https://technet.microsoft.com/library/aa997560%28v=exchg.150%29.aspx.aspx#Anchor_1)o en las instrucciones de PowerShell [aquí](https://support.microsoft.com/help/2984402/-5.7.1-smtp-550-5.7.1-resolver.rst.authrequired-nondelivery-report-when-external-users-try-to-send-mail-to-mail-enabled-public-folders-in-office-365.aspx).
  

