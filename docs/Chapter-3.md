# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

**_Segmento Objetivo 1: Clara Diaz - Doctora_**
![alt text](<../assets/imgs/Clara Diaz - To-be.jpg>)

**_Segmento Objetivo 2: Carlos Orbegozo - Estudiante de Medicina_**
![alt text](<../assets/imgs/Carlos - To - Be.jpg>)

## 3.2. User Stories

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
