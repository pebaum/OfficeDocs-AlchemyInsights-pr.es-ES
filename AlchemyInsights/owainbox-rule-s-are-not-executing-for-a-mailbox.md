---
title: 1332 OWA-las reglas de la bandeja de entrada no se ejecutan para un buzón
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1332
ms.assetid: 383d1c77-5e4b-4a69-92d6-c404d890b6b7
ms.openlocfilehash: c0b221b5335254bd0f1eb4b258efa6946376ca12
ms.sourcegitcommit: 1a4b8fa9e38a95ca811085af516edb81caf2018c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/13/2019
ms.locfileid: "31858761"
---
# <a name="an-inbox-rule-doesnt-work-as-expected"></a>Una regla de la bandeja de entrada no funciona como se esperaba

Compruebe las siguientes opciones de configuración:

- Un mensaje puede redirigirse, reenviarse o responderse automáticamente en función de las reglas de la bandeja de entrada sólo una vez. Una regla de redireccionamiento (una regla de bandeja de entrada o una regla de flujo de correo, también denominada regla de transporte) puede Agregar un máximo de diez destinatarios de reenvío a un mensaje. Para obtener más información, vea los límites de las [reglas diario, transporte y bandeja de entrada](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).

- Las reglas de la bandeja de entrada no funcionan en el buzón de registro en diario alternativo. Para obtener más información acerca del buzón de correo de registro en diario alternativo, consulte [buzón de registro en diario alternativo](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).

Para solucionar estos problemas, consulte [KB 2829319](https://support.microsoft.com/kb/2829319).

Si no se aplican los problemas anteriores, ejecute el informe de diagnóstico de reglas de la bandeja de entrada antes de remitir el problema al soporte técnico de Microsoft:

1. Abra el buzón en Outlook en la web y haga clic en **Opciones** \> de **configuración** \> para organizar **las reglas**de la bandeja de entrada de **correo electrónico** \> .

2. En la parte inferior de la página, haga clic en **si las reglas no funcionan haga clic aquí para generar un informe de diagnóstico**.
