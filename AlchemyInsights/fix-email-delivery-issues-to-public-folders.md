---
title: Corregir problemas de entrega de correo electrónico en carpetas públicas habilitadas para correo
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1956
ms.assetid: ''
ms.openlocfilehash: 900b6cc2765937ee005c7e7dce5d33bbdf582601
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/07/2019
ms.locfileid: "34752696"
---
# <a name="fix-email-delivery-issues-to-mail-enabled-public-folders"></a><span data-ttu-id="b7558-102">Corregir problemas de entrega de correo electrónico en carpetas públicas habilitadas para correo</span><span class="sxs-lookup"><span data-stu-id="b7558-102">Fix email delivery issues to mail-enabled public folders</span></span>

<span data-ttu-id="b7558-103">Si los remitentes externos no pueden enviar mensajes a sus carpetas públicas habilitadas para correo y los remitentes reciben el siguiente error: **no se encontró (550 5.4.1)**, compruebe que el dominio de correo electrónico de la carpeta pública esté configurado como un dominio de retransmisión interna en lugar de un dominio autoritativo:</span><span class="sxs-lookup"><span data-stu-id="b7558-103">If external senders can't send messages to your mail-enabled public folders, and the senders receive the error: **couldn't be found (550 5.4.1)**, verify the email domain for the public folder is configured as an internal relay domain instead of an authoritative domain:</span></span>

1. <span data-ttu-id="b7558-104">Abra el [centro de administración de Exchange (EAC)](https://docs.microsoft.com/Exchange/exchange-admin-center).</span><span class="sxs-lookup"><span data-stu-id="b7558-104">Open the [Exchange admin center (EAC)](https://docs.microsoft.com/Exchange/exchange-admin-center).</span></span>

2. <span data-ttu-id="b7558-105">Vaya a \*\*\*\* \> **dominios aceptados**de flujo de correo, seleccione el dominio aceptado y, a continuación, haga clic en **Editar**.</span><span class="sxs-lookup"><span data-stu-id="b7558-105">Go to **Mail flow** \> **Accepted domains**, select the accepted domain, and then click **Edit**.</span></span>

3. <span data-ttu-id="b7558-106">En la página de propiedades que se abre, si el tipo de dominio \*\*\*\* está configurado como autoritativo, cambie el valor a retransmisión **interna** y, a continuación, haga clic en **Guardar**.</span><span class="sxs-lookup"><span data-stu-id="b7558-106">In the properties page that opens, if the domain type is set to **Authoritative**, change the value to **Internal relay** and then click **Save**.</span></span>

<span data-ttu-id="b7558-107">Si los remitentes externos reciben el error **que no tiene permiso (550 5.7.13)**, ejecute el siguiente comando en [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) para ver los permisos de los usuarios anónimos en la carpeta pública:</span><span class="sxs-lookup"><span data-stu-id="b7558-107">If external senders receive the error **you don't have permission (550 5.7.13)**, run the following command in [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) to see the permissions for anonymous users in the public folder:</span></span>

<span data-ttu-id="b7558-108">`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous`Por ejemplo, `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous`.</span><span class="sxs-lookup"><span data-stu-id="b7558-108">`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous` For example, `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous`.</span></span>

<span data-ttu-id="b7558-109">Para permitir que los usuarios externos envíen correo electrónico a esta carpeta pública, agregue el derecho de acceso CreateItems al usuario anónimo.</span><span class="sxs-lookup"><span data-stu-id="b7558-109">To allow external users to send email to this public folder, add the CreateItems access right to the user Anonymous.</span></span> <span data-ttu-id="b7558-110">Por ejemplo, `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.</span><span class="sxs-lookup"><span data-stu-id="b7558-110">For example, `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.</span></span>
