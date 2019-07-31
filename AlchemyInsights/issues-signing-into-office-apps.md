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
- "2559"
ms.openlocfilehash: 5f500ecf1f779fb1be4d257fd050a3ad054087dc
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938352"
---
# <a name="fixing-the-office-apps-your-computers-trusted-platform-module-is-not-functioning-properly-message"></a><span data-ttu-id="0b469-102">El mensaje "el módulo de plataforma de confianza del equipo no funciona correctamente" para corregir las aplicaciones de Office</span><span class="sxs-lookup"><span data-stu-id="0b469-102">Fixing the Office apps "Your computer's Trusted Platform module is not functioning properly" message</span></span>

<span data-ttu-id="0b469-103">Para solucionar este error, intente lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="0b469-103">To fix this error, try the following:</span></span>

- <span data-ttu-id="0b469-104">Instale las actualizaciones más recientes para [Windows](https://support.microsoft.com/help/4027667/windows-10-update) y [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span><span class="sxs-lookup"><span data-stu-id="0b469-104">Install the latest updates for [Windows](https://support.microsoft.com/help/4027667/windows-10-update) and [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span></span>
- <span data-ttu-id="0b469-105">[Borre las credenciales de Office](https://docs.microsoft.com/eoffice/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) con el administrador de credenciales de Windows.</span><span class="sxs-lookup"><span data-stu-id="0b469-105">[Clear Office credentials](https://docs.microsoft.com/eoffice/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="0b469-106">**Nota:** Las rutas del registro para Office 2016 han cambiado a 16,0.</span><span class="sxs-lookup"><span data-stu-id="0b469-106">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="0b469-107">(Por ejemplo: \Software\Microsoft\Office\16.0\Common\Identity\)</span><span class="sxs-lookup"><span data-stu-id="0b469-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>
- <span data-ttu-id="0b469-108">Pruebe el [proceso de recuperación del usuario](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-2) para corregir los errores del módulo de plataforma de confianza (TPM).</span><span class="sxs-lookup"><span data-stu-id="0b469-108">Try the [user recovery process](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-2) to fix Trusted Platform Module (TPM) failures.</span></span>
- <span data-ttu-id="0b469-109">Establezca EnableADAL = 0 mediante los pasos siguientes:</span><span class="sxs-lookup"><span data-stu-id="0b469-109">Set the EnableADAL = 0 using the following steps:</span></span>  
    1. <span data-ttu-id="0b469-110">Haga clic con el botón secundario en el botón Inicio de Windows, elija **Ejecutar**, escriba regedit y, a continuación, elija **Aceptar**. \*\*\*\*</span><span class="sxs-lookup"><span data-stu-id="0b469-110">Right-click the Windows Start button, choose **Run**, type **regedit**, and then choose **OK**.</span></span>
    2. <span data-ttu-id="0b469-111">Seleccione **sí** para permitir que el editor del registro realice cambios en el dispositivo.</span><span class="sxs-lookup"><span data-stu-id="0b469-111">Select **Yes** to allow Registry Editor to make changes to your device.</span></span>
    3. <span data-ttu-id="0b469-112">En el editor del registro, agregue un valor DWORD de **EnableADAL** con un valor de **0** en HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity.</span><span class="sxs-lookup"><span data-stu-id="0b469-112">In Registry Editor, add a DWORD value of **EnableADAL** with a setting of **0** under HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity.</span></span>

<span data-ttu-id="0b469-113">Para obtener más información, vea [problemas de conexión en el inicio de sesión después de actualizar a Office 2016 Build 16.0.7967 en Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span><span class="sxs-lookup"><span data-stu-id="0b469-113">For more information, see [Connection issues in sign-in after update to Office 2016 build 16.0.7967 on Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span></span>