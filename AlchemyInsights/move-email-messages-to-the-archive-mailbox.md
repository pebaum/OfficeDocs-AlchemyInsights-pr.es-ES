---
title: Mover mensajes de correo electrónico al buzón de archivo
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1083"
- "3100008"
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: a5ad81e97df0ed5c337a622126173df94af80bb8
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43713663"
---
# <a name="move-email-to-the-archive-mailbox"></a><span data-ttu-id="f42b3-102">Mover el correo electrónico al buzón de archivo</span><span class="sxs-lookup"><span data-stu-id="f42b3-102">Move email to the archive mailbox</span></span>

1. <span data-ttu-id="f42b3-103">Confirme que se ha habilitado un **buzón de archivo** .</span><span class="sxs-lookup"><span data-stu-id="f42b3-103">Confirm that an **Archive mailbox** has been enabled.</span></span> <span data-ttu-id="f42b3-104">Si no es así, siga los pasos de [este artículo](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) para habilitar el buzón de archivo.</span><span class="sxs-lookup"><span data-stu-id="f42b3-104">If not, use the steps in [this article](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) to enable the archive mailbox.</span></span>

2. <span data-ttu-id="f42b3-105">Para archivar mensajes automáticamente en el buzón de archivo, se debe establecer una etiqueta de retención con la acción **mover a archivo** para que se **aplique automáticamente a toda la etiqueta del buzón (predeterminado)**.</span><span class="sxs-lookup"><span data-stu-id="f42b3-105">To archive messages automatically to the archive mailbox, a retention tag with the **Move to archive** action must be set to **applied automatically to entire mailbox (default) tag**.</span></span> <span data-ttu-id="f42b3-106">Siga los pasos que se describen aquí para crear la etiqueta: [archivar la etiqueta predeterminada](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#create-a-custom-archive-default-policy-tag).</span><span class="sxs-lookup"><span data-stu-id="f42b3-106">Use the steps here to create the tag: [Archive Default tag](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#create-a-custom-archive-default-policy-tag).</span></span>

3. <span data-ttu-id="f42b3-107">A continuación, agregue la etiqueta de **archivo** a la Directiva de retención.</span><span class="sxs-lookup"><span data-stu-id="f42b3-107">Next, add the **Archive** tag to your retention policy.</span></span> <span data-ttu-id="f42b3-108">En el centro de administración de Exchange, seleccione **directivas de retención** > agregue la **etiqueta mover a archivo** a la Directiva > **Guardar**.</span><span class="sxs-lookup"><span data-stu-id="f42b3-108">In the Exchange admin center, choose **Retention Policies** > add the **Move to Archive tag** to the policy > **Save**.</span></span>

4. <span data-ttu-id="f42b3-109">Ahora [asigne la Directiva de retención](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) al buzón de correo del usuario específico.</span><span class="sxs-lookup"><span data-stu-id="f42b3-109">Now [Assign the Retention Policy](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) to the specific user's mailbox.</span></span> <span data-ttu-id="f42b3-110">La misma directiva se aplicará al buzón **principal** y al buzón de **archivo** .</span><span class="sxs-lookup"><span data-stu-id="f42b3-110">The same policy will be applied to both the **Primary** and the **Archive** mailbox.</span></span>

<span data-ttu-id="f42b3-111">Puede que sea necesario forzar la ejecución del Asistente para carpeta administrada (MFA) y aplicar la nueva configuración al buzón de correo del usuario.</span><span class="sxs-lookup"><span data-stu-id="f42b3-111">It may be necessary to force the Managed Folder Assistant (MFA) to run and apply the new settings to the user's mailbox.</span></span> <span data-ttu-id="f42b3-112">Ejecute el comando siguiente mientras [está conectado a Exo PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) para iniciar el Asistente para carpeta administrada para un buzón específico:</span><span class="sxs-lookup"><span data-stu-id="f42b3-112">Run the following command while [connected to EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) to start the Managed Folder Assistant for a specific mailbox:</span></span>
  
<span data-ttu-id="f42b3-113">Start-ManagedFolderAssistant-Identity<name of the mailbox></span><span class="sxs-lookup"><span data-stu-id="f42b3-113">Start-ManagedFolderAssistant -Identity <name of the mailbox></span></span>

<span data-ttu-id="f42b3-114">Para obtener más información sobre cómo configurar una directiva de archivo, consulte [configurar una directiva de archivo y eliminación para los buzones](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span><span class="sxs-lookup"><span data-stu-id="f42b3-114">For more information on setting up an archive policy, see [Set up an archive and deletion policy for mailboxes](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span></span>
  