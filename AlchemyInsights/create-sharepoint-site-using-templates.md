---
title: Crear un sitio en SharePoint Online
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 84f2b70e-2b23-4039-8305-85783798feed
ms.openlocfilehash: b9009fdbdc2a5e7443151446daade1685d2f5d45
ms.sourcegitcommit: 317eeed39c7777a922442992d67733726c41d9e1
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/04/2020
ms.locfileid: "41770440"
---
# <a name="create-sharepoint-sites-using-templates"></a>Crear sitios de SharePoint con plantillas

La capacidad de guardar un sitio como plantilla no es compatible con la comunicación o los sitios de grupo modernos. Para obtener más información sobre el uso de plantillas [, vea guardar, descargar y cargar un sitio de SharePoint como plantilla](https://docs.microsoft.com/sharepoint/dev/general-development/save-download-and-upload-a-sharepoint-site-as-a-template).

Estos son algunos problemas o soluciones comunes en relación con guardar un sitio o una lista como una plantilla en SharePoint Online. 

**El botón Guardar plantilla de sitio o lista no está disponible o no se encuentra**

Los administradores tendrán que permitir el script personalizado para habilitar las características de plantilla. Para obtener instrucciones detalladas, vea ejemplos y consideraciones. 

- [Permitir o impedir scripts personalizados](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)

- El comando Guardar sitio como plantilla no es compatible y puede causar problemas en sitios que usan la infraestructura de publicación de SharePoint Server.

**La plantilla de sitio no se puede crear o no funciona correctamente**

Puede que la plantilla falte una [característica](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) y no se activará. Si la característica no está disponible para activarse en la colección de sitios actual, no se puede usar la plantilla de sitio para crear un sitio.

- Compruebe si hay listas o bibliotecas que superen el [umbral límite](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) de la vista de lista de 5000 elementos, ya que esto puede bloquear la creación de una plantilla de sitio.

- Es posible que el sitio esté usando demasiados recursos y, por lo tanto, la plantilla de sitio supera el límite de 50 MB.


- Hay problemas para mostrar los datos de una lista que usa una columna de búsqueda. Para obtener más información, vea [la lista generada por plantillas no muestra los datos de la lista de búsqueda correcta en SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).

Para obtener información más detallada sobre los problemas comunes y las soluciones, consulte [crear y usar plantillas de sitio](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).



