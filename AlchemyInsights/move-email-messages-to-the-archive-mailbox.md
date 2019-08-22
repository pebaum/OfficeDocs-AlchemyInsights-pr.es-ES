---
title: Mover mensajes de correo electrónico al buzón de archivo
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1083"
- "3100008"
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: ce52df446fc4c23c06476e8836ade6a6810d158f
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36549021"
---
# <a name="move-email-to-the-archive-mailbox"></a><span data-ttu-id="f0e95-102">Mover el correo electrónico al buzón de archivo</span><span class="sxs-lookup"><span data-stu-id="f0e95-102">Move email to the archive mailbox</span></span>

1. <span data-ttu-id="f0e95-103">Confirme que se ha habilitado un **buzón de archivo** .</span><span class="sxs-lookup"><span data-stu-id="f0e95-103">Confirm that an **Archive mailbox** has been enabled.</span></span> <span data-ttu-id="f0e95-104">Si no es así, siga los pasos de [este artículo](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) para habilitar el buzón de archivo.</span><span class="sxs-lookup"><span data-stu-id="f0e95-104">If not, use the steps in [this article](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) to enable the archive mailbox.</span></span>

2. <span data-ttu-id="f0e95-105">Para archivar mensajes automáticamente en el buzón de archivo, se debe establecer una etiqueta de retención con la acción **mover a archivo** para que se **aplique automáticamente a toda la etiqueta del buzón (predeterminado)**.</span><span class="sxs-lookup"><span data-stu-id="f0e95-105">To archive messages automatically to the archive mailbox, a retention tag with the **Move to archive** action must be set to **applied automatically to entire mailbox (default) tag**.</span></span> <span data-ttu-id="f0e95-106">Siga los pasos que se describen aquí para crear la etiqueta: archivar la [etiqueta predeterminada](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Foffice365%2Fsecuritycompliance%2Fset-up-an-archive-and-deletion-policy-for-mailboxes%23create-a-custom-archive-default-policy-tag&data=04%7C01%7Cstephow%40microsoft.com%7C89934e16dbd84ebdef6708d6b319b348%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C636893320296576506%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C-1&sdata=UibWi%2BtrO3ITZ6iF%2FtKQj5JyxzEb9Mu9frBJPT6FNFI%3D&reserved=0).</span><span class="sxs-lookup"><span data-stu-id="f0e95-106">Use the steps here to create the tag: [Archive Default tag](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Foffice365%2Fsecuritycompliance%2Fset-up-an-archive-and-deletion-policy-for-mailboxes%23create-a-custom-archive-default-policy-tag&data=04%7C01%7Cstephow%40microsoft.com%7C89934e16dbd84ebdef6708d6b319b348%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C636893320296576506%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C-1&sdata=UibWi%2BtrO3ITZ6iF%2FtKQj5JyxzEb9Mu9frBJPT6FNFI%3D&reserved=0).</span></span>

3. <span data-ttu-id="f0e95-107">A continuación, agregue la etiqueta de **archivo** a la Directiva de retención.</span><span class="sxs-lookup"><span data-stu-id="f0e95-107">Next, add the **Archive** tag to your retention policy.</span></span> <span data-ttu-id="f0e95-108">En el centro de administración de Exchange, seleccione **directivas de retención** > agregue la **etiqueta mover a archivo** a la Directiva > **Guardar**.</span><span class="sxs-lookup"><span data-stu-id="f0e95-108">In the Exchange admin center, choose **Retention Policies** > add the **Move to Archive tag** to the policy > **Save**.</span></span>

4. <span data-ttu-id="f0e95-109">Ahora [asigne la Directiva de retención](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) al buzón de correo del usuario específico.</span><span class="sxs-lookup"><span data-stu-id="f0e95-109">Now [Assign the Retention Policy](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) to the specific user's mailbox.</span></span> <span data-ttu-id="f0e95-110">La misma directiva se aplicará al buzón **principal** y al buzón de **archivo** .</span><span class="sxs-lookup"><span data-stu-id="f0e95-110">The same policy will be applied to both the **Primary** and the **Archive** mailbox.</span></span>

<span data-ttu-id="f0e95-111">Puede que sea necesario forzar la ejecución del Asistente para carpeta administrada (MFA) y aplicar la nueva configuración al buzón de correo del usuario.</span><span class="sxs-lookup"><span data-stu-id="f0e95-111">It may be necessary to force the Managed Folder Assistant (MFA) to run and apply the new settings to the user's mailbox.</span></span> <span data-ttu-id="f0e95-112">Ejecute el comando siguiente mientras [está conectado a Exo PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) para iniciar el Asistente para carpeta administrada para un buzón específico:</span><span class="sxs-lookup"><span data-stu-id="f0e95-112">Run the following command while [connected to EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) to start the Managed Folder Assistant for a specific mailbox:</span></span>
  
<span data-ttu-id="f0e95-113">Start-ManagedFolderAssistant-Identity<name of the mailbox></span><span class="sxs-lookup"><span data-stu-id="f0e95-113">Start-ManagedFolderAssistant -Identity <name of the mailbox></span></span>

<span data-ttu-id="f0e95-114">Para obtener más información sobre cómo configurar una directiva de archivo, consulte [configurar una directiva de archivo y eliminación para](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users)los buzones.</span><span class="sxs-lookup"><span data-stu-id="f0e95-114">For more information on setting up an archive policy, see [Set up an archive and deletion policy for mailboxes](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span></span>
  