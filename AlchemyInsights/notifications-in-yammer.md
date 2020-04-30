---
title: Notificaciones de Yammer
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002878"
- "5480"
ms.openlocfilehash: ff4c13560b9cbf283e5c6b92a259debdf96cca62
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/27/2020
ms.locfileid: "43911919"
---
# <a name="notifications-in-yammer"></a>Notificaciones de Yammer

Para alertarle sobre una nueva actividad en conversaciones relevantes, [Yammer envía notificaciones](https://support.microsoft.com/en-gb/office/enable-or-disable-yammer-email-and-phone-notifications-93e530e0-189f-4768-8f28-7683d48cc996) ya sea por correo electrónico o, si usa Yammer en su dispositivo móvil, a través de notificaciones de inserción. De forma predeterminada, Yammer envía notificaciones para muchos tipos de actividad en la red. Los usuarios pueden actualizar la configuración del correo electrónico a través del sitio web de Yammer y las notificaciones de inserción se configuran con la aplicación móvil. 

Yammer ha agregado compatibilidad para [correos electrónicos interactivos en Outlook](https://techcommunity.microsoft.com/t5/outlook-blog/interactive-yammer-emails-in-outlook-on-the-web-are-here/ba-p/1209420). Algunos mensajes de correo electrónico (copia del mensaje) serán interactivos en Outlook en la Web. Una actualización posterior lo llevará a otras versiones de Outlook.

**Tipos de notificaciones en Yammer**

- Correos electrónicos (actualizaciones de un grupo, alguien le invita a un grupo, recibe un mensaje en la bandeja de entrada, etc.)
- Notificaciones de inserción (enviadas a dispositivos móviles cuando le mencionen, reciba un mensaje en su bandeja de entrada, etc.)
- Mensajes emergentes de escritorio (cuando haya instalado la aplicación de escritorio de Yammer, mostrará notificaciones para los usuarios llamadas "notificaciones del sistema").
- Avisos de campana (en el sitio web de Yammer, los usuarios verán notificaciones para diferentes eventos. Es posible que estas notificaciones no siempre tengan un correo electrónico o una notificación de inserción asociada.

Existe más [Información detallada sobre las notificaciones](https://support.microsoft.com/en-gb/office/enable-or-disable-yammer-email-and-phone-notifications-93e530e0-189f-4768-8f28-7683d48cc996).

**Administrar notificaciones**

Los usuarios deben administrar sus propias notificaciones. La información está disponible en [cómo habilitar y deshabilitar las notificaciones de correo electrónico y móvil de Yammer](https://support.microsoft.com/en-gb/office/enable-or-disable-yammer-email-and-phone-notifications-93e530e0-189f-4768-8f28-7683d48cc996). 

Los administradores no pueden deshabilitar todas las notificaciones o controlar las notificaciones en nombre de los usuarios. Los administradores pueden [controlar el logotipo incluido en los correos electrónicos y si los usuarios necesitan confirmar los mensajes](https://docs.microsoft.com/yammer/configure-your-yammer-network/configure-email-and-yammer) publicados por correo electrónico.

**Notificaciones por correo electrónico enviadas a varios usuarios de la organización**

En ocasiones, Yammer enviará una única notificación por correo electrónico y la recibirán muchos más usuarios de su organización de lo esperado. Esto sucede cuando se agrega una lista de distribución, u otro tipo de dirección de correo electrónico no individual, a Yammer. Yammer no sabe en todos los casos si una dirección de correo electrónico pertenece a un solo usuario o si es una dirección de correo electrónico que hará que se envíe un correo electrónico a muchos destinatarios. Cuando se produce este problema, debe tomar medidas para [suspender (desactivar) el usuario no válido con esa dirección de correo electrónico](https://docs.microsoft.com/yammer/manage-yammer-users/add-block-or-remove-users#remove-users) en Yammer. 

Para reducir la probabilidad de que este problema se produzca, debería:

1. [Exigir la identidad de Office 365](https://docs.microsoft.com/yammer/configure-your-yammer-network/enforce-office-365-identity) para Yammer.
2. Evitar que los remitentes externos envíen correos electrónicos a su organización, o limitar los remitentes a una lista aprobada.

Si se produce este problema:

1. Identifique el destinatario del correo electrónico, que debería coincidir con el usuario de Yammer. Por ejemplo, all-in-sales@fabrikam.com es una lista de distribución para todos los usuarios de ventas. Esta lista de distribución se puede identificar desde el correo electrónico de Yammer recibido por los usuarios.
2. Use la [característica desactivar (suspender) en el Administrador de red](https://docs.microsoft.com/yammer/manage-yammer-users/add-block-or-remove-users#remove-users) para suspender al usuario que tiene la dirección de correo electrónico all-in-sales@fabrikam.com. La suspensión se puede deshacer, por lo que es más seguro que la eliminación. La eliminación del usuario se producirá automáticamente después de 90 días.
3. También puede revisar la [Exportación de usuarios](https://docs.microsoft.com/yammer/manage-security-and-compliance/export-yammer-enterprise-data#ExportUsers) para identificar otras direcciones de correo electrónico que no sean de usuario que se deban suspender.
