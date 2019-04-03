---
title: Guardar el sitio o la lista como plantilla
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 368ff1fa-82cf-4a07-986e-140b212ffc5c
ms.openlocfilehash: 7930551c0938501d006f791491594f9d6d9ba260
ms.sourcegitcommit: 56c52c73e752414d66785f175c3a0e2925ad41c1
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/02/2019
ms.locfileid: "31044021"
---
# <a name="save-site-or-list-as-a-template"></a><span data-ttu-id="228cc-102">Guardar el sitio o la lista como plantilla</span><span class="sxs-lookup"><span data-stu-id="228cc-102">Save site or list as a template</span></span>

<span data-ttu-id="228cc-103">Las plantillas de sitio de SharePoint son definiciones preintegradas diseñadas en torno a una necesidad empresarial concreta.</span><span class="sxs-lookup"><span data-stu-id="228cc-103">SharePoint site templates are prebuilt definitions designed around a particular business need.</span></span> <span data-ttu-id="228cc-104">Para obtener más información, vea [uso de plantillas para crear diferentes tipos de sitios de SharePoint](https://support.office.com/en-us/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span><span class="sxs-lookup"><span data-stu-id="228cc-104">For more information, see [Using templates to create different kinds of SharePoint sites](https://support.office.com/en-us/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span></span>

<span data-ttu-id="228cc-105">Estos son algunos problemas o soluciones comunes en relación con guardar un sitio o una lista como una plantilla en SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="228cc-105">Here are some common issues/solutions regarding Saving a Site or List as a template in SharePoint Online.</span></span>

<span data-ttu-id="228cc-106">El **botón Guardar plantilla de sitio o lista no está disponible o no se**encuentra.</span><span class="sxs-lookup"><span data-stu-id="228cc-106">**Save site/list template button is not available or missing**.</span></span> 

- <span data-ttu-id="228cc-107">Los administradores tendrán que permitir el script personalizado para habilitar las características de plantilla.</span><span class="sxs-lookup"><span data-stu-id="228cc-107">Administrators will need to Allow Custom Script to enable the template features.</span></span> <span data-ttu-id="228cc-108">Para ver los pasos detallados, ejemplos y consideraciones, consulte [Allow or impida Custom script](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script).</span><span class="sxs-lookup"><span data-stu-id="228cc-108">For detailed steps, examples and considerations see [Allow or prevent custom script](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script).</span></span>


- <span data-ttu-id="228cc-109">El comando Guardar sitio como plantilla no es compatible y puede causar problemas en sitios que usan la infraestructura de publicación de SharePoint Server.</span><span class="sxs-lookup"><span data-stu-id="228cc-109">The Save site as template command is not supported and can cause problems on sites that use the SharePoint Server Publishing Infrastructure.</span></span>


**<span data-ttu-id="228cc-110">La plantilla de sitio no se puede crear o no funciona correctamente</span><span class="sxs-lookup"><span data-stu-id="228cc-110">The site template cannot be created or does not work correctly</span></span>**

- <span data-ttu-id="228cc-111">Puede que la plantilla falte una [característica](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) y no se activará.</span><span class="sxs-lookup"><span data-stu-id="228cc-111">The template may be missing a [feature](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) and won’t activate.</span></span> <span data-ttu-id="228cc-112">Si la característica no está disponible para activarse en la colección de sitios actual, no se puede usar la plantilla de sitio para crear un sitio.</span><span class="sxs-lookup"><span data-stu-id="228cc-112">If the feature is not available to activate in the current site collection, you cannot use the site template to create a site.</span></span>


- <span data-ttu-id="228cc-113">Compruebe si hay listas o bibliotecas que superen el [umbral límite](https://support.office.com/en-us/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) de la vista de lista de 5000 elementos, ya que esto puede bloquear la creación de una plantilla de sitio.</span><span class="sxs-lookup"><span data-stu-id="228cc-113">Check to see if any lists or libraries exceed the [List View Limit Threshold](https://support.office.com/en-us/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) of 5000 items as this can block creation of a site template.</span></span>


- <span data-ttu-id="228cc-114">Es posible que el sitio esté usando demasiados recursos y, por lo tanto, la plantilla de sitio supera el límite de 50 megabytes (MB).</span><span class="sxs-lookup"><span data-stu-id="228cc-114">The site may be using too many resources and therefore the site template exceeds the 50 megabyte (MB) limit.</span></span>


- <span data-ttu-id="228cc-115">Hay problemas para mostrar los datos de una lista que usa una columna de búsqueda.</span><span class="sxs-lookup"><span data-stu-id="228cc-115">There are problems displaying data from a list that uses a lookup column.</span></span> <span data-ttu-id="228cc-116">Para obtener más información, vea [la lista generada por plantillas no muestra los datos de la lista de búsqueda correcta en SharePoint Online](https://support.office.com/en-us/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a).</span><span class="sxs-lookup"><span data-stu-id="228cc-116">For more information, see [Template-generated list doesn’t display data from the correct lookup list in SharePoint Online](https://support.office.com/en-us/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a).</span></span>


<span data-ttu-id="228cc-117">Para obtener información más detallada acerca de los problemas comunes y las soluciones, consulte [crear y usar plantillas de sitio](https://support.office.com/en-us/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span><span class="sxs-lookup"><span data-stu-id="228cc-117">For more detailed information on common problems and solutions please reference, [Create and use site templates](https://support.office.com/en-us/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span></span>

