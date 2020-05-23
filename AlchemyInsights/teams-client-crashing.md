---
title: ¿El cliente de Teams está fallando?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002323"
- "4512"
ms.openlocfilehash: c49dfbf422b312f4744711d5f12b0eb83b6ebf2e
ms.sourcegitcommit: b398afd92d4259f893c25b48aec65921e6cc68d6
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 05/16/2020
ms.locfileid: "44268789"
---
# <a name="teams-client-crashing"></a><span data-ttu-id="980e3-102">¿El cliente de Teams está fallando?</span><span class="sxs-lookup"><span data-stu-id="980e3-102">Teams client crashing?</span></span>

<span data-ttu-id="980e3-103">Si el cliente de Teams está fallando, intenta lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="980e3-103">If your Teams client is crashing, try the following:</span></span>

- <span data-ttu-id="980e3-104">Si está usando la aplicación de escritorio de Teams, asegúrese de que la aplicación esté completamente actualizada.</span><span class="sxs-lookup"><span data-stu-id="980e3-104">If you are using the Teams desktop app, [make sure the app is fully updated](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).</span></span>

- <span data-ttu-id="980e3-105">Asegúrese de que todas las [URL e intervalos de direcciones de Microsoft 365](https://docs.microsoft.com/microsoftteams/connectivity-issues) sean accesibles.</span><span class="sxs-lookup"><span data-stu-id="980e3-105">Make sure all the [Microsoft 365 URLs and address ranges](https://docs.microsoft.com/microsoftteams/connectivity-issues) are accessible.</span></span>

- <span data-ttu-id="980e3-106">Inicie sesión con su cuenta de administrador de inquilino y compruebe el [panel de estado del servicio](https://docs.microsoft.com/office365/enterprise/view-service-health) para verificar que no exista ninguna interrupción o degradación del servicio.</span><span class="sxs-lookup"><span data-stu-id="980e3-106">Log in with your tenant admin account and check your [Service Health Dashboard](https://docs.microsoft.com/office365/enterprise/view-service-health) to verify that no outage or service degradation exists.</span></span>

 - <span data-ttu-id="980e3-107">Como último paso, puede intentar borrar la memoria caché del cliente de Teams:</span><span class="sxs-lookup"><span data-stu-id="980e3-107">As a last step, you can attempt to clear your Teams client cache:</span></span>

    1.  <span data-ttu-id="980e3-108">Salir completamente del cliente de escritorio de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="980e3-108">Fully exit the Microsoft Teams desktop client.</span></span> <span data-ttu-id="980e3-109">Puede hacer clic con el botón derecho del ratón en **Teams** desde la Bandeja de Iconos y luego hacer clic en **Salir**, o ejecutar el Administrador de Tareas y finalizar el proceso por completo.</span><span class="sxs-lookup"><span data-stu-id="980e3-109">You can right-click **Teams** from the Icon Tray and click **Quit**, or run Task Manager and fully kill the process.</span></span>

    2.  <span data-ttu-id="980e3-110">Ve al Explorador de archivos, y escribe %appdata%\Microsoft\teams.</span><span class="sxs-lookup"><span data-stu-id="980e3-110">Go to File Explorer, and type in %appdata%\Microsoft\teams.</span></span>

    3.  <span data-ttu-id="980e3-111">Una vez en el directorio, verá algunas de las siguientes carpetas:</span><span class="sxs-lookup"><span data-stu-id="980e3-111">Once in the directory, you'll see a few of the following folders:</span></span>

         - <span data-ttu-id="980e3-112">Desde la memoria **caché de aplicaciones**, vaya a almacenamiento en caché y elimine cualquiera de los archivos en la ubicación de caché: %appdata%\Microsoft\teams\application cache\cache.</span><span class="sxs-lookup"><span data-stu-id="980e3-112">From within **Application Cache**, go to Cache and delete any of the files in the Cache location:  %appdata%\Microsoft\teams\application cache\cache.</span></span>

        - <span data-ttu-id="980e3-113">En **Blob_storage**, elimine todos los archivos: %appdata%\Microsoft\teams\blob_storage.</span><span class="sxs-lookup"><span data-stu-id="980e3-113">From within **Blob_storage**, delete all files: %appdata%\Microsoft\teams\blob_storage.</span></span>

        - <span data-ttu-id="980e3-114">En **Cache**, elimine todos los archivos: %appdata%\Microsoft\teams\Cache.</span><span class="sxs-lookup"><span data-stu-id="980e3-114">From within **Cache**, delete all files: %appdata%\Microsoft\teams\Cache.</span></span>

        - <span data-ttu-id="980e3-115">En **databases**, elimine todos los archivos: %appdata%\Microsoft\teams\databases.</span><span class="sxs-lookup"><span data-stu-id="980e3-115">From within **databases**, delete all files: %appdata%\Microsoft\teams\databases.</span></span>

        - <span data-ttu-id="980e3-116">En **GPUCache**, elimine todos los archivos: %appdata%\Microsoft\teams\GPUcache.</span><span class="sxs-lookup"><span data-stu-id="980e3-116">From within **GPUCache**, delete all files: %appdata%\Microsoft\teams\GPUcache.</span></span>

        - <span data-ttu-id="980e3-117">En **IndexedDB**, elimine el archivo con extensión .db: %appdata%\Microsoft\teams\IndexedDB.</span><span class="sxs-lookup"><span data-stu-id="980e3-117">From within **IndexedDB**, delete the .db file: %appdata%\Microsoft\teams\IndexedDB.</span></span>

        - <span data-ttu-id="980e3-118">En **Local Storage**, elimine todos los archivos: %appdata%\Microsoft\teams\Local Storage.</span><span class="sxs-lookup"><span data-stu-id="980e3-118">From within **Local Storage**, delete all files: %appdata%\Microsoft\teams\Local Storage.</span></span>

        - <span data-ttu-id="980e3-119">Por último, en **tmp**, elimine cualquier archivo: %appdata%\Microsoft\teams\tmp.</span><span class="sxs-lookup"><span data-stu-id="980e3-119">Lastly, from within **tmp**, delete any file: %appdata%\Microsoft\teams\tmp.</span></span>

    4. <span data-ttu-id="980e3-120">Reinicie su cliente de Teams.</span><span class="sxs-lookup"><span data-stu-id="980e3-120">Restart your Teams client.</span></span>

<span data-ttu-id="980e3-121">Si el cliente de su equipo aún se bloquea, ¿puede reproducir el problema?</span><span class="sxs-lookup"><span data-stu-id="980e3-121">If your Teams client is still crashing, can you reproduce the issue?</span></span> <span data-ttu-id="980e3-122">En ese caso:</span><span class="sxs-lookup"><span data-stu-id="980e3-122">If so:</span></span> 

1. <span data-ttu-id="980e3-123">Use la Grabación de acciones de usuario para capturar los pasos.</span><span class="sxs-lookup"><span data-stu-id="980e3-123">Use the Steps Recorder to capture your steps.</span></span>
    - <span data-ttu-id="980e3-124">Cierre todas las aplicaciones innecesarias o confidenciales.</span><span class="sxs-lookup"><span data-stu-id="980e3-124">Close ALL unnecessary or confidential applications.</span></span>
    - <span data-ttu-id="980e3-125">Inicie sesión con la cuenta de usuario afectada, abra la Grabación de acciones de usuario y reproduzca el problema.</span><span class="sxs-lookup"><span data-stu-id="980e3-125">Launch the Steps Recorder and reproduce the issue while logged in with the affected user account.</span></span>
    
2. <span data-ttu-id="980e3-126">Anexe el archivo a su caso de soporte técnico.</span><span class="sxs-lookup"><span data-stu-id="980e3-126">Attach the file to your support case.</span></span>
