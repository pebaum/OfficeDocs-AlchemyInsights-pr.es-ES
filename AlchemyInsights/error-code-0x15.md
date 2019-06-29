---
title: Código de error 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "919"
- "2000022"
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Si recibe un error al activar Office 2013 en implementaciones de servicios de escritorio remoto (RDS), considere la posibilidad de habilitar ADAL editando el registro.
ms.openlocfilehash: e2249d8ebbd2313c64dda5656a3243fa76d97a9a
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/28/2019
ms.locfileid: "35388262"
---
Si recibe un error al activar Office 2013 en implementaciones de servicios de escritorio remoto (RDS), considere la posibilidad de habilitar ADAL editando el registro.
  
|**Clave del registro**|**Type**|**Value**|
|:-----|:-----|:-----|
|HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL  <br/> |REG_DWORD  <br/> |1   <br/> |

Para obtener más información, consulte [Habilitar la autenticación moderna para Office 2013 en dispositivos Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).
  
> [!NOTE]
>  ADAL está habilitado de forma predeterminada en Office 365 ProPlus y Office 2016. > servicios de escritorio remoto (RDS) se llamaba Terminal Services.
  