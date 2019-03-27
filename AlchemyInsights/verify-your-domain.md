---
title: Verify your domain
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/5/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 81fd176b-3d67-4e52-9ab8-d36602412734
ms.openlocfilehash: d215f3af0cf4b46b12c8cb51a9572adb00f354e4
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/22/2019
ms.locfileid: "30766365"
---
# <a name="verify-your-domain"></a><span data-ttu-id="9dcd4-102">Verify your domain</span><span class="sxs-lookup"><span data-stu-id="9dcd4-102">Verify your domain</span></span>

 <span data-ttu-id="9dcd4-103">**Es probable que el registro no se haya actualizado a través de Internet.**</span><span class="sxs-lookup"><span data-stu-id="9dcd4-103">**The record probably hasn't updated across the Internet.**</span></span>
  
<span data-ttu-id="9dcd4-104">Normalmente, solo se tarda unos minutos para poder ver el nuevo registro, pero en ocasiones puede tardar varias horas en realizarse.</span><span class="sxs-lookup"><span data-stu-id="9dcd4-104">It typically only takes a few minutes for us to be able to see the new record, but occasionally it can take as long as a few hours.</span></span> 
  
- <span data-ttu-id="9dcd4-105">Si ya ha esperado ese tiempo, compruebe que ha copiado y pegado el valor exacto en el registro de verificación TXT en el host DNS.</span><span class="sxs-lookup"><span data-stu-id="9dcd4-105">If you've waited that long already, double-check that you've copied and pasted the exact value into the TXT verification record at your DNS host.</span></span> <span data-ttu-id="9dcd4-106">Uno de los problemas habituales es no incluir la parte de "MS=" del registro.</span><span class="sxs-lookup"><span data-stu-id="9dcd4-106">One common issue is not including the "MS=" part of the record.</span></span> <span data-ttu-id="9dcd4-107">¡También la necesitamos!</span><span class="sxs-lookup"><span data-stu-id="9dcd4-107">We need that too!</span></span>
    
- <span data-ttu-id="9dcd4-108">En algunos hosts DNS, tiene que llevar a cabo un paso adicional para guardar el archivo de zona (donde se almacena el registro DNS), de modo que se actualice a través de Internet.</span><span class="sxs-lookup"><span data-stu-id="9dcd4-108">At some DNS hosts, you have to take an extra step to save the zone file (where the DNS record is stored) so that it will update across the Internet.</span></span> <span data-ttu-id="9dcd4-109">Asegúrese de que haya guardado los cambios de manera que Office 365 pueda ver y comprobar el registro.</span><span class="sxs-lookup"><span data-stu-id="9dcd4-109">Make sure you've saved your changes so Office 365 can see and verify the record.</span></span>
    

