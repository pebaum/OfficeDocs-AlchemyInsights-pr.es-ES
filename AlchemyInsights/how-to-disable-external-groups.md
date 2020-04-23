---
title: Cómo deshabilitar grupos externos
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "966"
- "6000006"
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: 2159feb4aa3999072de57d76790a2959c7355976
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43720785"
---
# <a name="how-to-disable-external-groups"></a>Cómo deshabilitar grupos externos

La mensajería externa de Yammer aplica reglas de transporte de Exchange (ETR), un conjunto de controles proactivos para impedir el uso compartido de la información de la empresa. Para restringir a los usuarios la creación de grupos externos, debe configurar una regla de transporte de Exchange (ETR) y, a continuación, configurar Yammer para usar la regla de transporte de Exchange para bloquear la mensajería externa.
  
Una vez que haya creado una regla en el centro de administración de Exchange Online, siga estos pasos para establecer ETR para que se aplique en Yammer:
  
- Inicie sesión en Yammer como administrador verificado y, en el **centro de administración de Yammer**, vaya a la **configuración \> de seguridad de seguridad y contenido** de C.

- En **Mensajería externa**, seleccione **aplicar las reglas de transporte de Exchange Online Exchange (ETR) en Yammer.**

- Elija **Guardar**.

Para obtener más información, vea [deshabilitar la mensajería externa en una red de Yammer](https://docs.microsoft.com/yammer/work-with-external-users/disable-external-messaging).
  