---
title: Adición de usuarios externos a un grupo de distribución
ms.author: chrisda
author: chrisda
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: caa0f310-0bb7-48e3-8ad2-cb358b53bbba
ms.openlocfilehash: 7dbc69bced9ca800d3f95081b77dda5e49662579
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/27/2020
ms.locfileid: "43910949"
---
# <a name="add-external-users-to-a-distribution-group"></a>Agregar usuarios externos a un grupo de distribución

Agregar un contacto externo a un grupo de distribución (DG) es un proceso de dos pasos:
  
1. Cree un contacto de correo para el usuario externo:
    
    1. En el centro de administración, vaya a la página[contactos](https://admin.microsoft.com/adminportal/home#/Contact) de **usuarios** > . 
    
    2. Seleccione **Agregar un contacto**.
    
    3. Escriba la información de su contacto y seleccione **Agregar**.
    
2. Agregue el contacto de correo a su DG:
    
    1. En el centro de administración, vaya a **la** > [Groups](https://admin.microsoft.com/adminportal/home#/groups) página grupos de grupos. 
    
    2. Busque el DG al que desea agregar el usuario externo y selecciónelo para abrir el cuadro de diálogo de edición.
    
    3. En la pestaña **miembros** , seleccione **Ver todos y administrar miembros**. 
    
    4. Seleccione **Agregar miembros**.
    
    5. Seleccione el contacto de correo que creó en el paso anterior y, a continuación, seleccione **Guardar**.
    
Si después de seguir estos pasos los usuarios externos no pueden enviar correos electrónicos al DG o no reciben correos electrónicos, puede que el DG esté marcado para permitir solo los mensajes de correo electrónico de los usuarios internos. Puede comprobar esta configuración y arreglarla siguiendo las instrucciones que se indican [aquí](https://docs.microsoft.com/exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/fix-error-code-5-7-133-in-exchange-online).
  
 **Nota:** Estas instrucciones no se aplican si el tipo de su grupo es "Microsoft 365 Group" en lugar de "grupo de distribución". Si ese es el caso, puede Agregar el usuario externo directamente al grupo desde Outlook. Encontrará información detallada sobre los invitados de Microsoft 365 Groups y las instrucciones para agregar invitados externos en [este artículo](https://support.office.com/article/Guest-access-in-Office-365-Groups-bfc7a840-868f-4fd6-a390-f347bf51aff6.aspx).
  