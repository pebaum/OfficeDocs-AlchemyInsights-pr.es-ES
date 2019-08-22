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
ms.custom:
- "47"
- "48"
- "8"
ms.assetid: 81fd176b-3d67-4e52-9ab8-d36602412734
ms.openlocfilehash: 3dd96a9731cfd75882dd3bb397005b19d471c882
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/22/2019
ms.locfileid: "36531376"
---
# <a name="verify-your-domain"></a><span data-ttu-id="aa906-102">Verify your domain</span><span class="sxs-lookup"><span data-stu-id="aa906-102">Verify your domain</span></span>

 <span data-ttu-id="aa906-103">**Es probable que el registro no se haya actualizado a través de Internet.**</span><span class="sxs-lookup"><span data-stu-id="aa906-103">**The record probably hasn't updated across the Internet.**</span></span>
  
<span data-ttu-id="aa906-104">Normalmente, solo se tarda unos minutos para poder ver el nuevo registro, pero en ocasiones puede tardar varias horas en realizarse.</span><span class="sxs-lookup"><span data-stu-id="aa906-104">It typically only takes a few minutes for us to be able to see the new record, but occasionally it can take as long as a few hours.</span></span> 
  
- <span data-ttu-id="aa906-105">Si ya ha esperado ese tiempo, compruebe que ha copiado y pegado el valor exacto en el registro de verificación TXT en el host DNS.</span><span class="sxs-lookup"><span data-stu-id="aa906-105">If you've waited that long already, double-check that you've copied and pasted the exact value into the TXT verification record at your DNS host.</span></span> <span data-ttu-id="aa906-106">Uno de los problemas habituales es no incluir la parte de "MS=" del registro.</span><span class="sxs-lookup"><span data-stu-id="aa906-106">One common issue is not including the "MS=" part of the record.</span></span> <span data-ttu-id="aa906-107">¡También la necesitamos!</span><span class="sxs-lookup"><span data-stu-id="aa906-107">We need that too!</span></span>

- <span data-ttu-id="aa906-108">En algunos hosts DNS, tiene que llevar a cabo un paso adicional para guardar el archivo de zona (donde se almacena el registro DNS), de modo que se actualice a través de Internet.</span><span class="sxs-lookup"><span data-stu-id="aa906-108">At some DNS hosts, you have to take an extra step to save the zone file (where the DNS record is stored) so that it will update across the Internet.</span></span> <span data-ttu-id="aa906-109">Asegúrese de que haya guardado los cambios de manera que Office 365 pueda ver y comprobar el registro.</span><span class="sxs-lookup"><span data-stu-id="aa906-109">Make sure you've saved your changes so Office 365 can see and verify the record.</span></span>
