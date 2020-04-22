---
title: Actualizar los servidores de nombres de dominio para que apunten a Microsoft
ms.author: v-crytho
author: CrystalThomasMS
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 5d38b331-a0e8-4937-8bda-4f8f715e1976
ms.custom:
- "6"
- "14"
ms.openlocfilehash: b49ca9422f582f906fc6c108c85cc26150474548
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43720010"
---
# <a name="update-your-domain-nameservers-to-point-to-microsoft"></a>Actualizar los servidores de nombres de dominio para que apunten a Microsoft

Nota: Los cambios de Nameserver a veces pueden tardar hasta 48 horas en propagarse.
  
Para configurar su dominio con Microsoft, los servidores de nombres en su registrador deben actualizarse. Cree o edite los registros del servidor DNS en el registrador de dominios.
  
1. Vaya al sitio web del registrador de dominios y busque el área donde puede modificar los servidores DNS.

2. Cree edite dos registros de servidores DNS para que coincidan con estos valores:

  - ns1.bdm.microsoftonline.com

  - ns2.bdm.microsoftonline.com

3. Guarde los cambios.

También puede encontrar instrucciones detalladas en este artículo: [cambiar los servidores de nombres para configurar Microsoft 365 con cualquier registrador de dominios](https://docs.microsoft.com/office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)
  