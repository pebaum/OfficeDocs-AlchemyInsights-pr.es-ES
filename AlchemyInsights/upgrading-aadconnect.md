---
title: 932 actualizar los
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "932"
- "1300025"
ms.assetid: 8f43f36c-9722-43a4-b0de-c5341c06dac5
ms.openlocfilehash: fcc5fddb5cfd15407d0533449035317d187931ed
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766510"
---
# <a name="upgrade-azure-ad-connect"></a><span data-ttu-id="1bc28-102">Actualizar Azure AD Connect</span><span class="sxs-lookup"><span data-stu-id="1bc28-102">Upgrade Azure AD Connect</span></span>

<span data-ttu-id="1bc28-103">De forma predeterminada, la actualización automática está habilitada para Azure AD Connect, lo que ayuda a asegurarse de que está ejecutando la versión más reciente.</span><span class="sxs-lookup"><span data-stu-id="1bc28-103">By default, automatic upgrade is enabled for Azure AD Connect, which helps to ensure you're running the latest version.</span></span> <span data-ttu-id="1bc28-104">Para comprobar la configuración de la actualización automática, use el cmdlet **Get-ADSyncAutoUpgrade** en Azure ad PowerShell.</span><span class="sxs-lookup"><span data-stu-id="1bc28-104">To verify the automatic upgrade settings, use the **Get-ADSyncAutoUpgrade** cmdlet in Azure AD PowerShell.</span></span> <span data-ttu-id="1bc28-105">El cmdlet devolverá uno de los siguientes valores:</span><span class="sxs-lookup"><span data-stu-id="1bc28-105">The cmdlet will return one of following values:</span></span>

- <span data-ttu-id="1bc28-106">**Habilitada**: la actualización automática está habilitada.</span><span class="sxs-lookup"><span data-stu-id="1bc28-106">**Enabled**: Automatic upgrade is enabled.</span></span>

- <span data-ttu-id="1bc28-107">**Deshabilitado**: la actualización automática está deshabilitada.</span><span class="sxs-lookup"><span data-stu-id="1bc28-107">**Disabled**: Automatic upgrade is disabled.</span></span>

- <span data-ttu-id="1bc28-108">**Suspendido**: el sistema ya no cumple los requisitos para recibir actualizaciones automáticas.</span><span class="sxs-lookup"><span data-stu-id="1bc28-108">**Suspended**: The system is no longer eligible to receive automatic upgrades.</span></span> <span data-ttu-id="1bc28-109">No puede configurar este valor; se establece en el sistema.</span><span class="sxs-lookup"><span data-stu-id="1bc28-109">You can't configure this value; it's set by the system.</span></span>

<span data-ttu-id="1bc28-110">Para obtener más información, consulte [actualización automática](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).</span><span class="sxs-lookup"><span data-stu-id="1bc28-110">For more information, see [Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).</span></span>

<span data-ttu-id="1bc28-111">Para descargar la versión más reciente de Azure AD Connect, vaya [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594)a.</span><span class="sxs-lookup"><span data-stu-id="1bc28-111">To download the latest version of Azure AD Connect, go to [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594).</span></span>
