---
title: Retransmitir correo electrónico a través de Office 365
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "154"
- "3000003"
ms.assetid: 84191e23-496c-495a-a2ec-28c5ae0d4c0b
ms.openlocfilehash: e971593b7a67e1bb40243fc762bace6b87a35741
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 10/25/2019
ms.locfileid: "36745414"
---
# <a name="set-up-a-multifunction-device-or-application-to-send-email-using-office-365"></a><span data-ttu-id="70c10-102">Configurar una aplicación o dispositivo multifunción para enviar correos electrónicos mediante Office 365</span><span class="sxs-lookup"><span data-stu-id="70c10-102">Set up a multifunction device or application to send email using Office 365</span></span>

<span data-ttu-id="70c10-103">Para obtener más información sobre las opciones disponibles y los pasos, vea [Cómo configurar un dispositivo o aplicación multifunción para enviar correo mediante Office 365](https://docs.microsoft.com/Exchange/mail-flow-best-practices/how-to-set-up-a-multifunction-device-or-application-to-send-email-using-office-3).</span><span class="sxs-lookup"><span data-stu-id="70c10-103">To learn about your options and the steps, see [How to set up a multifunction device or application to send email using Office 365](https://docs.microsoft.com/Exchange/mail-flow-best-practices/how-to-set-up-a-multifunction-device-or-application-to-send-email-using-office-3).</span></span>
  
<span data-ttu-id="70c10-104">**Nota:** si tiene un dispositivo o aplicación que ha dejado de funcionar recientemente, tenga en cuenta que hemos comenzado a [deshabilitar el cifrado 3DES](https://docs.microsoft.com/office365/securitycompliance/technical-reference-details-about-encryption) según lo previsto.</span><span class="sxs-lookup"><span data-stu-id="70c10-104">**Note:** If you have a device or application which recently stopped working, please note we have recently begun [disabling the 3DES cipher](https://docs.microsoft.com/office365/securitycompliance/technical-reference-details-about-encryption) as planned.</span></span> <span data-ttu-id="70c10-105">Para ver los dispositivos afectados, vaya al [informe de clientes de autenticación SMTP](https://protection.office.com/mailflow/dashboard).</span><span class="sxs-lookup"><span data-stu-id="70c10-105">To see affected devices, go to the [SMTP Auth Clients report](https://protection.office.com/mailflow/dashboard).</span></span> <span data-ttu-id="70c10-106">Los errores comunes podrían ser similares a: error de autenticación, error de TLS, error del algoritmo de cifrado, error de coincidencia del algoritmo o conexión perdida.</span><span class="sxs-lookup"><span data-stu-id="70c10-106">Common errors could be similar to: Authentication failure/error, TLS failure/error, Cipher algorithm error, Algorithm mismatch, or Connection dropped.</span></span> <span data-ttu-id="70c10-107">Para resolver el problema:</span><span class="sxs-lookup"><span data-stu-id="70c10-107">To resolve this issue:</span></span>
 - <span data-ttu-id="70c10-108">**Windows Server 2003 IIS SMTP dejará de funcionar, se necesita una versión más reciente de Windows.**</span><span class="sxs-lookup"><span data-stu-id="70c10-108">**Windows Server 2003 IIS SMTP will no longer work – a newer version of Windows is required.**</span></span>  
 - <span data-ttu-id="70c10-109">Póngase en contacto con el proveedor de su aplicación o dispositivo para ver si admite un cifrado moderno o si hay una actualización.</span><span class="sxs-lookup"><span data-stu-id="70c10-109">Please check with your application or device vendor to see if a modern cipher is supported or if there is an update.</span></span>
