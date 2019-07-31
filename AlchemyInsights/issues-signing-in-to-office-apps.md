---
title: Problemas al iniciar sesión en las aplicaciones de Office
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000571"
- "2560"
ms.openlocfilehash: de0a1b78724db9a8e93d8d599ce3b503abcb86e2
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938349"
---
# <a name="fixing-the-office-apps-sorry-another-account-from-your-organization-is-already-signed-in-message"></a><span data-ttu-id="e5bd6-102">Corrección de las aplicaciones de Office "lo sentimos, otra cuenta de su organización ya ha iniciado sesión" Message</span><span class="sxs-lookup"><span data-stu-id="e5bd6-102">Fixing the Office apps "Sorry, another account from your organization is already signed in" message</span></span>

<span data-ttu-id="e5bd6-103">Para solucionar este error, intente lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="e5bd6-103">To fix this error, try the following:</span></span>

- <span data-ttu-id="e5bd6-104">Quite todas las cuentas de trabajo, excepto la cuenta afectada, mediante la configuración de Windows > **acceso a la oficina o a la escuela**.</span><span class="sxs-lookup"><span data-stu-id="e5bd6-104">Remove all work accounts, except the affected account, using Windows Settings > **Access work or school**.</span></span>
- <span data-ttu-id="e5bd6-105">[Borre las credenciales de Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) con el administrador de credenciales de Windows.</span><span class="sxs-lookup"><span data-stu-id="e5bd6-105">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="e5bd6-106">**Nota:** Las rutas del registro para Office 2016 han cambiado a 16,0.</span><span class="sxs-lookup"><span data-stu-id="e5bd6-106">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="e5bd6-107">(Por ejemplo: \Software\Microsoft\Office\16.0\Common\Identity\)</span><span class="sxs-lookup"><span data-stu-id="e5bd6-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>
- <span data-ttu-id="e5bd6-108">Abra una aplicación de Office y elija la opción**Cerrar sesión**de la**cuenta** > de **archivo** > . A continuación, inicie sesión con una cuenta de usuario con una licencia válida.</span><span class="sxs-lookup"><span data-stu-id="e5bd6-108">Open an Office app, choose **File** > **Account** > **Sign Out**. Then sign in using a user account with a valid license.</span></span> <span data-ttu-id="e5bd6-109">Para obtener información detallada, consulte [accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span><span class="sxs-lookup"><span data-stu-id="e5bd6-109">For detailed information, see [Accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span></span>
- <span data-ttu-id="e5bd6-110">Para Mac, consulte [no se puede iniciar sesión en una aplicación de Office 2016 para Mac](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).</span><span class="sxs-lookup"><span data-stu-id="e5bd6-110">For Mac, see [Can't sign in to an Office 2016 for Mac app](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).</span></span>

<span data-ttu-id="e5bd6-111">Para obtener más información, vea ["lo sentimos, otra cuenta de su organización ya ha iniciado sesión en este equipo" en Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in).</span><span class="sxs-lookup"><span data-stu-id="e5bd6-111">For more information, see ["Sorry, another account from your organization is already signed in on this computer" in Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in).</span></span>