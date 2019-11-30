---
title: Resolución de errores de producto sin licencia
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3412"
- "9001428"
ms.openlocfilehash: 178811c81775b22676a0106283be4e516d40a95b
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/27/2019
ms.locfileid: "39628043"
---
# <a name="suggestions-for-solving-unlicensed-product-errors"></a>Sugerencias para solucionar errores de "producto sin licencia"

Para solucionar errores relacionados con un "producto sin licencia", pruebe lo siguiente:

- Compruebe si el estado de la suscripción ha expirado.
- Asegúrese de que tiene una suscripción que permita licencias de cliente, como Office 365 Business o Business Premium, y [Asegúrese de que el usuario tenga una licencia asignada](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users). 
- Asegúrese de que el usuario inicia sesión en Office con la misma cuenta que tiene asignada la licencia.
- Consulte la [Página de estado del servicio de Office 365](https://docs.microsoft.com/office365/enterprise/view-service-health) para ver si hay algún problema conocido con el servicio.
- Compruebe el firewall, el software antivirus y la configuración de proxy para confirmar que no están bloqueando el acceso de las aplicaciones de Office a Internet. Consulte [Office 365 URL e intervalos de direcciones IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).

También puede probar las siguientes acciones de solución de problemas: 

- Abra una aplicación de Office y [cierre la sesión](https://support.office.com/article/5a20dc11-47e9-4b6f-945d-478cb6d92071) de las cuentas de usuario existentes. [Quite](https://docs.microsoft.com/office365/admin/manage/remove-licenses-from-users) y [vuelva a asignar](https://docs.microsoft.com/office365/admin/manage/assign-licenses-to-users) la licencia de Office y, a continuación, [inicie sesión en Office](https://support.office.com/article/628ea040-f265-49de-b986-be09c3ebf8a9) con la cuenta de usuario afectada.
- Ejecute el [solucionador de problemas de activación](https://aka.ms/SARA-OfficeActivation-Alchemy).
- [Restablezca el estado de activación de Office](https://docs.microsoft.com/office365/troubleshoot/activation/reset-office-365-proplus-activation-state). 
- [Realizar una reparación en línea de Office](https://support.office.com/Article/7821d4b6-7c1d-4205-aa0e-a6b40c5bb88b).

Para obtener soluciones adicionales para la solución de problemas, consulte: 

- [Errores de activación y de producto sin licencia en Office](https://support.office.com/Article/0d23d3c0-c19c-4b2f-9845-5344fedc4380)
- ["Lo sentimos, no podemos conectarnos a tu cuenta. Intente de nuevo más tarde "al activar Office.](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365)