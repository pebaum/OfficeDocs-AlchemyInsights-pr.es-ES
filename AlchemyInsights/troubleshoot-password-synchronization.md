---
title: Solucionar problemas de sincronización de contraseña
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 1cba32c4-37ce-4ec1-9e58-8d3440b53d57
ms.openlocfilehash: c71fce8621057093d23891c26f7b0285fdc8b9ed
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29491126"
---
# <a name="troubleshoot-password-synchronization"></a><span data-ttu-id="85eb0-102">Solucionar problemas de sincronización de contraseña</span><span class="sxs-lookup"><span data-stu-id="85eb0-102">Troubleshoot password synchronization</span></span>

<span data-ttu-id="85eb0-103">Para solucionar los problemas que no las contraseñas se sincronizada con Azure Connect AD versión 1.1.614.0 o posterior:</span><span class="sxs-lookup"><span data-stu-id="85eb0-103">To troubleshoot issues where no passwords are synchronized with Azure AD Connect version 1.1.614.0 or later:</span></span>
  
1. <span data-ttu-id="85eb0-104">Abra una nueva sesión de Windows PowerShell en el servidor de Azure de AD de conectar con la opción **Ejecutar como administrador** .</span><span class="sxs-lookup"><span data-stu-id="85eb0-104">Open a new Windows PowerShell session on your Azure AD Connect server with the **Run as Administrator** option.</span></span> 
    
2. <span data-ttu-id="85eb0-105">Ejecute **Set-ExecutionPolicy RemoteSigned** o **Set-ExecutionPolicy sin restricciones**.</span><span class="sxs-lookup"><span data-stu-id="85eb0-105">Run **Set-ExecutionPolicy RemoteSigned** or **Set-ExecutionPolicy Unrestricted**.</span></span> 
    
3. <span data-ttu-id="85eb0-106">Iniciar al Asistente para la conexión de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="85eb0-106">Start the Azure AD Connect wizard.</span></span>
    
4. <span data-ttu-id="85eb0-107">Navegue hasta el \*\* tareas adicionales \*\* página, seleccione \*\* Troubleshoot \*\* y haga clic en **siguiente**.</span><span class="sxs-lookup"><span data-stu-id="85eb0-107">Navigate to the \*\* Additional Tasks \*\* page, select \*\* Troubleshoot \*\*, and click **Next**.</span></span> 
    
5. <span data-ttu-id="85eb0-108">En la página de solución de problemas, haga clic en el menú de **Inicio para iniciar la solución de problemas** en PowerShell.</span><span class="sxs-lookup"><span data-stu-id="85eb0-108">On the Troubleshooting page, click **Launch to start the troubleshooting** menu in PowerShell.</span></span> 
    
6. <span data-ttu-id="85eb0-109">En el menú principal, seleccione **Solución de problemas de sincronización de contraseña**.</span><span class="sxs-lookup"><span data-stu-id="85eb0-109">In the main menu, select **Troubleshoot Password Synchronization**.</span></span> 
    
7. <span data-ttu-id="85eb0-110">En el menú sub, seleccione **la sincronización de contraseña no funciona en absoluto**.</span><span class="sxs-lookup"><span data-stu-id="85eb0-110">In the sub menu, select **Password Synchronization does not work at all**.</span></span> 
    
 <span data-ttu-id="85eb0-111">**Comprender los resultados de la tarea de solución de problemas**</span><span class="sxs-lookup"><span data-stu-id="85eb0-111">**Understand the results of the troubleshooting task**</span></span>
  
<span data-ttu-id="85eb0-112">La tarea de solución de problemas realiza las siguientes comprobaciones:</span><span class="sxs-lookup"><span data-stu-id="85eb0-112">The troubleshooting task performs the following checks:</span></span>
  
- <span data-ttu-id="85eb0-113">Valida que la característica de sincronización de contraseña está habilitada para el inquilino de Azure AD.</span><span class="sxs-lookup"><span data-stu-id="85eb0-113">Validates that the password synchronization feature is enabled for your Azure AD tenant.</span></span>
    
- <span data-ttu-id="85eb0-114">Valida que el servidor de Azure Connect AD no está en modo de ensayo.</span><span class="sxs-lookup"><span data-stu-id="85eb0-114">Validates that the Azure AD Connect server is not in staging mode.</span></span>
    
- <span data-ttu-id="85eb0-115">Para cada conector de Active Directory de local existente al (que corresponde a un bosque de Active Directory existente):</span><span class="sxs-lookup"><span data-stu-id="85eb0-115">For each existing on-premises Active Directory connector (which corresponds to an existing Active Directory forest):</span></span>
    
- 
  - <span data-ttu-id="85eb0-116">Valida que está habilitada la característica de sincronización de contraseña.</span><span class="sxs-lookup"><span data-stu-id="85eb0-116">Validates that the password synchronization feature is enabled.</span></span>
    
  - <span data-ttu-id="85eb0-117">Busca los eventos de latido de sincronización de contraseña en los registros de eventos de aplicación de Windows.</span><span class="sxs-lookup"><span data-stu-id="85eb0-117">Searches for password synchronization heartbeat events in the Windows Application Event logs.</span></span>
    
  - <span data-ttu-id="85eb0-118">Para cada dominio de Active Directory en el conector de Active Directory local:</span><span class="sxs-lookup"><span data-stu-id="85eb0-118">For each Active Directory domain under the on-premises Active Directory connector:</span></span>
    
  - <span data-ttu-id="85eb0-119">Valida que el dominio está accesible desde el servidor de Azure Connect de AD.</span><span class="sxs-lookup"><span data-stu-id="85eb0-119">Validates that the domain is reachable from the Azure AD Connect server.</span></span>
    
  - <span data-ttu-id="85eb0-120">Valida que las cuentas de servicios de dominio de Active Directory (AD DS) utilizadas por el conector de Active Directory local tiene el nombre de usuario correcto, contraseña y permisos necesarios para la sincronización de contraseña.</span><span class="sxs-lookup"><span data-stu-id="85eb0-120">Validates that the Active Directory Domain Services (AD DS) accounts used by the on-premises Active Directory connector has the correct username, password, and permissions required for password synchronization.</span></span>
    
<span data-ttu-id="85eb0-121">Para obtener más ayuda de solución de problemas de sincronización de contraseñas, consulte [solucionar problemas sincronización de contraseñas con la sincronización de Azure Connect de AD](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).</span><span class="sxs-lookup"><span data-stu-id="85eb0-121">For more help troubleshooting password sync, see [Troubleshoot password synchronization with Azure AD Connect sync](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).</span></span>
  

