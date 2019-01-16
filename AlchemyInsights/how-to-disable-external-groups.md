---
title: Cómo deshabilitar a grupos externos
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: 4807dbfbabcea1f13785bd39bb48e4bbaa8d0f0f
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28313531"
---
# <a name="how-to-disable-external-groups"></a>Cómo deshabilitar a grupos externos

Yammer mensajería externa aplica reglas de transporte de Exchange (ETRs), un conjunto de controles proactivos para evitar que la información de la empresa desde la que se está compartiendo. Con el fin de evitar que los usuarios crear grupos externos, debe configurar una regla de transporte de Exchange (ETR) y, a continuación, configurar Yammer para usar la regla de transporte de Exchange para bloquear la mensajería externa. 
  
Una vez haya creado una regla en el centro de administración de Exchange Online, siga estos pasos para establecer ETR que se debe aplicar en Yammer:
  
- Inicie sesión en Yammer como un administrador de comprobada y en el **Centro de administración de Yammer**, vaya a C **ontenido y seguridad \> configuración de seguridad.**
    
- En **Mensajería externa**, seleccione **aplicar las reglas de transporte de Exchange Online de Exchange (ETRs) en Yammer.**
    
- Elija **Guardar**. 
    
Para obtener más información, consulte [Control externo de mensajería en una red de Yammer con las reglas de transporte de Exchange](https://support.office.com/en-us/article/Control-external-messaging-in-a-Yammer-network-with-Exchange-Transport-Rules-f8fd6403-c8f3-4307-9230-65304d6000d9)
  

