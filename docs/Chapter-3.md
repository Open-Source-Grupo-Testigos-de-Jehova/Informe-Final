# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

Luego de realizar el ai-is con sus fases propuestas, para el to-be se realizaron nuevos procesos enfocados en mejorar las fases de los segmentos objetivos con nuestro proyecto.

**_Segmento Objetivo 1: Clara Diaz - Doctora_**
![alt text](<../assets/imgs/Clara Diaz - To-be.jpg>)

**_Segmento Objetivo 2: Carlos Orbegozo - Estudiante de Medicina_**
![alt text](<../assets/imgs/Carlos - To - Be.jpg>)

## 3.2. User Stories

Los User Stories sirven para describir de manera más detallada las diferentes funciones de la aplicación, adaptándolas a las necesidades y prioridades de los usuarios. Estas historias también capturan el propósito de uso de las personas, brindando una comprensión más completa de cómo se relacionan con la aplicación y qué esperan lograr con ella.

<table>
    <tr>
        <th>Epic / Story ID</th>
        <th>Título</th>
        <th>Descripción</th>
        <th>Criterios de Aceptación</th>
        <th>Relacionado con (Epic ID)</th>
    </tr>
    <tr>
        <td>EP01</td>
        <td>Funciones de Usuario</td>
        <td>Como médico, deseo tener funciones y opciones relacionadas a mi usuario para manejar mis datos y acciones en la cuenta.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>EP02</td>
        <td>Visualizacion de Apartados</td>
        <td>Como médico, deseo tener opciones de detalles y búsqueda para visualizar los datos que me interesan en la plataforma.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>EP03</td>
        <td>Landing Page</td>
        <td>Como médico, deseo visitar una Landing Page para informarme sobre MedicDefense y lo que ofrece.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>EP04</td>
        <td>Interacción con Abogado</td>
        <td>Como médico, deseo tener funciones y opciones relacionadas al abogado para tratar con él u opinar de sus servicios.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
    <tr>
        <td>EP05</td>
        <td>Infraestructura y Seguridad</td>
        <td>Como administrador, quiero que la plataforma integre robustos sistemas de seguridad y manejo de datos, para proteger la información de los usuarios.</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>EP06</td>
        <td>Interacción y Accesibilidad</td>
        <td>Como desarrollador, quiero implementar interfaces y funcionalidades accesibles para mejorar la interacción del usuario con la plataforma.</td>
        <td></td>
        <td></td>
    </tr>
        <td>HU01</td>
        <td>Gestión de las cuentas de los usuarios</td>
        <td>Como usuario de la plataforma de MedicDefense, quiero tener la capacidad de gestionar mi cuenta personal, para mantener mi información profesional actualizada y asegurar que la experiencia de la plataforma sea lo más relevante y segura posible.</td>
        <td>Scenario: Creación y Actualización de Cuenta por el Usuario<br><br>GIVEN el usuario necesita crear y actualizar su cuenta para acceder a sus servicios personalizados <br><br>WHEN selecciona la opción de crear una nueva cuenta o editar su cuenta existente en la aplicación,<br><br>AND completa la información requerida como su nombre, especialidad, correo electrónico, y contraseña,<br><br>THEN la aplicación procesa y confirma la creación o actualización de su cuenta.</td>
        <td>EP01</td>
    </tr>
    <tr>
        <td>HU02</td>
        <td>Verificación de Credenciales Médicas</td>
        <td>Como médico registrado en la plataforma, quiero que mi perfil pase por un proceso de verificación de credenciales médicas para aumentar mi credibilidad dentro de la comunidad y tener acceso a recursos especializados.</td>
        <td>Scenario: Subida y Verificación de Credenciales Médicas por el Usuario<br><br>GIVEN que el médico se registra en la plataforma y necesita verificar su identidad profesional,<br><br>WHEN suba sus documentos de credenciales médicas a través de la interfaz de usuario designada para ello,<br><br>AND envíe la documentación para su revisión,<br><br>THEN la plataforma inicia el proceso de verificación de manera automática, y una vez verificadas, su perfil se actualiza con un distintivo que indica su estatus verificado.</td>
        <td>EP01</td>
    </tr>
    <tr>
        <td>HU03</td>
        <td>Gestión de Roles de Cuentas</td>
        <td>Como administrador de la plataforma, necesito poder asignar, modificar y revocar roles de usuario para gestionar adecuadamente el acceso a diversas áreas de la plataforma.</td>
        <td>Scenario: Asignación de Rol a un Usuario Nuevo por el Administrador <br><br>GIVEN que el administrador de la plataforma necesita asignar roles adecuados a los usuarios según su perfil profesional, <br><br>WHEN un usuario nuevo se registra y completa su perfil,<br><br>AND revisa la información de perfil y documentos subidos del usuario,<br><br>THEN se asigna un rol correspondiente a su perfil (como 'Estudiante de Medicina', 'Médico General', 'Asesor Legal').</td>
        <td>EP01</td>
    </tr>
    <tr>
        <td>HU04</td>
        <td>Eliminar cuenta Usuario</td>
        <td>Como usuario de la plataforma de MedicDefense, quiero poder eliminar mi cuenta para no tener vinculo con el sitio web.</td>
        <td>Scenario: El Usuario elimina una cuenta<br>
        <br>GIVEN el Cliente quiere eliminar su cuenta del sitio web<br>
        <br>WHEN complete las verificaciones para ver que sea el usuario de la cuenta,<br><br>AND presione el botón "eliminar cuenta" del apartado de configuración,<br><br>THEN se eliminara su cuenta exitosamente.</td>
        <td>EP01</td>
    </tr>
    <tr>
        <td>HU05</td>
        <td>Visualización de lista de tipos de suscripción</td>
        <td>Como visitante de la landing page de MedicDefense, quiero visitar la lista de tipos de suscripción para seleccionar alguno.</td>
        <td>Scenario: El visitante quiere visualizar tipos de suscripciones<br>
        <br>GIVEN el Cliente quiere visualizar los tipos de suscripciones enl sitio web<br>
        <br>WHEN tiene curiosidad sobre los precios de las suscripciones para usar el sitio web,<br>
        <br>AND complete las acciones para dirigirse al apartado,<br>
        <br>THEN irá al apartado "suscripciones" dentro del sitio web y podrá ver las promociones que tiene el sitio web.</td>
        <td>EP01</td>
    </tr>
    <tr>
        <td>HU06</td>
        <td>Visualizar actividades del Usuario</td>
        <td>Como usuario de la plataforma de MedicDefense,quiero visualizar la lista de las actividades que realizo para tener un control y orden en las acciones que realizo.</td>
        <td>Scenario: El usuario quiere visualizar sus actividades en el sitio web<br>
    <br>GIVEN el usuario quiere visualizar sus actividades<br>
    <br>WHEN se le asignen en las asesorias y/o reuniones<br>
    <br>AND complete las acciones para dirigirse al apartado,<br>
    <br>THEN irá al apartado de "actividades" dentro del sitio web y podrá visualizarlos.</td>
        <td>EP02</td>
    </tr>
    <tr>
    <td>HU07</td>
        <td>Búsqueda por Filtros</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder realizar búsqueda por medio de filtros para facilitar el acceso a ello.</td>
        <td>Scenario: Busqueda de Abogado Médico por el Usuario<br>
    <br>GIVEN que el usuario necesite realizar una búsqueda de abogado médico,<br>
    <br>WHEN seleccione la búsqueda por filtros,<br>
    <br>THEN escoje los parámetros de filtro y la búsqueda será exitosa de acuerdo a lo seleccionado.</td>
        <td>EP02</td>
    </tr>
    <tr>
    <td>HU08</td>
        <td>Suscripción a un plan</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de suscribirme a un plan mensual o anual para tener los beneficios de la suscripción.</td>
        <td>Scenario: Suscripción a un plan de usuario<br>
    <br>GIVEN que el usuario quiere inscribirse en la plataforma MedicDefense,<br>
    <br>WHEN escoje el tipo de suscripción (mensual o anual) de acuerdo a lo que se beneficie,<br>
    <br>THEN realizara el pago y podra recibir los beneficios de la suscripción escogida.</td>
        <td>EP04</td>
    </tr>
    <tr>
   <td>HU09</td>
    <td>Perfil de abogado médico</td>
    <td>Como usuario, quiero poder acceder al perfil completo de un abogado específico al hacer clic en el botón "Perfil".</td>
    <td>Scenario: Acceso al perfil completo de un abogado<br><br>GIVEN el usuario está interesado en conocer más sobre un abogado en particular,<br><br>WHEN hace clic en el botón "Perfil" asociado a un abogado en la página principal,<br><br>THEN espera que se abra un card que se superpone mostrando el perfil completo del abogado seleccionado.</td>
    <td>EP02</td>
    </tr>
    <tr>
    <td>HU10</td>
        <td>Visualización del caso y documentos</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder visualizar toda la documentacion de mi caso.</td>
        <td>Scenario: Visualización de documentacion<br>
    <br>GIVEN un usuario quiere ver su caso con su respectiva documentacion en MedicDefense,<br>
    <br>WHEN entre a la sección “Resumen DE”,<br>
    <br>AND seleccione su caso,<br>
    <br>THEN podrá visualizar toda la documentacion de su caso.</td>
        <td>EP02</td>
    </tr>
    <tr>
    <td>HU11</td>
        <td>Contacto directo con mi medico asesor</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de contactarme rapida y eficientemente con mi seleccionado medico asesor.</td>
        <td>Scenario: Contacto con el medido asesor seleccionado<br>
    <br>GIVEN un usuario quiere contactarse con su medico asesor en MedicDefense,<br>
    <br>WHEN entre a la sección “Perfiles de Abogados” dentro del sitio web,<br>
    <br>THEN tendrá la informacion del medico asesor que seleccionó para poder tener contacto con él.</td>
        <td>EP04</td>
    </tr>
    <tr>
    <td>HU12</td>
        <td>Cambiar de medico asesor</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder cambiar de medico asesor si asi lo deseara por motivos personales o reservados.</td>
        <td>Scenario: Cambio de medico defensor/asesor<br>
    <br>GIVEN que el usuario que quiere cambiar de medico defensor o asesor<br>
    <br>WHEN  asi lo desee el usuario poder tener contacto con el sitio web y solicitarles personalmente un cambio en el medico que me esta defendiendo o asesorando,<br>
    <br>THEN entra a la sección "Contacto", esperando que se acepte la solicitud de cambio.</td>
        <td>EP01</td>
    </tr>
    <tr>
    <td>HU13</td>
        <td>Visualización de servicios</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección donde se expliquen los servicios para estar mejor informado a la hora de confiar en su servicio.</td>
        <td>Scenario: Visualizar información sobre los servicios<br><br>GIVEN un visitante entre a visualizar la landing page,<br><br>WHEN se encuentre navegando por la landing page,<br><br>THEN encuentra una sección con información acerca de los servicios de MedicDefense.</td>
        <td>EP03</td>
    </tr>
    <tr>
    <td>HU14</td>
        <td>Sección de contacto</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección de contacto para facilitar la comunicación al momento de solicitar el servicio.</td>
        <td>Scenario: Visualización de una sección de contacto<br><br>GIVEN un visitante accede a la landing page,<br><br>WHEN se encuentre navegando por la landing page,<br><br>THEN encuentra una sección de contacto con campos como nombre, correo, teléfono, mensaje para solicitar información.</td>
        <td>EP03</td>
    </tr>
    <tr>
    <td>HU15</td>
        <td>Sección about us</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección de about us para informarme sobre la empresa que está brindando los servicios.</td>
        <td>Scenario: Visualización de una sección about us<br><br>GIVEN un visitante explora la landing page,<br><br>WHEN se encuentre navegando por la landing page,<br><br>THEN encuentra una sección about us que le brinda información acerca de la empresa cuyos servicios le interesan.</td>
        <td>EP03</td>
    </tr>
    <tr>
    <td>HU16</td>
        <td>Sección de Creadores</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección de creadores para facilitar tener el conocimiento de los creadores de la empresa.</td>
        <td>Scenario: Visualización de una sección creadores<br>
    <br>GIVEN un visitante accede a la landing page,
