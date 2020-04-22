---
title: DLP no funciona como se esperaba
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1241"
- "3200001"
ms.assetid: f6fcf5ad-55a1-4f25-af27-1f7c1ce06409
ms.openlocfilehash: efb4a19f345fe6b8a1e8bb72abeba4a923c05777
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43704430"
---
# <a name="dlp-not-working-as-expected"></a><span data-ttu-id="d5b83-102">DLP no funciona como se esperaba</span><span class="sxs-lookup"><span data-stu-id="d5b83-102">DLP not working as expected</span></span>

<span data-ttu-id="d5b83-103">**Importante**: durante estos tiempos, se siguen pasos para asegurarse de que los servicios de SharePoint Online y OneDrive estén altamente disponibles. Para obtener más información, visite [Ajustes temporales de características de SharePoint Online](https://aka.ms/ODSPAdjustments).</span><span class="sxs-lookup"><span data-stu-id="d5b83-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

 <span data-ttu-id="d5b83-104">**Configuración de DLP**</span><span class="sxs-lookup"><span data-stu-id="d5b83-104">**Setting up DLP**</span></span>

<span data-ttu-id="d5b83-105">¿Tiene problemas con la **prevención de pérdida de datos (DLP)** en Office 365 que no funciona como se esperaba?</span><span class="sxs-lookup"><span data-stu-id="d5b83-105">Are you having problems with **Data Loss Prevention (DLP)** in Office 365 not working as expected?</span></span> <span data-ttu-id="d5b83-106">Si es así, asegúrese de que la **Directiva DLP** está correctamente configurada y de que los datos contienen lo que la **Directiva DLP** busca cuando se evalúa.</span><span class="sxs-lookup"><span data-stu-id="d5b83-106">If so, make sure that your **DLP policy** is set up correctly, and that your data contains what the **DLP policy** is looking for when it is being evaluated.</span></span>
  
<span data-ttu-id="d5b83-107">Las directivas de DLP le permiten identificar y proteger la información confidencial de su organización.</span><span class="sxs-lookup"><span data-stu-id="d5b83-107">DLP policies allows you to identify and protect sensitive information in your organization.</span></span> <span data-ttu-id="d5b83-108">Para configurar directivas de DLP, use la información que se muestra [aquí](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span><span class="sxs-lookup"><span data-stu-id="d5b83-108">To setup DLP policies, use the information [here](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span></span>
  
 <span data-ttu-id="d5b83-109">**Qué buscan las directivas de DLP**</span><span class="sxs-lookup"><span data-stu-id="d5b83-109">**What DLP policies look for**</span></span>
  
<span data-ttu-id="d5b83-110">Al usar los **tipos de información confidencial integrados** en los centros de seguridad y cumplimiento, las directivas de DLP buscan patrones y elementos específicos al detectar estos tipos confidenciales.</span><span class="sxs-lookup"><span data-stu-id="d5b83-110">When using the **built-in sensitive information types** in the Security and Compliance centers, DLP policies look for specific patterns and elements when detecting these sensitive types.</span></span>
  
- <span data-ttu-id="d5b83-111">**Tipos de información confidencial integrados**</span><span class="sxs-lookup"><span data-stu-id="d5b83-111">**Built-in Sensitive Information Types**</span></span>

    <span data-ttu-id="d5b83-112">Para obtener información sobre los tipos confidenciales integrados y qué busca una directiva DLP cuando se detecta el tipo confidencial, vea: [Qué buscan los tipos de información confidencial](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span><span class="sxs-lookup"><span data-stu-id="d5b83-112">For information on the built-in Sensitive types and what a DLP policy looks for when detecting the Sensitive type, see: [What the sensitive information types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span></span>

- <span data-ttu-id="d5b83-113">**Tipos personalizados de información confidencial**</span><span class="sxs-lookup"><span data-stu-id="d5b83-113">**Custom Sensitive Information Types**</span></span>

    <span data-ttu-id="d5b83-114">Si está intentando crear tipos personalizados de información confidencial, use el siguiente artículo para obtener información sobre cómo crear un tipo confidencial personalizado: [crear un tipo personalizado de información confidencial](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="d5b83-114">If you are trying to create custom sensitive information types, use the following article for information on how to create a custom sensitive type: [Create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span></span>

<span data-ttu-id="d5b83-115">**Probar una directiva DLP**</span><span class="sxs-lookup"><span data-stu-id="d5b83-115">**Test a DLP policy**</span></span>

<span data-ttu-id="d5b83-116">Para probar los datos con un tipo de información confidencial integrado o personalizado, use la opción **tipo de prueba** en **clasificaciones** > de**información confidencial**.</span><span class="sxs-lookup"><span data-stu-id="d5b83-116">To test your data with a built-in or custom sensitive information type, use the **Test type** option under **Classifications** > **Sensitive info types**.</span></span> <span data-ttu-id="d5b83-117">Para obtener más información, vea [probar tipos personalizados de información confidencial](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span><span class="sxs-lookup"><span data-stu-id="d5b83-117">For more information, see [Test custom sensitive information types](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span></span>

 <span data-ttu-id="d5b83-118">**Informes**</span><span class="sxs-lookup"><span data-stu-id="d5b83-118">**Reports**</span></span>
  
- <span data-ttu-id="d5b83-119">Obtenga información confidencial sobre los datos con [informes de DLP.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span><span class="sxs-lookup"><span data-stu-id="d5b83-119">Get sensitive data insights with [DLP Reports.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span></span>

- <span data-ttu-id="d5b83-120">Vea los detalles específicos del evento con un [Informe de incidentes](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).</span><span class="sxs-lookup"><span data-stu-id="d5b83-120">See specific details of the event with an [Incident Report](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).</span></span>
