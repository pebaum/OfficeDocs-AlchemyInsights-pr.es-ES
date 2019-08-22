---
title: Error de corrección 0x8004de40 en OneDrive
ms.author: kirks
author: Techwriter40
ms.date: 6/20/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: d436184bdc0e283db217ea734fb2c8e05f85b4e7
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36525076"
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