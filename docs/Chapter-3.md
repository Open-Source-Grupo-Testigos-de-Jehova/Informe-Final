# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

**_Segmento Objetivo 1: Clara Diaz - Doctora_**
![alt text](<../assets/imgs/Clara Diaz - To-be.jpg>)

**_Segmento Objetivo 2: Carlos Orbegozo - Estudiante de Medicina_**
![alt text](<../assets/imgs/Carlos - To - Be.jpg>)

## 3.2. User Stories
| Epics             |User Stories|
|-----------------------------|---------|
| Autenticación y autorización| 1. Gestión de las cuentas de los usuarios<br>2. Verificación de credenciales médicas<br>3. Gestión de roles de cuentas|
|||
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

| ID | US01|
|----------|-------------|
| Nombre   | Registro Cliente  |
| Cliente  | Cliente |
| Declaración   | Como Cliente quiero registrarme en el sitio web para acceder a sus servicios |
|  Descripción  | El cliente se registra en el sitio web |
|     Escenario y criterio de aceptación       | Escenario 1: El cliente no tiene una cuenta |
|            | DADO que el Cliente es nuevo en el sitio web |
|            | CUANDO no se ha sido registrado anteriormente |
|            | ENTONCES al rellenar el formulario del aplicativo móvil se registrará exitosamente |
|            | Escenario 2: El Cliente tiene una cuenta |
|            | DADO que el Cliente es no es nuevo en el sitio web |
|            | CUANDO ha sido registrado anteriormente |
|            | ENTONCES al rellenar el formulario con los mismos datos no se registrará |
|            | Escenario 3: El Cliente intenta registrarse pero no completa el nombre |
|            | DADO que intenta registrarse en el sitio web |
|            | CUANDO completa todos los otros datos pero deja vacío el nombre |
|            | ENTONCES al darle registrar le aparecerá el mensaje "El nombre del Cliente es obligatorio". |
|            | Escenario 4: El Cliente intenta registrarse pero no completa el apellido |
|            | DADO que intenta registrarse en el sitio web |
|            | CUANDO completa todos los otros datos pero deja vacío el apellido |
|            | ENTONCES al darle registrar le aparecerá el mensaje "El apellido del Cliente es obligatorio". |
|            | Escenario 5: El Cliente intenta registrarse pero no completa la contraseña |
|            | DADO que intenta registrarse en el sitio web |
|            | CUANDO completa todos los otros datos pero deja en blanco la contraseña |
|            | ENTONCES al darle registro le aparecerá el mensaje "La contraseña es obligatoria". |
|            | Escenario 6: El Cliente intenta registrarse pero no completa la edad |
|            | DADO que intenta registrarse en el sitio web |
|            | CUANDO completa todos los otros datos pero deja en blanco la edad |
|            | ENTONCES al darle registro le aparecerá el mensaje "La edad es obligatoria". |
|            | Escenario 7: El Cliente intenta registrarse pero pone una edad menor a 18 |
|            | DADO que intenta registrarse en el sitio web |
|            | CUANDO completa todos los otros datos pero pone una edad menor a 18 |
|            | ENTONCES al darle registrar le aparecerá el mensaje "La edad mínima es de 18". |
|            | Escenario 8: El Cliente intenta registrarse pero pone una edad mayor a 30 |
|            | DADO que intenta registrarse en el sitio web |
|            | CUANDO completa todos los otros datos pero pone pone una edad mayor a 30 |
|            | ENTONCES al darle registrar le aparecerá el mensaje "La edad máxima es de 30". |
|            | Escenario 9: El Cliente intenta registrarse pero no completa el correo |
|            | DADO que intenta registrarse en el sitio web |
|            | CUANDO completa todos los otros datos pero deja en blanco el correo |
|            | ENTONCES al darle registro le aparecerá el mensaje "El Email es obligatorio". |
|            | Escenario 10: El Cliente intenta registrarse pero pone un correo inválido |
|            | DADO que intenta registrarse en el sitio web |
|            | CUANDO completa todos los otros datos pero el correo no es válido |
|            | ENTONCES al darle registro le aparecerá el mensaje "El Email es inválido". |
|            | Escenario 11: El Cliente intenta registrarse pero no ingresa 9 dígitos en el teléfono |
|            | DADO que intenta registrarse en el sitio web |
|            | CUANDO completa todos los otros datos pero no ingresa 9 dígitos en el teléfono |
|            | ENTONCES al darle registro le aparecerá el mensaje "El teléfono es inválido". |
|            | Escenario 12: El Cliente quiere registrarse pero completa erróneamente el teléfono |
|            | DADO que intenta registrarse en el sitio web |
|            | CUANDO completa todos los otros datos pero no completa correctamente el teléfono |
|            | ENTONCES al darle actualizar le aparecerá el mensaje "Solo se admiten números". |


| ID | US02|
|----------|-------------|
| Nombre   | Eliminar cuenta Cliente |
| Cliente  | Cliente |
| Declaración   | Como Cliente quiero eliminarón mi cuenta |
|  Descripción  | El cliente elimina su cuenta |
|     Escenario y criterio de aceptación       | Escenario 1: El cliente elimina su cuenta |
|            |DADO de que el Cliente quiere eliminar su cuenta del sitio web  |
|            | CUANDO éste decidido a hacerlo |
|            |ENTONCES al presionar el botón "eliminar cuenta" del apartado de configuración se eliminara su cuenta exitosamente |

| ID | US03|
|----------|-------------|
| Nombre   | Visualización de lista de tipos de suscripción |
| Cliente  | Cliente |
| Declaración   | Como Clientes quiero visualizar la lista de tipos de suscripción para seleccionar alguno |
|  Descripción  | El Cliente quiere visualizar los tipos de suscripciones de el sitio web |
|     Escenario y criterio de aceptación       | Escenario 1: El Cliente quiere visualizar tipos de suscripciones |
|            |DADO de que el Cliente quiere visualizar los tipos de suscripciones enl sitio web  |
|            | CUANDO tiene curiosidad sobre los precios de las suscripciones para usarl sitio web |
|            |ENTONCES irá al apartado "suscripciones" dentro del sitio web y podrá ver las promociones que tiene el sitio web |

## 3.3. Impact Mapping

## 3.4. Product Backlog
