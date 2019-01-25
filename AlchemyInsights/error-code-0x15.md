---
title: Código de error 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Si recibe un error durante la activación de Office 2013 en las implementaciones de servicios de escritorio remoto (RDS), considere la posibilidad de habilitar ADAL mediante la edición del registro.
ms.openlocfilehash: 89f9270169e13fd7706f7826c624ef8ae4d47b3f
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29499399"
---
Si recibe un error durante la activación de Office 2013 en las implementaciones de servicios de escritorio remoto (RDS), considere la posibilidad de habilitar ADAL mediante la edición del registro. 
  
|**Clave del registro**|**Tipo**|**Valor**|
|:-----|:-----|:-----|
|HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL  <br/> |REG_DWORD  <br/> |^1  <br/> |
   
Para obtener más información, vea [Habilitar moderno Authentication for Office 2013 en dispositivos de Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).
  
> [!NOTE]
>  ADAL está habilitada de forma predeterminada en Office 365 ProPlus y Office 2016. > servicios de escritorio remoto (RDS) se denominaba anteriormente Terminal Services. 
  

