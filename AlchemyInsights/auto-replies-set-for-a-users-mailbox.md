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
ms.openlocfilehash: 4ffe8d77dad7db5fd5806fe879cf4934e5ca7c4a
ms.sourcegitcommit: 89ae9e8b36d1980f89f07b016fff0ec48f96b620
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2020
ms.locfileid: "43788899"
---
# <a name="set-auto-replies-for-a-users-mailbox"></a><span data-ttu-id="a5654-102">Establecer respuestas automáticas para un buzón de correo</span><span class="sxs-lookup"><span data-stu-id="a5654-102">Set auto replies for a user's mailbox</span></span>

<span data-ttu-id="a5654-103">**Método 1**</span><span class="sxs-lookup"><span data-stu-id="a5654-103">**Method 1**</span></span>

1. <span data-ttu-id="a5654-104">Iniciar sesión en el Portal de Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="a5654-104">Sign in to the Microsoft 365 portal.</span></span>

2. <span data-ttu-id="a5654-105">Vaya a **Usuarios > Usuarios activos** (o **Grupos > Buzones compartidos** si configura esto en un buzón compartido).</span><span class="sxs-lookup"><span data-stu-id="a5654-105">Go to **Users > Active users** (or **Groups > Shared mailboxes** if you set this on a shared mailbox).</span></span>

3. <span data-ttu-id="a5654-106">Seleccione un usuario que tenga un buzón de Microsoft Exchange.</span><span class="sxs-lookup"><span data-stu-id="a5654-106">Select a user who has a Microsoft Exchange mailbox.</span></span>

4. <span data-ttu-id="a5654-107">En el menú emergente de la derecha, vaya a **Configuración de correo > Respuestas automáticas** (si se trata de un buzón compartido, haga clic en **Respuestas automáticas** en la parte emergente).</span><span class="sxs-lookup"><span data-stu-id="a5654-107">On the fly-out menu on the right, go to **Mail settings > Automatic replies** (if it's a shared mailbox, just click **Automatic replies** on the fly-out).</span></span>

<span data-ttu-id="a5654-108">**Método 2**</span><span class="sxs-lookup"><span data-stu-id="a5654-108">**Method 2**</span></span>

1. <span data-ttu-id="a5654-109">Iniciar sesión en el Portal de administración de Microsoft 365 con las credenciales de administrador.</span><span class="sxs-lookup"><span data-stu-id="a5654-109">Sign in to the Microsoft 365 admin portal by using administrator credentials.</span></span>

2. <span data-ttu-id="a5654-110">Expanda **Centros de administración** y, luego, haga clic en **Exchange**.</span><span class="sxs-lookup"><span data-stu-id="a5654-110">Expand **Admin Centers**, and then click **Exchange**.</span></span>

3. <span data-ttu-id="a5654-111">Haga clic en la imagen de la esquina superior derecha, luego en **Otro usuario** y, a continuación, seleccione el buzón de usuario que quiere cambiar.</span><span class="sxs-lookup"><span data-stu-id="a5654-111">Click the picture in the upper-right corner, click **Another User**, and then select the user mailbox that you want to change.</span></span>

4. <span data-ttu-id="a5654-112">En el lado izquierdo, seleccione **Opciones**, haga clic en **Organizar correo electrónico** y, a continuación, haga clic en **Respuestas automáticas.**</span><span class="sxs-lookup"><span data-stu-id="a5654-112">On the left side, select **Options**, click **Organize E-mail**, and then click **Automatic replies.**</span></span>

<span data-ttu-id="a5654-113">**Método 3**</span><span class="sxs-lookup"><span data-stu-id="a5654-113">**Method 3**</span></span>

<span data-ttu-id="a5654-114">Ejecute los siguientes cmdlet en Exchange Online PowerShell:</span><span class="sxs-lookup"><span data-stu-id="a5654-114">Run the following cmdlet in Exchange Online PowerShell:</span></span>

<span data-ttu-id="a5654-115">PowerShellCopy</span><span class="sxs-lookup"><span data-stu-id="a5654-115">PowerShellCopy</span></span>

```
    Set-MailboxAutoReplyConfiguration
```

<span data-ttu-id="a5654-116">Para obtener más información sobre este cmdlet, consulte [Set-MailboxAutoReplyConfiguration](https://docs.microsoft.com/powershell/module/exchange/mailboxes/set-mailboxautoreplyconfiguration).</span><span class="sxs-lookup"><span data-stu-id="a5654-116">For more information about this cmdlet, see [Set-MailboxAutoReplyConfiguration](https://docs.microsoft.com/powershell/module/exchange/mailboxes/set-mailboxautoreplyconfiguration).</span></span>
