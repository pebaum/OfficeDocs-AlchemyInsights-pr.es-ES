---
title: Implementación de Teams como independiente o con instalaciones de Office nuevas o existentes
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000660"
- "2509"
ms.openlocfilehash: 4b843407f05db207f3b676c03c7088d3d0ba062e
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43704650"
---
# <a name="deploying-teams-as-standalone-or-with-new-or-existing-office-installations"></a>Implementación de Teams como independiente o con instalaciones de Office nuevas o existentes

Microsoft Teams ahora se incluye como parte de las ***nuevas instalaciones*** de las aplicaciones de Microsoft 365 para empresas, Microsoft 365 apps for Business y Office para Mac. Para obtener más información, vea [¿Cuándo Microsoft Teams se incluirá en las nuevas instalaciones de Office?](https://docs.microsoft.com/deployoffice/teams-install#when-will-microsoft-teams-start-being-included-with-new-installations-of-office-365-proplus)

Además, a partir de la versión 1906 en el canal mensual, los equipos se ***agregarán a las instalaciones existentes*** de Microsoft 365 apps for Enterprise (y Microsoft 365 apps for Business) en dispositivos que ejecuten Windows cuando actualice la instalación existente a la versión más reciente. Para obtener más información, vea [¿Qué ocurre con las instalaciones existentes de Office?](https://docs.microsoft.com/deployoffice/teams-install#what-about-existing-installations-of-office-365-proplus)

> [!NOTE]
> Si no desea esperar a esta programación de lanzamiento, puede implementar Teams como independiente para los usuarios siguiendo [estas instrucciones](https://docs.microsoft.com/MicrosoftTeams/msi-deployment) o puede hacer que los usuarios instalen Teams para sí mismos [https://teams.microsoft.com/downloads](https://teams.microsoft.com/downloads).

Si su organización no está preparada para implementar Microsoft Teams, tenemos los pasos que puede seguir para ***excluir equipos*** de instalaciones [nuevas](https://docs.microsoft.com/deployoffice/teams-install#how-to-exclude-microsoft-teams-from-new-installations-of-office-365-proplus) o [existentes](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-control-the-installation-of-microsoft-teams) de Office. Si desea que Microsoft Teams esté instalado, pero no quiere que los equipos se inicien automáticamente para el usuario una vez instalado, consulte [impedir que Microsoft Teams se inicie automáticamente después](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-prevent-microsoft-teams-from-starting-automatically-after-installation)de la instalación.

Para ***desinstalar Teams*** desde un dispositivo que ejecuta Windows, vea [desinstalar Microsoft Teams](https://support.office.com/article/3b159754-3c26-4952-abe7-57d27f5f4c81). Para limpiar Microsoft Teams de varios equipos o usuarios de destino, vea limpieza de la [implementación de Microsoft Teams](https://docs.microsoft.com/microsoftteams/scripts/powershell-script-teams-deployment-clean-up).

Si está usando equipos compartidos, servicios de escritorio remoto (RDS) o infraestructura de escritorio virtual (VDI), consulte [Shared Computer and VDI Environments with Microsoft Teams](https://docs.microsoft.com/deployoffice/teams-install#shared-computer-and-vdi-environments-with-microsoft-teams).

Si está usando Office para Mac, consulte [instalaciones de Microsoft Teams en un equipo Mac](https://docs.microsoft.com/deployoffice/teams-install#microsoft-teams-installations-on-a-mac).

> [!NOTE]
> Una vez instalado Microsoft Teams, se [actualiza automáticamente](https://docs.microsoft.com/deployoffice/teams-install#feature-and-quality-updates-for-microsoft-teams) cada dos semanas aproximadamente, con nuevas características y actualizaciones de calidad. 