---
title: Error de corrección 0x8004de40 en OneDrive
ms.author: pebaum
author: pebaum
ms.date: 6/20/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 48b29f57763ca22a71a23b2afddcac0e8e8a95db
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/15/2019
ms.locfileid: "40052054"
---
# <a name="fix-0x8004de40-error-in-onedrive"></a>Error de corrección 0x8004de40 en OneDrive

Si recibe un error 0x8004de40 con OneDrive:

- Reinicie el equipo afectado mientras está conectado a su dominio de directorio de Acitve.
- Si un reinicio no soluciona el problema, separe y vuelva a unirse al dispositivo desde Azure AD. 

**Nota**: debe estar en la red corporativa mientras realiza estos pasos. No realice estos pasos cuando no pueda conectarse a su infraestructura corporativa (por ejemplo, mientras viaja). 

- Abra un símbolo del sistema elevado. 
- Para abrir un símbolo del sistema con privilegios elevados, haga clic en- **iniciar**, haga clic con el botón secundario en **símbolo del sistema**y haga clic en **Ejecutar como administrador**.
- Escriba *dsregcmd/Leave* y presione **entrar**.
- Cuando termine, escriba *dsregcmd/join* y presione **entrar**.
- Cuando termine, cierre el símbolo del sistema.
- Reinicie el equipo e inicie sesión en OneDrive.