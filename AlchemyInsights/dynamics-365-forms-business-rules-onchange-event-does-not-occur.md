---
title: 'Dynamics 365 Forms Business Rules: regla de negocios que no se desencadena para un formulario'
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1926"
- "6200018"
ms.openlocfilehash: 4ade8d2f68b465298e2d6efff3eef4f04f25c3bf
ms.sourcegitcommit: a413a0e27ef4ab8c484fa9fccff8bbef381c8b96
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/16/2019
ms.locfileid: "35748833"
---
# <a name="onchange-event-does-not-occur-if-the-field-is-changed-programmatically"></a>El evento OnChange no se produce si el campo se cambia mediante programación

El evento *onchange* no se produce si el campo se cambia mediante programación con el *atributo.* método [SetValue](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) . Si desea que se ejecuten controladores de eventos del evento *onchange* después de establecer el valor, debe usar el *atributo formContext. Data. Entity.* método [fireOnchange](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) en el código.

[https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange)
