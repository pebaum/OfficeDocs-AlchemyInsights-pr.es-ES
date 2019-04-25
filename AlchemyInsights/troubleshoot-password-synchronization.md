---
title: Solucionar problemas de sincronización de contraseñas
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 1cba32c4-37ce-4ec1-9e58-8d3440b53d57
ms.openlocfilehash: 1320c0fe839337188162824439be6f15f86b6c90
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "32390463"
---
# <a name="troubleshoot-password-synchronization"></a><span data-ttu-id="53356-102">Solucionar problemas de sincronización de contraseñas</span><span class="sxs-lookup"><span data-stu-id="53356-102">Troubleshoot password synchronization</span></span>

<span data-ttu-id="53356-103">Para solucionar problemas en los que no se ha sincronizado ninguna contraseña con Azure AD Connect versión 1.1.614.0 o posterior:</span><span class="sxs-lookup"><span data-stu-id="53356-103">To troubleshoot issues where no passwords are synchronized with Azure AD Connect version 1.1.614.0 or later:</span></span>
  
1. <span data-ttu-id="53356-104">Abra una nueva sesión de Windows PowerShell en su servidor de Azure AD Connect con la opción **Ejecutar como administrador** .</span><span class="sxs-lookup"><span data-stu-id="53356-104">Open a new Windows PowerShell session on your Azure AD Connect server with the **Run as Administrator** option.</span></span> 
    
2. <span data-ttu-id="53356-105">Ejecute **Set-ExecutionPolicy RemoteSigned** o **Set-ExecutionPolicy**Unrestricted.</span><span class="sxs-lookup"><span data-stu-id="53356-105">Run **Set-ExecutionPolicy RemoteSigned** or **Set-ExecutionPolicy Unrestricted**.</span></span> 
    
3. <span data-ttu-id="53356-106">Inicie el Asistente de Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="53356-106">Start the Azure AD Connect wizard.</span></span>
    
4. <span data-ttu-id="53356-107">Vaya a la página \* \* tareas adicionales \* \*, seleccione \* \* solución de problemas \* \* y haga clic en **siguiente**.</span><span class="sxs-lookup"><span data-stu-id="53356-107">Navigate to the \*\* Additional Tasks \*\* page, select \*\* Troubleshoot \*\*, and click **Next**.</span></span> 
    
5. <span data-ttu-id="53356-108">En la página solución de problemas, haga clic en **iniciar para iniciar el** menú de solución de problemas en PowerShell.</span><span class="sxs-lookup"><span data-stu-id="53356-108">On the Troubleshooting page, click **Launch to start the troubleshooting** menu in PowerShell.</span></span> 
    
6. <span data-ttu-id="53356-109">En el menú principal, seleccione **solucionar problemas de sincronización de contraseña**.</span><span class="sxs-lookup"><span data-stu-id="53356-109">In the main menu, select **Troubleshoot Password Synchronization**.</span></span> 
    
7. <span data-ttu-id="53356-110">En el menú secundario, seleccione la **sincronización de contraseña no funciona**.</span><span class="sxs-lookup"><span data-stu-id="53356-110">In the sub menu, select **Password Synchronization does not work at all**.</span></span> 
    
 <span data-ttu-id="53356-111">**Comprender los resultados de la tarea de solución de problemas**</span><span class="sxs-lookup"><span data-stu-id="53356-111">**Understand the results of the troubleshooting task**</span></span>
  
<span data-ttu-id="53356-112">La tarea de solución de problemas realiza las comprobaciones siguientes:</span><span class="sxs-lookup"><span data-stu-id="53356-112">The troubleshooting task performs the following checks:</span></span>
  
- <span data-ttu-id="53356-113">Valida que la característica de sincronización de contraseña esté habilitada para el inquilino de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="53356-113">Validates that the password synchronization feature is enabled for your Azure AD tenant.</span></span>
    
- <span data-ttu-id="53356-114">Valida que el servidor de Azure AD Connect no está en modo de ensayo.</span><span class="sxs-lookup"><span data-stu-id="53356-114">Validates that the Azure AD Connect server is not in staging mode.</span></span>
    
- <span data-ttu-id="53356-115">Para cada conector de Active Directory local existente (que corresponda a un bosque de Active Directory existente):</span><span class="sxs-lookup"><span data-stu-id="53356-115">For each existing on-premises Active Directory connector (which corresponds to an existing Active Directory forest):</span></span>
    
- 
  - <span data-ttu-id="53356-116">Valida que la característica de sincronización de contraseña esté habilitada.</span><span class="sxs-lookup"><span data-stu-id="53356-116">Validates that the password synchronization feature is enabled.</span></span>
    
  - <span data-ttu-id="53356-117">Busca eventos Heartbeat de sincronización de contraseña en los registros de eventos de aplicación de Windows.</span><span class="sxs-lookup"><span data-stu-id="53356-117">Searches for password synchronization heartbeat events in the Windows Application Event logs.</span></span>
    
  - <span data-ttu-id="53356-118">Para cada dominio de Active Directory en el conector de Active Directory local:</span><span class="sxs-lookup"><span data-stu-id="53356-118">For each Active Directory domain under the on-premises Active Directory connector:</span></span>
    
  - <span data-ttu-id="53356-119">Valida que el dominio es accesible desde el servidor de Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="53356-119">Validates that the domain is reachable from the Azure AD Connect server.</span></span>
    
  - <span data-ttu-id="53356-120">Valida que las cuentas de servicios de dominio de Active Directory (AD DS) que usa el conector de Active Directory local tengan el nombre de usuario, la contraseña y los permisos correctos necesarios para la sincronización de contraseña.</span><span class="sxs-lookup"><span data-stu-id="53356-120">Validates that the Active Directory Domain Services (AD DS) accounts used by the on-premises Active Directory connector has the correct username, password, and permissions required for password synchronization.</span></span>
    
<span data-ttu-id="53356-121">Para obtener más información sobre cómo solucionar problemas de la sincronización de contraseñas, consulte [solucionar problemas de sincronización de contraseña con sincronización de Azure ad Connect](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).</span><span class="sxs-lookup"><span data-stu-id="53356-121">For more help troubleshooting password sync, see [Troubleshoot password synchronization with Azure AD Connect sync](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).</span></span>
  

