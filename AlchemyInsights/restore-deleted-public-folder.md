---
title: Restaurar una carpeta pública eliminada
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
- "3488"
ms.openlocfilehash: 7b04612daca61650d162c1dde240e25c1b185b04
ms.sourcegitcommit: 8ba12eff67e405f5922ea4cc35155e3036447859
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/15/2020
ms.locfileid: "42063754"
---
# <a name="restore-a-deleted-public-folder"></a>Restaurar una carpeta pública eliminada

**Para restaurar elementos eliminados de una carpeta pública**:

- Vea [no puede recuperar los elementos eliminados de una carpeta pública que no es de correo en Outlook 2016](https://aka.ms/pfrec).
 
**Para restaurar una carpeta pública eliminada (de cualquier tipo)**: 

- Use el siguiente comando de PowerShell EXO:

    Sintaxis:

    >$pf = Get-PublicFolder \ NON_IPM_SUBTREE \ DUMPSTER_ROOT-recurse |? {$_. Name-EQ "\<name_of_deleted_public_Folder"}; Set-PublicFolder $pf. Identity-path \<ruta de acceso en la que se va a restaurar la carpeta>

    Ejemplo: en el siguiente comando se restaurará Subfolder1 y se colocará en \Parent1:

    >$pf = Get-PublicFolder \ NON_IPM_SUBTREE \ DUMPSTER_ROOT-recurse |? {$_. Name-EQ "Subfolder1"}; Set-PublicFolder $pf. Identity-path \Parent1

Consulte [restaurar una carpeta pública eliminada](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) para obtener más información.
