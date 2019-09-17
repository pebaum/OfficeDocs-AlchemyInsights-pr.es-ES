---
title: Enviar notificaciones personalizadas con Intune
ms.author: brenduns
author: brenduns
manager: dougeby
ms.date: 07/31/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 9000679
ms.openlocfilehash: 1244f07fd56cf603280f1710520a04d579224e44
ms.sourcegitcommit: 16f08d051afca3c6d0de32826324f91cf63ab5ba
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/16/2019
ms.locfileid: "36992329"
---
# <a name="how-to-send-custom-notifications-to-the-users-of-managed-ios-and-android-devices"></a><span data-ttu-id="2602c-102">Cómo enviar notificaciones personalizadas a los usuarios de dispositivos administrados iOS y Android</span><span class="sxs-lookup"><span data-stu-id="2602c-102">How to send custom notifications to the users of managed iOS and Android devices</span></span>

<span data-ttu-id="2602c-103">Las notificaciones personalizadas para Intune las procesa la aplicación portal de empresa en el dispositivo de un usuario.</span><span class="sxs-lookup"><span data-stu-id="2602c-103">Custom notifications for Intune are processed by the Company Portal app on a user’s device.</span></span> <span data-ttu-id="2602c-104">A continuación, la aplicación crea la notificación de inserción en ese dispositivo.</span><span class="sxs-lookup"><span data-stu-id="2602c-104">The app then creates the push notification on that device.</span></span>

<span data-ttu-id="2602c-105">Los siguientes son requisitos previos de dispositivos para admitir la recepción de notificaciones personalizadas, y para que la aplicación cree la notificación de inserción:</span><span class="sxs-lookup"><span data-stu-id="2602c-105">The following are device prerequisites to support receipt of custom notifications, and for the app to then create the push notification:</span></span>

- <span data-ttu-id="2602c-106">El dispositivo debe tener instalada la aplicación portal de empresa.</span><span class="sxs-lookup"><span data-stu-id="2602c-106">The device must have the Company Portal app installed.</span></span>  

- <span data-ttu-id="2602c-107">El dispositivo debe permitir que la aplicación de portal de empresa envíe notificaciones de inserción.</span><span class="sxs-lookup"><span data-stu-id="2602c-107">The device must allow the Company Portal app to send push notifications.</span></span> <span data-ttu-id="2602c-108">Cuando la aplicación se instale o actualice, se le pedirá al usuario que permita las notificaciones.</span><span class="sxs-lookup"><span data-stu-id="2602c-108">When the app is installed or updated, it will prompt the user to permit notifications.</span></span>

- <span data-ttu-id="2602c-109">Los dispositivos Android deben tener instalado Google Play Services.</span><span class="sxs-lookup"><span data-stu-id="2602c-109">Android devices must have Google Play Services installed.</span></span>

- <span data-ttu-id="2602c-110">El dispositivo debe estar inscrito con Intune.</span><span class="sxs-lookup"><span data-stu-id="2602c-110">The device must be enrolled with Intune.</span></span>

<span data-ttu-id="2602c-111">Para obtener más información, incluido cómo enviar un mensaje, consulte la documentación de la [característica](https://docs.microsoft.com/intune/custom-notifications).</span><span class="sxs-lookup"><span data-stu-id="2602c-111">For more information including how to send a message, see the [feature documentation](https://docs.microsoft.com/intune/custom-notifications).</span></span>
