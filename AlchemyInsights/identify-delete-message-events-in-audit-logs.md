---
title: Identificar eventos de eliminación de mensajes en registros de auditoría
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1370"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 797a4b1146862faf91d2b9e8d74feade90f71650
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716513"
---
# <a name="audit-logs-for-deleted-email-messages"></a>Registros de auditoría para mensajes de correo electrónico eliminados

A partir de enero 2019, Microsoft activa el registro de auditoría de buzones de correo de forma predeterminada. De lo contrario, para revisar los eventos eliminar mensaje para un usuario específico, debe habilitar manualmente las acciones de eliminación para auditar. Si el registro de auditoría de buzones de correo ya está habilitado para su organización o para el usuario específico, siga los pasos que se indican a continuación.

1. Inicie sesión en el [centro de cumplimiento de & de seguridad de Microsoft 365](https://protection.office.com/)

2. Haga clic en **búsqueda e investigación** y seleccione **búsqueda de registros de auditoría**.

3. Seleccione el intervalo de fechas en los campos **fecha de inicio** y **fecha de finalización** . Especifique el nombre de usuario del usuario que desea investigar (el usuario que eliminó los elementos). En el campo **actividades** , seleccione **mensajes eliminados de la carpeta elementos eliminados** y **mensajes movidos a la carpeta elementos eliminados**.

4. Haga clic en **Buscar**.

En los resultados, seleccione un registro de auditoría. En el control flotante de detalles, haga clic en **más información**. La información adicional sobre el elemento eliminado (por ejemplo, la línea de asunto y la ubicación del elemento cuando se eliminó) se muestra en el campo **AffectedItems** . La propiedad **ClientInfoString** se mostrará si la eliminación se produjo en Outlook, en Outlook en la web (anteriormente conocido como Outlook Web App) o en cualquier otro dispositivo.

Para obtener más información, vea [determinar quién ha configurado el reenvío de correo para un buzón](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-deleted-email-items).

**Nota**: no puede recuperar elementos eliminados con la característica de registro de auditoría. Para recuperar los mensajes eliminados en Outlook en la web, vea [recuperar elementos eliminados en Outlook Web App](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).
