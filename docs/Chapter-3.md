# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

**_Segmento Objetivo 1: Clara Diaz - Doctora_**
![alt text](<../assets/imgs/Clara Diaz - To-be.jpg>)

**_Segmento Objetivo 2: Carlos Orbegozo - Estudiante de Medicina_**
![alt text](<../assets/imgs/Carlos - To - Be.jpg>)

## 3.2. User Stories
| Epics             |User Stories|
|-----------------------------|---------|
| Autenticación y autorización| 1. Gestión de las cuentas de los usuarios<br>2. Verificación de credenciales médicas<br>3. Gestión de roles de cuentas<br>4. Eliminar cuenta de Usuario|
|Visualizacion de Apartados|5. Visualización de lista de tipos de suscripción<br>6.Visualizar actividades del Usuario|
|||
|||

<table>
  <tr>
    <th colspan="5">Historia de Usuario 1</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU01</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP01</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">Anatoly Noriega</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Gestión de las cuentas de los usuarios</td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como usuario de la plataforma de MedicDefense, quiero tener la capacidad de gestionar mi cuenta personal, para mantener mi información profesional actualizada y asegurar que la experiencia de la plataforma sea lo más relevante y segura posible.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: Creación y Actualización de Cuenta por el Usuario<br><br>Dado que soy un usuario que necesita crear y actualizar mi cuenta para acceder a servicios personalizados,<br><br>Cuando selecciono la opción de crear una nueva cuenta o editar mi cuenta existente en la aplicación,<br><br>Y completo la información requerida como mi nombre, especialidad, correo electrónico, y contraseña,<br><br>Entonces la aplicación procesa y confirma la creación o actualización de mi cuenta.</td>
</table>
<table>
  <tr>
    <th colspan="5">Historia de Usuario 2</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU02</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP01</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">Anatoly Noriega</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Verificación de Credenciales Médicas</td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como médico registrado en la plataforma, quiero que mi perfil pase por un proceso de verificación de credenciales médicas para aumentar mi credibilidad dentro de la comunidad y tener acceso a recursos especializados.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: Subida y Verificación de Credenciales Médicas por el Usuario<br><br>Dado que soy un médico que se registra en la plataforma <br><br>Y necesito verificar mi identidad profesional,<br><br>Cuando subo mis documentos de credenciales médicas a través de la interfaz de usuario designada para ello,<br><br>Y envío la documentación para su revisión,<br><br>Entonces la plataforma inicia el proceso de verificación de manera automática,<br><br>Y una vez verificadas, mi perfil se actualiza con un distintivo que indica mi estatus verificado.</td>
</table>
<table>
  <tr>
    <th colspan="5">Historia de Usuario 3</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU03</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP01</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">Anatoly Noriega</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Gestión de Roles de Cuentas</td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como administrador de la plataforma, necesito poder asignar, modificar y revocar roles de usuario para gestionar adecuadamente el acceso a diversas áreas de la plataforma.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: Asignación de Rol a un Usuario Nuevo por el Administrador<br><br>Dado que soy el administrador de la plataforma <br><br>Y necesito asignar roles adecuados a los usuarios según su perfil profesional,<br><br>Cuando un usuario nuevo se registra y completa su perfil,<br><br>Y reviso la información de perfil y documentos subidos del usuario,<br><br>Entonces asigno un rol correspondiente a su perfil (como 'Estudiante de Medicina', 'Médico General', 'Asesor Legal'),</td>
</table>

<table>
  <tr>
    <th colspan="5">Historia de Usuario 4</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU04</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP01</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">  Gabriel Garcia</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Eliminar cuenta Usuario</td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como usuario de la plataforma de MedicDefense,necesito poder eliminar mi cuenta en caso sea necesario para no tener vinculo con el sitio web.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: El Usuario no tiene una cuenta<br><br>DADO de que el Cliente quiere eliminar su cuenta del sitio web<br><br>CUANDO éste decidido a hacerlo,<br><br>Y complete las verificaciones para ver que sea el usuario de la cuenta,<br><br>ENTONCES al presionar el botón "eliminar cuenta" del apartado de configuración se eliminara su cuenta exitosamente.</td>
</table>

<table>
  <tr>
    <th colspan="5">Historia de Usuario 5</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU05</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP02</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">  Gabriel Garcia</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Visualización de lista de tipos de suscripción</td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como usuario de la plataforma de MedicDefense,quiero visualizar la lista de tipos de suscripción para seleccionar alguno.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: El Usuario quiere visualizar tipos de suscripciones<br><br>DADO de que el Cliente quiere visualizar los tipos de suscripciones enl sitio web<br><br>CUANDO tiene curiosidad sobre los precios de las suscripciones para usarl sitio web,<br><br>Y complete las acciones para dirigirse al apartado,<br><br>ENTONCES irá al apartado "suscripciones" dentro del sitio web y podrá ver las promociones que tiene el sitio web.</td>
</table>

