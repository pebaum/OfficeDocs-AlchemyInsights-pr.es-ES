---
title: 2609-retención-o-eDiscovery-Hold
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2609"
- "9000048"
ms.openlocfilehash: 85c41995545efd8e1526d9f7dce4a23929f85be5
ms.sourcegitcommit: 24e8248b0f061a76af50bf566d7a13fc24d29d99
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/05/2019
ms.locfileid: "37994098"
---
# <a name="unable-to-delete-items-in-sharepoint-online-or-onedrive-for-business"></a>No se pueden eliminar elementos en SharePoint Online o OneDrive para la empresa

Es posible que usted o sus usuarios no puedan eliminar elementos en SharePoint Online o OneDrive para la empresa porque una directiva de retención, una etiqueta de retención o una retención de exhibición de documentos electrónicos se aplican a un sitio de SharePoint de OneDrive o a un elemento específico. Esto incluye no poder eliminar un documento, una versión de documento, una carpeta, una biblioteca de documentos, una lista, una aplicación, un sitio o una colección de sitios. A continuación se muestran algunos ejemplos de los mensajes de error que puede recibir si intenta eliminar un elemento que se conserva:

- "Este sitio no se puede eliminar porque está incluido en una directiva de retención o retención de exhibición de documentos electrónicos"
- "Este sitio tiene una directiva de cumplimiento establecida para la eliminación de bloques"
- "Una directiva de cumplimiento bloquea actualmente esta eliminación de sitio"
- "Esta colección de sitios no se puede eliminar porque contiene sitios incluidos en una retención de exhibición de documentos electrónicos o una directiva de retención"
- "Tiene que eliminar todos los elementos de esta carpeta antes de eliminar la carpeta"
- "No se pueden eliminar las versiones de este elemento porque está en retención o Directiva de retención"
- "El elemento no se puede eliminar mientras está en espera"
- "La etiqueta que se aplica a este elemento impide que se edite o elimine"
- "No se puede eliminar la lista cuando está en retención o en una directiva de retención"
- "No se puede eliminar la lista si está bloqueada o si se le ha aplicado una directiva de retención"

Para eliminar elementos en uno de estos escenarios, se debe quitar la Directiva de retención, la etiqueta de retención o la retención de exhibición de documentos electrónicos (o se debe excluir un sitio de una directiva de retención). Debe deshabilitar o excluir la retención respectiva que está causando este problema. Una vez quitada la retención o la Directiva de retención, el cambio puede tardar hasta 24 horas en surtir efecto. 

Para obtener información sobre las diferentes características de retención y retención que se pueden aplicar a los sitios de SharePoint y a las cuentas de OneDrive, vea uno de los siguientes temas.

- [Información general sobre las directivas de retención](https://docs.microsoft.com/microsoft-365/compliance/retention-policies)

- [Introducción a las etiquetas de retención](https://docs.microsoft.com/microsoft-365/compliance/labels)

- [Administrar suspensiones en la exhibición avanzada de documentos electrónicos](https://docs.microsoft.com/microsoft-365/compliance/managing-holds)

- [suspensiones de eDiscovery](https://docs.microsoft.com/microsoft-365/compliance/ediscovery-cases#step-4-place-content-locations-on-hold)

- [Directivas de cierre y eliminación de sitios heredados](https://support.office.com/article/Use-policies-for-site-closure-and-deletion-A8280D82-27FD-48C5-9ADF-8A5431208BA5)
