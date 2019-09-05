---
title: Guardar el sitio o la lista como plantilla
ms.author: pebaum
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 368ff1fa-82cf-4a07-986e-140b212ffc5c
ms.openlocfilehash: 1fe0a2f5bf65ef4e8cabf3d05a701c8eff966435
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/04/2019
ms.locfileid: "36752049"
---
# <a name="save-site-or-list-as-a-template"></a>Guardar el sitio o la lista como plantilla

Las plantillas de sitio de SharePoint son definiciones preintegradas diseñadas en torno a una necesidad empresarial concreta. Para obtener más información, vea [uso de plantillas para crear diferentes tipos de sitios de SharePoint](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).

Estos son algunos problemas o soluciones comunes en relación con guardar un sitio o una lista como una plantilla en SharePoint Online.

El **botón Guardar plantilla de sitio o lista no está disponible o no se**encuentra. 

- Los administradores tendrán que permitir el script personalizado para habilitar las características de plantilla. Para ver los pasos detallados, ejemplos y consideraciones, consulte [Allow or impida Custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).


- El comando Guardar sitio como plantilla no es compatible y puede causar problemas en sitios que usan la infraestructura de publicación de SharePoint Server.


**La plantilla de sitio no se puede crear o no funciona correctamente**

- Puede que la plantilla falte una [característica](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) y no se activará. Si la característica no está disponible para activarse en la colección de sitios actual, no se puede usar la plantilla de sitio para crear un sitio.


- Compruebe si hay listas o bibliotecas que superen el [umbral límite](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) de la vista de lista de 5000 elementos, ya que esto puede bloquear la creación de una plantilla de sitio.


- Es posible que el sitio esté usando demasiados recursos y, por lo tanto, la plantilla de sitio supera el límite de 50 megabytes (MB).


- Hay problemas para mostrar los datos de una lista que usa una columna de búsqueda. Para obtener más información, vea [la lista generada por plantillas no muestra los datos de la lista de búsqueda correcta en SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).


Para obtener información más detallada acerca de los problemas comunes y las soluciones, consulte [crear y usar plantillas de sitio](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).

