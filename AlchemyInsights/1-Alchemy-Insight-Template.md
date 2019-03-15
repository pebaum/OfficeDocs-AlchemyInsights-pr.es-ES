---
title: 'igual que FILENAME es mejor [RULE #-deScription]'
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 4/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: e248c2ee3cbb9a86f21c1f36be10c893df76ff52
ms.sourcegitcommit: 3070905131e6d8449981231a3551c0bb4ca38ae6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/14/2019
ms.locfileid: "30634521"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a>Falta el encabezado de Alchemy H1, H2's no funciona.
Procedimientos recomendados y directrices para la creación de Alchemy:

1. **No anide información de Alchemy en las carpetas**: esto interrumpirá la estructura de la dirección URL. Estamos intentando solucionar esto.
1. Los archivos de la carpeta **AlchemyInsights** deben tener el identificador de la regla y el nombre de la regla del [portal de socios de Alchemy](https://alchemyportal.azurewebsites.net) en el nombre del archivo.
    1. precio. ***976-procedimiento-habilitado: retención en litigios***
1. Use los metadatos en la parte superior de este archivo como plantilla. No se requiere ninguna otra cosa.
1. En el [portal de socios de Alchemy](https://alchemyportal.azurewebsites.net), desplácese hacia abajo hasta la sección título de la **visión del cliente** y úsela como punto de partida para su título H1 para la visión. 
    > [!NOTE]
    > La información de Alchemy solo debe tener un solo H1 en la parte superior o se interrumpirá en producción. H2s no representarlas, use **negrita** u otras convenciones para indicar secciones independientes.
1. A continuación, rellene el texto del cuerpo con el borrador de material en la sección información del cliente de la página de la regla de Alchemy.
    1. Las listas con viñetas están bien
    1. También las listas numeradas
    1. **Negrita** y *cursiva* son a-OK
    1. Los vínculos siempre deben ser **"vínculos a Web"/external** o **vínculos profundos a elementos**de la interfaz de usuario, no a vínculos internos.

Y esto ya es un poco demasiado largo. El procedimiento recomendado es de unos 400 caracteres---------------------------------

Una vez que el contenido esté listo, extráigalo a la rama activa. A continuación, vaya al [portal de socios de Alchemy](https://alchemyportal.azurewebsites.net) y escriba el nombre de archivo en el campo URL. Asegúrese de que la información de revisión revisada y publicada dice "sí" y, a continuación, haga clic en actualizar regla. **(El aspecto será Prettier en la nueva versión del portal de lanzamiento de próximamente).** 
 ![](media/for-content-team.PNG)

