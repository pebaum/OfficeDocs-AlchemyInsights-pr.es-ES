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
# <a name="enable-office-365-advanced-threat-protection-for-sharepoint-online-onedrive-and-microsoft-teams"></a><span data-ttu-id="f0069-102">Habilitación de la protección contra amenazas avanzada de Office 365 para SharePoint Online, OneDrive y Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="f0069-102">Enable Office 365 Advanced Threat Protection for SharePoint Online, OneDrive, and Microsoft Teams</span></span>

1. <span data-ttu-id="f0069-103">Vaya a https://protection.office.com e inicie sesión.</span><span class="sxs-lookup"><span data-stu-id="f0069-103">Go to https://protection.office.com and sign in.</span></span>
2. <span data-ttu-id="f0069-104">Seleccione \*\*\*\* > \*\*\*\* directiva > de administración de amenazas:**datos adjuntos seguros**.</span><span class="sxs-lookup"><span data-stu-id="f0069-104">Choose **Threat management** > **Policy** > **Safe Attachments**.</span></span>
3. <span data-ttu-id="f0069-105">Seleccione **Activar ATP para SharePoint, OneDrive y Microsoft Teams**y, a continuación, haga clic en **Guardar**.</span><span class="sxs-lookup"><span data-stu-id="f0069-105">Select **Turn on ATP for SharePoint, OneDrive, and Microsoft Teams**, and then click **Save**.</span></span>
4. <span data-ttu-id="f0069-106">Recomenda Como administrador global o administrador de SharePoint Online, ejecute el cmdlet [set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) con el parámetro **DisallowInfectedFileDownload** establecido en *true*.</span><span class="sxs-lookup"><span data-stu-id="f0069-106">(Recommended) As a global administrator or a SharePoint Online administrator, run the [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) cmdlet with the **DisallowInfectedFileDownload** parameter set to *true*.</span></span>
5. <span data-ttu-id="f0069-107">Recomenda [Configurar alertas](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) para los archivos detectados.</span><span class="sxs-lookup"><span data-stu-id="f0069-107">(Recommended) [Set up alerts](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) for detected files.</span></span>

> [!NOTE]
> <span data-ttu-id="f0069-108">ATP detendrá la exploración de todos los archivos en SharePoint Online, OneDrive o Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="f0069-108">ATP will nto scan every single file in SharePoint Online, OneDrive, or Microsoft Teams.</span></span> <span data-ttu-id="f0069-109">Los archivos se examinan de forma asincrónica, a través de un proceso que usa eventos de actividad de uso compartido e invitados, junto con heurística inteligente y señales de amenazas para identificar archivos malintencionados.</span><span class="sxs-lookup"><span data-stu-id="f0069-109">Files are scanned asynchronously, through a process that uses sharing and guest activity events, along with smart heuristics and threat signals to identify malicious files.</span></span> <span data-ttu-id="f0069-110">Consulte [https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span><span class="sxs-lookup"><span data-stu-id="f0069-110">See [https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span></span>