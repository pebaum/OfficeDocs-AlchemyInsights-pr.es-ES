---
title: Crear un sitio en SharePoint Online
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 84f2b70e-2b23-4039-8305-85783798feed
ms.openlocfilehash: 2097933dd20f326a7bda2151596d514c37d566ff
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/04/2019
ms.locfileid: "34717783"
---
# <a name="create-sharepoint-sites-using-templates"></a>Crear sitios de SharePoint con plantillas

Las plantillas de sitio de SharePoint son definiciones preintegradas diseñadas en torno a una necesidad empresarial concreta. Para obtener más información, vea <a href="https://support.office.com/en-us/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4">uso de plantillas para crear diferentes tipos de sitios de SharePoint.</a></span></p> <p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Estos son algunos problemas o soluciones comunes en relación con guardar un sitio o una lista como una plantilla en SharePoint Online.</span></p> <p><strong style="mso-bidi-font-weight: normal;"><u><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">El botón Guardar plantilla de sitio o lista no está disponible o no se encuentra.</span></u></strong></p> <ul> <li><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Los administradores tendrán que permitir el script personalizado para habilitar las características de plantilla. Para ver los pasos detallados, ejemplos y consideraciones, consulte </span> </span> <a style="orphans: 2; -webkit-text-stroke-width: 0px; word-spacing: 0px;" href="https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script">Allow or impida Custom script</a>.</li> <li><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">El comando Guardar sitio como plantilla no es compatible y puede causar problemas en sitios que usan la infraestructura de publicación de SharePoint Server.</span></li> </ul> <p><strong style="mso-bidi-font-weight: normal;"><u><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">La plantilla de sitio no se puede crear o no funciona correctamente</span></u></strong></p> <ul> <li><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Es posible que falte una <a href="https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx">característica</a> en la plantilla&rsquo;y que se haya logrado la activación. Si la característica no está disponible para activarse en la colección de sitios actual, no se puede usar la plantilla de sitio para crear un sitio.</span></li> <li><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Compruebe si hay listas o bibliotecas que superen el <a href="https://support.office.com/en-us/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59">umbral límite de la vista de lista de</a> 5000 elementos, ya que esto puede bloquear la creación de una plantilla de sitio.</span></li> <li><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Es posible que el sitio esté usando demasiados recursos y, por lo tanto, la plantilla de sitio supera el límite de 50 MB.</span></li> <li>
Hay problemas para mostrar los datos de una lista que usa una columna de búsqueda. Para obtener más información, </span> <span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;"> <a style="box-sizing: border-box; -webkit-text-stroke-width: 0px; word-spacing: 0px;" href="https://support.office.com/en-us/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a"> <span style="color: #0067b8; text-decoration: none; text-underline: none;">consulte lista generada por plantilla&rsquo;no muestra datos de la lista de búsqueda correcta en SharePoint Online.

Para obtener información más detallada sobre los problemas comunes y las soluciones <a href="https://support.office.com/en-us/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989">, consulte crear y usar plantillas de sitio.



