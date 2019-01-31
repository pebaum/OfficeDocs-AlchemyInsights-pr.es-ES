---
title: Solución de problemas de inscripción de dispositivos de Windows en Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 20e9bd42-2db0-4dd7-b480-966571494dd9
ms.openlocfilehash: 8c5e7cc502d016ad658383685523dc240dfb4dc6
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/30/2019
ms.locfileid: "29661580"
---
# <a name="troubleshoot-issues-with-enrolling-windows-devices-in-microsoft-intune"></a><span data-ttu-id="53b80-102">Solución de problemas de inscripción de dispositivos de Windows en Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="53b80-102">Troubleshoot issues with enrolling Windows devices in Microsoft Intune</span></span>

<span data-ttu-id="53b80-103">Revise los recursos enumerados a continuación para resolver el problema ahora.</span><span class="sxs-lookup"><span data-stu-id="53b80-103">Review the resources listed below to resolve your issue now.</span></span> 
  
<span data-ttu-id="53b80-104">Algunos mensajes de error comunes y los pasos de la solución:</span><span class="sxs-lookup"><span data-stu-id="53b80-104">Some common error messages and resolution steps:</span></span>
  
 <span data-ttu-id="53b80-p101">**No se puede instalar el software, 0x80cf4017:** El certificado de cuenta ha caducado. Vuelva a descargar el paquete de software de cliente de PC en la consola de administración Intune. Revise esta documentación para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="53b80-p101">**The software cannot be installed, 0x80cf4017:** Your account certificate has expired. Re-download the PC Client software package in the Intune Admin Console. Review this documentation for more information.</span></span> 
  
 <span data-ttu-id="53b80-108">**Código de error 0x801c0003:** El error puede producirse en los siguientes escenarios:</span><span class="sxs-lookup"><span data-stu-id="53b80-108">**Error code 0x801c0003:** The error can occur in the following scenarios:</span></span> 
  
1. <span data-ttu-id="53b80-p102">El usuario tiene más dispositivos inscritos que el límite de dispositivos. Revise estos documentos para [quitar un dispositivo](https://docs.microsoft.com/intune/devices-wipe) o [cambiar el límite de dispositivos](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span><span class="sxs-lookup"><span data-stu-id="53b80-p102">The user has more devices enrolled than the device limit. Review these documents to [remove a device](https://docs.microsoft.com/intune/devices-wipe) or [change the device limit](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span></span>
    
2. <span data-ttu-id="53b80-p103">"Los usuarios pueden unirse a dispositivos a Azure AD" se establece en "none". Establecido en all o seleccione los usuarios. Revise [esta documentación](https://docs.microsoft.com/azure/active-directory/device-management-azure-portal#configure-device-settings) para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="53b80-p103">"Users may join devices to Azure AD" is set to "none". Set it to all or select users. Review [this documentation](https://docs.microsoft.com/azure/active-directory/device-management-azure-portal#configure-device-settings) for more information.</span></span> 
    
3. <span data-ttu-id="53b80-p104">El dispositivo ya está inscrito por otro usuario. Si ese es el caso, quite el dispositivo desde la consola de Azure Intune o manualmente anular inscripción el dispositivo antes de intentar de nuevo.</span><span class="sxs-lookup"><span data-stu-id="53b80-p104">The device is already enrolled by another user. If that's the case, remove the device from the Azure Intune console or manually unenroll the device before trying again.</span></span>
    
4. <span data-ttu-id="53b80-p105">El dispositivo es 10 Windows Home. Sólo 10 para profesionales de Windows, la educación y las SKU de empresa pueden unir a Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="53b80-p105">The device is Windows 10 Home. Only Windows 10 Pro, Education and Enterprise SKUs can join Azure Active Directory.</span></span>
    
<span data-ttu-id="53b80-118">Recursos adicionales para ayudar a resolver el problema:</span><span class="sxs-lookup"><span data-stu-id="53b80-118">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="53b80-p106">Usar [Intune Portal de solución de problemas](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) para diagnosticar y resolver los errores comunes de inscripción. Revise [este documento](https://docs.microsoft.com/intune/help-desk-operators) para obtener más detalles.</span><span class="sxs-lookup"><span data-stu-id="53b80-p106">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures. Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span> 
    
2. <span data-ttu-id="53b80-121">Revise estos documentos para obtener una lista de errores comunes que impiden la inscripción y resoluciones a cada uno: [Guía de solución de problemas](https://support.microsoft.com/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) y [solución de problemas doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span><span class="sxs-lookup"><span data-stu-id="53b80-121">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) and [Troubleshooting doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span></span>
    
<span data-ttu-id="53b80-122">[Obtenga información sobre cómo inscribirse los dispositivos de Windows en Microsoft Intune](https://docs.microsoft.com/intune/windows-enroll).</span><span class="sxs-lookup"><span data-stu-id="53b80-122">[Learn how to enroll Windows devices in Microsoft Intune](https://docs.microsoft.com/intune/windows-enroll).</span></span>
  

