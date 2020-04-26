---
title: Solucionar el error No se detectó la aplicación
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000171"
- "1712"
ms.openlocfilehash: e07c6b128a39f1fb1c998d051aafe72205d8cbee
ms.sourcegitcommit: 82155846ce771c18050e6113d6c199b34a1504ff
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/24/2020
ms.locfileid: "43810500"
---
# <a name="mitigate-the-application-was-not-detected-error"></a><span data-ttu-id="45ad5-102">Solucionar el error "No se detectó la aplicación"</span><span class="sxs-lookup"><span data-stu-id="45ad5-102">Mitigate "The application was not detected" error</span></span>

<span data-ttu-id="45ad5-103">El error de instalación de la aplicación, "no se detectó la aplicación después de completar la instalación correctamente", generado por Intune, puede producirse en todas las plataformas de SO principales (Windows, iOS y Android).</span><span class="sxs-lookup"><span data-stu-id="45ad5-103">The app installation error, “The application was not detected after installation completed successfully,” reported by Intune, may occur on all major OS platforms (Windows, iOS and Android).</span></span>

<span data-ttu-id="45ad5-104">Entre los escenarios más comunes que generan este error se incluyen:</span><span class="sxs-lookup"><span data-stu-id="45ad5-104">The most common scenarios that generate this error include:</span></span>

- <span data-ttu-id="45ad5-105">Se ha actualizado la aplicación fuera de Intune (desde una tienda de aplicaciones de terceros) después de la implementación inicial.</span><span class="sxs-lookup"><span data-stu-id="45ad5-105">The app has been updated outside of Intune (from a third-party app store) after the initial deployment.</span></span> <span data-ttu-id="45ad5-106">Por ejemplo, algunas aplicaciones, como Google Chrome, pueden realizar actualizaciones automáticas.</span><span class="sxs-lookup"><span data-stu-id="45ad5-106">For example some applications such as Google Chrome may perform auto updates.</span></span>
- <span data-ttu-id="45ad5-107">Un usuario ha desinstalado la aplicación después de la instalación inicial.</span><span class="sxs-lookup"><span data-stu-id="45ad5-107">A user has uninstalled the app after the initial install.</span></span>

<span data-ttu-id="45ad5-108">Para mitigar este problema, primero realice una revisión de los dispositivos afectados para determinar el escenario en el que se produce el error.</span><span class="sxs-lookup"><span data-stu-id="45ad5-108">To mitigate this issue, first perform a review of the affected devices to determine the scenario in which the error occurs.</span></span>

- <span data-ttu-id="45ad5-109">Si la aplicación se ha actualizado fuera de Intune, la implementación de la aplicación puede configurarse para ignorar la versión de la aplicación.</span><span class="sxs-lookup"><span data-stu-id="45ad5-109">If the app has been updated outside of Intune, the app deployment can be set to ignore the application version.</span></span> <span data-ttu-id="45ad5-110">Para ello, en \*\*Configuración de la aplicación > Información de la aplicación, \*\*establezca **Ignorar versión de la aplicación** en **Sí**.</span><span class="sxs-lookup"><span data-stu-id="45ad5-110">To do so, under **App Configuration > App Information**, set **Ignore App** version to **Yes**.</span></span>
- <span data-ttu-id="45ad5-111">Al dirigirse al cliente, puede ser apropiado implementar la aplicación como "necesaria" y asegurarse de que se implemente la versión más reciente.</span><span class="sxs-lookup"><span data-stu-id="45ad5-111">When targeting the client, it may be appropriate to deploy the application as “required,” and to ensure that the latest version is deployed.</span></span>
- <span data-ttu-id="45ad5-112">Por otra parte, en la plataforma de iOS, es posible usar la función **autoupdate** asociada al programa de compras por volumen de Apple, que se puede configurar para que actualice automáticamente a nuevas versiones de las aplicaciones cuando estén disponibles.</span><span class="sxs-lookup"><span data-stu-id="45ad5-112">Alternatively, on the iOS platform, it is possible to use the **autoupdate** functionality associated with the Apple Volume Purchase Program, which can be configured to automatically update to new application versions as they become available.</span></span>

<span data-ttu-id="45ad5-113">Para más información sobre la solución de problemas de instalación de aplicaciones, vea [Solucionar problemas de instalación de aplicación](https://docs.microsoft.com/intune/troubleshoot-app-install).</span><span class="sxs-lookup"><span data-stu-id="45ad5-113">For more information about troubleshooting app installation issues, please see [Troubleshoot app installation issues](https://docs.microsoft.com/intune/troubleshoot-app-install).</span></span>
