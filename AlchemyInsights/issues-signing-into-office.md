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
- "2574"
ms.openlocfilehash: 3622a3408b25b43090e9414ae5ffcfc2760264ee
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938350"
---
# <a name="issues-signing-in-to-office-apps"></a><span data-ttu-id="72c6e-102">Problemas al iniciar sesión en las aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="72c6e-102">Issues signing in to Office apps</span></span>

<span data-ttu-id="72c6e-103">Para solucionar los problemas de inicio de sesión con las aplicaciones de Office, pruebe lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="72c6e-103">To fix sign-in issues with Office apps, try the following:</span></span>

- <span data-ttu-id="72c6e-104">Quite todas las cuentas de trabajo, excepto la cuenta afectada, mediante la configuración de Windows > **acceso a la oficina o a la escuela**.</span><span class="sxs-lookup"><span data-stu-id="72c6e-104">Remove all work accounts, except the affected account, using Windows Settings > **Access work or school**.</span></span>
- <span data-ttu-id="72c6e-105">[Borre las credenciales de Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) con el administrador de credenciales de Windows.</span><span class="sxs-lookup"><span data-stu-id="72c6e-105">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="72c6e-106">**Nota:** Las rutas del registro para Office 2016 han cambiado a 16,0.</span><span class="sxs-lookup"><span data-stu-id="72c6e-106">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="72c6e-107">(Por ejemplo: \Software\Microsoft\Office\16.0\Common\Identity\)</span><span class="sxs-lookup"><span data-stu-id="72c6e-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>
- <span data-ttu-id="72c6e-108">Abra una aplicación de Office y elija la opción**Cerrar sesión**de la**cuenta** > de **archivo** > . A continuación, inicie sesión con una cuenta de usuario con una licencia válida.</span><span class="sxs-lookup"><span data-stu-id="72c6e-108">Open an Office app, choose **File** > **Account** > **Sign Out**. Then sign in using a user account with a valid license.</span></span> <span data-ttu-id="72c6e-109">Para obtener información detallada, consulte [accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span><span class="sxs-lookup"><span data-stu-id="72c6e-109">For detailed information, see [Accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span></span>
- <span data-ttu-id="72c6e-110">Para Mac, consulte [no se puede iniciar sesión en una aplicación de Office 2016 para Mac](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).</span><span class="sxs-lookup"><span data-stu-id="72c6e-110">For Mac, see [Can't sign in to an Office 2016 for Mac app](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).</span></span>
- <span data-ttu-id="72c6e-111">Si se producen errores al conectar con Office 365 mediante Office 2013, habilite la autenticación moderna para el cliente de Office.</span><span class="sxs-lookup"><span data-stu-id="72c6e-111">If the errors occurs while connecting to Office 365 using Office 2013, enable modern authentication for Office client.</span></span>

<span data-ttu-id="72c6e-112">Para obtener más información, vea:</span><span class="sxs-lookup"><span data-stu-id="72c6e-112">For more information, see:</span></span>
- [<span data-ttu-id="72c6e-113">No puede iniciar sesión en Office 365, Azure o Intune</span><span class="sxs-lookup"><span data-stu-id="72c6e-113">You can't sign in to Office 365, Azure, or Intune</span></span>](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-365-azure-intune)
- [<span data-ttu-id="72c6e-114">Problemas de conexión en el inicio de sesión después de actualizar a Office 2016 compilación 16.0.7967 en Windows 10</span><span class="sxs-lookup"><span data-stu-id="72c6e-114">Connection issues in sign-in after update to Office 2016 build 16.0.7967 on Windows 10</span></span>](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016)
- [<span data-ttu-id="72c6e-115">"Lo sentimos, otra cuenta de su organización ya ha iniciado sesión en este equipo" en Office</span><span class="sxs-lookup"><span data-stu-id="72c6e-115">"Sorry, another account from your organization is already signed in on this computer" in Office</span></span>](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in)
- [<span data-ttu-id="72c6e-116">Solucionar problemas de inicio de sesión con la autenticación moderna de Office al usar ADFS</span><span class="sxs-lookup"><span data-stu-id="72c6e-116">Troubleshoot sign-in issues with Office modern authentication when you use ADFS</span></span>](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-issue-with-modern-auth)