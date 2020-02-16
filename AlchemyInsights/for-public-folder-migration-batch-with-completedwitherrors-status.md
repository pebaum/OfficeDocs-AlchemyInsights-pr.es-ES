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
# <a name="for-public-folder-migration-batch-with-completedwitherrors-status"></a>Para el lote de migración de carpetas públicas con estado CompletedWithErrors

Siga estos pasos para completar el lote y omitir los elementos incorrectos o grandes: 
1. Aprobar los elementos omitidos en el lote de migración:

    Set-MigrationBatch \<batchname>-ApproveSkippedItems 
2. Use el siguiente comando para aprobar los elementos omitidos en las solicitudes de migración que se han "sincronizado" pero que no se han completado:

    $pf = Get-PublicFolderMailboxMigrationRequest | Get-PublicFolderMailboxMigrationRequestStatistics-IncludeReport; ForEach ($i en $pf) {if ($i. LargeItemsEncountered-gt 0-o $i. BadItemsEncountered-gt 0) {set-PublicFolderMailboxMigrationRequest $i. Identity. IdentifyingGuid-SkippedItemApprovalTime $ ([DateTime]:: UtcNow)}}
3. El lote de migración y las solicitudes deben reanudarse y completarse en unos minutos.

