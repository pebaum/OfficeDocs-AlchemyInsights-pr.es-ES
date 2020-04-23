---
title: Cambiar NameServers
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "5"
- "14"
ms.openlocfilehash: 572f8befd84f55cb07a3535852a46e735d3ed620
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43706772"
---
# <a name="update-your-domain-nameservers-to-point-to-microsoft"></a>Actualizar los servidores de nombre de dominio para que señalen a Microsoft

Nota: Los cambios de Nameserver a veces pueden tardar hasta 48 horas en propagarse.
  
Para configurar su dominio en Microsoft 365, los servidores DNS en su registrador deben actualizarse. Cree o edite los registros del servidor DNS en el registrador de dominios.
  
1. Vaya al sitio web del registrador de dominios y busque el área donde puede modificar los servidores DNS.
  
2. Cree edite dos registros de servidores DNS para que coincidan con estos valores:

  - ns1.bdm.microsoftonline.com

  - ns2.bdm.microsoftonline.com

3. Guarde los cambios.

También encontrará instrucciones detalladas en este artículo: [Cambiar los servidores DNS con cualquier registrador de dominio](https://docs.microsoft.com//office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)
  