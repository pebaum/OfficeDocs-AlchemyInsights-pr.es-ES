---
title: Dar acceso a los usuarios a SharePoint y OneDrive
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.date: 11/14/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: 9326932e93970edc96396a141c9b36b14e7b4d4d
ms.sourcegitcommit: 241e21b6da226563bf70bdb1f5bad3d91c38cd2c
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/05/2019
ms.locfileid: "34736664"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a><span data-ttu-id="6dbc8-102">Dar acceso a los usuarios a SharePoint y OneDrive</span><span class="sxs-lookup"><span data-stu-id="6dbc8-102">Give users access to SharePoint and OneDrive</span></span>

<span data-ttu-id="6dbc8-103">Este problema se produce con más frecuencia cuando se elimina un usuario y se vuelve a crear con el mismo nombre principal de usuario (UPN).</span><span class="sxs-lookup"><span data-stu-id="6dbc8-103">This issue most frequently occurs when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="6dbc8-104">La nueva cuenta se crea con un valor de PUID (identificador único de pasaporte) diferente.</span><span class="sxs-lookup"><span data-stu-id="6dbc8-104">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="6dbc8-105">Cuando el usuario intenta tener acceso a una colección de sitios o a su OneDrive, el usuario tiene un PUID incorrecto.</span><span class="sxs-lookup"><span data-stu-id="6dbc8-105">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="6dbc8-106">Un segundo escenario implica la sincronización de directorios con una unidad organizativa (OU) de Active Directory.</span><span class="sxs-lookup"><span data-stu-id="6dbc8-106">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="6dbc8-107">Si los usuarios ya han iniciado sesión en SharePoint y, a continuación, se mueven a otra unidad organizativa y se resincronizan con SharePoint, pueden experimentar este problema.</span><span class="sxs-lookup"><span data-stu-id="6dbc8-107">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

<span data-ttu-id="6dbc8-108">Para resolver este problema, restaure el UPN original con los pasos del artículo[restaurar un usuario en Office 365](https://docs.microsoft.com/en-us/office365/admin/add-users/restore-user?view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="6dbc8-108">To resolve this issue you should restore the original UPN with the steps in the article,[Restore a user in Office 365](https://docs.microsoft.com/en-us/office365/admin/add-users/restore-user?view=o365-worldwide).</span></span>

<span data-ttu-id="6dbc8-109">Una vez hecho esto, puede comprobar que el usuario tiene derechos de administrador en el sitio de OneDrive siguiendo los pasos para [Agregar un administrador para el onedrive de un usuario](https://docs.microsoft.com/en-us/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive)</span><span class="sxs-lookup"><span data-stu-id="6dbc8-109">After this is done, you can verify the user has admin rights to the OneDrive site by following the steps to [Add admin's for a user's OneDrive](https://docs.microsoft.com/en-us/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive)</span></span>

<span data-ttu-id="6dbc8-110">Para obtener más información sobre los niveles de permisos, vea el artículo [sobre los niveles de permisos en SharePoint](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels).</span><span class="sxs-lookup"><span data-stu-id="6dbc8-110">For more information on permission levels, see the article, [Understanding permission levels in SharePoint](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels).</span></span>
