---
title: Código de error 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Si recibe un error durante la activación de Office 2013 en las implementaciones de servicios de escritorio remoto (RDS), considere la posibilidad de habilitar ADAL mediante la edición del registro.
ms.openlocfilehash: 6d4076ecb5c6ee3c3cf4c4610ad4aa29ab477d8a
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29929109"
---
Si recibe un error durante la activación de Office 2013 en las implementaciones de servicios de escritorio remoto (RDS), considere la posibilidad de habilitar ADAL mediante la edición del registro. 
  
|**Clave del registro**|**Tipo**|**Valor**|
|:-----|:-----|:-----|
|HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL  <br/> |REG_DWORD  <br/> |1  <br/> |
   
Para obtener más información, vea [Habilitar moderno Authentication for Office 2013 en dispositivos de Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).
  
> [!NOTE]
>  ADAL está habilitada de forma predeterminada en Office 365 ProPlus y Office 2016. > servicios de escritorio remoto (RDS) se denominaba anteriormente Terminal Services. 
  

