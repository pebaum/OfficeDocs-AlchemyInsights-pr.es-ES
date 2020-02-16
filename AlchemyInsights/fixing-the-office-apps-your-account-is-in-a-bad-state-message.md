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
ms.openlocfilehash: e591c56dd207a5bcb3979be3f66052121100b162
ms.sourcegitcommit: 2572c4e5a981d5f3f556835061c568cfd08b78da
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/27/2019
ms.locfileid: "41969825"
---
# <a name="fixing-the-office-apps-your-account-is-in-a-bad-state-error"></a><span data-ttu-id="95f07-102">Error al reparar las aplicaciones de Office "la cuenta está en mal estado"</span><span class="sxs-lookup"><span data-stu-id="95f07-102">Fixing the Office apps "Your account is in a bad state" error</span></span>

<span data-ttu-id="95f07-103">Para solucionar este error, pruebe las siguientes opciones en el equipo afectado:</span><span class="sxs-lookup"><span data-stu-id="95f07-103">To fix this error, try the following options on the affected computer:</span></span>

- <span data-ttu-id="95f07-104">Abra una aplicación de Office, \*\*\*\* > seleccione Cerrar sesión en la**cuenta** > **de archivo de todas las cuentas**.</span><span class="sxs-lookup"><span data-stu-id="95f07-104">Open an Office app, select **File** > **Account** > **Sign Out of all accounts**.</span></span> <span data-ttu-id="95f07-105">Inicie sesión de nuevo con una cuenta de usuario con una licencia válida.</span><span class="sxs-lookup"><span data-stu-id="95f07-105">Sign in again using a user account with a valid license.</span></span> <span data-ttu-id="95f07-106">Para obtener información detallada, consulte [accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span><span class="sxs-lookup"><span data-stu-id="95f07-106">For detailed information, see [Accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span></span>
- <span data-ttu-id="95f07-107">[Borre las credenciales de Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) con el administrador de credenciales de Windows.</span><span class="sxs-lookup"><span data-stu-id="95f07-107">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br>
  <span data-ttu-id="95f07-108">**Nota:** Las rutas del registro para Office 2016 han cambiado a 16,0.</span><span class="sxs-lookup"><span data-stu-id="95f07-108">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="95f07-109">Por ejemplo, \Software\Microsoft\Office\16.0\Common\Identity</span><span class="sxs-lookup"><span data-stu-id="95f07-109">For example, \Software\Microsoft\Office\16.0\Common\Identity</span></span>\
- <span data-ttu-id="95f07-110">En el equipo afectado, establezca EnableADAL = 0 mediante los pasos siguientes:</span><span class="sxs-lookup"><span data-stu-id="95f07-110">On the affected computer, set the EnableADAL = 0 using the following steps:</span></span>  
     1. <span data-ttu-id="95f07-111">Haga clic con el botón derecho en el botón Windows y seleccione **Ejecutar**.</span><span class="sxs-lookup"><span data-stu-id="95f07-111">Right-click the Windows button and select **Run**.</span></span> <span data-ttu-id="95f07-112">En el cuadro **abrir** , escriba **regedit**y, a continuación, seleccione **Aceptar**.</span><span class="sxs-lookup"><span data-stu-id="95f07-112">In the **Open** box, type **regedit**, and then select **OK**.</span></span>
     2. <span data-ttu-id="95f07-113">Seleccione **sí** cuando se le pregunte si desea permitir que el editor del registro realice cambios en el dispositivo.</span><span class="sxs-lookup"><span data-stu-id="95f07-113">Select **Yes** when prompted to allow Registry Editor to make changes to your device.</span></span>
    3. <span data-ttu-id="95f07-114">En el editor del registro, agregue un valor DWORD de EnableADAL con un valor de 0 en HKEY_CURRENT_USER \Software\Microsoft\Office\16.0\Common\Identity.</span><span class="sxs-lookup"><span data-stu-id="95f07-114">In the Registry Editor, add a DWORD value of EnableADAL with a setting of 0 under HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity.</span></span>
- <span data-ttu-id="95f07-115">Si el error se produce al conectar con Office 365 mediante Office 2013, [habilite la autenticación moderna](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication) para el cliente de Office.</span><span class="sxs-lookup"><span data-stu-id="95f07-115">If the error occurs while connecting to Office 365 using Office 2013, [enable modern authentication](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication) for the Office client.</span></span>

<span data-ttu-id="95f07-116">Para obtener más información, vea [cómo solucionar problemas de aplicaciones que no son de explorador que no pueden iniciar sesión en Office 365, Azure o Intune](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1).</span><span class="sxs-lookup"><span data-stu-id="95f07-116">For more information, see [How to troubleshoot non-browser apps that can't sign in to Office 365, Azure, or Intune](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1).</span></span>

