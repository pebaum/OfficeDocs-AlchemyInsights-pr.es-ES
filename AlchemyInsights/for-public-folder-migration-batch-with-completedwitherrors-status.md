---
title: Para el lote de migración de carpetas públicas con estado CompletedWithErrors
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3532"
ms.openlocfilehash: 4243cdf0170fed1eadac6560d2a04e1a861c63e5
ms.sourcegitcommit: 9aaa61d717e0fd475d2e9f0507c42aa40d073b5f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/15/2020
ms.locfileid: "42043621"
---
# <a name="for-public-folder-migration-batch-with-completedwitherrors-status"></a><span data-ttu-id="9224a-102">Para el lote de migración de carpetas públicas con estado CompletedWithErrors</span><span class="sxs-lookup"><span data-stu-id="9224a-102">For Public folder migration batch with CompletedWithErrors status</span></span>

<span data-ttu-id="9224a-103">Siga estos pasos para completar el lote y omitir los elementos incorrectos o grandes:</span><span class="sxs-lookup"><span data-stu-id="9224a-103">Use the following steps to complete the batch, skipping the large/bad items:</span></span> 
1. <span data-ttu-id="9224a-104">Aprobar los elementos omitidos en el lote de migración:</span><span class="sxs-lookup"><span data-stu-id="9224a-104">Approve the skipped items on migration batch:</span></span>

    <span data-ttu-id="9224a-105">Set-MigrationBatch \<batchname>-ApproveSkippedItems</span><span class="sxs-lookup"><span data-stu-id="9224a-105">Set-MigrationBatch \<batchname> -ApproveSkippedItems</span></span> 
2. <span data-ttu-id="9224a-106">Use el siguiente comando para aprobar los elementos omitidos en las solicitudes de migración que se han "sincronizado" pero que no se han completado:</span><span class="sxs-lookup"><span data-stu-id="9224a-106">Use the following command to approve the skipped items on migration requests that are “Synced” but not completed:</span></span>

    <span data-ttu-id="9224a-107">$pf = Get-PublicFolderMailboxMigrationRequest | Get-PublicFolderMailboxMigrationRequestStatistics-IncludeReport; ForEach ($i en $pf) {if ($i. LargeItemsEncountered-gt 0-o $i. BadItemsEncountered-gt 0) {set-PublicFolderMailboxMigrationRequest $i. Identity. IdentifyingGuid-SkippedItemApprovalTime $ ([DateTime]:: UtcNow)}}</span><span class="sxs-lookup"><span data-stu-id="9224a-107">$pf=Get-PublicFolderMailboxMigrationRequest | Get-PublicFolderMailboxMigrationRequestStatistics -IncludeReport; ForEach ($i in $pf) {if ($i.LargeItemsEncountered -gt 0 -or $i.BadItemsEncountered -gt 0) {Set-PublicFolderMailboxMigrationRequest $i.Identity.IdentifyingGuid -SkippedItemApprovalTime $([DateTime]::UtcNow)}}</span></span>
3. <span data-ttu-id="9224a-108">El lote de migración y las solicitudes deben reanudarse y completarse en unos minutos.</span><span class="sxs-lookup"><span data-stu-id="9224a-108">The migration batch and requests should resume and complete in a few minutes.</span></span>

