---
title: Cómo deshabilitar grupos externos
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "966"
- "6000006"
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: 95e60599b5298090db23bf887cb860350280964f
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/28/2019
ms.locfileid: "35384842"
---
# <a name="how-to-disable-external-groups"></a>Cómo deshabilitar grupos externos

La mensajería externa de Yammer aplica reglas de transporte de Exchange (ETR), un conjunto de controles proactivos para impedir el uso compartido de la información de la empresa. Para restringir a los usuarios la creación de grupos externos, debe configurar una regla de transporte de Exchange (ETR) y, a continuación, configurar Yammer para usar la regla de transporte de Exchange para bloquear la mensajería externa.
  
Una vez que haya creado una regla en el centro de administración de Exchange Online, siga estos pasos para establecer ETR para que se aplique en Yammer:
  
- Inicie sesión en Yammer como administrador verificado y, en el **centro de administración de Yammer**, vaya a la **configuración \> de seguridad de seguridad y contenido** de C.

- En **Mensajería externa**, seleccione **aplicar las reglas de transporte de Exchange Online Exchange (ETR) en Yammer.**

- Elija **Guardar**.

Para obtener más información, consulte [controlar la mensajería externa en una red de Yammer con las reglas de transporte de Exchange](https://support.office.com/article/Control-external-messaging-in-a-Yammer-network-with-Exchange-Transport-Rules-f8fd6403-c8f3-4307-9230-65304d6000d9)
  