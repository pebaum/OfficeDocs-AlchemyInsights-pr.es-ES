---
title: 1332 OWA - reglas de bandeja de entrada no se ejecutan para un buzón de correo
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 383d1c77-5e4b-4a69-92d6-c404d890b6b7
ms.openlocfilehash: 0d3b7ce3d6b32d94a012eb3767c0747eed80f6e5
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29915821"
---
# <a name="an-inbox-rule-doesnt-work-as-expected"></a>Una regla de bandeja de entrada no funciona como se esperaba

Compruebe la configuración siguiente:
  
- Puede redirigir un mensaje, reenviado o respondido automáticamente en función de las reglas de bandeja de entrada sólo una vez. Una regla de redirección (una regla de bandeja de entrada o una regla de flujo de correo, también conocido como una regla de transporte) puede agregar un máximo de diez de reenvío de destinatarios a un mensaje. Para obtener más información, vea [los límites de regla de diario, transporte y Bandeja de entrada](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).
    
- Reglas de bandeja de entrada no funcionan en el buzón de registro en diario alternativo. Para obtener más información acerca del buzón de registro en diario alternativo, consulte [mailbox de registro en diario alternativo](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).
    
Para solucionar estos problemas, vea [KB 2829319](https://support.microsoft.com/kb/2829319).
  
Si no se aplican los problemas anteriores, ejecute el informe de diagnóstico de regla de bandeja de entrada antes de pasar el problema a Microsoft Support:
  
1. Abra el buzón de correo en Outlook en el web y haga clic en **configuración de** \> **Opciones** \> **correo electrónico organizar** \> **reglas de bandeja de entrada**.
    
2. En la parte inferior de la página, haga clic en **si las reglas no funcionan, haga clic aquí para generar un informe de diagnóstico**.
    