<br>
    <br>WHEN se encuentre navegando por la landing page,<br><br>
    THEN encuentra una sección creadores que le brinda información acerca de los creadores de la empresa.</td>
        <td>EP03</td>
    </tr>
    <tr>
    <td>HU17</td>
        <td>Sección de inicio</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección de inicio con una barra de navegación para poder desplazarme mejor por la landing page.</td>
        <td>Scenario: Visualización de una sección inicio<br>
    <br>GIVEN un visitante ingresa a la landing page,<br>
    <br>WHEN se encuentre navegando por la landing page,<br>
    <br>THEN encuentra una sección inicio que tenga una barra de navegación donde puede ver el logo para poder desplazarse mejor.</td>
        <td>EP03</td>
    </tr>
    <tr>
    <td>HU18</td>
        <td>Integración de pagos</td>
        <td>Como administrador, quiero integrar un sistema de pagos seguro para gestionar las suscripciones y compras en la plataforma.</td>
        <td>Scenario: Implementar un proceso de pago seguro para las suscripciones.<br>
    <br>GIVEN un usuario ha elegido un plan de suscripción y desea pagar,<br>
    <br>WHEN introduce la información de su método de pago y confirma la transacción,<br>
    <br>AND el sistema verifica la validez de la información de pago,<br>
    <br>THEN el sistema procesa el pago de forma segura y actualiza el estatus de la suscripción en la base de datos.</td>
        <td>EP05</td>
    </tr>
    <td>HU19</td>
        <td>Base de datos de usuarios</td>
        <td>Como administrador, quiero implementar una base de datos segura y escalable, para proteger y gestionar eficazmente la información de los usuarios.</td>
        <td>Scenario: Acceder a datos de usuario para auditorías internas.<br>
    <br>GIVEN que el administrador necesita verificar la integridad de los datos de los usuarios,<br>
    <br>WHEN realiza una consulta en la base de datos,<br>
    <br>THEN la base de datos valida los permisos del administrador,<br>
    <br>AND proporciona los datos solicitados de manera rápida y segura.</td>
        <td>EP05</td>
    </tr>
    <td>HU20</td>
        <td>API para gestión de perfiles</td>
        <td>Como desarrollador, quiero APIs robustas para crear, editar y eliminar perfiles de usuario.</td>
        <td>Scenario: Un administrador necesita actualizar información de un perfil por motivos de seguridad.<br>
    <br>GIVEN que un perfil de usuario necesita actualización urgente,<br>
    <br>WHEN el administrador modifica y guarda los cambios en el perfil,<br>
    <br>AND confirma la operación,<br>
    <br>THEN la API actualiza los datos en la base de datos,<br>
    <br>AND notifica al administrador que la actualización fue exitosa.
    </td>
        <td>EP06</td>
    </tr>
    <td>HU21</td>
        <td>Logging de Actividades</td>
        <td>Como administrador, quiero un sistema de logging robusto para registrar la actividad en la plataforma, facilitando la auditoría y la detección temprana de problemas.</td>
        <td>Scenario: Registrar una actividad crítica para la auditoría de seguridad.<br>
    <br>GIVEN que se lleva a cabo una acción crítica en la plataforma,<br>
    <br>WHEN la acción es ejecutada,<br>
    <br>THEN el sistema registra detalladamente la acción en los logs de seguridad,<br>
    <br>AND notifica a los administradores de seguridad sobre la actividad registrada.</td>
        <td>EP05</td>
    </tr>
    <td>HU22</td>
        <td>API para búsqueda por filtros</td>
        <td>Como desarrollador, quiero crear una API para búsquedas por filtros, para mejorar la accesibilidad de la información.</td>
        <td>Scenario: Administrar búsquedas avanzadas para encontrar registros específicos de usuarios.<br>
    <br>GIVEN que el administrador necesita encontrar perfiles específicos basados en criterios complejos,<br>
    <br>WHEN utiliza la API de búsqueda por filtros en la interfaz de administración,<br>
    <br>THEN la API proporciona resultados precisos y rápidos, ayudando al administrador a gestionar eficientemente la información.</td>
        <td>EP06</td>
    </tr>
    <td>HU23</td>
        <td>Servicio de notificaciones</td>
        <td>Como desarrollador, quiero implementar un servicio de notificaciones, para mantener a los usuarios informados.</td>
        <td>Scenario: Notificar a los usuarios sobre una actualización de seguridad importante.<br>
    <br>GIVEN que se ha emitido una actualización de seguridad,<br>
    <br>WHEN el sistema procesa la actualización,<br>
    <br>AND identifica los usuarios afectados,<br>
    <br>THEN el servicio de notificaciones envía automáticamente alertas,<br>
    <br>AND los usuarios reciben las notificaciones en tiempo real.</td>
        <td>EP06</td>
    </tr>
    <td>HU24</td>
        <td>Soporte para múltiples navegadores</td>
        <td>Como desarrollador, quiero garantizar la compatibilidad en múltiples navegadores, para una experiencia de usuario uniforme.</td>
        <td>Scenario: Verificar y asegurar la compatibilidad de la plataforma en diferentes navegadores.<br>
    <br>GIVEN que los administradores y usuarios acceden a la plataforma desde diversos navegadores,<br>
    <br>WHEN navegan y realizan operaciones críticas,<br>
    <br>THEN el sistema mantiene una funcionalidad consistente y segura, sin importar el navegador utilizado.</td>
        <td>EP06</td>
    </tr>
        <tr>
