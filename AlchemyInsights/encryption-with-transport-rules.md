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
# <a name="encryption-with-transport-rules"></a>Cifrado con reglas de transporte

En el [Centro de administración de Exchange](https://go.microsoft.com/fwlink/p/?linkid=834822) (EAC), puede usar las funciones de cifrado de mensajes de Office (OME) en las reglas de flujo del correo para desencadenar el cifrado de mensajes. Elija la opción **Aplicar el cifrado de mensajes de Office 365 y la protección de derechos** en la condición de Regla de transporte.

- Para más información, consulte [Definir regla de flujo de correo para cifrar](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email).

- En PowerShell, use el cmdlet [New-TransportRule](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email?view=o365-worldwide#use-exchange-online-powershell-to-create-a-mail-flow-rule-for-encrypting-email-messages-without-the-new-ome-capabilities) y establezca el parámetro *ApplyOME* en $true.
