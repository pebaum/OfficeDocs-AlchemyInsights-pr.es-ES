---
title: Enviar notificaciones personalizadas con Intune
ms.author: brenduns
author: brenduns
manager: dougeby
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000679"
- "2565"
ms.openlocfilehash: 969649084a2ac536ee1b41f225c3be5415a27c4b
ms.sourcegitcommit: 2572c4e5a981d5f3f556835061c568cfd08b78da
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/27/2019
ms.locfileid: "40886874"
---
# <a name="how-to-send-custom-notifications-to-the-users-of-managed-ios-and-android-devices"></a><span data-ttu-id="44dae-102">Cómo enviar notificaciones personalizadas a los usuarios de dispositivos administrados iOS y Android</span><span class="sxs-lookup"><span data-stu-id="44dae-102">How to send custom notifications to the users of managed iOS and Android devices</span></span>

<span data-ttu-id="44dae-103">Las notificaciones personalizadas para Intune las procesa la aplicación portal de empresa en el dispositivo de un usuario.</span><span class="sxs-lookup"><span data-stu-id="44dae-103">Custom notifications for Intune are processed by the Company Portal app on a user’s device.</span></span> <span data-ttu-id="44dae-104">A continuación, la aplicación crea la notificación de inserción en ese dispositivo.</span><span class="sxs-lookup"><span data-stu-id="44dae-104">The app then creates the push notification on that device.</span></span>

<span data-ttu-id="44dae-105">Los siguientes son requisitos previos de dispositivos para admitir la recepción de notificaciones personalizadas, y para que la aplicación cree la notificación de inserción:</span><span class="sxs-lookup"><span data-stu-id="44dae-105">The following are device prerequisites to support receipt of custom notifications, and for the app to then create the push notification:</span></span>

- <span data-ttu-id="44dae-106">El dispositivo debe tener instalada la aplicación portal de empresa.</span><span class="sxs-lookup"><span data-stu-id="44dae-106">The device must have the Company Portal app installed.</span></span>  

- <span data-ttu-id="44dae-107">El dispositivo debe permitir que la aplicación de portal de empresa envíe notificaciones de inserción.</span><span class="sxs-lookup"><span data-stu-id="44dae-107">The device must allow the Company Portal app to send push notifications.</span></span> <span data-ttu-id="44dae-108">Cuando la aplicación se instale o actualice, se le pedirá al usuario que permita las notificaciones.</span><span class="sxs-lookup"><span data-stu-id="44dae-108">When the app is installed or updated, it will prompt the user to permit notifications.</span></span>

- <span data-ttu-id="44dae-109">Los dispositivos Android deben tener instalado Google Play Services.</span><span class="sxs-lookup"><span data-stu-id="44dae-109">Android devices must have Google Play Services installed.</span></span>

- <span data-ttu-id="44dae-110">El dispositivo debe estar inscrito con Intune.</span><span class="sxs-lookup"><span data-stu-id="44dae-110">The device must be enrolled with Intune.</span></span>

<span data-ttu-id="44dae-111">Para obtener más información, incluido cómo enviar un mensaje, consulte la documentación de la [característica](https://docs.microsoft.com/intune/custom-notifications).</span><span class="sxs-lookup"><span data-stu-id="44dae-111">For more information including how to send a message, see the [feature documentation](https://docs.microsoft.com/intune/custom-notifications).</span></span>
