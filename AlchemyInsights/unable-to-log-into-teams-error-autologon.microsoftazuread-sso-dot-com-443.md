---
title: No se puede iniciar sesión en Teams por el error autologon.microsoftazuread-sso.com:443
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 686e8f18-b871-4dd2-864f-8562947ab583
ms.collection: Adm_O365
ms.custom:
- "9001686"
- "3750"
ms.openlocfilehash: 77049153939989d1c63789adfec0b494d047a6e4
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932288"
---
# <a name="unable-to-log-into-teams-due-to-error-autologonmicrosoftazuread-sso-dot-com443"></a><span data-ttu-id="e054b-102">No se puede iniciar sesión en Teams por el error autologon.microsoftazuread-sso dot com:443</span><span class="sxs-lookup"><span data-stu-id="e054b-102">Unable to log into Teams due to error autologon.microsoftazuread-sso dot com:443</span></span>

<span data-ttu-id="e054b-103">Si el SSO de conexión directa está habilitado como la autenticación de O365, quizás tenga que agregar la dirección URL "autologon.microsoftazuread-sso.com" a los sitios de intranet.</span><span class="sxs-lookup"><span data-stu-id="e054b-103">If Seamless SSO is enabled as the O365 authentication, the URL "autologon.microsoftazuread-sso.com" may need to be added to Intranet Sites.</span></span>  <span data-ttu-id="e054b-104">Si se ha agregado anteriormente a Sitios de confianza y usa SSO de conexión directa, se debe quitar de Sitios de confianza.</span><span class="sxs-lookup"><span data-stu-id="e054b-104">If it has previously been added to Trusted Sites  and Seamless SSO is in use, it should be removed from Trusted Sites.</span></span>

<span data-ttu-id="e054b-105">Consulte la [Lista de comprobación de solución de problemas de SSO de conexión directa](https://docs.microsoft.com/azure/active-directory/hybrid/tshoot-connect-sso#troubleshooting-checklist).</span><span class="sxs-lookup"><span data-stu-id="e054b-105">Please review the [Seamless SSO Troubleshooting Checklist](https://docs.microsoft.com/azure/active-directory/hybrid/tshoot-connect-sso#troubleshooting-checklist).</span></span>

<span data-ttu-id="e054b-106">Siga estos pasos para agregar una dirección URL a la lista de sitios de la intranet:</span><span class="sxs-lookup"><span data-stu-id="e054b-106">Follow these steps to add a URL to Intranet Sites list:</span></span>

1. <span data-ttu-id="e054b-107">Para abrir Internet Explorer, haga clic en el botón **Inicio**.</span><span class="sxs-lookup"><span data-stu-id="e054b-107">Open Internet Explorer by clicking the **Start** button.</span></span> <span data-ttu-id="e054b-108">En el cuadro de búsqueda, escriba Internet Explorer y, a continuación, en la lista de resultados, haga clic en **Internet Explorer**.</span><span class="sxs-lookup"><span data-stu-id="e054b-108">In the search box, type Internet Explorer, and then, in the list of results, click **Internet Explorer**.</span></span>
2. <span data-ttu-id="e054b-109">Haga clic en **Herramientas** y, luego, en **Opciones de Internet**.</span><span class="sxs-lookup"><span data-stu-id="e054b-109">Click **Tools**, and then click **Internet options**.</span></span>
3. <span data-ttu-id="e054b-110">Haga clic en la pestaña **Seguridad**.</span><span class="sxs-lookup"><span data-stu-id="e054b-110">Click the **Security** tab.</span></span>
4. <span data-ttu-id="e054b-111">Ahora, haga clic en **Sitios de Intranet local**, después, haga clic en el botón **sitios** y, luego, en el botón**Avanzado**.</span><span class="sxs-lookup"><span data-stu-id="e054b-111">Now click on **Local Intranet sites** and then click on the **sites** button and then **Advanced** button.</span></span>
5. <span data-ttu-id="e054b-112">Escriba la dirección URL del sitio web y haga clic en **Agregar**.</span><span class="sxs-lookup"><span data-stu-id="e054b-112">Enter the Website URL and click **Add**.</span></span>
6. <span data-ttu-id="e054b-113">Cuando haya terminado, haga clic en **Cerrar.**</span><span class="sxs-lookup"><span data-stu-id="e054b-113">When you are finished, click **Close**.</span></span>

<span data-ttu-id="e054b-114">Para obtener más información, vea [Documentación sobre cómo implementar SSO de conexión directa para O365](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-sso-quick-start) (incluye el proceso basado en directivas para agregar una dirección URL a los sitios de intranet en el Paso 3).</span><span class="sxs-lookup"><span data-stu-id="e054b-114">For more information, see [Documentation for deploying Seamless SSO for O365](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-sso-quick-start) (includes Policy-based process to add a URL to Intranet Sites in Step 3).</span></span>
