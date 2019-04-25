---
title: Cómo deshabilitar grupos externos
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: 4d911c319c3e8e327f9b3af3ba67816e646bc468
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "32399680"
---
# <a name="how-to-disable-external-groups"></a><span data-ttu-id="2fe0f-102">Cómo deshabilitar grupos externos</span><span class="sxs-lookup"><span data-stu-id="2fe0f-102">How to disable External Groups</span></span>

<span data-ttu-id="2fe0f-103">La mensajería externa de Yammer aplica reglas de transporte de Exchange (ETR), un conjunto de controles proactivos para impedir el uso compartido de la información de la empresa.</span><span class="sxs-lookup"><span data-stu-id="2fe0f-103">Yammer external messaging applies Exchange Transport Rules (ETRs), a set of proactive controls to prevent company information from being shared.</span></span> <span data-ttu-id="2fe0f-104">Para restringir a los usuarios la creación de grupos externos, debe configurar una regla de transporte de Exchange (ETR) y, a continuación, configurar Yammer para usar la regla de transporte de Exchange para bloquear la mensajería externa.</span><span class="sxs-lookup"><span data-stu-id="2fe0f-104">In order to restrict users from creating external groups, you need to configure an Exchange transport rule (ETR), and then configure Yammer to use the Exchange Transport rule to block external messaging.</span></span> 
  
<span data-ttu-id="2fe0f-105">Una vez que haya creado una regla en el centro de administración de Exchange Online, siga estos pasos para establecer ETR para que se aplique en Yammer:</span><span class="sxs-lookup"><span data-stu-id="2fe0f-105">Once you have created a rule in Exchange Online admin center, follow these steps to set ETR to apply in Yammer:</span></span>
  
- <span data-ttu-id="2fe0f-106">Inicie sesión en Yammer como administrador verificado y, en el **centro de administración de Yammer**, vaya a la **configuración de \> seguridad de seguridad y C-carpa.**</span><span class="sxs-lookup"><span data-stu-id="2fe0f-106">Log on to Yammer as a verified admin, and in the **Yammer admin center**, go to C **ontent and Security \> Security Settings.**</span></span>
    
- <span data-ttu-id="2fe0f-107">En **Mensajería externa**, seleccione **aplicar las reglas de transporte de Exchange Online Exchange (ETR) en Yammer.**</span><span class="sxs-lookup"><span data-stu-id="2fe0f-107">Under **External Messaging**, select **Enforce your Exchange Online Exchange Transport Rules (ETRs) in Yammer.**</span></span>
    
- <span data-ttu-id="2fe0f-108">Seleccione **Guardar**.</span><span class="sxs-lookup"><span data-stu-id="2fe0f-108">Choose **Save**.</span></span> 
    
<span data-ttu-id="2fe0f-109">Para obtener más información, consulte [controlar la mensajería externa en una red de Yammer con las reglas de transporte de Exchange](https://support.office.com/article/Control-external-messaging-in-a-Yammer-network-with-Exchange-Transport-Rules-f8fd6403-c8f3-4307-9230-65304d6000d9)</span><span class="sxs-lookup"><span data-stu-id="2fe0f-109">For more information, see [Control external messaging in a Yammer network with Exchange Transport rules](https://support.office.com/article/Control-external-messaging-in-a-Yammer-network-with-Exchange-Transport-Rules-f8fd6403-c8f3-4307-9230-65304d6000d9)</span></span>
  

