---
title: Instalación de DKIM en Office 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1388
ms.assetid: ''
ms.openlocfilehash: 0f81fe02135f3d0901ffe5a26d7aa3dad70c3770
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/07/2019
ms.locfileid: "34765451"
---
# <a name="setup-dkim-in-office-365"></a>Instalación de DKIM en Office 365

[Aquí](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365)se indican las instrucciones completas para configurar DKIM para los dominios personalizados en Office 365.

1. Para **cada** dominio personalizado, debe crear **dos** registros CNAME de DKIM en el servicio de hospedaje de DNS de su dominio (normalmente, el registrador de dominios). Por ejemplo, contoso.com y fourthcoffee.com requieren cuatro registros CNAME de DKIM: dos para contoso.com y dos para fourthcoffee.com.

   Los registros CNAME de DKIM para **cada** dominio personalizado usan los siguientes formatos:

   - **Nombre de host**:`selector1._domainkey.<CustomDomain>`

     **Apunta a la dirección o al valor**:`selector1-<DomainGUID>._domainkey.<InitialDomain>`

     **TTL**: 3600

   - **Nombre de host**:`selector2._domainkey.<CustomDomain>`

     **Apunta a la dirección o al valor**:`selector2-<DomainGUID>._domainkey.<InitialDomain>`

     **TTL**: 3600

   \<DomainGUID\> es el texto a la izquierda de `.mail.protection.outlook.com` en el registro MX personalizado para el dominio personalizado (por ejemplo, `contoso-com` para el dominio contoso.com). \<InitialDomain\> es el dominio que usó al registrarse en Office 365 (por ejemplo, contoso.onmicrosoft.com).

2. Una vez que haya creado los registros CNAME para sus dominios personalizados, siga las instrucciones siguientes:

   a. [Inicie sesión en Office 365](https://support.office.microsoft.com/article/e9eb7d51-5430-4929-91ab-6157c5a050b4) con su cuenta profesional o educativa.

   b. Seleccione el icono del iniciador de aplicaciones en la esquina superior izquierda y elija **Administrador**.

   c. En el panel de navegación inferior izquierdo, expanda **Administración** y elija **Exchange**.

   d. Vaya a **protección** > **DKIM**.

   e. Seleccione el dominio y, a continuación, elija **Habilitar** para **firmar mensajes para este dominio con firmas DKIM**. Repita este paso para cada dominio personalizado.
