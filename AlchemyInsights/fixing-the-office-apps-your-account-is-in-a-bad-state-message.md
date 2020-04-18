---
title: Corrección de las aplicaciones de Office la cuenta está en un mensaje de estado incorrecto
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2558"
- "9000571"
ms.openlocfilehash: b28865ff1da434a254c9051183074be35cdd0252
ms.sourcegitcommit: 9b2b162ad651e2c3d9d0c746f67a78334592f076
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/17/2020
ms.locfileid: "43547979"
---
# <a name="fixing-the-office-apps-your-account-is-in-a-bad-state-error"></a><span data-ttu-id="1eebc-102">Error al reparar las aplicaciones de Office "la cuenta está en mal estado"</span><span class="sxs-lookup"><span data-stu-id="1eebc-102">Fixing the Office apps "Your account is in a bad state" error</span></span>

<span data-ttu-id="1eebc-103">Para solucionar este error, pruebe las siguientes opciones en el equipo afectado:</span><span class="sxs-lookup"><span data-stu-id="1eebc-103">To fix this error, try the following options on the affected computer:</span></span>

- <span data-ttu-id="1eebc-104">Abra una aplicación de Office, **File** > seleccione Cerrar sesión en la**cuenta** > **de archivo de todas las cuentas**.</span><span class="sxs-lookup"><span data-stu-id="1eebc-104">Open an Office app, select **File** > **Account** > **Sign Out of all accounts**.</span></span> <span data-ttu-id="1eebc-105">Inicie sesión de nuevo con una cuenta de usuario con una licencia válida.</span><span class="sxs-lookup"><span data-stu-id="1eebc-105">Sign in again using a user account with a valid license.</span></span> <span data-ttu-id="1eebc-106">Para obtener información más detallada, consulte [Cuentas en Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span><span class="sxs-lookup"><span data-stu-id="1eebc-106">For detailed information, see [Accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span></span>
- <span data-ttu-id="1eebc-107">[Borre las credenciales de Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) con el administrador de credenciales de Windows.</span><span class="sxs-lookup"><span data-stu-id="1eebc-107">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br>
  <span data-ttu-id="1eebc-108">**Nota:** Las rutas del registro para Office 2016 han cambiado a 16,0.</span><span class="sxs-lookup"><span data-stu-id="1eebc-108">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="1eebc-109">Por ejemplo, \Software\Microsoft\Office\16.0\Common\Identity</span><span class="sxs-lookup"><span data-stu-id="1eebc-109">For example, \Software\Microsoft\Office\16.0\Common\Identity</span></span>\
- <span data-ttu-id="1eebc-110">Si el error se produce al conectar con Office 365 mediante Office 2013, [habilite la autenticación moderna](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication) para el cliente de Office.</span><span class="sxs-lookup"><span data-stu-id="1eebc-110">If the error occurs while connecting to Office 365 using Office 2013, [enable modern authentication](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication) for the Office client.</span></span>

<span data-ttu-id="1eebc-111">Para obtener más información, vea [cómo solucionar problemas de aplicaciones que no son de explorador que no pueden iniciar sesión en Office 365, Azure o Intune](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1).</span><span class="sxs-lookup"><span data-stu-id="1eebc-111">For more information, see [How to troubleshoot non-browser apps that can't sign in to Office 365, Azure, or Intune](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1).</span></span>

