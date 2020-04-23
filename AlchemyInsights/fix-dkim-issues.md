---
title: Corregir problemas de configuración de DKIM
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1389
ms.assetid: ''
ms.openlocfilehash: d725eb0d46dcbf1b5b6d77ca9f59fcafa5298bf1
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43717579"
---
# <a name="fix-dkim-setup-issues"></a>Corregir problemas de configuración de DKIM

Si experimenta problemas para habilitar DKIM para su dominio personalizado, siga estos pasos:

- La mayoría de los problemas de configuración de DKIM están relacionados con registros DNS incorrectos. Compruebe que el registro CNAME de DKIM (**no** un registro txt) tiene el formato correcto. Para obtener más información, vea este [tema](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).

- Después de crear o actualizar los registros DNS de DKIM en el servicio de hospedaje DNS para su dominio (normalmente, el registrador de dominios), espere a que se propaguen los registros DNS.

- Si no puede crear los registros DNS de DKIM en el centro de administración, puede \<reemplazar\> CustomDomain por su dominio personalizado (por ejemplo, contoso.com) y ejecutar este comando en [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true`.
