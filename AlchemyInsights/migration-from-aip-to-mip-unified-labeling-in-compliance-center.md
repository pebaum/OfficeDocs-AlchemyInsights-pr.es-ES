---
title: Migración de AIP a MIP o etiquetado unificado en el centro de seguridad y cumplimiento
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002278"
- "5114"
ms.openlocfilehash: 7ce9c387fc94f59674a922c5fe071fc0fb030344
ms.sourcegitcommit: e6d73d240669342fde9d4d25b0ee2838b7e43965
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 05/14/2020
ms.locfileid: "44236568"
---
# <a name="migration-from-aip-to-mipunified-labeling-in-the-compliance-center"></a>Migración de AIP a MIP o etiquetado unificado en el centro de seguridad y cumplimiento

Para migrar de etiquetas de AIP a etiquetado unificado en el centro de seguridad y cumplimiento, haga lo siguiente:

**Activar la protección desde Azure Portal**

1. Si aún no lo ha hecho, abra una nueva ventana del explorador e [inicie sesión en Azure Portal](https://docs.microsoft.com/azure/information-protection/deploy-use/configure-policy#signing-in-to-the-azure-portal). Desplácese hasta la hoja de **Azure Information Protection**. Por ejemplo, en el menú de central, haga clic en **Todos los servicios** y comience a escribir **Información** en el cuadro Filtro. Seleccione **Azure Information Protection**. Si no ha accedido a la hoja de Azure Information Protection antes, consulte los [pasos adicionales](https://docs.microsoft.com/azure/information-protection/deploy-use/configure-policy#to-access-the-azure-information-protection-blade-for-the-first-time) únicos para agregar esta hoja al portal. Para abrir la hoja de Azure Information Protection, debe tener un [plan de Azure Information Protection Premium](https://www.microsoft.com/cloud-platform/azure-information-protection-pricing) o un plan de Office 365 que incluya derechos de administración. Si tiene una de estas suscripciones pero ve un mensaje que indica que no se puede encontrar una suscripción válida, [póngase en contacto con el soporte técnico de Microsoft](https://docs.microsoft.com/azure/information-protection/get-started/information-support#to-contact-microsoft-support) o use los canales de soporte técnico estándar.

2. Localice las opciones del menú **Administrar** y seleccione **Activación de protección**. Haga clic en **Activar** y confirme la acción. Cuando haya finalizado la activación, la barra de información mostrará **La activación se completó correctamente**.

**Migrar las etiquetas de Azure Information Protection al Centro de seguridad y cumplimiento de Office 365**

1. Asegúrese de que ha iniciado sesión como un usuario con permisos de administrador global.

2. Desplácese hasta la hoja de **Azure Information Protection**.

3. En la opción del menú **Administrar**, seleccione **Etiquetado unificado**.

4. En la hoja **Azure Information Protection: etiquetado unificado**, haga clic en **Activar** y siga las instrucciones que se muestran en línea.

**Nota**: compruebe que tiene los permisos adecuados antes de activar la Migración del Centro de seguridad y cumplimiento. Vea estos artículos para obtener más información:

1. [¿Necesita ser un administrador global para configurar Azure Information Protection o se puede delegar en otros administradores?](https://docs.microsoft.com/azure/information-protection/faqs#do-you-need-to-be-a-global-admin-to-configure-azure-information-protection-or-can-i-delegate-to-other-administrators)

2. [Información importante sobre los roles administrativos después de migrar al Centro de seguridad y cumplimiento.](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels#important-information-about-administrative-roles)

Para obtener más información sobre la migración de AIP al etiquetado unificado en el centro de seguridad y cumplimiento, vea [Migrar etiquetas](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels).
