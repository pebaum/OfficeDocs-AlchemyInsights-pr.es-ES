---
title: Supervisión de acceso condicional
ms.author: pebaum
author: pebaum
ms.date: 8/1/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: dcb86c54-769e-4832-9f88-bc45f1e5f36c
ms.openlocfilehash: 756c5e98ed3e9cedd0152b5747ea6bf1ed31778e
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/12/2019
ms.locfileid: "29902380"
---
# <a name="monitoring-conditional-access"></a><span data-ttu-id="6b536-102">Supervisión de acceso condicional</span><span class="sxs-lookup"><span data-stu-id="6b536-102">Monitoring Conditional Access</span></span>

<span data-ttu-id="6b536-p101">Usuarios con acceso condicional recibirá un correo electrónico de notificación si no cumplen los requisitos de acceso de la organización. Para resolver, se recomienda una o varias de las siguientes soluciones:</span><span class="sxs-lookup"><span data-stu-id="6b536-p101">Users targeted with conditional access will receive a notification email if they do not meet your organization's access requirements. To resolve, we recommend one or more of the following solutions:</span></span>
  
- <span data-ttu-id="6b536-p102">Si se supone que el dispositivo se inscriben, avisar al usuario ir a la aplicación de Portal de empresa y compruebe que aparece en el Portal de la compañía. Si no es así, el usuario debe inscribirse el dispositivo.</span><span class="sxs-lookup"><span data-stu-id="6b536-p102">If the device is presumed to be enrolled, advise the user to go to the Company Portal app and verify that it appears in the Company Portal. If it doesn't, the user should enroll the device.</span></span>
    
- <span data-ttu-id="6b536-p103">En el portal de Azure, vaya a **Intune \> cumplimiento de dispositivo**. Haga clic en **cumplimiento de dispositivo**de **Monitor** . Ver el informe de cumplimiento de normas de dispositivos para comprobar que el dispositivo del usuario está marcado como compatible.</span><span class="sxs-lookup"><span data-stu-id="6b536-p103">In the Azure portal go to **Intune \> Device compliance**. Under **Monitor** click **Device compliance**. View your device compliance report to verify that the user's device is marked as compliant.</span></span> 
    
- <span data-ttu-id="6b536-p104">En el portal de Azure, vaya a **Intune \> cumplimiento de dispositivo**. En **Administrar**, haga clic en **directivas**. En la lista de directivas de cumplimiento, compruebe que tiene asignado un perfil de dispositivo del usuario. Si no se ha asignado ningún perfil, Intune no podrá comprobar el estado de cumplimiento del dispositivo.</span><span class="sxs-lookup"><span data-stu-id="6b536-p104">In the Azure portal go to **Intune \> Device compliance**. Under **Manage**, click **Policies**. In the list of compliance policies, verify that a profile is assigned to your user's device. If no profile is assigned, then Intune will not be able to confirm the device's compliance status.</span></span> 
    
- <span data-ttu-id="6b536-114">Editar la asignación de acceso condicional del usuario.</span><span class="sxs-lookup"><span data-stu-id="6b536-114">Edit the user's conditional access assignment.</span></span>
    
1. <span data-ttu-id="6b536-115">En el portal de Azure, vaya a **Intune \> acceso condicional \> directivas**</span><span class="sxs-lookup"><span data-stu-id="6b536-115">In the Azure portal go to **Intune \> Conditional access \> Policies**</span></span>
    
2. <span data-ttu-id="6b536-116">Seleccione una directiva de la lista</span><span class="sxs-lookup"><span data-stu-id="6b536-116">Select a policy from the list</span></span>
    
3. <span data-ttu-id="6b536-117">Haga clic en **usuarios y grupos**</span><span class="sxs-lookup"><span data-stu-id="6b536-117">Click **Users and groups**</span></span>
    
4. <span data-ttu-id="6b536-p105">Para dirigir una directiva determinada en una persona, agregarlos a la lista de **inclusión** . Para asegurarse de que una persona se omite en la directiva, agregarlos a la lista de **exclusión** .</span><span class="sxs-lookup"><span data-stu-id="6b536-p105">To target a certain policy at someone, add them to the **Include** list. To ensure that a person is omitted from the policy, add them to the **Exclude** list.</span></span> 
    
<span data-ttu-id="6b536-120">Más información: [cómo controlar el acceso condicional dispositivos](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)</span><span class="sxs-lookup"><span data-stu-id="6b536-120">Read more: [How to Monitor Conditional Access devices](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)</span></span>
  

