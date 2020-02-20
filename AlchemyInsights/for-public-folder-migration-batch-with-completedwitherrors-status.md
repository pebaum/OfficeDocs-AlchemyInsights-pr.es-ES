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
# <a name="for-public-folder-migration-batch-with-completedwitherrors-status"></a>Para el lote de migración de carpetas públicas con estado CompletedWithErrors

Siga estos pasos para completar el lote y omitir los elementos incorrectos o grandes: 
1. Aprobar los elementos omitidos en el lote de migración:

    `Set-MigrationBatch \<batchname> -ApproveSkippedItems` 
2. Use el siguiente comando para aprobar los elementos omitidos en las solicitudes de migración que se han "sincronizado" pero que no se han completado:

    `$pf=Get-PublicFolderMailboxMigrationRequest | Get-PublicFolderMailboxMigrationRequestStatistics -IncludeReport; ForEach ($i in $pf) {if ($i.LargeItemsEncountered -gt 0 -or $i.BadItemsEncountered -gt 0) {Set-PublicFolderMailboxMigrationRequest $i.Identity.IdentifyingGuid -SkippedItemApprovalTime $([DateTime]::UtcNow)}}`
3. El lote de migración y las solicitudes deben reanudarse y completarse en unos minutos.

