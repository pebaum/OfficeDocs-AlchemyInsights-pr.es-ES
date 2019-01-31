---
title: Mover mensajes de correo electrónico para el buzón de archivo
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: 2147c70f64087bf95fc4e39c193caeac3b2c5361
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/30/2019
ms.locfileid: "29660400"
---
Problemas de los elementos en el buzón de archivo de archivado. Asegúrese de que haber realizado los pasos siguientes:
  
1. Confirme que se ha habilitado un **buzón de correo de archivar** . Si no es así, siga los pasos de [este artículo](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) para habilitar el buzón de archivo. 
    
2. En el centro de administración de Exchange, seleccione **Las etiquetas de retención** en **Administración de cumplimiento de normas**, crear una **etiqueta de retención** con la acción **mover a archivo** que contiene la **Antigüedad de retención**de deseada.
    
3. En el centro de administración de Exchange, seleccione **Las directivas de retención**, crear una **Directiva de retención** y agregar la etiqueta de retención **mover a archivo** a esa directiva. 
    
4. [Asignar la directiva de retención](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) para el buzón de un usuario específico. La misma directiva se aplicará a la **principal** y el buzón de **archivo** . 
    
El buzón del usuario ahora debería tener una directiva de archivo para mover los elementos en el buzón de archivo. Es posible que sea necesario forzar la administrados carpeta Ayudante (MFA) para ejecutar y aplicar la nueva configuración para el buzón del usuario. Ejecute el siguiente comando mientras [conectado a EXO de PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) para iniciar el Asistente para carpeta administrada para un buzón específico: 
  
```
Start-ManagedFolderAssistant -Identity <name of the mailbox>
```

Desea obtener más información acerca de cómo configurar una directiva de archivo, vea [Configurar una directiva de eliminación y de archivo para los buzones de correo](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).
  

