---
title: Habilitación de Office 365 ATP para SharePoint, OneDrive y Microsoft Teams
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/01/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Admin_O365
ms.custom: 3100021
ms.openlocfilehash: ae2f574663ae3233a056589c2d5a578171f3b2f4
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "32403050"
---
# <a name="enable-office-365-advanced-threat-protection-for-sharepoint-online-onedrive-and-microsoft-teams"></a>Habilitación de la protección contra amenazas avanzada de Office 365 para SharePoint Online, OneDrive y Microsoft Teams

1. Vaya a https://protection.office.com e inicie sesión.
2. Seleccione **** > **** directiva > de administración de amenazas:**datos adjuntos seguros**.
3. Seleccione **Activar ATP para SharePoint, OneDrive y Microsoft Teams**y, a continuación, haga clic en **Guardar**.
4. Recomenda Como administrador global o administrador de SharePoint Online, ejecute el cmdlet [set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) con el parámetro **DisallowInfectedFileDownload** establecido en *true*.
5. Recomenda [Configurar alertas](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) para los archivos detectados.

> [!NOTE]
> ATP detendrá la exploración de todos los archivos en SharePoint Online, OneDrive o Microsoft Teams. Los archivos se examinan de forma asincrónica, a través de un proceso que usa eventos de actividad de uso compartido e invitados, junto con heurística inteligente y señales de amenazas para identificar archivos malintencionados. Consulte [https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).