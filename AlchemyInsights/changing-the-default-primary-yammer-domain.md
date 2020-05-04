---
title: Cambiar el dominio de Yammer predeterminado
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002662"
- "5162"
ms.openlocfilehash: 099feb5c58a2b1068a2ec501ff966c6ac73d804d
ms.sourcegitcommit: 87aa36e3ff4835efb120a320c5169bfa77199ec4
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 05/01/2020
ms.locfileid: "43991328"
---
# <a name="changing-the-defaultprimary-yammer-domain"></a>Cambiar el dominio de Yammer principal o predeterminado

La URL de Yammer contiene el nombre de dominio principal actual para la red de Yammer. Este nombre de dominio puede no coincidir con el conjunto de nombres de dominio principal en Office 365 o Azure AD. Las diferencias en el comportamiento se basan en el número de dominios personalizados que se agregan al espacio empresarial y en si Yammer se encuentra en una configuración admitida (1 espacio empresarial: 1 red o 1:1). Hay documentación sobre [dominios de Yammer y Office 365](https://docs.microsoft.com/yammer/configure-your-yammer-network/manage-yammer-domains) disponible.

El motivo más común por el que se ve un dominio incorrecto es que existen varias redes de Yammer y deben combinarse. [Combinar en una sola red](https://docs.microsoft.com/yammer/configure-your-yammer-network/consolidate-multiple-yammer-networks) con la herramienta de migración de red es un primer paso importante. Realice esto antes de intentar establecer el dominio principal.

**No hay dominios personalizados**

Para los nuevos espacios empresariales, el dominio predeterminado (por ejemplo, fabrikam.onmicrosoft.com) del espacio empresarial se usará para Yammer. El dominio principal se establece en yammer.com/fabrikam.onmicrosoft.com.

**Único dominio personalizado**

Yammer seleccionará automáticamente el dominio personalizado (por ejemplo, fabrikam.com) del espacio empresarial como el dominio principal en Yammer. Se establece en yammer.com/fabrikam.com. Este cambio lo realiza el servicio de sincronización del dominio y puede tardar hasta 24 horas en aplicarse.

**Varios dominios personalizados**

Yammer puede tener un dominio principal distinto del dominio del espacio empresarial predeterminado. Ya que hay varios dominios personalizados, Yammer no intenta adivinar el dominio correcto entre los disponibles. Debe abrir un caso de soporte técnico para solicitar que el nombre de dominio principal se cambie al dominio principal que prefiera.

**Información de solución de problemas adicional**

En algunos casos, es posible que se hayan movido dominios entre espacios empresariales y el servicio de sincronización del dominio no se haya podido ejecutar correctamente. Es posible que se produzcan problemas de inicio de sesión o de otro tipo, además de un dominio principal incorrecto. Para resolver este problema, es posible que tenga que mover los dominios a la red adecuada con la ayuda del Soporte técnico de Microsoft. Esta situación requiere asistencia directa y puede tardar algún tiempo en solucionarse, especialmente si hay una lista de nombres de dominio muy larga. Abra un caso de soporte técnico para obtener ayuda con la resolución de estos tipos de problemas.

Cuando trabaje con agentes de soporte técnico, comprobarán que los dominios estén verificados en un espacio empresarial de su control. Es posible que formulen preguntas adicionales de verificación sobre sus dominios si se han agregado a su espacio empresarial, pero no se han comprobado por DNS. Asegúrese de que los dominios están comprobados por DNS para acelerar el proceso.
