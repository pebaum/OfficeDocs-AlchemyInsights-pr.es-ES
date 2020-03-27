---
title: Es posible que DLP necesite un tipo personalizado
ms.author: pebaum
author: pebaum
manager: laurawi
ms.date: ''
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1647"
- "3200001"
ms.assetid: ''
ms.openlocfilehash: 87fcb5c3cc9ccd525265097b66d9d9b3a85c5feb
ms.sourcegitcommit: d108a2da2f5dab05246e30b5108cca5173e09051
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/26/2020
ms.locfileid: "42977287"
---
# <a name="dlp-might-need-a-custom-type"></a><span data-ttu-id="5979a-102">Es posible que DLP necesite un tipo personalizado</span><span class="sxs-lookup"><span data-stu-id="5979a-102">DLP might need a custom type</span></span>

<span data-ttu-id="5979a-103">**Importante**: durante estas horas sin precedentes, estamos llevando a cabo pasos para garantizar que los servicios de SharePoint Online y OneDrive sigan estando disponibles; visite [ajustes temporales de características de SharePoint Online](https://aka.ms/ODSPAdjustments) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="5979a-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="5979a-104">**Es posible que DLP requiera un tipo de información personalizada**</span><span class="sxs-lookup"><span data-stu-id="5979a-104">**DLP may require a custom information type**</span></span>

<span data-ttu-id="5979a-105">Con una directiva de prevención de pérdida de datos (DLP), puede identificar y proteger los datos confidenciales de su organización.</span><span class="sxs-lookup"><span data-stu-id="5979a-105">With a data loss prevention (DLP) policy, you can identify and protect sensitive data in your organization.</span></span> <span data-ttu-id="5979a-106">En algunos escenarios, es posible que necesite crear su propio tipo **personalizado** de información confidencial para proteger los datos de su organización.</span><span class="sxs-lookup"><span data-stu-id="5979a-106">In some scenarios, you might need to create your own **custom** sensitive information type to protect your organization's data.</span></span>

<span data-ttu-id="5979a-107">Por ejemplo, es posible que su organización necesite identificar y proteger los identificadores de los empleados u otros datos en algún formato específico de su organización. Si es así, consulte los artículos siguientes para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="5979a-107">For example, your organization might need to identify and protect employee IDs or other data in some format specific to your org. If so, see the following articles for more information.</span></span>
  
 <span data-ttu-id="5979a-108">**Personalizar un tipo de información confidencial integrado**</span><span class="sxs-lookup"><span data-stu-id="5979a-108">**Customize a built-in sensitive information type**</span></span>
  
<span data-ttu-id="5979a-109">Si un tipo de información confidencial incorporado satisface sus necesidades con solo unos cuantos ajustes, puede [personalizar un tipo de información confidencial integrada](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="5979a-109">If a built-in sensitive information type would meet your needs with just a few tweaks, you can [customize a built-in sensitive information type](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type).</span></span> <span data-ttu-id="5979a-110">Por ejemplo, puede Agregar o quitar palabras clave, o bien agregar o quitar evidencias auxiliares, como una fecha o una dirección.</span><span class="sxs-lookup"><span data-stu-id="5979a-110">For example, you can add or remove keywords, or add or remove supporting evidence such as a date or address.</span></span>
  
 <span data-ttu-id="5979a-111">**Crear un tipo personalizado de información confidencial**</span><span class="sxs-lookup"><span data-stu-id="5979a-111">**Create a custom sensitive information type**</span></span>
  
<span data-ttu-id="5979a-112">Pero si necesita identificar y proteger por completo un tipo diferente de información confidencial, puede [crear un tipo personalizado de información confidencial](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) en la interfaz de usuario del centro de seguridad & cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="5979a-112">But if you need to identify and protect a different type of sensitive information altogether, you can [create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) in the UI of the Security & Compliance Center.</span></span>
  
<span data-ttu-id="5979a-113">**Crear un tipo personalizado de información confidencial en PowerShell del Centro de seguridad y cumplimientol**</span><span class="sxs-lookup"><span data-stu-id="5979a-113">**Create a custom sensitive information type in Security & Compliance Center PowerShell**</span></span>

<span data-ttu-id="5979a-114">Por último, si la interfaz de usuario no proporciona todas las opciones que necesita, puede [crear un tipo personalizado de información confidencial en el PowerShell del centro de cumplimiento de & de seguridad](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span><span class="sxs-lookup"><span data-stu-id="5979a-114">Finally, if the UI doesn't provide all the options you need, you can [create a custom sensitive information type in Security & Compliance Center PowerShell](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span></span> <span data-ttu-id="5979a-115">Al comenzar con un archivo XML, puede usar todas las opciones disponibles.</span><span class="sxs-lookup"><span data-stu-id="5979a-115">By starting with an XML file, you can use every option available.</span></span>
