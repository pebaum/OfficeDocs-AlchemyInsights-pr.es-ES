---
title: 2491 mensajes de correo electrónico de alerta de la Directiva "phish entregado debido a inquilino o usuario reemplazado"
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 2491
ms.assetid: ''
ms.openlocfilehash: 456b186ecea59422c791c79d4df056ad8446bc70
ms.sourcegitcommit: 7c90dcc570d32ebd968e3e4e816a7b482890b3a4
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 08/13/2019
ms.locfileid: "36391548"
---
# <a name="alert-email-messages-from-the-phish-delivered-due-to-tenant-or-user-override-policy"></a><span data-ttu-id="0b19c-102">Mensajes de correo electrónico de alerta de la Directiva "phish entregado debido a inquilino o usuario reemplazado"</span><span class="sxs-lookup"><span data-stu-id="0b19c-102">Alert email messages from the 'Phish Delivered due to tenant or user override' policy</span></span>

<span data-ttu-id="0b19c-103">Se ha realizado una directiva de alerta predeterminada denominada "phish entregado debido a inquilino o usuario reemplazado" a los inquilinos con Office 365 ATP P1 y las licencias P2.</span><span class="sxs-lookup"><span data-stu-id="0b19c-103">A default alert policy named "Phish Delivered due to tenant or user override" has been rolled out to tenants with Office 365 ATP P1 and P2 licenses.</span></span> <span data-ttu-id="0b19c-104">Si recibió esta alerta, estos son los pasos para investigar:</span><span class="sxs-lookup"><span data-stu-id="0b19c-104">If you received this alert, here are the steps to investigate:</span></span>

1. <span data-ttu-id="0b19c-105">En el mensaje de alerta, haga clic en **Ver alerta** para ir a la página **alertas** en el centro de seguridad & cumplimiento.</span><span class="sxs-lookup"><span data-stu-id="0b19c-105">From the alert message, click **View Alert** to go to the **Alerts** page in the Security & Compliance Center.</span></span>

2. <span data-ttu-id="0b19c-106">Seleccione la alerta para ver la opción de **ver la lista de mensajes** o **ver los mensajes en el explorador**.</span><span class="sxs-lookup"><span data-stu-id="0b19c-106">Select the alert to see the option to **View message list** or **View messages in Explorer**.</span></span> <span data-ttu-id="0b19c-107">Ambas opciones le ofrecen los detalles del mensaje, que incluye el identificador del mensaje.</span><span class="sxs-lookup"><span data-stu-id="0b19c-107">Both of these options take you to the details of the message, which includes the Message ID.</span></span> <span data-ttu-id="0b19c-108">Tenga en cuenta que el vínculo del explorador de amenazas filtrará automáticamente los mensajes que coinciden con los criterios de la alerta.</span><span class="sxs-lookup"><span data-stu-id="0b19c-108">Note that the Threat Explorer link will automatically filter the messages that match the alert criteria.</span></span> <span data-ttu-id="0b19c-109">Es posible que deba ajustar el filtro de fecha en el explorador de amenazas.</span><span class="sxs-lookup"><span data-stu-id="0b19c-109">You might need to adjust the date filter in Threat Explorer.</span></span>

<span data-ttu-id="0b19c-110">El mensaje de suplantación de identidad se entregó debido a un reemplazo configurado manualmente:</span><span class="sxs-lookup"><span data-stu-id="0b19c-110">The phishing message was delivered because of a manually configured override:</span></span>

- <span data-ttu-id="0b19c-111">Un remitente o dominio permitidos establecido por el usuario.</span><span class="sxs-lookup"><span data-stu-id="0b19c-111">An allowed sender or domain set by the user.</span></span>

- <span data-ttu-id="0b19c-112">Un remitente o dominio permitidos establecido por el administrador en una directiva contra correo no deseado.</span><span class="sxs-lookup"><span data-stu-id="0b19c-112">An allowed sender or domain set by the admin in an anti-spam policy.</span></span>

- <span data-ttu-id="0b19c-113">Una dirección IP permitida en una directiva de filtro de conexión.</span><span class="sxs-lookup"><span data-stu-id="0b19c-113">An allowed IP address in a connection filter policy.</span></span>

- <span data-ttu-id="0b19c-114">Una regla de flujo de correo (también denominada regla de transporte) que está configurada para permitir mensajes en.</span><span class="sxs-lookup"><span data-stu-id="0b19c-114">A mail flow rule (also known as a transport rule) that's configured to allow messages in.</span></span>

<span data-ttu-id="0b19c-115">Si cree que el mensaje se marcó incorrectamente como phish, use el complemento de [mensajes de informe](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) de Outlook para enviar ejemplos de mensajes a Microsoft.</span><span class="sxs-lookup"><span data-stu-id="0b19c-115">If you believe the message was incorrectly marked as phish, use the Outlook [Report Message add-in](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) to submit message samples to Microsoft.</span></span>
