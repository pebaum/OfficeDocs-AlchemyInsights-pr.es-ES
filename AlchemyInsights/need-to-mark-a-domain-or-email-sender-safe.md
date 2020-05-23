---
title: ¿Necesita marcar un dominio o remitente de correo electrónico como seguro?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002921"
- "5673"
ms.openlocfilehash: 7dc1576fd61e87b319c7486c59ed125943b4d959
ms.sourcegitcommit: 43acdecef129bfffc8bbe8ebb08fdd581b238a03
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 05/18/2020
ms.locfileid: "44281188"
---
# <a name="need-to-mark-a-domain-or-email-sender-safe"></a>¿Necesita marcar un dominio o remitente de correo electrónico como seguro?

- No se recomienda el uso de **listas de remitentes seguros** ya que expone su organización a ataques de spam, phishing y suplantación de identidad.
- Sin embargo, si hay un requisito empresarial, **recomendamos** usar **[Reglas de flujo de correo](https://docs.microsoft.com/microsoft-365/security/office-365-security/create-safe-sender-lists-in-office-365?view=o365-worldwide#recommended-use-mail-flow-rules)** para esto. Nuestra guía garantiza la autenticación del remitente (comprueba que el dominio remitente no está falsificado). **Nota**: no recomendamos administrar los falsos positivos con las listas de remitentes seguros, ya que las excepciones al filtrado de correo no deseado pueden exponer la organización a ataques de seguridad. Si los usuarios reciben mensajes que se marcan incorrectamente como spam o correo electrónico no deseado, puede **[Informar de los mensajes y archivos a Microsoft](https://protection.office.com/reportsubmission)**.
- **Deberían evitarse** los remitentes seguros en Outlook, la lista de remitentes permitidos o la lista de dominios permitidos en las directivas antispam porque los remitentes omiten toda la protección contra correo no deseado, suplantación de identidad, protección contra phishing y autenticación de remitente (SPF, DKIM, DMARC). Este método es más adecuado solo para las pruebas temporales.
