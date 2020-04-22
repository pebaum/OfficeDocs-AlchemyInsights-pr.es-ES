---
title: Contra correo electrónico no deseado-5.7.23
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3156"
- "9001196"
ms.openlocfilehash: 307b738c40c620d057e68eff7d218c8c9b5eb665
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43676514"
---
# <a name="fix-email-delivery-issues-for-error-code-5723"></a>Corregir problemas de entrega de correo electrónico para el código de error 5.7.23

Compruebe el registro DNS de SPF de su dominio en un SPF o un comprobador de registros DNS disponible públicamente en la Web.

Compruebe que Microsoft no identificó el mensaje saliente como correo no deseado y se enrutó a través del [grupo de entrega de alto riesgo](https://docs.microsoft.com/office365/SecurityCompliance/high-risk-delivery-pool-for-outbound-messages). Los mensajes del grupo de entrega de alto riesgo no pasarán las comprobaciones de SPF y, por lo tanto, no serán aceptados por la organización de correo electrónico de destino.

Si el problema persiste, es posible que deba ponerse en contacto con el administrador del host de correo al que está intentando enviar correo electrónico. Tome nota del error externo detallado disponible en el mensaje de devolución. Es posible que el soporte técnico de Microsoft no pueda ayudarle más.