<td>HU25</td>
    <td>Configuración de la base de datos</td>
    <td>Como desarrollador, quiero diseñar y configurar la estructura de la base de datos para almacenar la información de los abogados, incluyendo campos como nombre, especialidad y ubicación.</td>
    <td>Scenario: Configuración de la base de datos<br><br>GIVEN el desarrollador quiere configurar la base de datos para almacenar la información de los abogados<br><br>WHEN define la estructura de la tabla 'abogados' con los campos requeridos como nombre, especialidad y ubicación,<br><br>THEN la base de datos está configurada correctamente para almacenar la información de los abogados.</td>
    <td>EP06</td>
  </tr>
  <tr>
    <td>HU26</td>
    <td>Implementación de la funcionalidad de búsqueda de abogados</td>
    <td>Como desarrollador, quiero agregar una función de búsqueda en la página de lista de abogados para que los usuarios puedan buscar abogados por nombre o especialidad.</td>
    <td>Scenario: Búsqueda de abogados<br><br>GIVEN el desarrollador quiere implementar la función de búsqueda de abogados en la aplicación,<br><br>WHEN desarrolla la función de búsqueda en la página de lista de abogados y configura los parámetros para buscar por nombre o especialidad,<br><br>THEN la búsqueda de abogados muestra resultados relevantes que coinciden con el término de búsqueda proporcionado.</td>
    <td>EP06</td>
  </tr>
    <tr>
    <td>HU27</td>
    <td>Creación y Gestión de la Entidad de Abogados</td>
    <td>Como desarrollador backend, quiero implementar la creación y gestión de la entidad de abogados en la base de datos para almacenar información detallada de los abogados.</td>
    <td>Scenario: Creación de Perfiles de Abogados<br><br>GIVEN el desarrollador quiere registrar nuevos abogados para almacenarlos en la base de datos de la plataforma,<br><br>WHEN se realiza una solicitud para crear un nuevo perfil de abogado, proporcionando información como nombre, especialidad, ubicación y otros detalles relevantes,<br><br>THEN se crea un nuevo registro en la base de datos que contiene la información completa del abogado.<br><br>Scenario: Actualización de Perfiles de Abogados<br><br>GIVEN el desarrollador quiere actualizar la información de un abogado existente en la plataforma para gestionar su información,<br><br>WHEN se realiza una solicitud para actualizar los detalles de un abogado, proporcionando el ID único del abogado y los campos que se desean modificar,<br><br>THEN el backend actualiza los datos del abogado correspondiente en la base de datos según los campos proporcionados.</td>
    <td>EP06</td>
    </tr>
    <tr>
    <td>HU28</td>
    <td>Creación y Gestión de Entidad de Usuario Médico/Estudiante</td>
    <td>Como desarrollador, quiero crear la entidad de usuario que represente tanto a médicos como a estudiantes de medicina en la plataforma, para asegurar que todos los atributos necesarios estén disponibles para cada tipo de usuario.
