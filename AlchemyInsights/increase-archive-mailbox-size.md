---
title: 305 aumentar el tamaño del buzón de archivo
ms.author: chrisda
author: chrisda
manager: dansimp
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 305
ms.assetid: ''
ms.openlocfilehash: a8c16d97040e9396d6cf9bd4a5da671a7da88e13
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/25/2019
ms.locfileid: "36661817"
---
# <a name="increase-the-archive-mailbox-size"></a>Aumentar el tamaño del buzón de archivo

Office 365 [limita](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#mailbox-storage-limits) el tamaño de los buzones de archivo en función de la licencia asignada a la cuenta de usuario. Cuando el buzón de archivo alcanza el 90% de su tamaño permitido, el usuario recibe una notificación por correo electrónico. Cuando un buzón de archivo alcanza su límite de tamaño, el usuario no puede mover más elementos al buzón de archivo. Office 365 no aumentará el tamaño de un buzón de archivo una vez que se alcance el límite de tamaño. En su lugar, los usuarios pueden realizar las siguientes acciones para liberar espacio en el buzón de archivo:

- Exporte los elementos a un archivo. pst mediante Outlook.

- Eliminar elementos del buzón de archivo.

Office 365 proporciona un **archivado ilimitado** para las licencias de Office 365 Enterprise E3 y E5. Un administrador debe habilitar esta característica antes de que el buzón de archivo alcance su tamaño máximo. Cuando está habilitado el archivado ilimitado, puede tardar hasta 30 días en agregarse espacio libre al buzón de archivo. Por lo tanto, se recomienda que los administradores comprueben el espacio libre en el buzón de archivo, lo que permite al usuario continuar usando el buzón de archivo mientras se expande. Para obtener más información, vea [información general sobre el archivado ilimitado en office 365](https://docs.microsoft.com/office365/securitycompliance/unlimited-archiving) y [Habilitar el archivado ilimitado en Office 365](https://docs.microsoft.com/office365/securitycompliance/enable-unlimited-archiving).

Para obtener más información acerca de cómo obtener acceso al buzón de archivo desde Outlook, consulte [requisitos de Outlook para obtener acceso a elementos en un archivo de expansión automática](https://docs.microsoft.com/office365/securitycompliance/unlimited-archiving#outlook-requirements-for-accessing-items-in-an-auto-expanded-archive). Para configurar una directiva de retención que mueva automáticamente elementos al buzón de archivo, consulte [configurar una directiva de archivo y eliminación para los buzones de la organización de Office 365](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes).

**Nota**: los archivos de expansión automática no se admiten para buzones de correo principales en Exchange 2010.
