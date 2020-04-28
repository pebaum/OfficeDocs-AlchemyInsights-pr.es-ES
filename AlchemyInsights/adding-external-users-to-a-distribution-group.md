---
title: Adición de usuarios externos a un grupo de distribución
ms.author: chrisda
author: chrisda
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: caa0f310-0bb7-48e3-8ad2-cb358b53bbba
ms.openlocfilehash: 7dbc69bced9ca800d3f95081b77dda5e49662579
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/27/2020
ms.locfileid: "43910949"
---
# <a name="add-external-users-to-a-distribution-group"></a><span data-ttu-id="12d22-102">Agregar usuarios externos a un grupo de distribución</span><span class="sxs-lookup"><span data-stu-id="12d22-102">Add external users to a Distribution Group</span></span>

<span data-ttu-id="12d22-103">Agregar un contacto externo a un grupo de distribución (DG) es un proceso de dos pasos:</span><span class="sxs-lookup"><span data-stu-id="12d22-103">Adding an external contact to a Distribution Group (DG) is a two-step process:</span></span>
  
1. <span data-ttu-id="12d22-104">Cree un contacto de correo para el usuario externo:</span><span class="sxs-lookup"><span data-stu-id="12d22-104">Create a Mail Contact for the external user:</span></span>
    
    1. <span data-ttu-id="12d22-105">En el centro de administración, vaya a la página[contactos](https://admin.microsoft.com/adminportal/home#/Contact) de **usuarios** > .</span><span class="sxs-lookup"><span data-stu-id="12d22-105">In the admin center, go to the **Users** > [Contacts](https://admin.microsoft.com/adminportal/home#/Contact) page.</span></span> 
    
    2. <span data-ttu-id="12d22-106">Seleccione **Agregar un contacto**.</span><span class="sxs-lookup"><span data-stu-id="12d22-106">Select **Add a contact**.</span></span>
    
    3. <span data-ttu-id="12d22-107">Escriba la información de su contacto y seleccione **Agregar**.</span><span class="sxs-lookup"><span data-stu-id="12d22-107">Type the information for your contact and select **Add**.</span></span>
    
2. <span data-ttu-id="12d22-108">Agregue el contacto de correo a su DG:</span><span class="sxs-lookup"><span data-stu-id="12d22-108">Add the Mail Contact to your DG:</span></span>
    
    1. <span data-ttu-id="12d22-109">En el centro de administración, vaya a **la** > [Groups](https://admin.microsoft.com/adminportal/home#/groups) página grupos de grupos.</span><span class="sxs-lookup"><span data-stu-id="12d22-109">In the admin center, go to the **Groups** > [Groups](https://admin.microsoft.com/adminportal/home#/groups) page.</span></span> 
    
    2. <span data-ttu-id="12d22-110">Busque el DG al que desea agregar el usuario externo y selecciónelo para abrir el cuadro de diálogo de edición.</span><span class="sxs-lookup"><span data-stu-id="12d22-110">Find the DG you want to add the external user to, and select it to open the edit dialog.</span></span>
    
    3. <span data-ttu-id="12d22-111">En la pestaña **miembros** , seleccione **Ver todos y administrar miembros**.</span><span class="sxs-lookup"><span data-stu-id="12d22-111">On the **Members** tab, select **View all and manage members**.</span></span> 
    
    4. <span data-ttu-id="12d22-112">Seleccione **Agregar miembros**.</span><span class="sxs-lookup"><span data-stu-id="12d22-112">Select **Add members**.</span></span>
    
    5. <span data-ttu-id="12d22-113">Seleccione el contacto de correo que creó en el paso anterior y, a continuación, seleccione **Guardar**.</span><span class="sxs-lookup"><span data-stu-id="12d22-113">Select the Mail Contact you created on the previous step, and then select **Save**.</span></span>
    
<span data-ttu-id="12d22-114">Si después de seguir estos pasos los usuarios externos no pueden enviar correos electrónicos al DG o no reciben correos electrónicos, puede que el DG esté marcado para permitir solo los mensajes de correo electrónico de los usuarios internos.</span><span class="sxs-lookup"><span data-stu-id="12d22-114">If after following these steps your external users can't send emails to the DG or don't receive emails from it, it could be that the DG is marked to only allow emails from internal users.</span></span> <span data-ttu-id="12d22-115">Puede comprobar esta configuración y arreglarla siguiendo las instrucciones que se indican [aquí](https://docs.microsoft.com/exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/fix-error-code-5-7-133-in-exchange-online).</span><span class="sxs-lookup"><span data-stu-id="12d22-115">You can check this configuration and fix it following the directions [here](https://docs.microsoft.com/exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/fix-error-code-5-7-133-in-exchange-online).</span></span>
  
 <span data-ttu-id="12d22-116">**Nota:** Estas instrucciones no se aplican si el tipo de su grupo es "Microsoft 365 Group" en lugar de "grupo de distribución".</span><span class="sxs-lookup"><span data-stu-id="12d22-116">**Note:** These instructions don't apply if your group's type is "Microsoft 365 group" instead of "Distribution group."</span></span> <span data-ttu-id="12d22-117">Si ese es el caso, puede Agregar el usuario externo directamente al grupo desde Outlook.</span><span class="sxs-lookup"><span data-stu-id="12d22-117">If that is the case, you can add the external user directly to the group from Outlook.</span></span> <span data-ttu-id="12d22-118">Encontrará información detallada sobre los invitados de Microsoft 365 Groups y las instrucciones para agregar invitados externos en [este artículo](https://support.office.com/article/Guest-access-in-Office-365-Groups-bfc7a840-868f-4fd6-a390-f347bf51aff6.aspx).</span><span class="sxs-lookup"><span data-stu-id="12d22-118">Detailed information on Microsoft 365 Groups guests as well as instructions for adding external guests can be found in [this article](https://support.office.com/article/Guest-access-in-Office-365-Groups-bfc7a840-868f-4fd6-a390-f347bf51aff6.aspx).</span></span>
  