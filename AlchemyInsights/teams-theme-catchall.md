---
title: Tema general de Teams
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "2605"
- "9000701"
ms.openlocfilehash: 47e9aa76f8624ce3ddf4cfd03637b5b2714eb435
ms.sourcegitcommit: d02e2b73aa7d0453d7baca1ea5a186cf6081d022
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 03/27/2020
ms.locfileid: "43030417"
---
# <a name="teams-common-issues-and-resolutions"></a>Problemas conocidos y resolución de Teams

**Importante**: debido al reciente aumento en el uso de los Teams, cuando asigne una licencia de Teams a un usuario, es posible que tarde 24 horas antes de que se configure completamente. Si no lo hace, no podrá asignarlas a las directivas de Teams, y es posible que no tengan acceso a algunas de las características de Teams como las conferencias de audio y llamadas.

**Problemas comunes y soluciones**

Para obtener una respuesta más específica, pruebe a volver a formular la pregunta para incluir los errores que vea o las características de Teams que está usando.

Si necesita ayuda para implementar Teams para admitir a los trabajadores remotos (WFH) debido a COVID-19, consulte [soporte técnico para trabajadores remotos con Microsoft Teams](https://docs.microsoft.com/microsoftteams/support-remote-work-with-teams). También puede optar para la ayuda de implementación del programa Microsoft 365 FastTrack; visite el [Centro de FastTrack](https://www.microsoft.com/fasttrack) para enviar una solicitud.

Para todos los clientes de Teams:

- **¿Es nuevo en Teams?** Consulte [Introducción a Microsoft Teams](https://docs.microsoft.com/microsoftteams/get-started-with-teams-quick-start).
- **Habilite el acceso de invitados a Teams:** revise la [lista de comprobación de acceso para invitados de Teams](https://docs.microsoft.com/microsoftteams/guest-access-checklist) y asegúrese de que se han completado todos los pasos. Recursos adicionales:
    - [Comprender el acceso de invitado de Microsoft Teams](https://docs.microsoft.com/microsoftteams/guest-access)
    - [Configuración de la lista de comprobación para el acceso de invitado de Microsoft Teams](https://docs.microsoft.com/microsoftteams/guest-access-checklist)
    - [Cómo se une un invitado a un Equipo](https://docs.microsoft.com/microsoftteams/guest-joins)

- **Llamadas y reuniones en Teams**: ¿Necesita ayuda para activar o configurar las audioconferencias en Microsoft Teams? ¿Se ha creado este usuario recientemente? Si es así, tendrá que esperar entre 2 y 24 horas **para que la configuración se aplique**. 

    Para comprobar que el usuario tiene licencia para las audioconferencias y un número de pago predeterminado:
    1.    Vaya a Usuarios activos y seleccione el usuario en cuestión.
    2.    Según la versión del centro de administración, elija **Licencias y aplicaciones** o haga clic en **Editar**, en **Licencias de producto**.
    3.    Confirme que el usuario tiene licencias seleccionadas para Audioconferencia, Microsoft Teams y Skype Empresarial Online (Plan 2).
    4.    En el Centro de administración de usuario haga clic en **Mostrar todo** y, después, **Teams**.
    5.    En el Centro de administración de Microsoft Teams, haga clic en **Portal heredado**.
    6.    En el Centro de administración de Skype Empresarial, haga clic en **Audioconferencia** y luego en **Usuarios**.
    7.    Seleccione el usuario en cuestión y compruebe que tiene un número de teléfono de pago predeterminado.
    
    Para obtener más información, consulte [Planes de llamadas para Office 365](https://docs.microsoft.com/microsoftteams/calling-plans-for-office-365) o llame al Equipo de facturación comercial de Microsoft Commerce para preguntas relacionadas con las licencias.

    Recursos adicionales:

    - [Reuniones y conferencias en Microsoft Teams](https://docs.microsoft.com/microsoftteams/deploy-meetings-microsoft-teams-landing-page)
    - [Audioconferencia en Office 365](https://docs.microsoft.com/microsoftteams/audio-conferencing-in-office-365)

- **La licencia exploratoria de Microsoft Teams**: permite a los usuarios de su organización que tienen Azure Active Directory (AAD) y a los que no tienen licencia para Teams activar una experiencia exploratoria de Teams Los administradores pueden activar o desactivar esta característica para los usuarios de su organización. La anterior [oferta de prueba comercial en la nube de Microsoft](https://docs.microsoft.com/microsoftteams/iw-trial-teams) se ha reemplazado por la experiencia exploratoria de Teams.

    Recursos adicionales:

    - [¿Cómo pueden los usuarios inscribirse en la experiencia exploratoria de Teams?](https://docs.microsoft.com/microsoftteams/teams-exploratory#how-users-sign-up-for-the-teams-exploratory-experience)
    - [Administrar la experiencia exploratoria de Teams](https://docs.microsoft.com/microsoftteams/teams-exploratory#manage-the-teams-exploratory-experience)

- **Canales privados**: los canales privados de Microsoft Teams crean espacios prioritarios para la colaboración con los equipos. Solo los usuarios del equipo que sean propietarios o miembros del canal privado podrán acceder al canal. Cualquier persona, incluidos los invitados, puede agregarse como miembro de un canal privado siempre y cuando ya sean miembros del equipo.

    Un canal privado puede ser útil para limitar la colaboración a solo aquellos usuarios que necesitan conocer una información o para facilitar la comunicación entre un grupo de personas asignadas a un proyecto específico, sin tener que crear un equipo adicional para administrar.

    Recursos adicionales:
    - [Creación y suscripción de canales privados](https://docs.microsoft.com/microsoftteams/private-channels#private-channel-creation-and-membership)
    - [Administrar la pertenencia y la configuración de canales privados](https://docs.microsoft.com/microsoftteams/private-channels#manage-private-channel-membership-and-settings)

- **Directivas de reunión**: las directivas de reunión se usan para controlar las características disponibles para sus participantes en reuniones programadas por usuarios de la organización. Después de crear una directiva y realizar los cambios, puede asignar usuarios a la directiva. 
    - **Cambiar o crear una directiva de reunión**: para cambiar o crear una directiva de reunión, vaya al **Centro de administración de Microsoft Teams > Reuniones > Directivas de reunión**. Seleccione una directiva de la lista o seleccione Agregar. Si va a crear una nueva directiva, agregue un nombre y una descripción. El nombre no puede contener caracteres especiales ni tener más de 64 caracteres. Elija la configuración y, después, haga clic en **Guardar**.

        Por ejemplo, supongamos que tiene un grupo de usuarios y quiere limitar el ancho de banda que necesitaría la reunión. Cree una nueva directiva personalizada denominada "ancho de banda limitado" y deshabilite las opciones siguientes:

        En **Audio y vídeo**:
        - Desactive Permitir la grabación en la nube.
        - Desactive Permitir vídeo IP.

        En **Uso compartido de contenido**:
        - Desactive el modo de uso compartido de la pantalla.
        - Desactive Permitir pizarra.
        - Desactive Permitir notas compartidas.

        Luego asigne la directiva a los usuarios:

- **Asignar una directiva de reunión a los usuarios**

    1. En el panel de navegación izquierdo del Centro de administración de Microsoft Teams, vaya a **Usuarios** y, después, haga clic en el usuario.
    2. Para seleccionar el usuario, haga clic a la izquierda del nombre de usuario y, después, en **Editar configuración**.
    3. En **Directiva de reunión**, seleccione la directiva que quiera asignar y haga clic en **Aplicar**.

    Para asignar una directiva a varios usuarios a la vez, vea [Modificar la configuración de usuario de Teams en masa](https://docs.microsoft.com/microsoftteams/edit-user-settings-in-bulk). Puede hacer lo siguiente:

    1. En el panel de navegación izquierdo del centro de administración de Microsoft Teams, vaya a **Reuniones > Directivas de reunión**.
    2. Haga clic a la izquierda del nombre de la directiva para seleccionarla.
    3. Seleccione **Administrar usuarios**.
    4. En el panel **Administrar usuarios**, busque el usuario por nombre para mostrar o por nombre de usuario, seleccione el nombre y, después, haga clic en **Agregar**. Repita este paso por cada usuario que quiera agregar.
    5. Cuando termine de agregar usuarios, haga clic en **Guardar**.

- **Solución de problemas de un teclado de marcado ausente:**  

    - Asegúrese de que el usuario tiene una [licencia de Teams](https://docs.microsoft.com/MicrosoftTeams/assign-teams-licenses) asignada.
    - Asegúrese de que el usuario tiene un [Plan de llamadas](https://docs.microsoft.com/MicrosoftTeams/calling-plan-landing-page) asignado.
    - Habilite a los usuarios para [Telefonía IP empresarial](https://docs.microsoft.com/skypeforbusiness/skype-for-business-hybrid-solutions/plan-your-phone-system-cloud-pbx-solution/enable-users-for-enterprise-voice-online-and-phone-system-voicemail#to-enable-your-users-for-phone-system-in-office-365-voice-and-voicemail).

- **Solución de problemas de inicio de sesión en Teams:** en primer lugar, asegúrese de que el [servicio de Microsoft Teams está en buen estado](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/servicehealth). Después, compruebe si hay códigos de error comunes y revise [¿Por qué tengo problemas para iniciar sesión en Microsoft Teams?](https://support.office.com/article/a02f683b-61a3-4008-9447-ee60c5593b0f)  Es posible que también tenga que revisar [Modelos de identidad y autenticación en Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/identify-models-authentication).

**Para los clientes de educación:**

Si sus usuarios ven el mensaje "¡Se lo ha perdido!", asegúrese de [Habilitar Microsoft Teams para su escuela](https://docs.microsoft.com/microsoft-365/education/intune-edu-trial/enable-microsoft-teams). En los inquilinos de EDU, Microsoft Teams no está habilitado por defecto; tendrá que activarlo primero.

Para obtener ayuda con las clases de Teams, consulte [Formación y aprendizaje remotos en Office 365 Educación](https://support.office.com/article/remote-teaching-and-learning-in-office-365-education-f651ccae-7b65-478b-8366-51bb884025c4) donde obtendrá la información más reciente sobre cómo configurar el centro educativo, la planificación de lecciones, las reuniones virtuales y cómo compartir contenido con los alumnos.

Por último, asegúrese de consultar los vídeos de aprendizaje, las cartas de aprendizaje y otros elementos de Microsoft Teams para administradores de TI aquí: https://docs.microsoft.com/MicrosoftTeams/itadmin-readiness#technical-training. 