<table>
  <tr>
    <th colspan="5">Historia de Usuario 6</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU06</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP02</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">  Gabriel Garcia</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Visualizar actividades del Usuario</td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como usuario de la plataforma de MedicDefense,quiero visualizar la lista de las actividades que realizo para tener un control y orden en las acciones que realizo.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: El Cliente quiere visualizar sus actividades en el sitio web<br><br>DADO de que el Cliente quiere visualizar sus actividades <br><br>CUANDO se le asignen en las asesorias y/o reuniones<br><br>Y complete las acciones para dirigirse al apartado,<br><br>ENTONCES irá al apartado de "actividades" dentro del sitio web y podrá visualizarlos.</td>
</table>

<table>
  <tr>
    <th colspan="5">Historia de Usuario 7</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU07</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP03</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">  Fabricio Apaza</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Búsqueda por Filtros</td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder realizar búsqueda por medio de filtros para facilitar el acceso a ello.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: Busqueda de Abogado Médico por el Usuario<br>
    <br>DADO que soy un usuario que necesita realizar una búsqueda de abogado médico,<br>
    <br>CUANDO selecciono la búsqueda por filtros,<br>
    <br>ENTONCES escojo los parámetros de filtro y la búsqueda será exitosa de acuerdo a lo seleccionado.
</td>
</table>

<table>
  <tr>
    <th colspan="5">Historia de Usuario 7</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU07</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP03</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">  Fabricio Apaza</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Búsqueda por Filtros</td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder realizar búsqueda por medio de filtros para facilitar el acceso a ello.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: Busqueda de Abogado Médico por el Usuario<br>
    <br>DADO que soy un usuario que necesita realizar una búsqueda de abogado médico,<br>
    <br>CUANDO selecciono la búsqueda por filtros,<br>
    <br>ENTONCES escojo los parámetros de filtro y la búsqueda será exitosa de acuerdo a lo seleccionado.
</td>
</table>


<table>
  <tr>
    <th colspan="5">Historia de Usuario 8</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU08</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP03</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">  Fabricio Apaza</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Suscripción a un plan </td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como usuario de la plataforma MedicDefense, quiero tener la capacidad de suscribirme a un plan mensual o anual para tener los beneficios de la suscripción.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: Suscripción a un plan de usuario<br>
    <br>DADO que soy un usuario que quiere inscribirse en la plataforma MedicDefense,<br>
    <br>CUANDO escojo el tipo de suscripción (mensual o anual) de acuerdo a lo que me beneficie,<br>
    <br>ENTONCES realizaré el pago y podré recibir los beneficios de la suscripción escogida.
</td>
</table>

<table>
  <tr>
    <th colspan="5">Historia de Usuario 9</th>
  </tr>
  <tr>
    <td colspan="2">ID-HU</td>
    <td colspan="1">HU09</td>
    <td colspan="1">Relación (EPIC ID)</td>
    <td colspan="1">EP03</td>
  </tr>
  <tr>
    <td colspan="2">Owner</td>
    <td colspan="3">  Fabricio Apaza</td>
</tr>
  <tr>
    <td colspan="2">Título HU</td>
    <td colspan="3">Visualización de Perfil de Abogado Médico</td>
  </tr>
  <tr>
<td colspan="2">Descripción HU</td>
    <td colspan="3">Como usuario de la plataforma MedicDefense, quiero tener la capacidad de poder visualizar el perfil del abogado médico para ver la información de sus datos y experiencia.</td>
    </tr>
<tr>
<td colspan="2">Criterios de Aceptación</td>
    <td colspan="3">Scenario: Visualización de perfil<br>
    <br>DADO que soy un usuario que quiere ver los perfiles de los abogados médicos en MedicDefense,<br>
    <br>CUANDO tiene curiosidad sobre los perfiles de los abogados médicos,<br>
    <br>ENTONCES entro a la sección “Perfiles de Abogados” dentro del sitio web y podré visualizar.
</td>
</table>



## 3.3. Impact Mapping

## 3.4. Product Backlog

<table>
    <tr>
        <th>#Orden</th>
        <th>User Story/Technical Story Id</th>
        <th>Título</th>
        <th>Descripción</th>
    </tr>
    <tr>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>4</td>
        <td>US04</td>
        <td>Eliminar cuenta Usuario</td>
        <td>Como usuario de la plataforma de MedicDefense,necesito poder eliminar mi cuenta en caso sea necesario para no tener vinculo con el sitio web.</td>
    </tr>
     <tr>
        <td>5</td>
        <td>US05</td>
        <td>Visualización de lista de tipos de suscripción</td>
        <td>Como usuario de la plataforma de MedicDefense,quiero visualizar la lista de tipos de suscripción para seleccionar alguno.</td>
    </tr>
    <tr>
        <td>6</td>
        <td>US06</td>
        <td>Visualizar actividades del Usuario</td>
        <td>Como usuario de la plataforma de MedicDefense,quiero visualizar la lista de las actividades que realizo para tener un control y orden en las acciones que realizo.</td>
    </tr>
</table>