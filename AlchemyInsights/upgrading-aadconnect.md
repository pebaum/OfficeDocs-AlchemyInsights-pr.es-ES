---
title: 932 actualizar los
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "932"
- "1300025"
ms.assetid: 8f43f36c-9722-43a4-b0de-c5341c06dac5
ms.openlocfilehash: ff3f74348599788edd8ce0991fe49bb6a54b55af
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36506100"
---
# <a name="upgrade-azure-ad-connect"></a>Actualizar Azure AD Connect

De forma predeterminada, la actualización automática está habilitada para Azure AD Connect, lo que ayuda a asegurarse de que está ejecutando la versión más reciente. Para comprobar la configuración de la actualización automática, use el cmdlet **Get-ADSyncAutoUpgrade** en Azure ad PowerShell. El cmdlet devolverá uno de los siguientes valores:

- **Habilitada**: la actualización automática está habilitada.

- **** Deshabilitado: la actualización automática está deshabilitada.

- **Suspendido**: el sistema ya no cumple los requisitos para recibir actualizaciones automáticas. No puede configurar este valor; se establece en el sistema.

Para obtener más información, consulte [actualización automática](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).

Para descargar la versión más reciente de Azure AD Connect, vaya [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594)a.
