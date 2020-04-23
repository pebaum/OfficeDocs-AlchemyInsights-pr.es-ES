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
ms.openlocfilehash: 87a0a2be6b222d35acbc862eed4f14fb3e3e36ac
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43764170"
---
# <a name="suggestions-for-solving-unlicensed-product-errors"></a>Sugerencias para solucionar errores de "producto sin licencia"

Para solucionar errores relacionados con un "producto sin licencia", pruebe lo siguiente:

- Compruebe si el estado de la suscripción ha expirado.
- Asegúrese de que tiene una suscripción que permita licencias de cliente, como Microsoft 365 apps for Business o Business Premium, y [Asegúrese de que el usuario tenga una licencia asignada](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users). 
- Asegúrese de que el usuario inicia sesión en Office con la misma cuenta que tiene asignada la licencia.
- Consulte la [Página estado del servicio](https://docs.microsoft.com/office365/enterprise/view-service-health) para ver si hay problemas conocidos con el servicio.
- Compruebe el firewall, el software antivirus y la configuración de proxy para confirmar que no están bloqueando el acceso de las aplicaciones de Office a Internet. Consulte [direcciones URL e intervalos de direcciones IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).

También puede probar las siguientes acciones de solución de problemas: 

- Abra una aplicación de Office y [cierre la sesión](https://support.office.com/article/5a20dc11-47e9-4b6f-945d-478cb6d92071) de las cuentas de usuario existentes. [Quite](https://docs.microsoft.com/office365/admin/manage/remove-licenses-from-users) y [vuelva a asignar](https://docs.microsoft.com/office365/admin/manage/assign-licenses-to-users) la licencia de Office y, a continuación, [inicie sesión en Office](https://support.office.com/article/628ea040-f265-49de-b986-be09c3ebf8a9) con la cuenta de usuario afectada.
- Ejecute el [solucionador de problemas de activación](https://aka.ms/SARA-OfficeActivation-Alchemy).
- [Restablezca el estado de activación de Office](https://docs.microsoft.com/office365/troubleshoot/activation/reset-office-365-proplus-activation-state). 
- [Realizar una reparación en línea de Office](https://support.office.com/Article/7821d4b6-7c1d-4205-aa0e-a6b40c5bb88b).

Para ver más medidas de solución de problemas, vea: 

- [Errores de activación y de producto sin licencia en Office](https://support.office.com/Article/0d23d3c0-c19c-4b2f-9845-5344fedc4380)
- [Error "Lo sentimos, no podemos conectarnos con su cuenta. Inténtelo de nuevo más tarde" al activar Office](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365)