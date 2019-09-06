---
title: Faltan términos en el almacén de términos de SharePoint Online
ms.author: pebaum
author: Techwriter40
ms.date: 10/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1243"
- "5200021"
ms.openlocfilehash: 0f9efe980987c9ffc64fcf9d5d72a67f0a622867
ms.sourcegitcommit: 23772ebd25a86a879ced40b10566a35e76a79eb5
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/05/2019
ms.locfileid: "36762093"
---
# <a name="enabling-bitlocker-encryption-with-intune"></a><span data-ttu-id="adbbc-102">Habilitación del cifrado de BitLocker con Intune</span><span class="sxs-lookup"><span data-stu-id="adbbc-102">Enabling Bitlocker Encryption with Intune</span></span>

<span data-ttu-id="adbbc-103">La Directiva de Intune Endpoint Protection se puede usar para establecer la configuración de cifrado de Boitlocker para dispositivos Windows como se describe en: Windows10 (y versiones posteriores) configuración para proteger dispositivos con Intune</span><span class="sxs-lookup"><span data-stu-id="adbbc-103">Intune Endpoint Protection Policy can be used to configure Boitlocker encryption settings for Windows devices as described in : Windows10 (and later) settings to protect devices using Intune</span></span>

<span data-ttu-id="adbbc-104">Debe tener en cuenta que muchos dispositivos nuevos que ejecutan Windows 10 admiten el cifrado de BitLocker automático que se desencadena sin la aplicación de la Directiva de MDM.</span><span class="sxs-lookup"><span data-stu-id="adbbc-104">You should be aware that many newer devices running Windows 10 support automatic bitlocker encryption which is triggered without the application of MDM policy.</span></span> <span data-ttu-id="adbbc-105">Esto puede afectar a la aplicación de la Directiva si se configuran las opciones no predeterminadas.</span><span class="sxs-lookup"><span data-stu-id="adbbc-105">This may impact application of policy if non default settings are configured.</span></span> <span data-ttu-id="adbbc-106">Consulte las preguntas más frecuentes para obtener más información.</span><span class="sxs-lookup"><span data-stu-id="adbbc-106">See FAQ for more detail.</span></span>


<span data-ttu-id="adbbc-107">P  + f p: ¿Qué ediciones de Windows admiten el cifrado de dispositivos con la Directiva de Endpoint Protection?</span><span class="sxs-lookup"><span data-stu-id="adbbc-107">FAQ  Q: Which editions of Windows support device encryption using the Endpoint Protection Policy?</span></span>
<span data-ttu-id="adbbc-108"> A: la configuración de la Directiva de la protección de extremos de Intune se implementa con el CSP de BitLocker.</span><span class="sxs-lookup"><span data-stu-id="adbbc-108"> A: The settings in Intune Endpoint Protection Policy  are implemented using the Bitlocker CSP.</span></span><span data-ttu-id="adbbc-109">No todas las ediciones ni las compilaciones de Windows admiten el CSP de BitLocker. 
     </span><span class="sxs-lookup"><span data-stu-id="adbbc-109">  Not all editions nor builds of Windows support the Bitlocker CSP. 
     </span></span> <span data-ttu-id="adbbc-110">En este momento, ediciones de Windows: Enterprise; Se admiten educación, móvil, Mobile Enterprise y Professional (desde la compilación 1809 en adelante).</span><span class="sxs-lookup"><span data-stu-id="adbbc-110">At this time Windows Editions: Enterprise; Education, Mobile, Mobile Enterprise and Professional (from build 1809 onwards) are supported.</span></span>




<span data-ttu-id="adbbc-111">P: Si ya se ha cifrado un dispositivo con BitLocker mediante la configuración predeterminada del sistema operativo para el método de cifrado y la seguridad de cifrado (XTS-AES-128), se aplicará una directiva con una configuración diferente para activar automáticamente el recifrado de la unidad con la nueva configuración.</span><span class="sxs-lookup"><span data-stu-id="adbbc-111">Q: If a device is already encrypted with Bitlocker using the OS default settings for encryption method and cipher strength (XTS-AES-128)  will applying a policy with different settings automatically trigger re-encryption of the drive with the new settings?</span></span>

<span data-ttu-id="adbbc-112">R: No.</span><span class="sxs-lookup"><span data-stu-id="adbbc-112">A: No.</span></span> <span data-ttu-id="adbbc-113">Para aplicar la nueva configuración de cifrado es necesario descifrar primero la unidad.</span><span class="sxs-lookup"><span data-stu-id="adbbc-113">In order to apply the new cipher settings the drive must first be decrypted.</span></span>

<span data-ttu-id="adbbc-114">Nota para que los dispositivos se inscriban con la prueba piloto automática, el cifrado automático que se produciría durante la OOBE no se desencadena hasta que se evalúe la Directiva de Intune, lo que permite usar la configuración basada en directivas en lugar de los valores predeterminados del sistema operativo</span><span class="sxs-lookup"><span data-stu-id="adbbc-114">Note For devices being enrolled with Autopilot the automatic encryption that would occur during OOBE is not triggered until Intune policy is evaluated which allows the policy based settings to be used in place of the OS defaults</span></span>




<span data-ttu-id="adbbc-115">P si un dispositivo está cifrado como resultado de la aplicación de la Directiva de Intune, ¿se descifrará cuando se elimine la Directiva?</span><span class="sxs-lookup"><span data-stu-id="adbbc-115">Q If a device is encrypted as a result of the  application of Intune policy will it be decrypted when that policy is removed?</span></span>

<span data-ttu-id="adbbc-116">A: la eliminación de la Directiva relacionada con el cifrado no produce el descifrado de las unidades configuradas.</span><span class="sxs-lookup"><span data-stu-id="adbbc-116">A: Removal of encryption related policy does NOT result in decryption of the drives which were configured.</span></span>




<span data-ttu-id="adbbc-117">P: ¿por qué la Directiva de cumplimiento de Intune muestra que el dispositivo no tiene "BitLocker habilitado", pero sí?</span><span class="sxs-lookup"><span data-stu-id="adbbc-117">Q: Why does intune Compliance policy show that my device does not have "Bitlocker Enabled" but it is?</span></span>

<span data-ttu-id="adbbc-118">A: el valor "BitLocker Enabled" de la Directiva de cumplimiento de Intune usa el cliente de atestación de estado del dispositivo Windows (DHA).</span><span class="sxs-lookup"><span data-stu-id="adbbc-118">A: The "Bitlocker enabled" setting in intune compliance policy utilizes the Windows Device Health Attestation  (DHA) client.</span></span> <span data-ttu-id="adbbc-119">Este cliente solo mide el estado del dispositivo durante el arranque.</span><span class="sxs-lookup"><span data-stu-id="adbbc-119">This client only measures device state at boot time.</span></span> <span data-ttu-id="adbbc-120">Por lo tanto, si un dispositivo no se reinició desde que se completó el cifrado de BitLocker, el servicio de cliente de DHA no informará de BitLocker como activo.</span><span class="sxs-lookup"><span data-stu-id="adbbc-120">So if a device has not been rebooted since bitlocker encryption was completed the DHA client service will not report bitlocker as being active.</span></span>