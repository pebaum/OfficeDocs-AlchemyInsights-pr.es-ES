---
title: Problemas comunes de Teams para los clientes de educación
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000701"
- "3831"
- "3832"
ms.openlocfilehash: d61d4484c720db51e7377201067008192940d1f8
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/22/2020
ms.locfileid: "43739453"
---
# <a name="teams-common-issues-for-education-customers"></a>Problemas comunes de Teams para los clientes de educación

**Para los clientes de educación:**

Si necesita ayuda para que Teams admita la formación remota, visite el [Centro de FastTrack](https://www.microsoft.com/fasttrack) para enviar una solicitud. Vea los siguientes problemas comunes para los clientes de educación de Teams:

- Se muestra el mensaje "**Se está perdiendo muchas cosas**"? asegúrese de [Habilitar Microsoft Teams para su escuela](https://docs.microsoft.com/microsoft-365/education/intune-edu-trial/enable-microsoft-teams). En los inquilinos de EDU, Microsoft Teams no está habilitado por defecto; tendrá que activarlo primero.

- **¿Es nuevo en Teams?** Revise [Formación y aprendizaje remotos en Office 365 Educación](https://support.office.com/article/remote-teaching-and-learning-in-office-365-education-f651ccae-7b65-478b-8366-51bb884025c4) para obtener la información más reciente sobre cómo configurar el centro educativo, la planificación de lecciones, las reuniones virtuales y cómo compartir contenido con los alumnos.

- Una vez que esté activado, los usuarios podrán ejecutar Teams, instalando clientes de [escritorio](https://docs.microsoft.com/MicrosoftTeams/get-clients#desktop-client) o [móviles](https://docs.microsoft.com/MicrosoftTeams/get-clients#mobile-clients), o desde el explorador en https://teams.microsoft.com.

- **Habilitar el acceso de invitados a Teams**: revise la [lista de comprobación de acceso para invitados de Teams](https://docs.microsoft.com/microsoftteams/guest-access-checklist) y asegúrese de que se han completado todos los pasos.
    - [Comprender el acceso de invitado de Microsoft Teams](https://docs.microsoft.com/microsoftteams/guest-access)
    - [Configuración de la lista de comprobación para el acceso de invitado de Microsoft Teams](https://docs.microsoft.com/microsoftteams/guest-access-checklist)
    - [Cómo se une un invitado a un Equipo](https://docs.microsoft.com/microsoftteams/guest-joins)

- **Llamadas y reuniones en Teams**: ¿Necesita ayuda para activar o configurar las audioconferencias en Microsoft Teams? ¿Se ha creado este usuario recientemente? Si es así, tendrá que esperar entre 2 y 24 horas para que la configuración se aplique. Para comprobar que el usuario tiene licencia para las audioconferencias y un número de pago predeterminado:
    1. Vaya a Usuarios activos y seleccione el usuario en cuestión.
    2. Según la versión del centro de administración, elija **Licencias y aplicaciones** o haga clic en **Editar**, en **Licencias de producto**.
    3. Confirme que el usuario tiene licencias seleccionadas para Audioconferencia, Microsoft Teams y Skype Empresarial Online (Plan 2).
    4. En el Centro de administración de usuario haga clic en **Mostrar todo** y, después, **Teams**.
    5. En el Centro de administración de Microsoft Teams, haga clic en **Portal heredado**.
    6. En el Centro de administración de Skype Empresarial, haga clic en **Audioconferencia** y luego en **Usuarios**.
    7. Seleccione el usuario en cuestión y compruebe que tiene un número de teléfono de pago predeterminado.

    Para obtener más información, consulte [Planes de llamadas](https://docs.microsoft.com/microsoftteams/calling-plans-for-office-365) o llame al Equipo de facturación comercial de Microsoft Commerce para preguntas relacionadas con las licencias.

    Recursos adicionales

    - [Reuniones y conferencias en Microsoft Teams](https://docs.microsoft.com/microsoftteams/deploy-meetings-microsoft-teams-landing-page)
    - [Audioconferencia](https://docs.microsoft.com/microsoftteams/audio-conferencing-in-office-365)

- **Directivas de reunión**: las directivas de reunión se usan para controlar las características disponibles para sus participantes para reuniones programadas por usuarios de la organización. Cuando cree una directiva y realice los cambios, puede asignar usuarios a la directiva.

    - **Cambiar o crear una directiva de reunión**: para cambiar o crear una directiva de reunión, vaya al **Centro de administración de Microsoft Teams > Reuniones > Directivas de reunión**. Seleccione una directiva de la lista o haga clic en **Agregar**. Si va a crear una nueva directiva, agregue un nombre y una descripción. El nombre no puede contener caracteres especiales ni tener más de 64 caracteres. Elija la configuración y, después, haga clic en **Guardar**. 
    
        Por ejemplo, supongamos que tiene un grupo de usuarios y quiere limitar el ancho de banda que necesitaría la reunión. Cree una nueva directiva personalizada denominada "ancho de banda limitado" y deshabilite las opciones siguientes:

        En **Audio y vídeo**:
        - Desactive **Permitir la grabación en la nube**.
        - Desactive **Permitir vídeo IP**.

        En **Uso compartido de contenido**:

        - Desactive el modo de uso compartido de la pantalla.
        - Desactive **Permitir pizarra**.
        - Desactive **Permitir notas compartidas**.

        Luego **asigne la directiva a los usuarios**:

    1. En el panel de navegación izquierdo del centro de administración de Microsoft Teams, vaya a **Usuarios** y, después, haga clic en el usuario.
    2. Para seleccionar el usuario, haga clic a la izquierda del nombre de usuario y, después, en **Editar configuración**.
    3. En **Directiva de reunión**, seleccione la directiva que quiera asignar y haga clic en **Aplicar**.

    Para asignar una directiva a varios usuarios a la vez, vea [Modificar la configuración de usuario de Teams en masa](https://docs.microsoft.com/microsoftteams/edit-user-settings-in-bulk).

    Puede hacer lo siguiente:
    1. En el panel de navegación izquierdo del centro de administración de Microsoft Teams, vaya a **Reuniones > Directivas de reunión**.
    2. Haga clic a la izquierda del nombre de la directiva para seleccionarla.
    3. Haga clic en **Administrar usuarios**.
    4. En el panel **Administrar usuarios**, busque el usuario por nombre para mostrar o por nombre de usuario, seleccione el nombre y, después, haga clic en **Agregar**. Repita este paso por cada usuario que quiera agregar.
    5. Cuando termine de agregar usuarios, haga clic en **Guardar**.

- **Solución de problemas de un teclado de marcado ausente:**
    - Asegúrese de que el usuario tiene una [licencia de Teams](https://docs.microsoft.com/MicrosoftTeams/assign-teams-licenses) asignada.
    - Asegúrese de que el usuario tiene un [Plan de llamadas](https://docs.microsoft.com/MicrosoftTeams/calling-plan-landing-page) asignado.
    - Habilite a los usuarios para [Telefonía IP empresarial](https://docs.microsoft.com/skypeforbusiness/skype-for-business-hybrid-solutions/plan-your-phone-system-cloud-pbx-solution/enable-users-for-enterprise-voice-online-and-phone-system-voicemail#to-enable-your-users-for-phone-system-in-office-365-voice-and-voicemail).

- **Solución de problemas de inicio de sesión en Teams:** en primer lugar, asegúrese de que el [Servicio de Microsoft Teams está en buen estado](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/servicehealth). Después, compruebe si hay códigos de error comunes y revise [¿Por qué tengo problemas para iniciar sesión en Microsoft Teams?](https://support.office.com/article/a02f683b-61a3-4008-9447-ee60c5593b0f) Es posible que también tenga que revisar [Modelos de identidad y autenticación en Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/identify-models-authentication).
