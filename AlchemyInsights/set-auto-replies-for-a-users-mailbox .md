---
title: Establecer respuestas automáticas para un buzón de correo
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000761"
- "3514"
ms.openlocfilehash: e3cc01298c10fd3ba21327a7fb5cc5396d0ad74d
ms.sourcegitcommit: 23e5b94f1758bfe202008384e300b81816975375
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/14/2020
ms.locfileid: "43506649"
---
# <a name="set-auto-replies-for-a-users-mailbox"></a><span data-ttu-id="82300-102">Establecer respuestas automáticas para un buzón de correo</span><span class="sxs-lookup"><span data-stu-id="82300-102">Set auto replies for a user's mailbox</span></span>

<span data-ttu-id="82300-103">**Método 1**</span><span class="sxs-lookup"><span data-stu-id="82300-103">**Method 1**</span></span>

1. <span data-ttu-id="82300-104">Iniciar sesión en el portal de Office 365</span><span class="sxs-lookup"><span data-stu-id="82300-104">Sign in to the Office 365 portal.</span></span>

2. <span data-ttu-id="82300-105">Vaya a **Usuarios > Usuarios activos** (o **Grupos > Buzones compartidos** si configura esto en un buzón compartido).</span><span class="sxs-lookup"><span data-stu-id="82300-105">Go to **Users > Active users** (or **Groups > Shared mailboxes** if you set this on a shared mailbox).</span></span>

3. <span data-ttu-id="82300-106">Seleccione un usuario que tenga un buzón de Microsoft Exchange.</span><span class="sxs-lookup"><span data-stu-id="82300-106">Select a user who has a Microsoft Exchange mailbox.</span></span>

4. <span data-ttu-id="82300-107">En el menú emergente de la derecha, vaya a **Configuración de correo > Respuestas automáticas** (si se trata de un buzón compartido, haga clic en **Respuestas automáticas** en la parte emergente).</span><span class="sxs-lookup"><span data-stu-id="82300-107">On the fly-out menu on the right, go to **Mail settings > Automatic replies** (if it's a shared mailbox, just click **Automatic replies** on the fly-out).</span></span>

<span data-ttu-id="82300-108">**Método 2**</span><span class="sxs-lookup"><span data-stu-id="82300-108">**Method 2**</span></span>

1. <span data-ttu-id="82300-109">Inicie sesión en el portal de administración de Office 365 con las credenciales de administrador.</span><span class="sxs-lookup"><span data-stu-id="82300-109">Sign in to the Office 365 admin portal by using administrator credentials.</span></span>

2. <span data-ttu-id="82300-110">Expanda **Centros de administración** y, luego, haga clic en **Exchange**.</span><span class="sxs-lookup"><span data-stu-id="82300-110">Expand **Admin Centers**, and then click **Exchange**.</span></span>

3. <span data-ttu-id="82300-111">Haga clic en la imagen de la esquina superior derecha, luego en **Otro usuario** y, a continuación, seleccione el buzón de usuario que quiere cambiar.</span><span class="sxs-lookup"><span data-stu-id="82300-111">Click the picture in the upper-right corner, click **Another User**, and then select the user mailbox that you want to change.</span></span>

4. <span data-ttu-id="82300-112">En el lado izquierdo, seleccione **Opciones**, haga clic en **Organizar correo electrónico** y, a continuación, haga clic en **Respuestas automáticas.**</span><span class="sxs-lookup"><span data-stu-id="82300-112">On the left side, select **Options**, click **Organize E-mail**, and then click **Automatic replies.**</span></span>

<span data-ttu-id="82300-113">**Método 3**</span><span class="sxs-lookup"><span data-stu-id="82300-113">**Method 3**</span></span>

<span data-ttu-id="82300-114">Ejecute los siguientes cmdlet en Exchange Online PowerShell:</span><span class="sxs-lookup"><span data-stu-id="82300-114">Run the following cmdlet in Exchange Online PowerShell:</span></span>

<span data-ttu-id="82300-115">PowerShellCopy</span><span class="sxs-lookup"><span data-stu-id="82300-115">PowerShellCopy</span></span>

    Set-MailboxAutoReplyConfiguration

<span data-ttu-id="82300-116">Para obtener más información sobre este cmdlet, consulte [Set-MailboxAutoReplyConfiguration](https://docs.microsoft.com/powershell/module/exchange/mailboxes/set-mailboxautoreplyconfiguration).</span><span class="sxs-lookup"><span data-stu-id="82300-116">For more information about this cmdlet, see [Set-MailboxAutoReplyConfiguration](https://docs.microsoft.com/powershell/module/exchange/mailboxes/set-mailboxautoreplyconfiguration).</span></span>