</td>
    <td>Scenario: Creación de la entidad de usuario<br><br>GIVEN el desarrollador quiere representar tanto a médicos como a estudiantes de medicina en el sistema para asegurar los atributos necesarios para cada tipo de usuario,<br><br>WHEN define y crea la entidad de usuario con atributos comunes como ID, nombre, especialidad, correo electrónico, contraseña, entre otros,<br><br>THEN la entidad de usuario está disponible en el sistema para ser utilizada en otras funcionalidades de la plataforma.<br><br>Scenario: Gestión de usuarios médicos/estudiantes<br><br>GIVEN el desarrollador quiere gestionar la información de médicos y estudiantes registrados para gestionar su información,<br><br>WHEN se implementa la funcionalidad para añadir, actualizar y eliminar usuarios a través de endpoints dedicados,<br><br>THEN los administradores pueden realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre la información de médicos y estudiantes de manera eficiente y segura.</td>
    <td>EP06</td>
    </tr>
    <tr>
    <td>HU29</td>
    <td>Gestión de Suscripciones</td>
    <td>Como desarrollador, quiero implementar la gestión de suscripciones para que los usuarios puedan ver, seleccionar y administrar sus planes de suscripción en la plataforma.</td>
    <td>Scenario: Manejo de Suscripciones<br><br>GIVEN el desarrollador backend necesita implementar la gestión de suscripciones en la plataforma,<br><br>WHEN desarrolla los endpoints necesarios en la API para visualizar, seleccionar y actualizar planes de suscripción,<br><br>THEN los usuarios pueden ver su suscripción actual, seleccionar nuevos planes si es necesario, y actualizar la información de pago de forma segura y eficiente.</td>
    <td>EP06</td>
    </tr>
    </tr>
    <td>HU30</td>
    <td>Creación y Gestión de Recursos Educativos</td>
    <td>Como desarrollador backend, quiero implementar la creación y gestión de recursos educativos en la base de datos para que los administradores puedan añadir, actualizar y eliminar recursos.</td>
    <td>Scenario: Creación de recursos educativos.
    <br><br>GIVEN el desarrollador necesita añadir un nuevo recurso educativo,
    <br><br>WHEN el desarrollador envía los detalles del recurso a través del endpoint de creación,
    <br><br>THEN el recurso educativo se almacena correctamente en la base de datos.
    <br><br>Scenario: Eliminación de recursos educativos
    <br><br>GIVEN el desarrollador necesita eliminar un recurso educativo,
    <br><br>WHEN el desarrollador envía una solicitud de eliminación a través del endpoint correspondiente,
    <br><br>THEN el recurso educativo se elimina correctamente de la base de datos.</td>
    <td>EP06</td>
    </tr>
    <tr>
    <td>HU31</td>
    <td>Implementación de Categorías a los Recursos</td>
    <td>Como desarrollador backend, quiero implementar la funcionalidad para gestionar categorías de los recursos educativos para organizar los recursos de manera eficiente.</td>
    <td>Scenario: Creación de categorías
    <br><br>GIVEN el desarrollador necesita crear una nueva categoría para los recursos educativos,
    <br><br>WHEN el desarrollador envía los detalles de la categoría a través del endpoint de creación,
    <br><br>THEN la categoría se almacena correctamente en la base de datos.
    <br><br>Scenario: Gestión de categorías
    <br><br>GIVEN el desarrollador desea actualizar una categoría existente en los recursos educativos,
    <br><br>WHEN el desarrollador envía una solicitud de actualización a través del endpoint correspondiente,
    <br><br>THEN la categoría se actualiza correctamente en la base de datos.</td>
    <td>EP06</td>
    </tr>
    <tr>
    <td>HU32</td>
    <td>Funcionalidad de Búsqueda Avanzada de Recursos Educativos</td>
    <td>Como desarrollador backend, quiero implementar una funcionalidad de búsqueda avanzada para que los usuarios puedan buscar recursos educativos por diferentes criterios.</td>
    <td>
        Scenario: Búsqueda de recursos educativos por título
        <br><br>GIVEN el desarrollador necesita implementar la búsqueda de recursos educativos por título,
        <br><br>WHEN se desarrolla el endpoint de búsqueda que recibe un término de búsqueda,
        <br><br>THEN se devuelve una lista de recursos educativos que coinciden con el término buscado.
        <br><br>Scenario: Búsqueda de recursos educativos por categoría
        <br><br>GIVEN el desarrollador necesita implementar la búsqueda de recursos educativos por categoría,
        <br><br>WHEN se desarrolla el endpoint de búsqueda que recibe una categoría como parámetro,
        <br><br>THEN se devuelven los recursos educativos que pertenecen a la categoría seleccionada.
        <br><br>Scenario: Búsqueda de recursos educativos por autor
        <br><br>GIVEN el desarrollador necesita implementar la búsqueda de recursos educativos por autor,
        <br><br>WHEN se desarrolla el endpoint de búsqueda que recibe el nombre del autor como parámetro,
        <br><br>THEN se devuelven los recursos educativos escritos por ese autor.
    </td>
    <td>EP06</td>
