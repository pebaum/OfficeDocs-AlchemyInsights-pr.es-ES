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
ms.openlocfilehash: ce37b260d126f876d2b6177515bd8a7c3874ef2c
ms.sourcegitcommit: d02e2b73aa7d0453d7baca1ea5a186cf6081d022
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 03/27/2020
ms.locfileid: "43030671"
---
# <a name="teams-client-crashing"></a><span data-ttu-id="15a5b-102">¿El cliente de Teams está fallando?</span><span class="sxs-lookup"><span data-stu-id="15a5b-102">Teams client crashing?</span></span>

<span data-ttu-id="15a5b-103">Si el cliente de Teams está fallando, intenta lo siguiente:</span><span class="sxs-lookup"><span data-stu-id="15a5b-103">If your Teams client is crashing, try the following:</span></span>

- <span data-ttu-id="15a5b-104">Si está usando la aplicación de escritorio de Teams, asegúrese de que la aplicación esté completamente actualizada.</span><span class="sxs-lookup"><span data-stu-id="15a5b-104">If you are using the Teams desktop app, [make sure the app is fully updated](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).</span></span>

- <span data-ttu-id="15a5b-105">Asegúrese de que todas las [URL e intervalos de direcciones de Office 365](https://docs.microsoft.com/microsoftteams/connectivity-issues) sean accesibles.</span><span class="sxs-lookup"><span data-stu-id="15a5b-105">Make sure all the [Office 365 URL's and address ranges](https://docs.microsoft.com/microsoftteams/connectivity-issues) are accessible.</span></span>

- <span data-ttu-id="15a5b-106">Inicie sesión con su cuenta de administrador y compruebe el [panel de estado del servicio](https://docs.microsoft.com/office365/enterprise/view-service-health) para verificar que no exista ninguna interrupción o degradación del servicio.</span><span class="sxs-lookup"><span data-stu-id="15a5b-106">Log in with your admin account and check your [Service Health Dashboard](https://docs.microsoft.com/office365/enterprise/view-service-health) to verify that no outage or service degradation exists.</span></span>

 - <span data-ttu-id="15a5b-107">Como último paso, puede intentar borrar la memoria caché del cliente de Teams:</span><span class="sxs-lookup"><span data-stu-id="15a5b-107">As a last step, you can attempt to clear your Teams client cache:</span></span>

    1.  <span data-ttu-id="15a5b-108">Salir completamente del cliente de escritorio de Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="15a5b-108">Fully exit the Microsoft Teams desktop client.</span></span> <span data-ttu-id="15a5b-109">Puede hacer clic con el botón derecho del ratón en **Teams** desde la Bandeja de Iconos y luego hacer clic en **Salir**, o ejecutar el Administrador de Tareas y finalizar el proceso por completo.</span><span class="sxs-lookup"><span data-stu-id="15a5b-109">You can right-click **Teams** from the Icon Tray and click **Quit**, or run Task Manager and fully kill the process.</span></span>

    2.  <span data-ttu-id="15a5b-110">Ve al Explorador de archivos, y escribe %appdata%\Microsoft\teams.</span><span class="sxs-lookup"><span data-stu-id="15a5b-110">Go to File Explorer, and type in %appdata%\Microsoft\teams.</span></span>

    3.  <span data-ttu-id="15a5b-111">Una vez en el directorio, verá algunas de las siguientes carpetas:</span><span class="sxs-lookup"><span data-stu-id="15a5b-111">Once in the directory, you'll see a few of the following folders:</span></span>

         - <span data-ttu-id="15a5b-112">Desde la memoria **caché de aplicaciones**, vaya a almacenamiento en caché y elimine cualquiera de los archivos en la ubicación de caché: %appdata%\Microsoft\teams\application cache\cache.</span><span class="sxs-lookup"><span data-stu-id="15a5b-112">From within **Application Cache**, go to Cache and delete any of the files in the Cache location:  %appdata%\Microsoft\teams\application cache\cache.</span></span>

        - <span data-ttu-id="15a5b-113">En **Blob_storage**, elimine todos los archivos: %appdata%\Microsoft\teams\blob_storage.</span><span class="sxs-lookup"><span data-stu-id="15a5b-113">From within **Blob_storage**, delete all files: %appdata%\Microsoft\teams\blob_storage.</span></span>

        - <span data-ttu-id="15a5b-114">En **Cache**, elimine todos los archivos: %appdata%\Microsoft\teams\Cache.</span><span class="sxs-lookup"><span data-stu-id="15a5b-114">From within **Cache**, delete all files: %appdata%\Microsoft\teams\Cache.</span></span>

        - <span data-ttu-id="15a5b-115">En **databases**, elimine todos los archivos: %appdata%\Microsoft\teams\databases.</span><span class="sxs-lookup"><span data-stu-id="15a5b-115">From within **databases**, delete all files: %appdata%\Microsoft\teams\databases.</span></span>

        - <span data-ttu-id="15a5b-116">En **GPUCache**, elimine todos los archivos: %appdata%\Microsoft\teams\GPUcache.</span><span class="sxs-lookup"><span data-stu-id="15a5b-116">From within **GPUCache**, delete all files: %appdata%\Microsoft\teams\GPUcache.</span></span>

        - <span data-ttu-id="15a5b-117">En **IndexedDB**, elimine el archivo con extensión .db: %appdata%\Microsoft\teams\IndexedDB.</span><span class="sxs-lookup"><span data-stu-id="15a5b-117">From within **IndexedDB**, delete the .db file: %appdata%\Microsoft\teams\IndexedDB.</span></span>

        - <span data-ttu-id="15a5b-118">En **Local Storage**, elimine todos los archivos: %appdata%\Microsoft\teams\Local Storage.</span><span class="sxs-lookup"><span data-stu-id="15a5b-118">From within **Local Storage**, delete all files: %appdata%\Microsoft\teams\Local Storage.</span></span>

        - <span data-ttu-id="15a5b-119">Por último, en **tmp**, elimine cualquier archivo: %appdata%\Microsoft\teams\tmp.</span><span class="sxs-lookup"><span data-stu-id="15a5b-119">Lastly, from within **tmp**, delete any file: %appdata%\Microsoft\teams\tmp.</span></span>

    4. <span data-ttu-id="15a5b-120">Reinicie su cliente de Teams.</span><span class="sxs-lookup"><span data-stu-id="15a5b-120">Restart your Teams client.</span></span>
