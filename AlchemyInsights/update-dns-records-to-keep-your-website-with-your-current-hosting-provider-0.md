---
title: Actualizar registros DNS para conservar su sitio web con su proveedor de hospedaje actual
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 48251355-7383-4fdc-a1e1-9dc2c85a8d29
ms.openlocfilehash: a79302259e294ea5bf3b1d29393a412edb27a388
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/15/2019
ms.locfileid: "28313757"
---
# <a name="update-dns-records-to-keep-your-website-with-your-current-hosting-provider"></a><span data-ttu-id="b2d1f-102">Actualizar registros DNS para conservar su sitio web con su proveedor de hospedaje actual</span><span class="sxs-lookup"><span data-stu-id="b2d1f-102">Update DNS records to keep your website with your current hosting provider</span></span>

1. <span data-ttu-id="b2d1f-103">En la página [Dominios](https://portal.office.com/adminportal/home#/Domains), en la lista de dominios, seleccione el que use para su sitio web y, después, **Configuración de DNS** en el panel de administración.</span><span class="sxs-lookup"><span data-stu-id="b2d1f-103">On the [Domains](https://portal.office.com/adminportal/home#/Domains) page, in the list of domains, select the domain you're using for your website, and then select **DNS settings** in the management pane.</span></span> 
    
2. <span data-ttu-id="b2d1f-104">Seleccione **Nuevo registro personalizado** y escriba lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="b2d1f-104">Select **+ New custom record** and enter the following:</span></span> 
    
  - <span data-ttu-id="b2d1f-105">Como **Tipo DNS**, escriba " **D (Dirección)** ".</span><span class="sxs-lookup"><span data-stu-id="b2d1f-105">For **DNS type** enter: **A (Address)**</span></span>
    
  - <span data-ttu-id="b2d1f-106">Como **Nombre de host o alias**, escriba " **@** ".</span><span class="sxs-lookup"><span data-stu-id="b2d1f-106">For **Host name or Alias**, type the following: **@**</span></span>
    
  - <span data-ttu-id="b2d1f-107">Como **Dirección IP**, escriba la dirección IP estática en la que se hospeda actualmente su sitio web (por ejemplo: 172.16.140.1).</span><span class="sxs-lookup"><span data-stu-id="b2d1f-107">For **IP Address**, type the static IP address for your website where it's currently hosted (for example, 172.16.140.1).</span></span> 
    
    <span data-ttu-id="b2d1f-p101">Esta dirección IP debe ser  *estática*  , no puede ser  *dinámica*  . Consulte al proveedor donde se hospeda el sitio web para asegurarse de que puede obtener una dirección IP estática para su sitio web público.</span><span class="sxs-lookup"><span data-stu-id="b2d1f-p101">This must be a  *static*  IP address for the website, not a  *dynamic*  IP address. Check with site where your website is hosted to make sure you can get a static IP address for your public website.</span></span> 
    
3. <span data-ttu-id="b2d1f-110">Seleccione **Guardar**.</span><span class="sxs-lookup"><span data-stu-id="b2d1f-110">Select **Save**.</span></span> 
    
<span data-ttu-id="b2d1f-111">Además, puede crear un registro CNAME para ayudar a los clientes a encontrar su sitio web.</span><span class="sxs-lookup"><span data-stu-id="b2d1f-111">In addition, you can create a CNAME record to help customers find your website.</span></span>
  
1. <span data-ttu-id="b2d1f-112">Seleccione **Nuevo registro personalizado** y escriba lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="b2d1f-112">Select **+ New custom record** and enter the following:</span></span> 
    
  - <span data-ttu-id="b2d1f-113">Como **Tipo DNS**, escriba " **CNAME (Alias)** ".</span><span class="sxs-lookup"><span data-stu-id="b2d1f-113">For **DNS type** enter: **CNAME (Alias)**</span></span>
    
  - <span data-ttu-id="b2d1f-114">Como **Nombre de host o alias**, escriba " **www** ".</span><span class="sxs-lookup"><span data-stu-id="b2d1f-114">For **Host name or Alias**, type the following: **www**</span></span>
    
  - <span data-ttu-id="b2d1f-115">Como **Dirección de destino**, escriba el FQDN (nombre de dominio completo) de su sitio web (por ejemplo, contoso.com).</span><span class="sxs-lookup"><span data-stu-id="b2d1f-115">For **Points to address**, type the fully qualified domain name (FQDN) for your website (for example, contoso.com).</span></span> 
    
2. <span data-ttu-id="b2d1f-116">Seleccione **Guardar**.</span><span class="sxs-lookup"><span data-stu-id="b2d1f-116">Select **Save**.</span></span> 
    

