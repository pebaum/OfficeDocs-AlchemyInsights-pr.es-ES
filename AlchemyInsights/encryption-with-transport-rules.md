---
title: Cifrado con reglas de transporte
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002635"
- "5154"
ms.openlocfilehash: 3f16c7e7be99a50cd57f47ea2801b3022c4aec95
ms.sourcegitcommit: 07725fcaf073f0ac145f98653b989afdb34c5ad0
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/28/2020
ms.locfileid: "43915288"
---
# <a name="encryption-with-transport-rules"></a><span data-ttu-id="a9df8-102">Cifrado con reglas de transporte</span><span class="sxs-lookup"><span data-stu-id="a9df8-102">Encryption with transport rules</span></span>

<span data-ttu-id="a9df8-103">En el [Centro de administración de Exchange](https://go.microsoft.com/fwlink/p/?linkid=834822) (EAC), puede usar las funciones de cifrado de mensajes de Office (OME) en las reglas de flujo del correo para desencadenar el cifrado de mensajes.</span><span class="sxs-lookup"><span data-stu-id="a9df8-103">In the [Exchange Admin Center](https://go.microsoft.com/fwlink/p/?linkid=834822) (EAC), you can use Office Message Encryption(OME) capabilities in your mail flow rules to trigger message encryption.</span></span> <span data-ttu-id="a9df8-104">Elija la opción **Aplicar el cifrado de mensajes de Office 365 y la protección de derechos** en la condición de Regla de transporte.</span><span class="sxs-lookup"><span data-stu-id="a9df8-104">Choose the **Apply Office 365 Message Encryption and rights protection** option on the Transport Rule condition.</span></span>

- <span data-ttu-id="a9df8-105">Para más información, consulte [Definir regla de flujo de correo para cifrar](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email).</span><span class="sxs-lookup"><span data-stu-id="a9df8-105">For more information, see [Define Mail flow rule to encrypt](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email).</span></span>

- <span data-ttu-id="a9df8-106">En PowerShell, use el cmdlet [New-TransportRule](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email?view=o365-worldwide#use-exchange-online-powershell-to-create-a-mail-flow-rule-for-encrypting-email-messages-without-the-new-ome-capabilities) y establezca el parámetro *ApplyOME* en $true.</span><span class="sxs-lookup"><span data-stu-id="a9df8-106">In Powershell, use the [New-TransportRule](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email?view=o365-worldwide#use-exchange-online-powershell-to-create-a-mail-flow-rule-for-encrypting-email-messages-without-the-new-ome-capabilities) cmdlet and set the *ApplyOME* parameter to $true.</span></span>
