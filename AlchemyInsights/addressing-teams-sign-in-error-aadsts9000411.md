---
title: Solucionar el error AADSTS9000411 de inicio de sesión en Teams
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000744"
- "5689"
ms.openlocfilehash: b70f1320ea1dfa29e6fa489bd02acfcd1d92971b
ms.sourcegitcommit: 88d2918aa51f4ba10771527380c3e0db0f5a9147
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 05/20/2020
ms.locfileid: "44328808"
---
# <a name="addressing-teams-sign-in-error-aadsts9000411"></a>Solucionar el error AADSTS9000411 de inicio de sesión en Teams

Al iniciar sesión en Microsoft Teams, es posible que reciba el error siguiente: **Estamos teniendo problemas para iniciar sesión en AADSTS9000411: la solicitud no tiene el formato correcto. El parámetro "login_hint" está duplicado.**

Para solucionar este problema, asegúrese de que sus clientes de Microsoft Teams estén actualizados. Para más información sobre cómo actualizar el cliente, consulte [Actualizar Microsoft Teams](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).

Si, por algún motivo, no puede actualizar el cliente, cerrar sesión en el cliente borrará la mayoría de los datos almacenados en caché. Sin embargo, si aún tiene problemas después de cerrar sesión o iniciar sesión, salga de Teams y borre la caché de cliente haciendo lo siguiente:
1. Cierre Microsoft Teams.
2. Vaya a: %appdata%\microsoft\teams y elimine todos los archivos.
3. Vuelva a abrir Microsoft Teams.
