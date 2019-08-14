---
title: 2491 mensajes de correo electrónico de alerta de la Directiva "phish entregado debido a inquilino o usuario reemplazado"
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 2491
ms.assetid: ''
ms.openlocfilehash: 456b186ecea59422c791c79d4df056ad8446bc70
ms.sourcegitcommit: 7c90dcc570d32ebd968e3e4e816a7b482890b3a4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/13/2019
ms.locfileid: "36391548"
---
# <a name="alert-email-messages-from-the-phish-delivered-due-to-tenant-or-user-override-policy"></a>Mensajes de correo electrónico de alerta de la Directiva "phish entregado debido a inquilino o usuario reemplazado"

Se ha realizado una directiva de alerta predeterminada denominada "phish entregado debido a inquilino o usuario reemplazado" a los inquilinos con Office 365 ATP P1 y las licencias P2. Si recibió esta alerta, estos son los pasos para investigar:

1. En el mensaje de alerta, haga clic en **Ver alerta** para ir a la página **alertas** en el centro de seguridad & cumplimiento.

2. Seleccione la alerta para ver la opción de **ver la lista de mensajes** o **ver los mensajes en el explorador**. Ambas opciones le ofrecen los detalles del mensaje, que incluye el identificador del mensaje. Tenga en cuenta que el vínculo del explorador de amenazas filtrará automáticamente los mensajes que coinciden con los criterios de la alerta. Es posible que deba ajustar el filtro de fecha en el explorador de amenazas.

El mensaje de suplantación de identidad se entregó debido a un reemplazo configurado manualmente:

- Un remitente o dominio permitidos establecido por el usuario.

- Un remitente o dominio permitidos establecido por el administrador en una directiva contra correo no deseado.

- Una dirección IP permitida en una directiva de filtro de conexión.

- Una regla de flujo de correo (también denominada regla de transporte) que está configurada para permitir mensajes en.

Si cree que el mensaje se marcó incorrectamente como phish, use el complemento de [mensajes de informe](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) de Outlook para enviar ejemplos de mensajes a Microsoft.
