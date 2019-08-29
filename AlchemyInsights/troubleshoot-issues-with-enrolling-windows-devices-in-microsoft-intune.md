---
title: Solucionar problemas relacionados con la inscripción de dispositivos Windows en Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 20e9bd42-2db0-4dd7-b480-966571494dd9
ms.custom:
- "784"
- "6200002"
ms.openlocfilehash: 7b298360fe31d3f52ef382e5b8f25ee3588c36c8
ms.sourcegitcommit: b3e55405af384e868fcd32ea794eb15d1356c3fc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/29/2019
ms.locfileid: "36665849"
---
# <a name="troubleshoot-issues-with-enrolling-windows-devices-in-microsoft-intune"></a><span data-ttu-id="eb0a4-102">Solucionar problemas relacionados con la inscripción de dispositivos Windows en Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="eb0a4-102">Troubleshoot issues with enrolling Windows devices in Microsoft Intune</span></span>

<span data-ttu-id="eb0a4-103">Revise los recursos que se enumeran a continuación para resolver su problema ahora.</span><span class="sxs-lookup"><span data-stu-id="eb0a4-103">Review the resources listed below to resolve your issue now.</span></span>
  
<span data-ttu-id="eb0a4-104">Algunos mensajes de error comunes y pasos de resolución:</span><span class="sxs-lookup"><span data-stu-id="eb0a4-104">Some common error messages and resolution steps:</span></span>
  
 <span data-ttu-id="eb0a4-105">**El software no se puede instalar, 0x80cf4017:** El certificado de cuenta ha expirado.</span><span class="sxs-lookup"><span data-stu-id="eb0a4-105">**The software cannot be installed, 0x80cf4017:** Your account certificate has expired.</span></span> <span data-ttu-id="eb0a4-106">Vuelva a descargar el paquete de software cliente de PC en la consola de administración de Intune.</span><span class="sxs-lookup"><span data-stu-id="eb0a4-106">Re-download the PC Client software package in the Intune Admin Console.</span></span> <span data-ttu-id="eb0a4-107">Consulte esta documentación para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="eb0a4-107">Review this documentation for more information.</span></span>
  
 <span data-ttu-id="eb0a4-108">**Código de error 0x801c0003:** El error puede producirse en las siguientes situaciones:</span><span class="sxs-lookup"><span data-stu-id="eb0a4-108">**Error code 0x801c0003:** The error can occur in the following scenarios:</span></span>
  
-  <span data-ttu-id="eb0a4-109">El usuario tiene más dispositivos inscritos que el límite del dispositivo.</span><span class="sxs-lookup"><span data-stu-id="eb0a4-109">The user has more devices enrolled than the device limit.</span></span> <span data-ttu-id="eb0a4-110">Revise estos documentos para [quitar un dispositivo](https://docs.microsoft.com/intune/devices-wipe) o [cambiar el límite del dispositivo](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span><span class="sxs-lookup"><span data-stu-id="eb0a4-110">Review these documents to [remove a device](https://docs.microsoft.com/intune/devices-wipe) or [change the device limit](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span></span>

-  <span data-ttu-id="eb0a4-111">"Los usuarios pueden unir dispositivos a Azure AD" se establece en "ninguno".</span><span class="sxs-lookup"><span data-stu-id="eb0a4-111">"Users may join devices to Azure AD" is set to "none."</span></span> <span data-ttu-id="eb0a4-112">Establézcalo en todos o seleccione usuarios.</span><span class="sxs-lookup"><span data-stu-id="eb0a4-112">Set it to all or select users.</span></span> <span data-ttu-id="eb0a4-113">Consulte [esta documentación](https://docs.microsoft.com/azure/active-directory/device-management-azure-portal#configure-device-settings) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="eb0a4-113">Review [this documentation](https://docs.microsoft.com/azure/active-directory/device-management-azure-portal#configure-device-settings) for more information.</span></span>

-  <span data-ttu-id="eb0a4-114">El dispositivo ya está inscrito por otro usuario.</span><span class="sxs-lookup"><span data-stu-id="eb0a4-114">The device is already enrolled by another user.</span></span> <span data-ttu-id="eb0a4-115">Si ese es el caso, quite el dispositivo de la consola de Azure Intune o elimine la inscripción del dispositivo manualmente antes de volver a intentarlo.</span><span class="sxs-lookup"><span data-stu-id="eb0a4-115">If that's the case, remove the device from the Azure Intune console or manually unenroll the device before trying again.</span></span>

-  <span data-ttu-id="eb0a4-116">El dispositivo es Windows 10 Home.</span><span class="sxs-lookup"><span data-stu-id="eb0a4-116">The device is Windows 10 Home.</span></span> <span data-ttu-id="eb0a4-117">Solo las SKU de Windows 10 Pro, Education y Enterprise pueden unirse a Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="eb0a4-117">Only Windows 10 Pro, Education and Enterprise SKUs can join Azure Active Directory.</span></span>

<span data-ttu-id="eb0a4-118">Recursos adicionales para ayudar a resolver el problema:</span><span class="sxs-lookup"><span data-stu-id="eb0a4-118">Additional resources to help resolve your issue:</span></span>
  
-  <span data-ttu-id="eb0a4-119">Use el [portal de solución de problemas](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) de Intune para diagnosticar y resolver errores comunes de inscripción.</span><span class="sxs-lookup"><span data-stu-id="eb0a4-119">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures.</span></span> <span data-ttu-id="eb0a4-120">Revise [este documento](https://docs.microsoft.com/intune/help-desk-operators) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="eb0a4-120">Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span>

-  <span data-ttu-id="eb0a4-121">Revise estos documentos para obtener una lista de errores comunes que impiden la inscripción y las resoluciones a cada uno: [Guía de solución de problemas](https://support.microsoft.com/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) y documento de solución de [problemas](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span><span class="sxs-lookup"><span data-stu-id="eb0a4-121">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) and [Troubleshooting doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span></span>

<span data-ttu-id="eb0a4-122">[Obtenga información sobre cómo inscribir dispositivos Windows en Microsoft Intune](https://docs.microsoft.com/intune/windows-enroll).</span><span class="sxs-lookup"><span data-stu-id="eb0a4-122">[Learn how to enroll Windows devices in Microsoft Intune](https://docs.microsoft.com/intune/windows-enroll).</span></span>
