---
title: No se está enviando correo electrónico de flujo de trabajo
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1586"
ms.openlocfilehash: 391d3a2dcc2676a405065115f375c802d2492119
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766150"
---
# <a name="workflow-email-is-not-being-sent-for-a-sharepoint-list-or-library"></a>El correo electrónico de flujo de trabajo no se envía a una lista o biblioteca de SharePoint

1. El correo electrónico de los flujos de trabajo no se envía a todos los usuarios o solo a usuarios específicos, o Ve el error **no se puede enviar el mensaje de correo electrónico. Asegúrese de que el correo electrónico tiene un destinatario válido**.

    Compruebe si el usuario existe en el grupo de permisos **todos los usuarios** (lista de información del usuario) para esa colección de sitios.  Dirección URL directa de ejemplo<tenant>: https://<sitename>. SharePoint.com/sites//_layouts/15/People.aspx? MembershipGroupId = 0

    - Si el usuario no existe, asegúrese de que el usuario haya iniciado sesión en la página. 
    - Si es un usuario externo, asegúrese de que su invitación se ha aceptado.
    - Si el usuario existe en el grupo permisos, asegúrese de que la dirección de correo electrónico es correcta.
    - Si no se establece aquí la dirección de correo electrónico de los usuarios, cree una alerta de ejemplo para ese usuario que fuerce la sincronización de esa cuenta de usuario de los perfiles de usuario de SharePoint con esta colección de sitios.
 
2. El correo electrónico de los flujos de trabajo se envía a los administradores de la colección de sitios, pero no a otros usuarios, y ve el error **http prohibido a <span>https:</span>//URL/_vti_bin/Client.XVC.SP.Utilities.Utility.sendEmail**.
 

    Vea [acceso denegado cuando se envía un correo electrónico a un grupo de SharePoint](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).

    Compruebe también que la característica de colección de sitios del **modo de bloqueo de permisos de usuario de acceso limitado** no está activa.


## <a name="related-topics"></a>Temas relacionados
¿Desea probar Microsoft Flow en SharePoint Online?
- [Crear flujo](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [Flujo y SharePoint](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


