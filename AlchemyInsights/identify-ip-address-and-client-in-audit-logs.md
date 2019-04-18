---
title: Identificar la dirección IP y el cliente en los registros de auditoría
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1367
ms.assetid: ''
ms.openlocfilehash: 7e30a638de5926aa11b8ae637613a48076d7bdc9
ms.sourcegitcommit: ffe2f489b1ac3aae62aa784c959da6a41c3261eb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/17/2019
ms.locfileid: "31909583"
---
# <a name="identify-ip-address-and-client-in-audit-logs"></a>Identificar la dirección IP y el cliente en los registros de auditoría

La dirección IP que corresponde a una actividad de un usuario o administrador se muestra en los registros de auditoría. También se registra la información del cliente. Estos son los pasos para identificar dicha información

1. Inicie sesión en el [centro de cumplimiento de & de seguridad de Office 365](https://protection.office.com/)

2. Haga clic en **búsqueda e investigación** y seleccione **búsqueda de registros de auditoría**.

   Si está interesado en una actividad específica, selecciónela en la lista **actividades** . Si no es así, se devolverán todas las actividades del usuario seleccionado (configuración predeterminada).

   **Nota**: es posible que algunas actividades no estén disponibles en el menú **actividades** ; sin embargo, estos elementos de auditoría se devolverán si se selecciona **Mostrar resultados para todas las actividades** (configuración predeterminada).

3. Especifique el nombre de usuario en el campo **usuarios** , seleccione el intervalo de fechas adecuado para la actividad y, a continuación, haga clic en **Buscar**.

En los resultados, puede ver la dirección IP de esa actividad en el panel de resultados. Seleccione el registro de auditoría para ver información detallada en **** el control flotante (por ejemplo, el cliente, el usuario que realizó la acción, etc.).

Para obtener más información, consulte [Buscar la dirección IP del equipo usado para obtener acceso a una cuenta en peligro](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).
