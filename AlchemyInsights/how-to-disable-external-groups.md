---
title: Cómo deshabilitar a grupos externos
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: 4807dbfbabcea1f13785bd39bb48e4bbaa8d0f0f
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29491506"
---
# <a name="how-to-disable-external-groups"></a><span data-ttu-id="ee901-102">Cómo deshabilitar a grupos externos</span><span class="sxs-lookup"><span data-stu-id="ee901-102">How to disable External Groups</span></span>

<span data-ttu-id="ee901-p101">Yammer mensajería externa aplica reglas de transporte de Exchange (ETRs), un conjunto de controles proactivos para evitar que la información de la empresa desde la que se está compartiendo. Con el fin de evitar que los usuarios crear grupos externos, debe configurar una regla de transporte de Exchange (ETR) y, a continuación, configurar Yammer para usar la regla de transporte de Exchange para bloquear la mensajería externa.</span><span class="sxs-lookup"><span data-stu-id="ee901-p101">Yammer external messaging applies Exchange Transport Rules (ETRs), a set of proactive controls to prevent company information from being shared. In order to restrict users from creating external groups, you need to configure an Exchange transport rule (ETR), and then configure Yammer to use the Exchange Transport rule to block external messaging.</span></span> 
  
<span data-ttu-id="ee901-105">Una vez haya creado una regla en el centro de administración de Exchange Online, siga estos pasos para establecer ETR que se debe aplicar en Yammer:</span><span class="sxs-lookup"><span data-stu-id="ee901-105">Once you have created a rule in Exchange Online admin center, follow these steps to set ETR to apply in Yammer:</span></span>
  
- <span data-ttu-id="ee901-106">Inicie sesión en Yammer como un administrador de comprobada y en el **Centro de administración de Yammer**, vaya a C **ontenido y seguridad \> configuración de seguridad.**</span><span class="sxs-lookup"><span data-stu-id="ee901-106">Log on to Yammer as a verified admin, and in the **Yammer admin center**, go to C **ontent and Security \> Security Settings.**</span></span>
    
- <span data-ttu-id="ee901-107">En **Mensajería externa**, seleccione **aplicar las reglas de transporte de Exchange Online de Exchange (ETRs) en Yammer.**</span><span class="sxs-lookup"><span data-stu-id="ee901-107">Under **External Messaging**, select **Enforce your Exchange Online Exchange Transport Rules (ETRs) in Yammer.**</span></span>
    
- <span data-ttu-id="ee901-108">Elija **Guardar**.</span><span class="sxs-lookup"><span data-stu-id="ee901-108">Choose **Save**.</span></span> 
    
<span data-ttu-id="ee901-109">Para obtener más información, consulte [Control externo de mensajería en una red de Yammer con las reglas de transporte de Exchange](https://support.office.com/en-us/article/Control-external-messaging-in-a-Yammer-network-with-Exchange-Transport-Rules-f8fd6403-c8f3-4307-9230-65304d6000d9)</span><span class="sxs-lookup"><span data-stu-id="ee901-109">For more information, see [Control external messaging in a Yammer network with Exchange Transport rules](https://support.office.com/en-us/article/Control-external-messaging-in-a-Yammer-network-with-Exchange-Transport-Rules-f8fd6403-c8f3-4307-9230-65304d6000d9)</span></span>
  

