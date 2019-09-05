---
title: Actualizar los servidores DNS de dominio a Office 365
ms.author: v-crytho
author: CrystalThomasMS
ms.date: 5/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 5d38b331-a0e8-4937-8bda-4f8f715e1976
ms.custom:
- "6"
- "14"
ms.openlocfilehash: 23d49c734148739ede0d5e5b53430a42b606c831
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/04/2019
ms.locfileid: "36742204"
---
# <a name="update-your-domain-nameservers-to-office-365"></a>Actualizar los servidores DNS de dominio a Office 365

Nota: Los cambios de Nameserver a veces pueden tardar hasta 48 horas en propagarse.
  
Para configurar su dominio en Office 365, los servidores DNS en su registrador deben actualizarse. Cree o edite los registros del servidor DNS en el registrador de dominios.
  
1. Vaya al sitio web del registrador de dominios y busque el área donde puede modificar los servidores DNS.

2. Cree edite dos registros de servidores DNS para que coincidan con estos valores:

  - ns1.bdm.microsoftonline.com

  - ns2.bdm.microsoftonline.com

3. Guarde los cambios.

También encontrará instrucciones detalladas en este artículo: [Cambiar los servidores DNS para configurar Office 365 con cualquier registrador de dominio](https://docs.microsoft.com/office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)
  