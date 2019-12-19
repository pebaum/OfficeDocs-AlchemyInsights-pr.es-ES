---
title: Error al validar el error de token de acceso durante la incorporación de escritorio de análisis
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2536"
- "9000657"
ms.openlocfilehash: 7472af5c4e19e5697b5fb4802ed1cbb2c74f1d19
ms.sourcegitcommit: f1fad2129d09660ec42dbce03ce2c6b4cfc9555a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/18/2019
ms.locfileid: "40741280"
---
# <a name="there-was-an-error-validating-access-token-error-during-desktop-analytics-onboarding"></a><span data-ttu-id="988a9-102">Error "error al validar el token de acceso" durante la incorporación de Desktop Analytics</span><span class="sxs-lookup"><span data-stu-id="988a9-102">"There was an error validating access token" error during Desktop Analytics onboarding</span></span>

<span data-ttu-id="988a9-103">Este error suele observarse cuando expira el token de autenticación.</span><span class="sxs-lookup"><span data-stu-id="988a9-103">This error is normally observed when the authentication token expires.</span></span> <span data-ttu-id="988a9-104">Normalmente, la actualización de la página actualiza el token.</span><span class="sxs-lookup"><span data-stu-id="988a9-104">Usually, refreshing the page refreshes the token.</span></span> <span data-ttu-id="988a9-105">Sin embargo, este problema puede persistir si hay directivas de acceso condicional aplicadas a la cuenta que se usa para la analítica de escritorio integrada.</span><span class="sxs-lookup"><span data-stu-id="988a9-105">However, this issue can persist if there are any Conditional Access policies applied to the account being used to on-board Desktop Analytics.</span></span> <span data-ttu-id="988a9-106">Puede revisar los registros de inicio de sesión de Azure AD en Azure portal para ver si hay errores de inicio de sesión para la cuenta que se usa para la incorporación de Desktop Analytics.</span><span class="sxs-lookup"><span data-stu-id="988a9-106">You can review the Azure AD Sign In logs in the Azure Portal to see if there are any sign-in failures for the account being used for Desktop Analytics onboarding.</span></span>

<span data-ttu-id="988a9-107">Para obtener más información acerca del acceso condicional, visite [planear la implementación de acceso condicional](https://docs.microsoft.com/azure/active-directory/conditional-access/plan-conditional-access).</span><span class="sxs-lookup"><span data-stu-id="988a9-107">For more information about Conditional Access, visit [Plan your Conditional Access deployment](https://docs.microsoft.com/azure/active-directory/conditional-access/plan-conditional-access).</span></span>