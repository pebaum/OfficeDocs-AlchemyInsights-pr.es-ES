---
title: igual que el nombre de archivo es mejor
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: e2dcca1295e37007593b34c2d818ad1d1133e4a1
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43676550"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a>Falta el encabezado de Alchemy H1, H2's no funciona.
Procedimientos recomendados y directrices para la creación de Alchemy:

1. **No anide información de Alchemy en las carpetas**: esto interrumpirá la estructura de la dirección URL. Estamos intentando solucionar esto.
1. Los archivos de la carpeta **AlchemyInsights** deben tener nombres de archivo en minúsculas con guiones para espacios en blanco por ejemplo. ***procedimiento de habilitación: retención por juicio***.
    1. Incluya el identificador de la regla o el identificador del cubo del [portal de socios de Alchemy](https://alchemyportal.azurewebsites.net) en el campo ms. Custom. precio. ***MS. Custom: 100021***
1. Use el resto de los metadatos en la parte superior de este archivo como plantilla.
1. En el [portal de socios de Alchemy](https://alchemyportal.azurewebsites.net), desplácese hacia abajo hasta la sección título de la **visión del cliente** y úsela como punto de partida para su título H1 para la visión. 
    > [!NOTE]
    > La información de Alchemy solo debe tener un solo H1 en la parte superior o se interrumpirá en producción. H2s no representarlas, use **negrita** u otras convenciones para indicar secciones independientes.
1. A continuación, rellene el texto del cuerpo con el borrador de material en la sección información del cliente de la página de la regla de Alchemy.
    1. Las listas con viñetas están bien
    1. También las listas numeradas
    1. **Negrita** y *cursiva* son a-OK
    1. Los vínculos siempre deben ser **"vínculos a Web"/external** o **vínculos profundos a elementos**de la interfaz de usuario, no a vínculos internos.
    1. Las imágenes no son compatibles oficialmente en este momento, pero se encuentra en la guía básica.

Y esto ya es un poco demasiado largo. El procedimiento recomendado es de unos 400 caracteres---------------------------------

Una vez que el contenido esté listo, extráigalo a la rama activa. A continuación, vaya al [portal de socios de Alchemy](https://alchemyportal.azurewebsites.net) y escriba el nombre de archivo en el campo URL. 