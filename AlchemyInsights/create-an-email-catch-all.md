---
title: Crear un correo electrónico atrapar todo
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001524"
- "3732"
ms.openlocfilehash: 35f31c1662547d57c2fc9978ffb495ac29abcc01
ms.sourcegitcommit: 67015549afcbe05f3b77ea314e2ef7e0e439f9f2
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/26/2020
ms.locfileid: "42286308"
---
# <a name="create-an-email-catch-all"></a>Crear un correo electrónico atrapar todo

No se recomienda el uso de una instrucción Catch. Es mejor proporcionar un rebote al remitente que permita que los remitentes sepan que no se pudo entregar el mensaje como dirigido para que puedan actuar. También puede limitar el buzón supervisado para que solo detecte direcciones de correo electrónico válidas anteriormente. 

Cualquier buzón de correo de tipo catch recibirá una buena cantidad de correo no deseado y puede, eventualmente, completarse si no está bien supervisado. (Hay límites de recepción). 

Si decide continuar, siga estos pasos:

1. Cree un grupo de distribución dinámico & incluya "todos los tipos de destinatarios".

2. Cree un buzón dedicado para capturar los mensajes de correo electrónico, por ejemplo, catchall@domain.com.

3. Para el dominio específico, establezca DomainType en "InternalRelay". Si más tarde quita la instrucción Catch, asegúrese de volver a establecer el dominio en autoritativo.

4. Cree una regla de transporte de flujo de flujo como sigue:

    - Si el remitente es "fuera de la organización"
    - Redirigir el mensaje a Catchall@domain.com
    - Excepto si el destinatario es miembro de allusers@domain.com (el grupo de distribución contiene todos los miembros)
    - Asegurarse de que valida que los nuevos buzones se agregan al grupo de distribución dinámico