</tr>
    <tr>
    <td>HU33</td>
    <td>Obtener todas las notificaciones</td>
    <td>Como desarrollador backend, quiero implementar un endpoint GET para obtener todas las notificaciones para permitir a los usuarios recuperar la lista completa de notificaciones almacenadas en el sistema.</td>
    <td>Scenario: Obtenención de todas las notificaciones
    <br><br>GIVEN el desarrollador necesita obtener todas las notificaciones,
    <br><br>WHEN el desarrollador realiza una solicitud GET a '/notifications',
    <br><br>THEN todas las notificaciones almacenadas en la base de datos se deben devolver en formato JSON.</td>
    <td>EP06</td>
    </tr>
    <tr>
    <td>HU34</td>
    <td>Crear una nueva notificación</td>
    <td>Como desarrollador backend, quiero implementar un endpoint POST para crear una nueva notificación para permitir a los usuarios enviar nuevas notificaciones que se almacenarán en el sistema.</td>
    <td>Scenario: Creación de una nueva notificación
    <br><br>GIVEN el desarrollador necesita crear una nueva notificación,
    <br><br>WHEN el desarrollador realiza una solicitud POST a '/notifications' con los detalles de la notificación en el cuerpo de la solicitud,
    <br><br>THEN se debe crear una nueva notificación en la base de datos y devolver un mensaje de confirmación junto con los detalles de la notificación creada.</td>
    <td>EP06</td>
    </tr>
    <tr>
    <td>HU35</td>
    <td>Obtener una notificación por ID</td>
    <td>Como desarrollador backend, quiero implementar un endpoint GET para obtener una notificación específica por su ID para permitir a los usuarios recuperar los detalles de una notificación particular basada en su identificador único.</td>
    <td>Scenario: Obtenención de notificación por ID
    <br><br>GIVEN el desarrollador necesita crear una notificación por ID,
    <br><br>WHEN el desarrollador realiza una solicitud GET a '/notifications/{id}' con un identificador de notificación válido,
    <br><br>THEN se deben devolver los detalles de la notificación correspondiente en formato JSON.</td>
    <td>EP06</td>
    </tr>
    <tr>
    <td>HU36</td>
    <td>Creación y gestión de recursos de casos legales</td>
    <td>Como desarrollador backend, quiero implementar la creación y gestión de casos legales para que los administradores puedan
    gestionar los casos legales.</td>
    <td>Scenario: Crear un caso legal
    <br><br>GIVEN el desarrollador necesita crear una nuevo caso legal,
    <br><br>WHEN el desarrollador realiza una solicitud POST con los detalles del caso legal,
    <br><br>THEN se debe crear un nuevo caso legal en la base de datos.
    <br><br>Scenario: Obtener todos los casos legales
    <br><br>GIVEN el desarrollador necesita obtener los casos legales,
    <br><br>WHEN el desarrollador realiza una solicitud GET,
    <br><br>THEN se debe devolver todos los casos legales existentes.
    <br><br>Scenario: Obtener de los casos legales por status
    <br><br>GIVEN el desarrollador necesita obtener los casos legales por status,
    <br><br>WHEN el desarrollador realiza una solicitud GET con el detalle de status,
    <br><br>THEN se debe devolver todos los casos legales existentes que coincidan con el status solicitado.</td>
    <td>EP06</td>
    </tr>
    <tr>
    <td>HU37</td>
    <td>Creación y gestión de recursos de consultas</td>
    <td>Como desarrollador backend, quiero implementar la creación y gestión de consultas para que los administradores puedan
    gestionar las consultas necesarias.</td>
    <td>Scenario: Crear una consulta
    <br><br>GIVEN el desarrollaodr necesita crear una nueva consulta,
    <br><br>WHEN el desarrollaodr realiza una solicitud POST con los detalles de la consulta,
    <br><br>THEN se debe crear una nueva consulta en la base de datos.
    <br><br>Scenario: Obtener las consultas
    <br><br>GIVEN el desarrollaodr necesita obtener las consultas,
    <br><br>WHEN el desarrollaodr realiza una solicitud GET,
    <br><br>THEN se debe devolver todas las consultas existentes.
    <br><br>Scenario: Eliminar las consultas
    <br><br>GIVEN el desarrollaodr necesita eliminar una consulta,
    <br><br>WHEN el desarrollaodr realiza una solicitud DELETE con el ID de la consulta,
    <br><br>THEN se debe eliminar la consulta existente que coincida con el ID solicitado.</td>
    <td>EP06</td>
    </tr>
    <tr>
    <td>HU38</td>
    <td>Creación y gestión de asuntos legales</td>
    <td>Como desarrollador backend, quiero implementar la creación y gestión de asuntos legales para que los administradores puedan
    gestionar los asuntos legales.</td>
    <td>Scenario: Crear un asunto legal
    <br><br>GIVEN el desarrollaodr necesita crear un nuevo asunto legal,
    <br><br>WHEN el desarrollaodr realiza una solicitud POST con los detalles del asunto legal,
    <br><br>THEN se debe crear un nuevo asunto legal en la base de datos.
    <br><br>Scenario: Obtener los asuntos legales
    <br><br>GIVEN el desarrollaodr necesita obtener los asuntos legales,
    <br><br>WHEN el desarrollaodr realiza una solicitud GET,
    <br><br>THEN se debe devolver todas los asuntos legales existentes.
    <br><br>Scenario: Obtener asunto legal por ID
    <br><br>GIVEN el desarrollaodr necesita obtner un solo asunto legal,
    <br><br>WHEN el desarrollaodr realiza una solicitud GET con el ID del asunto legal,
    <br><br>THEN se debe obtener el asunto legal que coincida con el ID solicitado.</td>
    <td>EP06</td>
    </tr>
