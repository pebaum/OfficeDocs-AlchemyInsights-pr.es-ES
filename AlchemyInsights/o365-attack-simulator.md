---
title: Simulador de ataque de 2681 en Microsoft 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2681"
ms.assetid: ''
ms.openlocfilehash: 74bd2dd62b24aaf6c9d7b387ab1d97ddab31e902
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43713483"
---
# <a name="attack-simulator-in-microsoft-365"></a><span data-ttu-id="0b4bb-102">Simulador de ataques en Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="0b4bb-102">Attack Simulator in Microsoft 365</span></span>

- <span data-ttu-id="0b4bb-103">¿Falta el simulador de ataque?</span><span class="sxs-lookup"><span data-stu-id="0b4bb-103">Are you missing Attack Simulator?</span></span> <span data-ttu-id="0b4bb-104">El simulador de ataque requiere el **plan 2 de la protección contra amenazas avanzada de office 365 (ATP plan 2)** u **Office 365 Enterprise E5**.</span><span class="sxs-lookup"><span data-stu-id="0b4bb-104">Attack Simulator requires **Office 365 Advanced Threat Protection Plan 2 (ATP Plan 2)** or **Office 365 Enterprise E5**.</span></span> <span data-ttu-id="0b4bb-105">El simulador de ataque **no** se incluye en el plan 1 de la protección contra amenazas avanzada de Office 365 (ATP plan 1), Office 365 Enterprise E3 o cualquier suscripción a Microsoft 365 para empresas.</span><span class="sxs-lookup"><span data-stu-id="0b4bb-105">Attack Simulator is **not** included in Office 365 Advanced Threat Protection Plan 1 (ATP Plan 1), Office 365 Enterprise E3, or any Microsoft 365 Apps for business subscriptions.</span></span>

- <span data-ttu-id="0b4bb-106">La cuenta que use para iniciar ataques simulados requiere permisos de administrador global o de administrador de seguridad y autenticación multifactor (MFA).</span><span class="sxs-lookup"><span data-stu-id="0b4bb-106">The account you use to launch simulated attacks requires global administrator or security administrator permissions and multi-factor authentication (MFA).</span></span> <span data-ttu-id="0b4bb-107">Para obtener más información acerca de los requisitos de los simuladores de ataques, vea [este tema](https://docs.microsoft.com/office365/securitycompliance/attack-simulator#before-you-begin).</span><span class="sxs-lookup"><span data-stu-id="0b4bb-107">For more information about Attack Simulator requirements, see [this topic](https://docs.microsoft.com/office365/securitycompliance/attack-simulator#before-you-begin).</span></span>

- <span data-ttu-id="0b4bb-108">Aspectos importantes que debe conocer sobre las simulaciones de ataque de **fuerza de contraseña** :</span><span class="sxs-lookup"><span data-stu-id="0b4bb-108">Important things to know about **Brute Force Password** attack simulations:</span></span>

  - <span data-ttu-id="0b4bb-109">Si la cuenta de destino tiene MFA habilitado y la contraseña se ha adivinado correctamente, la cuenta no se mostrará como comprometida (el segundo factor de autenticación será incompleto).</span><span class="sxs-lookup"><span data-stu-id="0b4bb-109">If the target account has MFA enabled and the password was guessed correctly, the account will not show as compromised (the second authentication factor will be incomplete).</span></span>

  - <span data-ttu-id="0b4bb-110">El archivo de contraseña no puede tener más de 10 MB.</span><span class="sxs-lookup"><span data-stu-id="0b4bb-110">The password file can't be larger than 10 MB.</span></span> <span data-ttu-id="0b4bb-111">Use una contraseña por línea e incluya una línea en blanco (retorno de carro) después de la última contraseña de la lista.</span><span class="sxs-lookup"><span data-stu-id="0b4bb-111">Use one password per line, and include a blank line (carriage return) after the last password in the list.</span></span>

- <span data-ttu-id="0b4bb-112">Aspectos importantes que debe conocer sobre las simulaciones de conexión de **"Spear phishing"** :</span><span class="sxs-lookup"><span data-stu-id="0b4bb-112">Important things to know about **Spear Phishing** attach simulations:</span></span>

  - <span data-ttu-id="0b4bb-113">Por diseño, no puede proporcionar un valor personalizado para la **dirección URL del servidor de inicio de sesión de suplantación de identidad**.</span><span class="sxs-lookup"><span data-stu-id="0b4bb-113">By design, you can't provide a custom value for **Phishing login server URL**.</span></span>

  - <span data-ttu-id="0b4bb-114">Si un destinatario usa el [complemento habilitar el mensaje de informe](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) para informar del mensaje como suplantación de identidad (phishing), es posible que no reciba alertas del mensaje (ya que se trata de un ataque simulado).</span><span class="sxs-lookup"><span data-stu-id="0b4bb-114">If a recipient uses the [Enable the Report Message add-in](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) to report the message as phishing, you might not receive alerts for the message (because this is a simulated attack).</span></span>

- <span data-ttu-id="0b4bb-115">Informes: una vez completado el ataque simulado, puede hacer clic en detalles de los **ataques** para ver el informe.</span><span class="sxs-lookup"><span data-stu-id="0b4bb-115">Reports: After the simulated attack is complete, you can click **Attack Details** to see the report.</span></span>

- <span data-ttu-id="0b4bb-116">Para obtener instrucciones detalladas y nuevas características en el simulador de ataques, consulte [simulador de ataques en Microsoft 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).</span><span class="sxs-lookup"><span data-stu-id="0b4bb-116">For detailed instructions and new features in Attack Simulator, see [Attack Simulator in Microsoft 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).</span></span>
