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
ms.openlocfilehash: 739e9d91f90e4c0374814d199e4372eb5625553a
ms.sourcegitcommit: 2a9d059262c07c33f9a740b3da4e6e3366b2f925
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/20/2020
ms.locfileid: "42158639"
---
# <a name="for-public-folder-migration-batch-with-completedwitherrors-status"></a><span data-ttu-id="e4874-102">Para el lote de migración de carpetas públicas con estado CompletedWithErrors</span><span class="sxs-lookup"><span data-stu-id="e4874-102">For Public folder migration batch with CompletedWithErrors status</span></span>

<span data-ttu-id="e4874-103">Siga estos pasos para completar el lote y omitir los elementos incorrectos o grandes:</span><span class="sxs-lookup"><span data-stu-id="e4874-103">Use the following steps to complete the batch, skipping the large/bad items:</span></span> 
1. <span data-ttu-id="e4874-104">Aprobar los elementos omitidos en el lote de migración:</span><span class="sxs-lookup"><span data-stu-id="e4874-104">Approve the skipped items on migration batch:</span></span>

    `Set-MigrationBatch \<batchname> -ApproveSkippedItems` 
2. <span data-ttu-id="e4874-105">Use el siguiente comando para aprobar los elementos omitidos en las solicitudes de migración que se han "sincronizado" pero que no se han completado:</span><span class="sxs-lookup"><span data-stu-id="e4874-105">Use the following command to approve the skipped items on migration requests that are “Synced” but not completed:</span></span>

    `$pf=Get-PublicFolderMailboxMigrationRequest | Get-PublicFolderMailboxMigrationRequestStatistics -IncludeReport; ForEach ($i in $pf) {if ($i.LargeItemsEncountered -gt 0 -or $i.BadItemsEncountered -gt 0) {Set-PublicFolderMailboxMigrationRequest $i.Identity.IdentifyingGuid -SkippedItemApprovalTime $([DateTime]::UtcNow)}}`
3. <span data-ttu-id="e4874-106">El lote de migración y las solicitudes deben reanudarse y completarse en unos minutos.</span><span class="sxs-lookup"><span data-stu-id="e4874-106">The migration batch and requests should resume and complete in a few minutes.</span></span>

