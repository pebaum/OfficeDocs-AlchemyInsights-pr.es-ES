---
title: 932 actualizar los
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "932"
- "1300025"
ms.assetid: 8f43f36c-9722-43a4-b0de-c5341c06dac5
ms.openlocfilehash: fcc5fddb5cfd15407d0533449035317d187931ed
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766510"
---
# <a name="upgrade-azure-ad-connect"></a>Actualizar Azure AD Connect

De forma predeterminada, la actualización automática está habilitada para Azure AD Connect, lo que ayuda a asegurarse de que está ejecutando la versión más reciente. Para comprobar la configuración de la actualización automática, use el cmdlet **Get-ADSyncAutoUpgrade** en Azure ad PowerShell. El cmdlet devolverá uno de los siguientes valores:

- **Habilitada**: la actualización automática está habilitada.

- **Deshabilitado**: la actualización automática está deshabilitada.

- **Suspendido**: el sistema ya no cumple los requisitos para recibir actualizaciones automáticas. No puede configurar este valor; se establece en el sistema.

Para obtener más información, consulte [actualización automática](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).

Para descargar la versión más reciente de Azure AD Connect, vaya [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594)a.
