---
title: 1332 OWA - reglas de bandeja de entrada no se ejecutan para un buzón de correo
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 383d1c77-5e4b-4a69-92d6-c404d890b6b7
ms.openlocfilehash: f090d0a9d84bc6a4d1a1f4c0af55102d4b0ddfbe
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28314240"
---
# <a name="an-inbox-rule-doesnt-work-as-expected"></a>Una regla de bandeja de entrada no funciona como se esperaba

Compruebe la configuración siguiente:
  
- Puede redirigir un mensaje, reenviado o respondido automáticamente en función de las reglas de bandeja de entrada sólo una vez. Una regla de redirección (una regla de bandeja de entrada o una regla de flujo de correo, también conocido como una regla de transporte) puede agregar un máximo de diez de reenvío de destinatarios a un mensaje. Para obtener más información, vea [los límites de regla de diario, transporte y Bandeja de entrada](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).
    
- Reglas de bandeja de entrada no funcionan en el buzón de registro en diario alternativo. Para obtener más información acerca del buzón de registro en diario alternativo, consulte [mailbox de registro en diario alternativo](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).
    
Para solucionar estos problemas, vea [KB 2829319](https://support.microsoft.com/kb/2829319).
  
Si no se aplican los problemas anteriores, ejecute el informe de diagnóstico de regla de bandeja de entrada antes de pasar el problema a Microsoft Support:
  
1. Abra el buzón de correo en Outlook en el web y haga clic en **configuración de** \> **Opciones** \> **correo electrónico organizar** \> **reglas de bandeja de entrada**.
    
2. En la parte inferior de la página, haga clic en **si las reglas no funcionan, haga clic aquí para generar un informe de diagnóstico**.
    

