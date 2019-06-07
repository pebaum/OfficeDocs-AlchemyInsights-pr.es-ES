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
# <a name="fix-dkim-setup-issues"></a>Corregir problemas de configuración de DKIM

Si experimenta problemas para habilitar DKIM para su dominio personalizado, siga estos pasos:

- La mayoría de los problemas de configuración de DKIM están relacionados con registros DNS incorrectos. Compruebe que el registro CNAME de DKIM (**no** un registro txt) tiene el formato correcto. Para obtener más información, vea este [tema](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).

- Después de crear o actualizar los registros DNS de DKIM en el servicio de hospedaje DNS para su dominio (normalmente, el registrador de dominios), espere a que se propaguen los registros DNS.

- Si no puede crear los registros DNS de DKIM en el centro de administración, puede \<reemplazar\> CustomDomain por su dominio personalizado (por ejemplo, contoso.com) y ejecutar este comando en [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true`.
