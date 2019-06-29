---
title: Solucionar problemas relacionados con la inscripción de dispositivos Android en Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d0269461-20a8-4c9e-83b2-8fcf608dc0a5
ms.custom:
- "787"
- "6200002"
ms.openlocfilehash: 9cdfda0d7dd45af260f46738cbc85aac46f53960
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 06/28/2019
ms.locfileid: "35367306"
---
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a><span data-ttu-id="30ff7-102">Solucionar problemas relacionados con la inscripción de dispositivos Android en Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="30ff7-102">Troubleshoot issues with enrolling Android devices in Microsoft Intune</span></span>

<span data-ttu-id="30ff7-103">Revise los recursos que se enumeran a continuación para resolver su problema ahora.</span><span class="sxs-lookup"><span data-stu-id="30ff7-103">Review the resources listed below to resolve your issue now.</span></span>
  
<span data-ttu-id="30ff7-104">Algunos problemas comunes y los pasos de la solución:</span><span class="sxs-lookup"><span data-stu-id="30ff7-104">Some common issues and resolution steps:</span></span>
  
 <span data-ttu-id="30ff7-105">**Error de dispositivo no cifrado en el portal de la empresa:** Las versiones más recientes de Android, en especial a partir de la versión 7.0, requieren un código de acceso de inicio para asegurarse de que el dispositivo está totalmente cifrado.</span><span class="sxs-lookup"><span data-stu-id="30ff7-105">**Device not Encrypted error in Company Portal:** Newer versions of Android, particularly starting with v7.0, require a startup passcode to make sure that your device is fully encrypted.</span></span> <span data-ttu-id="30ff7-106">Las soluciones comunes son habilitar un PIN de inicio o cifrar completamente el dispositivo.</span><span class="sxs-lookup"><span data-stu-id="30ff7-106">Common solutions are to enable a startup pin or fully encrypt the device.</span></span> <span data-ttu-id="30ff7-107">Revise [este documento](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="30ff7-107">Review [this document](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) for more information.</span></span>
  
 <span data-ttu-id="30ff7-108">Los **dispositivos no pueden protegerse con el servicio de Intune o mostrarse como "incorrecto" en la consola de administración de Intune:** Es posible que algunos dispositivos de Samsung 4,4 y 5,5 no protejan el servicio.</span><span class="sxs-lookup"><span data-stu-id="30ff7-108">**Devices fail to check in with the Intune service or display as "Unhealthy" in the Intune admin console:** Some Samsung 4.4 and 5.5 devices may not check into the service.</span></span> <span data-ttu-id="30ff7-109">Hay tres posibles soluciones a este problema:</span><span class="sxs-lookup"><span data-stu-id="30ff7-109">There are 3 possible solutions to this issue:</span></span>
  
1. <span data-ttu-id="30ff7-110">Abra manualmente la aplicación del portal de empresa de Intune, que iniciará automáticamente una sincronización del dispositivo.</span><span class="sxs-lookup"><span data-stu-id="30ff7-110">Manually open the Intune Company Portal app, which will automatically initiate a device sync.</span></span>

2. <span data-ttu-id="30ff7-111">Actualice el dispositivo a Android 6,0 o posterior.</span><span class="sxs-lookup"><span data-stu-id="30ff7-111">Update the device to Android 6.0 or higher.</span></span>

3. <span data-ttu-id="30ff7-112">Deshabilite el administrador inteligente de Samsung para administrar el portal de empresa de Intune.</span><span class="sxs-lookup"><span data-stu-id="30ff7-112">Disable Samsung Smart Manager from managing the Intune Company Portal.</span></span> <span data-ttu-id="30ff7-113">Revise [este documento](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) para obtener más información sobre estos problemas y sus soluciones.</span><span class="sxs-lookup"><span data-stu-id="30ff7-113">Review [this document](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) for further details on these issues and resolutions.</span></span>

 <span data-ttu-id="30ff7-114">**Tipo de licencia de usuario no válido** o **nombre de usuario no reconocido error:** el usuario debe tener asignado una licencia de Intune o EMS.</span><span class="sxs-lookup"><span data-stu-id="30ff7-114">**User License Type Invalid** or **User Name Not Recognized error:** The user needs to be assigned an Intune or EMS license.</span></span> <span data-ttu-id="30ff7-115">Revise estos documentos para asignar una licencia mediante: Centro de administración de Office o portal de Azure.</span><span class="sxs-lookup"><span data-stu-id="30ff7-115">Review these documents to assign a license through: Office Admin Center or Azure portal.</span></span>
  
<span data-ttu-id="30ff7-116">Recursos adicionales para ayudar a resolver el problema:</span><span class="sxs-lookup"><span data-stu-id="30ff7-116">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="30ff7-117">Use el [portal de solución de problemas](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) de Intune para diagnosticar y resolver errores comunes de inscripción.</span><span class="sxs-lookup"><span data-stu-id="30ff7-117">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures.</span></span> <span data-ttu-id="30ff7-118">Revise [este documento](https://docs.microsoft.com/intune/help-desk-operators) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="30ff7-118">Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span>

2. <span data-ttu-id="30ff7-119">Revise [este documento](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) para obtener una lista de errores comunes que impiden la inscripción y las resoluciones a cada uno.</span><span class="sxs-lookup"><span data-stu-id="30ff7-119">Review [this document](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) for a list of common errors that prevent enrollment and resolutions to each.</span></span>

3. <span data-ttu-id="30ff7-120">[Obtenga información sobre cómo inscribir dispositivos Android en Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).</span><span class="sxs-lookup"><span data-stu-id="30ff7-120">[Learn how to enroll Android devices in Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).</span></span>
