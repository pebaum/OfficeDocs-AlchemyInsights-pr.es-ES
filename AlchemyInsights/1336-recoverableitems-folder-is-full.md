---
title: Carpeta de RecoverableItems 1336 está llena
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: ee96abfa179c36ebaf43dbd327d4608b849395d3
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 01/24/2019
ms.locfileid: "29491112"
---
# <a name="the-recoverable-items-folder-is-full"></a><span data-ttu-id="e3778-102">La carpeta elementos recuperables está llena</span><span class="sxs-lookup"><span data-stu-id="e3778-102">The Recoverable Items folder is full</span></span>

<span data-ttu-id="e3778-p101">Para buzones de Exchange Online en Office 365, el límite de almacenamiento predeterminada para la carpeta elementos recuperables es de 30 GB. El límite de almacenamiento de la carpeta elementos recuperables se incrementa automáticamente a 100 GB si el buzón de correo se pondrá en suspensión por litigio, exhibición de documentos electrónicos, o que esté asignada a una directiva de retención de Office 365.</span><span class="sxs-lookup"><span data-stu-id="e3778-p101">For Exchange Online mailboxes in Office 365, the default storage limit for the Recoverable Items folder is 30 GB. The storage limit for the Recoverable Items folder is automatically increased to 100 GB if the mailbox is placed on Litigation Hold, eDiscovery hold, or is assigned to an Office 365 retention policy.</span></span>
  
<span data-ttu-id="e3778-105">Cuando la carpeta elementos recuperables alcanza el límite de almacenamiento, la funcionalidad de buzón de correo se ve afectada de las siguientes maneras:</span><span class="sxs-lookup"><span data-stu-id="e3778-105">When the Recoverable Items folder reaches the storage limit, mailbox functionality is affected in the following ways:</span></span>
  
- <span data-ttu-id="e3778-106">El usuario no puede eliminar elementos del buzón de correo.</span><span class="sxs-lookup"><span data-stu-id="e3778-106">The user can't delete items from the mailbox.</span></span>
    
- <span data-ttu-id="e3778-107">El asistente para carpetas administradas no puede eliminar elementos basados en la etiqueta de retención o en la configuración de carpetas administradas.</span><span class="sxs-lookup"><span data-stu-id="e3778-107">The Managed Folder Assistant can't delete items based on retention tag or managed folder settings.</span></span>
    
- <span data-ttu-id="e3778-108">Para los buzones de correo que tienen la recuperación de elemento único habilitada o se colocan en espera, el proceso de protección de la página de copia en escritura no puede mantener las versiones de los elementos modificadas por el usuario.</span><span class="sxs-lookup"><span data-stu-id="e3778-108">For mailboxes that have Single Item Recovery enabled or are placed on hold, the copy-on-write page protection process can't maintain versions of items edited by the user.</span></span>
    
- <span data-ttu-id="e3778-109">Para los buzones que tienen el buzón habilitado el registro de auditoría, no hay entradas de registro de auditoría de buzón pueden guardarse en la subcarpeta de auditorías en la carpeta elementos recuperables.</span><span class="sxs-lookup"><span data-stu-id="e3778-109">For mailboxes that have mailbox audit logging enabled, no mailbox audit log entries can be saved in the Audits subfolder in the Recoverable Items folder.</span></span>
    
<span data-ttu-id="e3778-p102">Para los buzones que no están en espera, los administradores pueden utilizar el `Search-Mailbox -SearchDumpsterOnly -DeleteContent` comando en Exchange Online PowerShell para eliminar elementos de la carpeta elementos recuperables. Para obtener más información, vea los temas siguientes:</span><span class="sxs-lookup"><span data-stu-id="e3778-p102">For mailboxes that aren't on hold, admins can use the  `Search-Mailbox -SearchDumpsterOnly -DeleteContent` command in Exchange Online PowerShell to delete items in the Recoverable Items folder. For more information, see the following topics:</span></span> 
  
- [<span data-ttu-id="e3778-112">Búsqueda y eliminación de mensajes</span><span class="sxs-lookup"><span data-stu-id="e3778-112">Search for and delete messages</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-for-and-delete-messagesadmin-help)
    
- [<span data-ttu-id="e3778-113">Search-Mailbox</span><span class="sxs-lookup"><span data-stu-id="e3778-113">Search-Mailbox</span></span>](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)
    
<span data-ttu-id="e3778-p103">Para los buzones de correo que están en espera, los administradores tienen que quitar la suspensión antes de que los elementos eliminados de la carpeta elementos recuperables. Para obtener más información, vea [Eliminar elementos en la carpeta de buzones de correo basados en la nube en retención de elementos recuperables](https://docs.microsoft.com/en-us/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="e3778-p103">For mailboxes that are on hold, admins have to remove the hold before they can deleted items from the Recoverable Items folder. For more information, see [Delete items in the Recoverable Items folder of cloud-based mailboxes on hold](https://docs.microsoft.com/en-us/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span></span>
  
<span data-ttu-id="e3778-p104">Para ayudar a evitar que la carpeta elementos recuperables completa, los administradores pueden aumentar el límite de almacenamiento de los elementos recuperables de carpeta para los buzones de correo en suspensión y configurar una directiva de retención de buzón de correo que mueve los elementos de la carpeta elementos recuperables para el archivo del usuario buzón de correo. Vea [aumentar la cuota de buzones de correo en suspensión de elementos recuperables](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="e3778-p104">To help prevent the Recoverable Items folder from becoming full, admins can increase the storage limit of the Recoverable Items folder for mailboxes on hold and set up a mailbox retention policy that moves items from the Recoverable Items folder to the user's archive mailbox. See [Increase the Recoverable Items quota for mailboxes on hold](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span></span>
  

