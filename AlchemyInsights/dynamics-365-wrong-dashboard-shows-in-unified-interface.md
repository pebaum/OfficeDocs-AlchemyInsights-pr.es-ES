---
title: Dynamics 365-se muestra un panel incorrecto en la interfaz unificada Dynamics 365
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1484"
- "6200024"
ms.openlocfilehash: 6edf6fbae0174f3fa4d635c7a99e7daae1243b60
ms.sourcegitcommit: a413a0e27ef4ab8c484fa9fccff8bbef381c8b96
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/16/2019
ms.locfileid: "35748829"
---
# <a name="wrong-dashboard-shows-in-dynamics-365-unified-interface"></a>Se muestra un panel equivocado en la interfaz unificada Dynamics 365

Hay varios motivos por los que puede ver un panel diferente del que esperaba:

## <a name="the-user-has-set-a-user-default-dashboard"></a>El usuario ha establecido un panel predeterminado del usuario 

Normalmente, puede identificar un panel predeterminado del usuario si el botón **establecer como predeterminado** no se muestra en la barra de comandos del panel. El panel predeterminado del usuario sobrescribirá el resto de los paneles predeterminados, incluso si el panel predeterminado del usuario no está en la aplicación actual.

Use la siguiente solución alternativa para no desactivar el panel predeterminado.

1. Cree un nuevo panel personal.

2. Establecer ese nuevo panel como usuario predeterminado.

3. Eliminar ese panel.

## <a name="the-dashboard-is-set-in-the-sitemap"></a>El panel se establece en el mapa del sitio

Puede que haya establecido un panel predeterminado de la organización seleccionando un panel y eligiendo "establecer como predeterminado" en "personalizar el sistema". Pero el panel definido en el diseñador de Sitemap tendrá prioridad sobre este panel, si el usuario tiene acceso a él.

Para que los usuarios vean el panel que ha establecido como predeterminado de la organización, puede:

* Establecer ese panel en el mapa del sitio

* Quitar el acceso al panel definido del mapa del sitio para esos usuarios
