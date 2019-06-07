---
title: Corregir problemas de configuración de DKIM
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1389
ms.assetid: ''
ms.openlocfilehash: 4d6dadbcbf71fe6e9ea56d6a82a7d8ababdd38ef
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/07/2019
ms.locfileid: "34765439"
---
# <a name="fix-dkim-setup-issues"></a><span data-ttu-id="47952-102">Corregir problemas de configuración de DKIM</span><span class="sxs-lookup"><span data-stu-id="47952-102">Fix DKIM setup issues</span></span>

<span data-ttu-id="47952-103">Si experimenta problemas para habilitar DKIM para su dominio personalizado, siga estos pasos:</span><span class="sxs-lookup"><span data-stu-id="47952-103">If you experience issues enabling DKIM for your custom domain, use the following steps:</span></span>

- <span data-ttu-id="47952-104">La mayoría de los problemas de configuración de DKIM están relacionados con registros DNS incorrectos.</span><span class="sxs-lookup"><span data-stu-id="47952-104">Most DKIM setup issues are related to incorrect DNS records.</span></span> <span data-ttu-id="47952-105">Compruebe que el registro CNAME de DKIM (**no** un registro txt) tiene el formato correcto.</span><span class="sxs-lookup"><span data-stu-id="47952-105">Verify the DKIM CNAME record (**not** a TXT record) is formatted correctly.</span></span> <span data-ttu-id="47952-106">Para obtener más información, vea este [tema](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).</span><span class="sxs-lookup"><span data-stu-id="47952-106">For more information, see this [topic](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).</span></span>

- <span data-ttu-id="47952-107">Después de crear o actualizar los registros DNS de DKIM en el servicio de hospedaje DNS para su dominio (normalmente, el registrador de dominios), espere a que se propaguen los registros DNS.</span><span class="sxs-lookup"><span data-stu-id="47952-107">After you create or update your DKIM DNS records at the DNS hosting service for your domain (typically, your domain registrar), wait for the DNS records to propagate.</span></span>

- <span data-ttu-id="47952-108">Si no puede crear los registros DNS de DKIM en el centro de administración, puede \<reemplazar\> CustomDomain por su dominio personalizado (por ejemplo, contoso.com) y ejecutar este comando en [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true`.</span><span class="sxs-lookup"><span data-stu-id="47952-108">If you can't create the DKIM DNS records in the admin center, you can replace \<CustomDomain\> with your custom domain (for example, contoso.com) and run this command in [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true`.</span></span>
