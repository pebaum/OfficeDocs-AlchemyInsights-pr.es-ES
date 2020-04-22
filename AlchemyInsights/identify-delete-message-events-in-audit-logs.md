---
title: Identificar eventos de eliminación de mensajes en registros de auditoría
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1370"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 797a4b1146862faf91d2b9e8d74feade90f71650
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716513"
---
# <a name="audit-logs-for-deleted-email-messages"></a><span data-ttu-id="7ee87-102">Registros de auditoría para mensajes de correo electrónico eliminados</span><span class="sxs-lookup"><span data-stu-id="7ee87-102">Audit logs for deleted email messages</span></span>

<span data-ttu-id="7ee87-103">A partir de enero 2019, Microsoft activa el registro de auditoría de buzones de correo de forma predeterminada.</span><span class="sxs-lookup"><span data-stu-id="7ee87-103">Starting in January 2019, Microsoft is turning on mailbox audit logging by default.</span></span> <span data-ttu-id="7ee87-104">De lo contrario, para revisar los eventos eliminar mensaje para un usuario específico, debe habilitar manualmente las acciones de eliminación para auditar.</span><span class="sxs-lookup"><span data-stu-id="7ee87-104">Otherwise, to review delete message events for a specific user, you need to manually enable the delete actions for auditing.</span></span> <span data-ttu-id="7ee87-105">Si el registro de auditoría de buzones de correo ya está habilitado para su organización o para el usuario específico, siga los pasos que se indican a continuación.</span><span class="sxs-lookup"><span data-stu-id="7ee87-105">If mailbox audit logging is already enabled for your organization or for the specific user, follow the steps below.</span></span>

1. <span data-ttu-id="7ee87-106">Inicie sesión en el [centro de cumplimiento de & de seguridad de Microsoft 365](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="7ee87-106">Log in to the [Microsoft 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="7ee87-107">Haga clic en **búsqueda e investigación** y seleccione **búsqueda de registros de auditoría**.</span><span class="sxs-lookup"><span data-stu-id="7ee87-107">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

3. <span data-ttu-id="7ee87-108">Seleccione el intervalo de fechas en los campos **fecha de inicio** y **fecha de finalización** .</span><span class="sxs-lookup"><span data-stu-id="7ee87-108">Select the date range in the **Start date** and **End date** fields.</span></span> <span data-ttu-id="7ee87-109">Especifique el nombre de usuario del usuario que desea investigar (el usuario que eliminó los elementos).</span><span class="sxs-lookup"><span data-stu-id="7ee87-109">Specify username for the user that you want to investigate (the user who deleted the items).</span></span> <span data-ttu-id="7ee87-110">En el campo **actividades** , seleccione **mensajes eliminados de la carpeta elementos eliminados** y **mensajes movidos a la carpeta elementos eliminados**.</span><span class="sxs-lookup"><span data-stu-id="7ee87-110">In the **Activities** field, select **Deleted messages from Deleted Items folder** and **Moved messages to Deleted Items folder**.</span></span>

4. <span data-ttu-id="7ee87-111">Haga clic en **Buscar**.</span><span class="sxs-lookup"><span data-stu-id="7ee87-111">Click **Search**.</span></span>

<span data-ttu-id="7ee87-112">En los resultados, seleccione un registro de auditoría.</span><span class="sxs-lookup"><span data-stu-id="7ee87-112">In the results, select an audit record.</span></span> <span data-ttu-id="7ee87-113">En el control flotante de detalles, haga clic en **más información**.</span><span class="sxs-lookup"><span data-stu-id="7ee87-113">In the details flyout, click **More Information**.</span></span> <span data-ttu-id="7ee87-114">La información adicional sobre el elemento eliminado (por ejemplo, la línea de asunto y la ubicación del elemento cuando se eliminó) se muestra en el campo **AffectedItems** .</span><span class="sxs-lookup"><span data-stu-id="7ee87-114">Additional information about the deleted item (for example, the subject line and the location of the item when it was deleted) is displayed in the **AffectedItems** field.</span></span> <span data-ttu-id="7ee87-115">La propiedad **ClientInfoString** se mostrará si la eliminación se produjo en Outlook, en Outlook en la web (anteriormente conocido como Outlook Web App) o en cualquier otro dispositivo.</span><span class="sxs-lookup"><span data-stu-id="7ee87-115">The **ClientInfoString** property will show if the deletion occurred in Outlook, Outlook on the web (formerly known as Outlook Web App), or any other device.</span></span>

<span data-ttu-id="7ee87-116">Para obtener más información, vea [determinar quién ha configurado el reenvío de correo para un buzón](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-deleted-email-items).</span><span class="sxs-lookup"><span data-stu-id="7ee87-116">For more information, see [Determining who set up email forwarding for a mailbox](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-deleted-email-items).</span></span>

<span data-ttu-id="7ee87-117">**Nota**: no puede recuperar elementos eliminados con la característica de registro de auditoría.</span><span class="sxs-lookup"><span data-stu-id="7ee87-117">**Note**: You can't retrieve deleted items using the audit log feature.</span></span> <span data-ttu-id="7ee87-118">Para recuperar los mensajes eliminados en Outlook en la web, vea [recuperar elementos eliminados en Outlook Web App](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).</span><span class="sxs-lookup"><span data-stu-id="7ee87-118">To retrieve deleted messages in Outlook on the web, see [Recover deleted items in Outlook Web App](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).</span></span>