</table>

## 3.3. Impact Mapping

En esta sección, se plantearon metas de negocio utilizando los criterios SMART para elaborar el Impact Mapping en base a nuestras User Personas y User Stories.

**Segmento 1**
![alt text](../assets/imgs/Clara-ImpactMap.png)

**Segmento 2**
![alt text](../assets/imgs/Carlos-ImpactMap.png)

## 3.4. Product Backlog

<table>
    <tr>
        <th>#Orden</th>
        <th>User Story/Technical Story Id</th>
        <th>Título</th>
        <th>Descripción</th>
        <th>Story Points (1 / 2 / 3 / 5 / 8)</th>
    </tr>
    <tr>
        <td>1</td>
        <td>US05</td>
        <td>Visualización de lista de tipos de suscripción</td>
        <td>Como usuario de la plataforma de MedicDefense, quiero visualizar la lista de tipos de suscripción para seleccionar alguno.</td>
        <td>2</td>
    </tr>
    <tr>
        <td>2</td>
        <td>US01</td>
        <td>Gestión de las cuentas de los usuarios</td>
        <td>Como usuario de la plataforma de MedicDefense, quiero tener la capacidad de gestionar mi cuenta personal, para mantener mi información profesional actualizada y asegurar que la experiencia de la plataforma sea lo más relevante y segura posible.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>3</td>
        <td>US04</td>
        <td>Eliminar cuenta Usuario</td>
        <td>Como usuario de la plataforma de MedicDefense, necesito poder eliminar mi cuenta en caso sea necesario para no tener vínculo con el sitio web.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>4</td>
        <td>US09</td>
        <td>Perfil de abogado médico</td>
        <td>Como usuario, quiero poder acceder al perfil completo de un abogado específico al hacer clic en el botón "Perfil".</td>
        <td>3</td>
    </tr>
    <tr>
        <td>5</td>
        <td>US12</td>
        <td>Cambiar de medico asesor</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder cambiar de medico asesor si así lo deseara por motivos personales o reservados.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>6</td>
        <td>US15</td>
        <td>Sección de about us</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección de about us para informarme sobre la empresa que está brindando los servicios.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>7</td>
        <td>US16</td>
        <td>Sección de contacto</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección de contacto para facilitar tener el conocimiento de los creadores de la empresa.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>8</td>
        <td>US17</td>
        <td>Sección de inicio</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección de inicio con una barra de navegación para poder desplazarme mejor por la landing page.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>9</td>
        <td>US24</td>
        <td>Soporte para múltiples navegadores</td>
        <td>Como desarrollador, quiero garantizar la compatibilidad en múltiples navegadores, para una experiencia de usuario uniforme.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>10</td>
        <td>US25</td>
        <td>Configuración de la base de datos</td>
        <td>Como desarrollador, quiero diseñar y configurar la estructura de la base de datos para almacenar la información de los abogados, incluyendo campos como nombre, especialidad y ubicación.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>11</td>
        <td>US26</td>
        <td>Implementación de la funcionalidad de búsqueda de abogados</td>
        <td>Como desarrollador, quiero agregar una función de búsqueda en la página de lista de abogados para que los usuarios puedan buscar abogados por nombre o especialidad.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>12</td>
        <td>US31</td>
        <td>Implementación de Categorías de Recursos</td>
        <td>Como desarrollador backend, quiero implementar la funcionalidad para gestionar categorías de los recursos educativos para organizar los recursos de manera eficiente.</td>
        <td>3</td>
    </tr>
    <tr>
        <td>13</td>
        <td>US13</td>
        <td>Visualización de servicios</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección donde se expliquen los servicios para estar mejor informado a la hora de confiar en su servicio.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>14</td>
        <td>US14</td>
        <td>Sección de contacto</td>
        <td>Como visitante de la landing page de MedicDefense, quiero ver una sección de contacto para facilitar la comunicación al momento de solicitar el servicio.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>15</td>
        <td>US07</td>
        <td>Interfaz de filtros de Busqueda</td>
        <td>Como desarrollador, quiero diseñar la interfaz de filtros para que los usuarios visualicen de manera clara los campos que pueden seleccionar.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>16</td>
        <td>US28</td>
        <td>Creación y Gestión de Entidad de Usuario Médico/Estudiante</td>
        <td>Como desarrollador, quiero crear la entidad de usuario que represente tanto a médicos como a estudiantes de medicina en la plataforma, para asegurar que todos los atributos necesarios estén disponibles para cada tipo de usuario.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>17</td>
        <td>US06</td>
        <td>Visualizar actividades del Usuario</td>
        <td>Como usuario de la plataforma de MedicDefense, quiero visualizar la lista de las actividades que realizo para tener un control y orden en las acciones que realizo.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>18</td>
        <td>US08</td>
        <td>Suscripción a un plan</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de suscribirme a un plan mensual o anual para tener los beneficios de la suscripción.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>19</td>
        <td>US10</td>
        <td>Visualización del caso y documentos</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder visualizar toda la documentación de mi caso.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>20</td>
        <td>US11</td>
        <td>Contacto directo con mi medico asesor</td>
        <td>Como usuario de la plataforma MedicDefense, quiero tener la capacidad de contactarme rápida y eficientemente con mi seleccionado medico asesor.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>21</td>
        <td>US20</td>
        <td>API para gestión de perfiles</td>
        <td>Como desarrollador, quiero APIs robustas para crear, editar y eliminar perfiles de usuario.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>22</td>
        <td>US22</td>
        <td>API para búsqueda por filtros</td>
        <td>Como desarrollador, quiero crear una API para búsquedas por filtros, para mejorar la accesibilidad de la información.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>23</td>
        <td>US23</td>
        <td>Servicio de notificaciones</td>
        <td>Como desarrollador, quiero implementar un servicio de notificaciones, para mantener a los usuarios informados.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>24</td>
        <td>US30</td>
        <td>Creación y Gestión de Recursos Educativos</td>
        <td>Como desarrollador backend, quiero implementar la creación y gestión de recursos educativos en la base de datos para que los administradores puedan añadir, actualizar y eliminar recursos.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>25</td>
        <td>US32</td>
        <td>Funcionalidad de Búsqueda Avanzada de Recursos Educativos</td>
        <td>Como desarrollador backend, quiero implementar una funcionalidad de búsqueda avanzada para que los usuarios puedan buscar recursos educativos por diferentes criterios.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>26</td>
        <td>US33</td>
        <td>Obtener todas las notificaciones</td>
        <td>Como desarrollador backend, quiero implementar un endpoint GET para obtener todas las notificaciones para permitir a los usuarios recuperar la lista completa de notificaciones almacenadas en el sistema.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>27</td>
        <td>US34</td>
        <td>Crear una nueva notificación</td>
        <td>Como desarrollador backend, quiero implementar un endpoint POST para crear una nueva notificación para permitir a los usuarios enviar nuevas notificaciones que se almacenarán en el sistema.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>28</td>
        <td>US35</td>
        <td>Obtener una notificación por ID</td>
        <td>Como desarrollador backend, quiero implementar un endpoint GET para obtener una notificación específica por su ID para permitir a los usuarios recuperar los detalles de una notificación particular basada en su identificador único.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>29</td>
        <td>US36</td>
        <td>Creación y gestión de recursos de casos legales</td>
        <td>Como desarrollador backend, quiero implementar la creación y gestión de casos legales para que los administradores puedan gestionar los casos legales.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>30</td>
        <td>US37</td>
        <td>Creación y gestión de recursos de consultas</td>
        <td>Como desarrollador backend, quiero implementar la creación y gestión de consultas para que los administradores puedan gestionar las consultas necesarias.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>31</td>
        <td>US38</td>
        <td>Creación y gestión de asuntos legales</td>
        <td>Como desarrollador backend, quiero implementar la creación y gestión de asuntos legales para que los administradores puedan gestionar los asuntos legales.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>32</td>
        <td>US19</td>
        <td>Base de datos de usuarios</td>
        <td>Como administrador, quiero implementar una base de datos segura y escalable, para proteger y gestionar eficazmente la información de los usuarios.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>33</td>
        <td>US27</td>
        <td>Creación y Gestión de la Entidad de Abogados</td>
        <td>Como desarrollador backend, quiero implementar la creación y gestión de la entidad de abogados en la base de datos para almacenar información detallada de los abogados.</td>
        <td>5</td>
    </tr>
    <tr>
        <td>34</td>
        <td>US29</td>
        <td>Gestión de Suscripciones</td>
        <td>Como desarrollador, quiero implementar la gestión de suscripciones para que los usuarios puedan ver, seleccionar y administrar sus planes de suscripción en la plataforma.</td>
        <td>8</td>
    </tr>
    <tr>
        <td>35</td>
        <td>US18</td>
        <td>Integración de pagos</td>
        <td>Como administrador, quiero integrar un sistema de pagos seguro para gestionar las suscripciones y compras en la plataforma.</td>
        <td>8</td>
    </tr>
    <tr>
        <td>36</td>
        <td>US21</td>
        <td>Logging de Actividades</td>
        <td>Como administrador, quiero un sistema de logging robusto para registrar la actividad en la plataforma, facilitando la auditoría y la detección temprana de problemas.</td>
        <td>8</td>
    </tr>
</table>
