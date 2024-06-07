# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

En esta sección se resume toda la información recopilada, analizando el codigo que utilizamos y la arquitectura y principios de ingenieria que empleamos a lo largo de nuestro trabajo.

### 5.1.1. Software Development Environment Configuration

En la siguiente sección se describe la ruta de referencia de cada uno de los productos de software para que cualquier miembro del equipo pueda desarrollar cada punto del trabajo.

- **UXPressia:** Plataforma que nos permitirá crear los user stories y también realizar múltiples mapas para evaluar sus prioridades. Además, ofrece opciones gráficas para mejorar el aspecto de nuestro trabajo. Puedes acceder a la plataforma en el siguiente enlace: [UXPressia](https://www.uxpressia.com/)
- **Figma:** Herramienta colaborativa que nos permitirá desarrollar los respectivos Wireframes y Mockups de nuestra Landing Page. Se puede acceder a la plataforma en el siguiente enlace: [Figma](https://www.figma.com/).
- **Vertabelo:** Plataforma que nos permitirá crear nuestro Diagrama de Base de Datos. Se puede acceder a la plataforma en el siguiente enlace: [Vertabelo](https://www.vertabelo.com/).
- **LucidChart:** Aplicación web destinada a la elaboración de Wireflows, Lean UX Canvas, User Flows y Diagramas de clases. Se puede acceder a la plataforma en el siguiente enlace: [LucidChart](https://www.lucidchart.com/).
- **GitHub:** Repositorio colaborativo en la nube utilizado para almacenar los avances de nuestro proyecto. Se puede acceder a la plataforma en el siguiente enlace: [Github](https://github.com/).
- **Visual Studio Code:** Entorno de desarrollo utilizado por nuestro equipo para el desarrollo del proyecto en general, incluido el Informe. Se puede acceder a la plataforma en el siguiente enlace: [Visual Studio Code](https://code.visualstudio.com/).
- **GitHub Pages:** Plataforma que permite hacer deployments sencillos y rápidos para nuestras páginas web. Se puede acceder a la plataforma en el siguiente enlace: [Github Pages](https://pages.github.com/).

- **HTML5:** Lenguaje para la elaboración de nuestra página web.
- **CSS3:** Tecnología para darle estilos a nuestra página web.
- **JavaScript:** Lenguaje de programación orientado a objetos que nos sirvió para implementar funcionalidades en nuestra Landing Page.

### 5.1.2. Source Code Management

Para gestionar las modificaciones en nuestro proyecto, emplearemos GitHub como plataforma y sistema de control de versiones. A continuación, se detallan los repositorios de GitHub para cada uno de nuestros productos:

- Organización del Equipo: https://github.com/Open-Source-Grupo-Testigos-de-Jehova
- Repositorio del Informe: https://github.com/Open-Source-Grupo-Testigos-de-Jehova/Informe-Final
- Repositorio del Landing Page: https://github.com/Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense
- Enlace del Landing Page: https://open-source-grupo-testigos-de-jehova.github.io/Landing-page-MedicDefense/
- Repositorio del Front-End: https://github.com/Open-Source-Grupo-Testigos-de-Jehova/frontend-app

Para estructurar nuestro control de versiones, implementaremos el modelo GitFlow como nuestro flujo de trabajo estándar. Esto implicará la creación de las siguientes ramas, además de la rama principal (main):

- Develop Branch: Esta rama contendrá el código en desarrollo y servirá como base para la integración de nuevas funcionalidades.
- Feature Branches: Cada nueva característica que se implemente requerirá su propio branch. Utilizaremos la convención de nombrar los branches de características como "feature/nombre-de-la-caracteristica".
- Release Branches: Antes de lanzar una nueva versión, crearemos una rama de release para realizar pruebas finales y correcciones.
- Hotfix Branches: En caso de surgir problemas en el desarrollo, se crearán branches de hotfix para poder solucionarlos sin afectar la rama principal.

Además, seguiremos el estándar establecido por Conventional Commits para asegurar una estructura clara y consistente en nuestros Commits, facilitando la colaboración y la comprensión del historial de versiones en nuestro equipo.

### 5.1.3. Source Code Style Guide & Conventions

A continuación, se detallan las referencias y convenciones que adoptaremos para programar en los diferentes lenguajes utilizados en nuestro proyecto:

Utilizaremos las siguientes referencias para establecer nuestras convenciones.
1. **HTML**:
- "HTML Style Guide and Coding Conventions"
- "Google HTML/CSS Style Guide"

2. **CSS**:
- "Google HTML/CSS Style Guide"

3. **JavaScript**:
- "Google JavaScript Style Guide"
- "MDN JavaScript guidelines"
- "W3C JavaScript Style Guide"
- "Angular coding style guide".

4. **Gherkin**:
- "Gherkin Conventions for Readable Specifications".

Es importante destacar que todas las convenciones y referencias mencionadas están en inglés, siguiendo las prácticas comunes en el desarrollo de software. De tal modo que, al seguir estas referencias nos ayudará a mantener un código claro, coherente y fácilmente comprensible para todo el equipo de desarrollo.

### 5.1.4. Software Deployment Configuration

Para desplegar nuestra landing page en la plataforma de GitHub, seguimos los siguientes pasos:

1. Creación del Repositorio Remoto en GitHub:
- Creamos un nuevo repositorio en GitHub de nuestro proyecto, el cual se utilizará para el desarrollo y deployment.
2. Inicialización del Repositorio:
- Se utilza el comando "*git init*" para inicializar el repositorio.
3. Subida de Archivos al Repositorio Remoto:
- Añadimos los archivos de nuestra landing page al repositorio local.
- Subimos los archivos al repositorio de GitHub con el comando "*git push -u origin master*" o sino utilizando Github Desktop.
4. Configuración de GitHub Pages:
- Accedemos a la sección de configuración del repositorio en GitHub y entramos al apartado de Github Pages.
- Seleccionamos la rama de GitHub Pages (main) como fuente para el deployment de nuestra Landing Page
5. Despliegue:
- Accedemos a la URL proporcionada por GitHub Pages para verificar que nuestra landing page se haya desplegado correctamente.

De tal modo, nuestra Landing Page estará inicializada utilizando Github Pages y podrá ser visible para cualquier usuario que tenga el enlace.
Enlace del Landing Page: https://open-source-grupo-testigos-de-jehova.github.io/Landing-page-MedicDefense/

Para desplegar el primer avance del FrontEnd Web Application se utilizó la plataforma Netlify.
1. Selecciona GitHub como proveedor de Git y autorizamos a Netlify para acceder a tus repositorios.

2. Elegimos el repositorio que contiene el proyecto de Angular.

3. Configura las opciones de compilación:
- Comando de compilación: ng build --prod
- Directorio de publicación: dist/frontendApp
- Hacemos clic en "Deploy site" para iniciar el proceso de despliegue.

4. Netlify compilará y desplegará automáticamente el proyecto Angular. 
- Una vez que el despliegue esté completo, nos proporcionará una URL para el sitio.

Enlace de la primera version del Frontend App: https://medicdefense.netlify.app/

## 5.2. Landing Page, Services & Applications Implementation
En esta sección se explicará y evidenciará el proceso de implementación, pruebas,
documentación y despliegue del Landing Page.

### 5.2.1. Sprint 1

### 5.2.1.1. Sprint Planning 1

Para este primer sprint nos enfocaremos en los tasks para la
elaboración de la Landing Page. Nos dividiremos entre nosotros cada
una de las tareas identificadas para el sprint.
<table>
<tr>
    <th colspan="5">Sprint #</th>
    <th colspan="9">Sprint 1</th>
  </tr>
      <tr>
    <td colspan="13">Sprint Planning Background</td>
  </tr>
  <tr>
    <td colspan="5">Date</td>
    <td colspan="8">2024-04-12</td>
</tr>
  <tr>
    <td colspan="5">Time</td>
    <td colspan="8">11:30 PM</td>
  </tr>
  <tr>
    <td colspan="5">Location</td>
    <td colspan="8">Via Discord y Google Meet</td>
<tr>
    <td colspan="5">Prepared By</td>
    <td colspan="8">Gabriel Garcia</td>
</tr>
<tr>
    <td colspan="5">Attendees (to planning meeting)</td>
    <td colspan="8">Gabriel Garcia, Diego Flores, Fabricio Apaza, Mathias Vasquez, Anatoly Noriega</td>
</tr>
<tr>
    <td colspan="5">Sprint n – 1 Review Summary</td>
    <td colspan="8">En esta seccion se planteo el desarrollo del landing page para nuestro proyecto llamado MedicDefense</td>
</tr>
<tr>
    <td colspan="5">Sprint n – 1 Retrospective Summary</td>
    <td colspan="8">En esta seccion todos los integrantes mencionaron tener aciertos en partes del codigo y en otras partes poder mejorar sus habilidades realizando landing pages</td>
</tr>
<tr>
    <td colspan="13">Sprint Goal & User Stories</td>
</tr>
<tr>
    <td colspan="5">Sprint n Goal</td>
    <td colspan="8">Culminar el landing Page</td>
</tr>
<tr>
    <td colspan="5">Sprint n Velocity</td>
    <td colspan="8">6 story points</td>
</tr>
<tr>
    <td colspan="5">Sum of Story Points</td>
    <td colspan="8">9 Story Points</td>
</tr>
</table>

### 5.2.1.2. Sprint Backlog 1

<table>
<tr>
    <th colspan="3">Sprint #</th>
    <th colspan="10">Sprint 1</th>
  </tr>
      <tr>
    <td colspan="3">User Story</td>
    <td colspan="10">Work-Item/Task</td>
  </tr>
  <tr>
    <td colspan="1">Id</td>
    <td colspan="2">Title</td>
    <td colspan="1">Id</td>
    <td colspan="2">Title</td>
    <td colspan="3">Description</td>
    <td colspan="1"> Estimation</td>
    <td colspan="2">Assigned To</td>
    <td colspan="1">Status(To-do /InProcess /To-Review /Done)</td>
</tr>
  <tr>
    <td colspan="1">5</td>
    <td colspan="2">Visualización de lista de tipos de suscripción</td>
    <td colspan="1">1</td>
    <td colspan="2">Añadir funcion para mostrar lista de tipos de suscrpción</td>
    <td colspan="3">Como visitador del alding page de MedicDefense,quiero visitar la lista de tipos de suscripción para seleccionar alguno.</td>
    <td colspan="1">1</td>
    <td colspan="2">Fabricio</td>
    <td colspan="1">Done</td>
  </tr>
  <tr>
    <td colspan="1">16</td>
    <td colspan="2">Sección de Creadores</td>
    <td colspan="1">2</td>
    <td colspan="2">Añadir funcion para mostrar los creadores de la empresa</td>
    <td colspan="3">Como visitante de la landing page de MedicDefense, quiero ver una sección de creadores para facilitar tener el conocimiento de los creadores de la empresa.</td>
    <td colspan="1">1</td>
    <td colspan="2">Mathias</td>
    <td colspan="1">Done</td>
<tr>
    <td colspan="1">13</td>
    <td colspan="2">Visualización de servicios</td>
    <td colspan="1">3</td>
    <td colspan="2">Añadir sección de servicios</td>
    <td colspan="3">Como visitante de la landing page de MedicDefense, quiero ver una sección donde se expliquen los servicios para estar mejor informado a la hora de confiar en su servicio.</td>
    <td colspan="1">1</td>
    <td colspan="2">Anatoly</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">14</td>
    <td colspan="2">Sección de contacto</td>
    <td colspan="1">4</td>
    <td colspan="2">Añadir sección de contacto</td>
    <td colspan="3">Como visitante de la landing page de MedicDefense, quiero ver una sección de contacto para facilitar la comunicación al momento de solicitar el servicio.</td>
    <td colspan="1">1</td>
    <td colspan="2">Gabriel</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">15</td>
    <td colspan="2">Sección nosotros</td>
    <td colspan="1">5</td>
    <td colspan="2">Añadir sección nosotros</td>
    <td colspan="3">Como visitante de la landing page de MedicDefense, quiero ver una sección nosotros para informarme sobre la empresa que está brindando los servicios.</td>
    <td colspan="1">1</td>
    <td colspan="2">Anatoly</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">16</td>
    <td colspan="2">Sección de inicio</td>
    <td colspan="1">6</td>
    <td colspan="2">Añadir sección de inicio</td>
    <td colspan="3">Como visitante de la landing page de MedicDefense, quiero ver una sección de inicio con una barra de navegación para poder desplazarme mejor por la landing page.</td>
    <td colspan="1">1</td>
    <td colspan="2">Diego</td>
    <td colspan="1">Done</td>
</tr>
</table>

### 5.2.1.3. Development Evidence for Sprint Review

<table>
    <tr>
        <th colspan="2">Repository</th>
        <th colspan="2">Branch</th>
        <th colspan="2">Commit Id</th>
        <th colspan="2">Commit Message</th>
        <th colspan="2">Commit Message Body</th>
        <th colspan="2">Commited on (Date)</th>
    </tr>
        <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
        <td colspan="2">Main</td>
        <td colspan="2">b6d10b1</td>
        <td colspan="2">feat: added contact section</td>
        <td colspan="2">-</td>
        <td colspan="2">06/04/2024</td>
    </tr>
        <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
        <td colspan="2">Main</td>
        <td colspan="2">4808ace</td>
        <td colspan="2">feat: Added "Our Services" code</td>
        <td colspan="2">-</td>
        <td colspan="2">06/04/2024</td>
    </tr>
     <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
        <td colspan="2">Main</td>
        <td colspan="2">168d5f0</td>
        <td colspan="2">chore: initial commit</td>
        <td colspan="2">-</td>
        <td colspan="2">06/04/2024</td>
    </tr>
    <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
        <td colspan="2">Main</td>
        <td colspan="2">7ace2eb</td>
        <td colspan="2">fix: updated image errors</td>
        <td colspan="2">-</td>
        <td colspan="2">10/04/2024</td>
    </tr>
    <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
        <td colspan="2">Main</td>
        <td colspan="2">b96e52c</td>
        <td colspan="2">fix: updated menu.js</td>
        <td colspan="2">-</td>
        <td colspan="2">10/04/2024</td>
    </tr>
    <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
        <td colspan="2">Main</td>
        <td colspan="2">0ad72ce</td>
        <td colspan="2">feat: add 'About Us' and 'Our Services' sections to landing page</td>
        <td colspan="2">-</td>
        <td colspan="2">06/04/2024</td>
    </tr>
</table>

### 5.2.1.4. Testing Suite Evidence for Sprint Review

**Unit Tests**

Test de visualización de lista de tipos de suscripción

- Clase relacionada: SubscriptionService

- Comportamiento: Verificar que la función para mostrar la lista de tipos de suscripción funciona correctamente.

Test de visualización de servicios

- Clase relacionada: ServiceController

- Comportamiento: Verificar que la sección de servicios se muestra correctamente en la página principal.

Test de visualización de sección de contacto

- Clase relacionada: ContactController

- Comportamiento: Verificar que la sección de contacto se muestra correctamente en la página principal.

Test de visualización de sección nosotros

- Clase relacionada: AboutUsController

- Comportamiento: Verificar que la sección nosotros se muestra correctamente en la página principal.

Test de visualización de sección de inicio

- Clase relacionada: NavigationController

- Comportamiento: Verificar que la barra de navegación se muestra correctamente en la página principal.

<table>
  <thead>
    <tr>
      <th>Repository</th>
      <th>Branch</th>
      <th>Commit Id</th>
      <th>Commit Message</th>
      <th>Commit Message Body</th>
      <th>Committed on (Date)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>main</td>
      <td>168d5f0532985817301307d0eb0e651ebb233a77</td>
      <td>initial commit</td>
      <td>- Created initial commit for landing page</td>
      <td>2024-04-06</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>main</td>
      <td>4808acedb5738c031b71416e6ea0fff5d057e0e5</td>
      <td>Added "Our Services"</td>
      <td>- created our services section to landing page</td>
      <td>2024-04-06</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>main</td>
      <td>b6d10b1525acdd2e4914c5de25d2ecb836884e94</td>
      <td>added contact section</td>
      <td>- created our contact section to landing page</td>
      <td>2024-04-06</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>main</td>
      <td>555441bd8dc434640170aae69d2f517df739251a</td>
      <td>Added "About us" and "Our Services"</td>
      <td>- Created About us and Our Services to landing page</td>
      <td>2024-04-06</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>main</td>
      <td>a778131e10a50a903dfd234b986164615c9871e2</td>
      <td>Added creators section</td>
      <td>- Created Creators to landing page</td>
      <td>2024-04-08</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>main</td>
      <td>2d479db24e63fa3b3e24f141b8bfc56d5efc2883</td>
      <td>update creators section</td>
      <td>- update creators section to landing page</td>
      <td>2024-04-09</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>main</td>
      <td>7ace2ebbe27f9ea32f3e94c00e516610f996e68d</td>
      <td>updated image errors</td>
      <td>- Resolved image errors by updating references or fixing issues, ensuring proper display of images</td>
      <td>2024-04-10</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>main</td>
      <td>5b77d4e726f5b1b0dac3a9b6f17c8731562d9608</td>
      <td>updated contact section</td>
      <td>- Enhanced the contact section by updating its functionality or improving user experience</td>
      <td>2024-04-10</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>main</td>
      <td>b96e52c2884c042e2a27a25de945b9f263f9365a</td>
      <td>updated menu.js</td>
      <td>- Updated menu.js file, potentially to improve menu functionality or fix bugs</td>
      <td>2024-04-10</td>
    </tr>
  </tbody>
</table>


### 5.2.1.5. Execution Evidence for Sprint Review

Para esta primera entrega, nuestro equipo a conseguido elaborar la Landing Page del proyecto "MedicDefense". De tal modo, se podrá visualizar la información necesaria de lo que ofrece nuestro proyecto.

**Sección de inicio**: Se implementó el Header de nuestra Landing Page.
![alt text](../assets/imgs/header.png)
**Sección de Nosotros**: Se implementó la sección de nosotros para describir un poco sobre quienes somos.
![alt text](../assets/imgs/nosotros.png)
**Sección de Servicios**: Se implementó la sección de los servicios ofrecidos.
![alt text](../assets/imgs/servicios.png)
**Sección de Planes**: Se implementó la sección de ver los tipos de suscripción.
![alt text](<../assets/imgs/nuestros planes.png>)
**Sección de contacto y creadores**: Se añadió la sección de contacto para facilitar la comunicación con los usuarios y la información de los creadores.
![alt text](../assets/imgs/footer.png)

### 5.2.1.6. Services Documentation Evidence for Sprint Review

En este sprint solo se trabajó el landing page.

### 5.2.1.7. Software Deployment Evidence for Sprint Review

Para el despliegue del Landing Page, hemos utilizado la herramienta de Github Pages para poder hacer un deployment. Para eso, hemos creado un repositorio donde hemos colocado el código de desarrollo de nuestra Landing Page.

![alt text](<../assets/imgs/Github Repositorio.png>)

Una vez creado el repositorio, entraremos a configuración del repositorio y escogemos el apartado de Pages. Se coloca la información necesaria, como la fuente del branch a utilizar para realizar el deployment. Luego de eso, Github Pages nos brindará el link y desplegará nuestra landing page en la Web.

![alt text](<../assets/imgs/Github Pages.png>)

### 5.2.1.8. Team Collaboration Insights during Sprint

Para el desarrollo de este primer sprint, todos los miembros del equipo desarrollaron y colaboraron de manera activa y continua. De tal modo, se muestra como evidencia los insights de cada miembro del equipo.

Commits:

![alt text](../assets/imgs/Insights.png)

Analiticas de Colaboración:

![alt text](../assets/imgs/AnaliticasLanding.png)

### 5.2.2. Sprint 2

### 5.2.2.1. Sprint Planning 2

Para este segundo sprint nos enfocaremos en los tasks para la
elaboración de Frontend Web Application. Nos dividiremos entre nosotros cada
una de las tareas identificadas para el sprint.

<table>
<tr>
    <th colspan="5">Sprint #</th>
    <th colspan="9">Sprint 2</th>
  </tr>
      <tr>
    <td colspan="13">Sprint Planning Background</td>
  </tr>
  <tr>
    <td colspan="5">Date</td>
    <td colspan="8">2024-04-28</td>
</tr>
  <tr>
    <td colspan="5">Time</td>
    <td colspan="8">8:40 PM</td>
  </tr>
  <tr>
    <td colspan="5">Location</td>
    <td colspan="8">Via Discord y Google Meet</td>
<tr>
    <td colspan="5">Prepared By</td>
    <td colspan="8">Gabriel Garcia</td>
</tr>
<tr>
    <td colspan="5">Attendees (to planning meeting)</td>
    <td colspan="8">Gabriel Garcia, Diego Flores, Fabricio Apaza, Mathias Vasquez, Anatoly Noriega</td>
</tr>
<tr>
    <td colspan="5">Sprint n – 2 Review Summary</td>
    <td colspan="8">En esta seccion se planteo el desarrollo la  primera version del frontend para nuestro proyecto llamado MedicDefense</td>
</tr>
<tr>
    <td colspan="5">Sprint n – 2 Retrospective Summary</td>
    <td colspan="8">En esta seccion todos los integrantes mencionaron tener aciertos en partes del codigo y en otras partes poder mejorar sus habilidades realizando el FrontEnd Web Application</td>
</tr>
<tr>
    <td colspan="13">Sprint Goal & User Stories</td>
</tr>
<tr>
    <td colspan="5">Sprint n Goal</td>
    <td colspan="8">Avance del FrontEnd Web Application</td>
</tr>
<tr>
    <td colspan="5">Sprint n Velocity</td>
    <td colspan="8">56 story points</td>
</tr>
<tr>
    <td colspan="5">Sum of Story Points</td>
    <td colspan="8">60 Story Points</td>
</tr>
</table>

### 5.2.2.2. Sprint Backlog 2

<table>
<tr>
    <th colspan="3">Sprint #</th>
    <th colspan="10">Sprint 2</th>
  </tr>
      <tr>
    <td colspan="3">User Story</td>
    <td colspan="10">Work-Item/Task</td>
  </tr>
  <tr>
    <td colspan="1">Id</td>
    <td colspan="2">Title</td>
    <td colspan="1">Id</td>
    <td colspan="2">Title</td>
    <td colspan="3">Description</td>
    <td colspan="1"> Estimation</td>
    <td colspan="2">Assigned To</td>
    <td colspan="1">Status(To-do /InProcess /To-Review /Done)</td>
</tr>
  <tr>
    <td colspan="1">25</td>
    <td colspan="2">Configuración de la base de datos</td>
    <td colspan="1">1</td>
    <td colspan="2">Crear y Configurar el Fake-API para el FrontEnd</td>
    <td colspan="3">Como desarrollador, necesito diseñar y configurar la estructura de la base de datos para almacenar la información de los abogados, incluyendo campos como nombre, especialidad, ubicación, etc.</td>
    <td colspan="1">3</td>
    <td colspan="2">Gabriel</td>
    <td colspan="1">Done</td>
  </tr>
  <tr>
    <td colspan="1">26</td>
    <td colspan="2">Desarrollo del frontend para la lista de abogados</td>
    <td colspan="1">2</td>
    <td colspan="2">Añadir Lista de Abogados</td>
    <td colspan="3">Como desarrollador, necesito crear componentes en el frontend para mostrar la lista de abogados y diseñar la interfaz de usuario utilizando la biblioteca Angular.</td>
    <td colspan="1">5</td>
    <td colspan="2">Gabriel</td>
    <td colspan="1">Done</td>
<tr>
    <td colspan="1">27</td>
    <td colspan="2">Integración del toolbar</td>
    <td colspan="1">3</td>
    <td colspan="2">Añadir Toolbar</td>
    <td colspan="3">Como desarrollador, necesito implementar un toolbar en el frontend y conectarlo con las diferentes opciones de la aplicación, asegurando una navegación fluida entre las secciones.</td>
    <td colspan="1">5</td>
    <td colspan="2">Gabriel</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">28</td>
    <td colspan="2">Estilizado y diseño responsivo</td>
    <td colspan="1">4</td>
    <td colspan="2">Añadir estilizado y diseño responsivo</td>
    <td colspan="3">Como desarrollador, necesito aplicar estilos CSS para garantizar un diseño atractivo y responsivo en todas las páginas de la aplicación, utilizando frameworks como Bootstrap o Material-UI.</td>
    <td colspan="1">5</td>
    <td colspan="2">Gabriel</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">29</td>
    <td colspan="2">Implementación de la funcionalidad de búsqueda de abogados</td>
    <td colspan="1">5</td>
    <td colspan="2">Añadir busqueda de abogados</td>
    <td colspan="3">Como desarrollador, necesito agregar una función de búsqueda en la página de lista de abogados para que los usuarios puedan buscar abogados por nombre o especialidad.</td>
    <td colspan="1">3</td>
    <td colspan="2">Gabriel</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">30</td>
    <td colspan="2">Implementación de la paginación de resultados</td>
    <td colspan="1">6</td>
    <td colspan="2">Añadir la paginación de resultados</td>
    <td colspan="3">Como desarrollador, necesito agregar funcionalidad de paginación en la página de lista de abogados para manejar grandes cantidades de resultados y mejorar la experiencia del usuario.</td>
    <td colspan="1">3</td>
    <td colspan="2">Gabriel</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">9</td>
    <td colspan="2">Perfil de abogado médico</td>
    <td colspan="1">7</td>
    <td colspan="2">Añadir Perfil de abogado médico</td>
    <td colspan="3">Como usuario, quiero poder acceder al perfil completo de un abogado específico al hacer clic en el botón "Perfil".</td>
    <td colspan="1">3</td>
    <td colspan="2">Fabricio</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">31</td>
    <td colspan="2">Implementar card que se superpone para mostrar perfiles de abogados</td>
    <td colspan="1">8</td>
    <td colspan="2">Añadir Card que muestre perfil de abogados</td>
    <td colspan="3">Como desarrollador quiero implementar un card que se superpone para mostrar los perfiles completos de los abogados seleccionados.</td>
    <td colspan="1">5</td>
    <td colspan="2">Fabricio</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">32</td>
    <td colspan="2">Implementar método para cargar información de abogado en el card que se superpone</td>
    <td colspan="1">9</td>
    <td colspan="2">Añadir metodo para cargar la información de abogado en el card</td>
    <td colspan="3">Como desarrollador quiero implementar un método para cargar dinámicamente la información completa de un abogado seleccionado, para proporcionar a los usuarios una experiencia fluida y sin problemas al explorar perfiles de abogados.</td>
    <td colspan="1">5</td>
    <td colspan="2">Fabricio</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">33</td>
    <td colspan="2">Implementación de la Entidad de Usuario</td>
    <td colspan="1">10</td>
    <td colspan="2">Añadir entidad de Usuario con sus respectivos atributos</td>
    <td colspan="3">Como desarrollador, quiero crear la entidad de usuario con todos los atributos necesarios para representar a médicos y estudiantes en la plataforma.</td>
    <td colspan="1">5</td>
    <td colspan="2">Anatoly</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">34</td>
    <td colspan="2">Diseño de la Sección de Perfil de Usuario</td>
    <td colspan="1">11</td>
    <td colspan="2">Añadir interfaz del perfil de usuario</td>
    <td colspan="3">Como desarrollador, quiero implementar un servicio de notificaciones, para mantener a los usuarios informados.</td>
    <td colspan="1">3</td>
    <td colspan="2">Anatoly</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">35</td>
    <td colspan="2">Diseño de la Interfaz de Edición de Perfil de Usuario</td>
    <td colspan="1">12</td>
    <td colspan="2">Añadir interfaz de edición del perfil de usuario</td>
    <td colspan="3">Como desarrollador, quiero diseñar la interfaz de edición de perfil para que los usuarios visualicen de manera clara los campos que pueden modificar en su perfil.</td>
    <td colspan="1">3</td>
    <td colspan="2">Anatoly</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">36</td>
    <td colspan="2">Diseño de la Interfaz de Edición de Filtros</td>
    <td colspan="1">13</td>
    <td colspan="2">Añadir interfaz de filtro</td>
    <td colspan="3">Como desarrollador, quiero diseñar la interfaz de filtros para que los usuarios visualicen de manera clara los campos que pueden seleccionar.</td>
    <td colspan="1">3</td>
    <td colspan="2">Mathias</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">37</td>
    <td colspan="2">Diseño de la sección Suscripciones</td>
    <td colspan="1">14</td>
    <td colspan="2">Añadir diseño de la seccion suscripciones</td>
    <td colspan="3">Como desarrollador, quiero implementar la sección de suscripción para obtener ayuda legal en caso de cometer alguna negligencia médica, para estar protegido legalmente.</td>
    <td colspan="1">3</td>
    <td colspan="2">Diego</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">38</td>
    <td colspan="2">Diseño de la interfaz Suscripciones</td>
    <td colspan="1">15</td>
    <td colspan="2">Añadir diseño de la interfaz Suscripciones</td>
    <td colspan="3">Como desarrollador, quiero implementar una interfaz donde se puede ver los detalles de la suscripción actual, para ver el plan seleccionado.</td>
    <td colspan="1">3</td>
    <td colspan="2">Diego</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">39</td>
    <td colspan="2">Diseño de la interfaz de pago Suscripciones</td>
    <td colspan="1">16</td>
    <td colspan="2">Añadir diseño de la interfaz de pago suscripciones</td>
    <td colspan="3">Como desarollador, quiero implementar una interfaz donde se pueda ingresar los detalles de una tarjeta de crédito y el monto a pagar, para completar el proceso de pago de la suscripción</td>
    <td colspan="1">3</td>
    <td colspan="2">Diego</td>
    <td colspan="1">Done</td>
</tr>
</table>

### 5.2.2.3. Development Evidence for Sprint Review

<table>
    <tr>
        <th colspan="2">Repository</th>
        <th colspan="2">Branch</th>
        <th colspan="2">Commit Id</th>
        <th colspan="2">Commit Message</th>
        <th colspan="2">Commit Message Body</th>
        <th colspan="2">Commited on (Date)</th>
    </tr>
        <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
        <td colspan="2">Develop</td>
        <td colspan="2">56853799d2969ae246d7b161ba4e729451f6e577</td>
        <td colspan="2">feat: added db.json and start.sh</td>
        <td colspan="2">-</td>
        <td colspan="2">27/04/24</td>
    </tr>
        <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
        <td colspan="2">Develop</td>
        <td colspan="2">eb08f314c976895d3b6b61955c81cdf96e3849fa</td>
        <td colspan="2">feat(static-content): added lawyers list and page no found.</td>
        <td colspan="2">-</td>
        <td colspan="2">27/04/24</td>
    </tr>
     <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
        <td colspan="2">Develop</td>
        <td colspan="2">81820b0e85b3959ccada181ae71969f108eb4b4e</td>
        <td colspan="2">feat(main-view): implemented main view with in-app-navigation.</td>
        <td colspan="2">-</td>
        <td colspan="2">27/04/24</td>
    </tr>
    <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
        <td colspan="2">Develop</td>
        <td colspan="2">341a49cb0a3501c91a29f67ae765835fa5529f47</td>
        <td colspan="2">feat(static-content): added lawyers profile</td>
        <td colspan="2">-</td>
        <td colspan="2">27/04/24</td>
    </tr>
    <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
        <td colspan="2">Develop</td>
        <td colspan="2">d1b71f4b7cde4b5d98ebf23b8623a6fbefb3ce14</td>
        <td colspan="2">feat(view): implemented view with lawyer-profile.</td>
        <td colspan="2">-</td>
        <td colspan="2">27/04/24</td>
    </tr>
    <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
        <td colspan="2">Develop</td>
        <td colspan="2">62c825a4b204f8c4c0eef699fbb035f4b4d182e0</td>
        <td colspan="2">feat(user): add User entity in user.entity.ts</td>
        <td colspan="2">-</td>
        <td colspan="2">28/04/24</td>
    </tr>
    <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
        <td colspan="2">Develop</td>
        <td colspan="2">fe00f707be521ea6e879e506455385f660f96da2</td>
        <td colspan="2">fix(User): correct implementation details in user.entity</td>
        <td colspan="2">-</td>
        <td colspan="2">28/04/24</td>
    </tr>
    <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
        <td colspan="2">Develop</td>
        <td colspan="2">25985a15a89a3b85d7946a26459c1e381fa2e36a</td>
        <td colspan="2">feat(profile): add new profile section</td>
        <td colspan="2">-</td>
        <td colspan="2">28/04/24</td>
    </tr>
    <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
        <td colspan="2">Develop</td>
        <td colspan="2">faa63ccb4631215b6415454907e1d0d1ce8223a1</td>
        <td colspan="2">feat(edit-profile): add new edit profile section</td>
        <td colspan="2">-</td>
        <td colspan="2">28/04/24</td>
    </tr>
        <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
        <td colspan="2">Develop</td>
        <td colspan="2">4c4e0abefd64de10451044343ae6ac3ad7f0c882</td>
        <td colspan="2">feat(lawyer-filer): implemented lawyer filter interface.</td>
        <td colspan="2">-</td>
        <td colspan="2">28/04/24</td>
    </tr>
    </tr>
        <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
        <td colspan="2">Develop</td>
        <td colspan="2">a4750ac76217e8bd07bd816380e01bd9ec7fc03f</td>
        <td colspan="2">feat(suscription): added suscription pay component.</td>
        <td colspan="2">-</td>
        <td colspan="2">28/04/24</td>
    </tr>
</table>

### 5.2.2.4. Testing Suite Evidence for Sprint Review

<table>
  <thead>
    <tr>
      <th>Repository</th>
      <th>Branch</th>
      <th>Commit Id</th>
      <th>Commit Message</th>
      <th>Commit Message Body</th>
      <th>Committed on (Date)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>56853799d2969ae246d7b161ba4e729451f6e577</td>
      <td>added db.json and start.sh</td>
      <td>Se añadió "db.json", una base de datos en JSON, y "start.sh", un script de inicio.</td>
      <td>25/04/24</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>7b69a52051f2d9dde597eacf136d0371a5ae4895</td>
      <td>added enviroments support files</td>
      <td>se han incluido archivos de soporte para entornos para facilitar la configuración y el funcionamiento en diferentes contextos de desarrollo</td>
      <td>27/04/24</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>3ed377edaa934a4d8600c371840f8f070bb50dca</td>
      <td>update support file for fake api.</td>
      <td>Se ha actualizado el archivo de soporte para la API falsa</td>
      <td>27/04/24</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>024ce6a20f9f3509ab52f97bc9807b6e0880b89b</td>
      <td>added base service.</td>
      <td>Se ha añadido un servicio base</td>
      <td>27/04/24</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>389daa9d83492686b84c04617bd13c4b0a7d431a</td>
      <td>added lawyers service.</td>
      <td>Se ha agregado un servicio de abogados</td>
      <td>27/04/24</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>5546695c70d62a17dc3723248bb1b01fb79bb3a8</td>
      <td>added needed component modules.</td>
      <td>Se han añadido los módulos de componentes necesarios.</td>
      <td>27/04/24</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>eb08f314c976895d3b6b61955c81cdf96e3849fa</td>
      <td>added lawyers list and page no found.</td>
      <td>Se ha agregado una lista de abogados junto con una página de "no encontrada"</td>
      <td>27/04/24<</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>81820b0e85b3959ccada181ae71969f108eb4b4e</td>
      <td>implemented main view with in-app-navigation.</td>
      <td>Se ha implementado la vista principal con navegación dentro de la aplicación.</td>
      <td>27/04/24<</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>fa9adce5335da947940cb0601823775afd977752</td>
      <td>Merge branch 'feature/lawyer-listing-and-search' into develop</td>
      <td>Se ha fusionado la rama "feature/lawyer-listing-and-search" en la rama "develop".</td>
      <td>27/04/24<</td>
    </tr>
     <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>e80adf27d54d85d5be44f3102f5932cf67e0327a</td>
      <td>update instructions for development server in README.md</td>
      <td>Se han actualizado las instrucciones para el servidor de desarrollo en el archivo README.md.</td>
      <td>27/04/24<</td>
    </tr>
     <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>b8e6bdf85f74be07124736c75575b53dc7d0ec84</td>
      <td>update lawyer data in db.json</td>
      <td>Se ha actualizado la información de los abogados en el archivo db.json.</td>
      <td>27/04/24<</td>
    </tr>
     <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>1f46cdc48fd6d2ffa4710cb881a3280ab7bbe6e8</td>
      <td>update Lawyer entity in lawyer.entity.ts</td>
      <td>Se ha actualizado la entidad Lawyer en el archivo lawyer.entity.ts</td>
      <td>27/04/24<</td>
    </tr>
     <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>bd9cb406ffecec4f765e5e167c1555e1de0a808c</td>
      <td>added new components modules</td>
      <td>Se han añadido nuevos módulos de componentes.</td>
      <td>27/04/24<</td>
    </tr>
     <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>d3ed2f983be5a7e3a11de8bb64af0c428524a84d</td>
      <td>added a getter in base service.</td>
      <td>Se ha agregado un getter en el servicio base.</td>
      <td>27/04/24<</td>
    </tr>
     <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>341a49cb0a3501c91a29f67ae765835fa5529f47</td>
      <td>added lawyers profilep</td>
      <td>Se ha añadido el perfil de abogados</td>
      <td>27/04/24<</td>
    </tr>
     <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>d1b71f4b7cde4b5d98ebf23b8623a6fbefb3ce14</td>
      <td>implemented view with lawyer-profile.</td>
      <td>Se ha implementado la vista con el perfil de abogado.</td>
      <td>27/04/24<</td>
    </tr>
     <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>66d75e3663f011ad68fb924f28567f006f4964ad</td>
      <td>update photos in db.json</td>
      <td>Se han actualizado las fotos en el archivo db.json.</td>
      <td>27/04/24<</td>
    </tr>
     <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>1a72ac51cba21ee8921cf36e3f80f3eeb823d1ee</td>
      <td>update lawyers-profile styles</td>
      <td>Se han actualizado los estilos del perfil de abogados.</td>
      <td>27/04/24<</td>
    </tr>
     <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>d0bbb98716f8097eeaf5189b268c412b55cb10f4</td>
      <td>Merge branch 'feature/lawyer-profile' into develop</td>
      <td>Se ha fusionado la rama "feature/lawyer-profile" en la rama "develop".</td>
      <td>27/04/24<</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>116092fcc09ac91471e2b14786a1bd5b63a76886</td>
      <td>error in word landing.</td>
      <td>Hay un error en la palabra "landing".</td>
      <td>28/04/24<</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>768640695baa5212a8468eab129ee40f075574f2</td>
      <td>added suscription component.</td>
      <td>Se ha añadido el componente de suscripción.</td>
      <td>28/04/24<</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>d2cc4392fde87e91e1384c713e7866841914bc58</td>
      <td>readded suscription component.</td>
      <td>Se ha vuelto a añadir el componente de suscripción.</td>
      <td>28/04/24<</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>62c825a4b204f8c4c0eef699fbb035f4b4d182e0</td>
      <td>correct implementation details in user.entity</td>
      <td>Se ha corregido la implementación en los detalles de la entidad de usuario en user.entity.</td>
      <td>28/04/24<</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>a4750ac76217e8bd07bd816380e01bd9ec7fc03f</td>
      <td>added suscription pay component.</td>
      <td>Se ha añadido el componente de pago de suscripción.</td>
      <td>28/04/24<</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>6f252c1e7912dc8ef870b1f3ec3158a76d7ff882</td>
      <td>removed unused constant.</td>
      <td>Se ha eliminado la constante no utilizada en la función de suscripción.</td>
      <td>28/04/24<</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>63b6c97512b83d1e9bd8b9acd0a4e8cd2711d620</td>
      <td>Merge branch 'feature/suscrptions' into develop</td>
      <td>Se ha fusionado la rama "feature/suscriptions" en la rama "develop".</td>
      <td>28/04/24<</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>25985a15a89a3b85d7946a26459c1e381fa2e36a</td>
      <td>feat(profile): add new profile section</td>
      <td>Se ha agregado una nueva sección de perfil.</td>
      <td>28/04/24<</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>faa63ccb4631215b6415454907e1d0d1ce8223a1</td>
      <td>feat(edit-profile): add new edit profile section</td>
      <td>Se ha agregado una nueva sección para editar el perfil.</td>
      <td>28/04/24<</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>7c236add4b5763054a50a5a0f0e7e3c70219af0e</td>
      <td>added summary section.</td>
      <td>Se ha añadido una sección de resumen al contenido estático.</td>
      <td>28/04/24<</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>42b7ef1ffc1d19010cbeaa1182ef2c5411e4bf84</td>
      <td>added needed component modules.</td>
      <td>Se han añadido los módulos de componentes necesarios para Material Design.</td>
      <td>29/04/24<</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>339016af024e40d825917f558c71654ef7ff0e36</td>
      <td>Merge branch 'feature/summary-section' into develop</td>
      <td>Se ha fusionado la rama "feature/summary-section" en la rama "develop".</td>
      <td>29/04/24<</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>b0305fea82b6e891369952034cbf40b556405c7e</td>
      <td>added lawyer filter component.</td>
      <td>Se ha añadido el componente de filtro de abogados.</td>
      <td>29/04/24<</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>4c4e0abefd64de10451044343ae6ac3ad7f0c882</td>
      <td>implemented lawyer filter interface.</td>
      <td>Se ha implementado la interfaz de filtro de abogados.</td>
      <td>29/04/24<</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td>42f53e5cda1a93e5a304b6a64bd5a4e423202d29</td>
      <td>Merge branch 'feature/lawyer-filter' into develop</td>
      <td>Se ha fusionado la rama "feature/lawyer-filter" en la rama "develop".</td>
      <td>29/04/24<</td>
    </tr>
  </tbody>
</table>


### 5.2.2.5. Execution Evidence for Sprint Review

Para esta segunda entrega, nuestro equipo a conseguido elaborar la primera versión de Frontend Web Application del proyecto "MedicDefense". De tal modo, se podrá visualizar la información necesaria de lo que ofrece nuestro proyecto.

Lista de Abogados y Toolbar:
![alt text](../assets/imgs/ListaAbogados.png)

Perfil Abogado:
![alt text](../assets/imgs/PerfilAbogado.png)

Busqueda Abogados:
![alt text](../assets/imgs/BusquedaAbogado.png)

Filtros Abogados:
![alt text](../assets/imgs/FiltrosAbogados.png)

Sección Resumen:
![alt text](../assets/imgs/ResumenAbogados.png)

Sección Suscripción:
![alt text](../assets/imgs/SuscripciónSección.png)

Suscripción Pago:
![alt text](../assets/imgs/SuscripciónPayment.png)

Sección Perfil Usuario:
![alt text](../assets/imgs/PerfilUsuario.png)

Editar Perfil Usuario:
![alt text](../assets/imgs/EditPerfilUser.png)


Enlace al video de Evidencia: https://upcedupe-my.sharepoint.com/:v:/g/personal/u201922146_upc_edu_pe/EcsD7o4DfFpPnvygTgabW9EBfx9hWmLUNARniRmaaV33MA?e=65UnnM&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

### 5.2.2.6. Services Documentation Evidence for Sprint Review

Durante este sprint, se ha desarrollado una Fake API de abogados que proporciona información sobre abogados ficticios. La API incluye detalles como el nombre del abogado, años de experiencia, especialización, casos ganados, tarifa por hora, correo electrónico y número de teléfono.

<table>
  <tr>
    <th>Endpoint</th>
    <th>Acción</th>
    <th>Verbo HTTP</th>
    <th>Sintaxis de Llamada</th>
    <th>Parámetros</th>
    <th>Ejemplo de Llamada</th>
    <th>Explicación del Response</th>
  </tr>
  <tr>
    <td>/api/lawyers</td>
    <td>Listar</td>
    <td>GET</td>
    <td>/api/lawyers</td>
    <td>-</td>
    <td>GET /api/lawyers</td>
    <td>200 OK: Devuelve una lista de todos los abogados.</td>
  </tr>
  <tr>
    <td>/api/lawyers/{id}</td>
    <td>Obtener</td>
    <td>GET</td>
    <td>/api/lawyers/{id}</td>
    <td>ID del abogado</td>
    <td>GET /api/lawyers/1</td>
    <td>200 OK: Devuelve los detalles del abogado con el ID especificado.</td>
  </tr>
</table>

Capturas de interaccion: 

-Creacion del Fake API

![alt text](../assets/imgs/fakeApi.png)

-Configuracion del servico HTTPClient

![alt text](../assets/imgs/lawyer-service.png)

-Uso en el componente lawyer-list

![alt text](../assets/imgs/lawyer-list.png)
-Iteracion en la vista HTML

![alt text](../assets/imgs/lawerlist-html.png)


Url del repositorio: https://github.com/Open-Source-Grupo-Testigos-de-Jehova/frontend-app

Commits relacionados: 

<table>
    <tr>
        <th colspan="2">Repository</th>
        <th colspan="2">Branch</th>
        <th colspan="2">Commit Id</th>
        <th colspan="2">Commit Message</th>
    </tr>
        <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
        <td colspan="2">Develop</td>
        <td colspan="2">56853799d2969ae246d7b161ba4e729451f6e577</td>
        <td colspan="2">feat: added db.json and start.sh</td>
    </tr>
        <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
        <td colspan="2">Develop</td>
        <td colspan="2">eb08f314c976895d3b6b61955c81cdf96e3849fa</td>
        <td colspan="2">feat(static-content): added lawyers list</td>
    </tr>
</table>    

### 5.2.2.7. Software Deployment Evidence for Sprint Review
Para el despliegue de la primera version del Frontend Web Application hemos utilizado la plataforma de terceros llamada Netlify. Esta plataforma nos permite el facil acceso a nuestro repositorio de Github, el cual por medio de ciertas configuraciones podemos tener como resultado el despliegue de nuestra primera version del Frontend Web Application.

![alt text](../assets/imgs/DeployEvidence.png)

![alt text](../assets/imgs/DeployEvidence2.png)

### 5.2.2.8. Team Collaboration Insights during Sprint

Para el desarrollo de este segundo sprint, todos los miembros del equipo desarrollaron y colaboraron de manera activa y continua. De tal modo, se muestra como evidencia los insights de cada miembro del equipo.

Commits:
![alt text](../assets/imgs/CommitsFrontEnd.png)

Network Graph:
![alt text](../assets/imgs/NetworkGraphFrontEnd.png)

### 5.2.3. Sprint 3

### 5.2.3.1. Sprint Planning 3

<table>
<tr>
    <th colspan="5">Sprint #</th>
    <th colspan="9">Sprint 3</th>
  </tr>
      <tr>
    <td colspan="13">Sprint Planning Background</td>
  </tr>
  <tr>
    <td colspan="5">Date</td>
    <td colspan="8">2024-06-05</td>
</tr>
  <tr>
    <td colspan="5">Time</td>
    <td colspan="8">4:20 PM</td>
  </tr>
  <tr>
    <td colspan="5">Location</td>
    <td colspan="8">Via Discord y Google Meet</td>
<tr>
    <td colspan="5">Prepared By</td>
    <td colspan="8">Gabriel Garcia</td>
</tr>
<tr>
    <td colspan="5">Attendees (to planning meeting)</td>
    <td colspan="8">Gabriel Garcia, Diego Flores, Fabricio Apaza, Anatoly Noriega, Mathias Vasquez, Carlos Avellaneda</td>
</tr>
<tr>
    <td colspan="5">Sprint n – 3 Review Summary</td>
    <td colspan="8">En esta seccion se planteo el desarrollo de los Web Services para nuestro proyecto llamado MedicDefense</td>
</tr>
<tr>
    <td colspan="5">Sprint n – 3 Retrospective Summary</td>
    <td colspan="8">En esta seccion todos los integrantes mencionaron tener aciertos en algunas partes del codigo desarrollado. Sin embargo, se pudo hacer un concenso, y a la vez, mejoramos nuestras habilidades realizando el Web Services</td>
</tr>
<tr>
    <td colspan="13">Sprint Goal & User Stories</td>
</tr>
<tr>
    <td colspan="5">Sprint n Goal</td>
    <td colspan="8">Desplegar la primera version de Web Services.</td>
</tr>
<tr>
    <td colspan="5">Sprint n Velocity</td>
    <td colspan="8">X story points</td>
</tr>
<tr>
    <td colspan="5">Sum of Story Points</td>
    <td colspan="8">X Story Points</td>
</tr>
</table>

### 5.2.1.2. Sprint Backlog 3

<table>
<tr>
    <th colspan="3">Sprint #</th>
    <th colspan="10">Sprint 3</th>
  </tr>
      <tr>
    <td colspan="3">User Story</td>
    <td colspan="10">Work-Item/Task</td>
  </tr>
  <tr>
    <td colspan="1">Id</td>
    <td colspan="2">Title</td>
    <td colspan="1">Id</td>
    <td colspan="2">Title</td>
    <td colspan="3">Description</td>
    <td colspan="1"> Estimation</td>
    <td colspan="2">Assigned To</td>
    <td colspan="1">Status(To-do /InProcess /To-Review /Done)</td>
</tr>
  <tr>
    <td colspan="1">46</td>
    <td colspan="2">Creación y gestión de recursos de casos legales</td>
    <td colspan="1">1</td>
    <td colspan="2">Creación y gestión de recursos de casos legales</td>
    <td colspan="3">Como desarrollador backend, quiero implementar la creación y gestión de casos legales para que los administradores puedan gestionar los casos legales.</td>
    <td colspan="1">5</td>
    <td colspan="2">Fabricio and Gabriel</td>
    <td colspan="1">Done</td>
  </tr>
  <tr>
    <td colspan="1">40</td>
    <td colspan="2">Creación y Gestión de Recursos Educativos</td>
    <td colspan="1">2</td>
    <td colspan="2">Creación y Gestión de Recursos Educativos</td>
    <td colspan="3">Como desarrollador backend, quiero implementar la creación y gestión de recursos educativos en la base de datos para que los administradores puedan añadir, actualizar y eliminar recursos.</td>
    <td colspan="1">5</td>
    <td colspan="2">Anatoly</td>
    <td colspan="1">Done</td>
<tr>
<tr>
    <td colspan="1">41</td>
    <td colspan="2">Implementación de Categorías de Recursos</td>
    <td colspan="1">3</td>
    <td colspan="2">Implementación de Categorías de Recursos</td>
    <td colspan="3">Como desarrollador backend, quiero implementar la funcionalidad para gestionar categorías y etiquetas de recursos educativos para organizar los recursos de manera eficiente.</td>
    <td colspan="1">3</td>
    <td colspan="2">Anatoly</td>
    <td colspan="1">Done</td>
<tr>
<tr>
    <td colspan="1">42</td>
    <td colspan="2">Funcionalidad de Búsqueda Avanzada de Recursos Educativos</td>
    <td colspan="1">4</td>
    <td colspan="2">Funcionalidad de Búsqueda Avanzada de Recursos Educativos</td>
    <td colspan="3">Como desarrollador backend, quiero implementar una funcionalidad de búsqueda avanzada para que los usuarios puedan buscar recursos educativos por diferentes criterios.</td>
    <td colspan="1">5</td>
    <td colspan="2">Anatoly</td>
    <td colspan="1">Done</td>
<tr>
<tr>
    <td colspan="1">43</td>
    <td colspan="2">Obtener todas las notificaciones</td>
    <td colspan="1">5</td>
    <td colspan="2">Obtener todas las notificaciones</td>
    <td colspan="3">Como desarrollador backend, quiero implementar un endpoint GET para obtener todas las notificaciones para permitir a los usuarios recuperar la lista completa de notificaciones almacenadas en el sistema.</td>
    <td colspan="1">5</td>
    <td colspan="2">Diego</td>
    <td colspan="1">Done</td>
<tr>
<tr>
    <td colspan="1">44</td>
    <td colspan="2">Crear una nueva notificación</td>
    <td colspan="1">6</td>
    <td colspan="2">Crear una nueva notificación</td>
    <td colspan="3">Como desarrollador backend, quiero implementar un endpoint POST para crear una nueva notificación para permitir a los usuarios enviar nuevas notificaciones que se almacenarán en el sistema.</td>
    <td colspan="1">5</td>
    <td colspan="2">Diego</td>
    <td colspan="1">Done</td>
<tr>
<tr>
    <td colspan="1">45</td>
    <td colspan="2">Obtener una notificación por ID</td>
    <td colspan="1">7</td>
    <td colspan="2">Obtener una notificación por ID</td>
    <td colspan="3">Como desarrollador backend, quiero implementar un endpoint GET para obtener una notificación específica por su ID para permitir a los usuarios recuperar los detalles de una notificación particular basada en su identificador único.</td>
    <td colspan="1">5</td>
    <td colspan="2">Diego</td>
    <td colspan="1">Done</td>
<tr>
<tr>
    <td colspan="1">18</td>
    <td colspan="2">Integración de pagos</td>
    <td colspan="1">8</td>
    <td colspan="2">Integración de pagos</td>
    <td colspan="3">Como administrador, quiero integrar un sistema de pagos seguro para gestionar las suscripciones y compras en la plataforma.</td>
    <td colspan="1">8</td>
    <td colspan="2">Mathias</td>
    <td colspan="1">Done</td>
<tr>
<tr>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="3"></td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
<tr>
<tr>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="3"></td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
<tr>

</table>

### 5.2.3.3. Development Evidence for Sprint Review

<table>
  <thead>
    <tr>
      <th>Repository</th>
      <th>Branch</th>
      <th>Commit Id</th>
      <th>Commit Message</th>
      <th>Commit Message Body</th>
      <th>Committed on (Date)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>Carlos Avellaneda</td>
      <td>ef480ccd255b89447523f90e8efc7a947a490001</td>
      <td>Merge Bounded Context of Consultation</td>
      <td>-</td>
      <td>05/06/2024</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>Anatoly Noriega</td>
      <td>b268969f824061e227a7d9c98ed91b53f0b11d66</td>
      <td>Merge Bounded Context of Educational</td>
      <td>-</td>
      <td>05/06/2024</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>Augusto Vasquez</td>
      <td>6e6603067d73c88a7e96dd0ecec0a71fd2f683aa</td>
      <td>Merge Bounded Context of Payment</td>
      <td>-</td>
      <td>05/06/2024</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>Diego Flores</td>
      <td>4b47b3d13182b9ad5f00b1eb2603b3e9fb5c3fe1</td>
      <td>Merge Bounded Context of Communication</td>
      <td>-</td>
      <td>05/06/2024</td>
    </tr>
     <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>Gabriel Garcia and Fabricio Apaza</td>
      <td>df35dfbd4c1b012e244eb905bb03d8cde62e29f7</td>
      <td>Merge Bounded Context of Legal Case</td>
      <td>-</td>
      <td>05/06/2024</td>
    </tr>
  </tbody>
</table>

### 5.2.3.4. Testing Suite Evidence for Sprint Review

<table>
  <thead>
    <tr>
      <th>Repository</th>
      <th>Branch</th>
      <th>Commit Id</th>
      <th>Commit Message</th>
      <th>Commit Message Body</th>
      <th>Committed on (Date)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>Carlos Avellaneda</td>
      <td>ef480ccd255b89447523f90e8efc7a947a490001</td>
      <td>Merge Bounded Context of Consultation</td>
      <td>-</td>
      <td>05/06/2024</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>Anatoly Noriega</td>
      <td>b268969f824061e227a7d9c98ed91b53f0b11d66</td>
      <td>Merge Bounded Context of Educational</td>
      <td>-</td>
      <td>05/06/2024</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>Augusto Vasquez</td>
      <td>6e6603067d73c88a7e96dd0ecec0a71fd2f683aa</td>
      <td>Merge Bounded Context of Payment</td>
      <td>-</td>
      <td>05/06/2024</td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>Diego Flores</td>
      <td>4b47b3d13182b9ad5f00b1eb2603b3e9fb5c3fe1</td>
      <td>Merge Bounded Context of Communication</td>
      <td>-</td>
      <td>05/06/2024</td>
    </tr>
     <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>Gabriel Garcia and Fabricio Apaza</td>
      <td>df35dfbd4c1b012e244eb905bb03d8cde62e29f7</td>
      <td>Merge Bounded Context of Legal Case</td>
      <td>-</td>
      <td>05/06/2024</td>
    </tr>
  </tbody>
</table>

### 5.2.3.5. Execution Evidence for Sprint Review
Para esta tercera entrega, nuestro equipo a conseguido elaborar la primera versión del Web Services del proyecto "MedicDefense".


### 5.2.3.6. Services Documentation Evidence for Sprint Review

Durante este sprint, se ha desarrollado el back-end de una API de abogados utilizando Java, JPA (Java Persistence API), y siguiendo los principios de Domain-Driven Design (DDD). La API proporciona información sobre abogados ficticios, incluyendo detalles como el nombre del abogado, años de experiencia, especialización, casos ganados, tarifa por hora, correo electrónico y número de teléfono, utilizando la convención de nomenclatura snake_case para los campos. Además, la API también proporciona información sobre recursos educativos (educational_resources), pagos (payments), casos legales (legal_cases) y consultas (consultations).

<table>
  <tr>
    <th>Endpoint</th>
    <th>Acción</th>
    <th>Verbo HTTP</th>
    <th>Sintaxis de Llamada</th>
    <th>Parámetros</th>
    <th>Ejemplo de Llamada</th>
    <th>Explicación del Response</th>
  </tr>
  <tr>
    <td>/api/v1/lawyers</td>
    <td>Listar</td>
    <td>GET</td>
    <td>/api/lawyers</td>
    <td>-</td>
    <td>GET /api/lawyers</td>
    <td>200 OK: Devuelve una lista de todos los abogados.</td>
  </tr>
  <tr>
    <td>/api/v1/lawyers/{id}</td>
    <td>Obtener</td>
    <td>GET</td>
    <td>/api/lawyers/{id}</td>
    <td>ID del abogado</td>
    <td>GET /api/lawyers/1</td>
    <td>200 OK: Devuelve los detalles del abogado con el ID especificado.</td>
  </tr>
  <tr>
    <td>/api/v1/legal-consultations/{legalConsultaationId}</td>
    <td>Obtener</td>
    <td>GET</td>
    <td>/api/v1/legal-consultations/{legalConsultaationId}</td>
    <td>ID del legal consultation</td>
    <td>GET /api/legal-consultations/{legalConsultaationId}</td>
    <td>200 OK: Devuelve los detalles de los legal consultations.</td>
  </tr>
  <tr>
    <td>/api/v1/legal-consultations/{legalConsultaationId}</td>
    <td>Recibir</td>
    <td>POST</td>
    <td>/api/v1/legal-consultations/{legalConsultaationId}</td>
    <td>ID del legal consultations</td>
    <td>POST/api/legal-consultations/{legalConsultaationId}</td>
    <td>200 OK: Devuelve los detalles del abogado con el ID especificado.</td>
  </tr>
  <tr>
    <td>/api/v1/legal-consultations/{legalConsultaationId}</td>
    <td>Eliminar</td>
    <td>Delete</td>
    <td>/api/v1/legal-consultations/{legalConsultaationId}</td>
    <td>ID del legaal consultations</td>
    <td>Delete /api/lawyers/1</td>
    <td>200 OK: Devuelve los detalles del abogado con el ID especificado.</td>
  </tr>
  <tr>
    <td>/api/v1/notifications/{notificationId}</td>
    <td>Obtener</td>
    <td>GET</td>
    <td>/api/v1/notifications/{notificationId}</td>
    <td>ID del notification</td>
    <td>GET /api/notifications/1</td>
    <td>200 OK: Devuelve los detalles del abogado con el ID especificado.</td>
  </tr>
  <tr>
    <td>/api/v1/notifications/{notificationId}</td>
    <td>Recibir</td>
    <td>POST</td>
    <td>/api/v1/notifications/{notificationId}</td>
    <td>ID de la notificacion</td>
    <td>POST /api/v1/notifications/1</td>
    <td>200 OK: Devuelve los detalles del abogado con el ID especificado.</td>
  </tr>
  <tr>
    <td>/api/v1/legalcases/{Id}</td>
    <td>Recibir</td>
    <td>POST</td>
    <td>/api/v1/legalcases/{Id}</td>
    <td>ID del legal cases</td>
    <td>POST /api/v1/legalcases/1</td>
    <td>200 OK: Devuelve los detalles del abogado con el ID especificado.</td>
  </tr>
  <tr>
    <td>/api/v1/payment/{id}</td>
    <td>Obtener</td>
    <td>GET</td>
    <td>/api/v1/payment/{id}</td>
    <td>ID del payment</td>
    <td>POST /api/v1/payment/1</td>
    <td>200 OK: Devuelve los detalles del abogado con el ID especificado.</td>
  </tr>
  <tr>
    <td>/api/v1/educaational-resources/{id}</td>
    <td>Recibir</td>
    <td>POST</td>
    <td>/api/v1/educaational-resources/{notificationId}</td>
    <td>ID del educational resource</td>
    <td>GET /api/v1/educaational-resources/1</td>
    <td>200 OK: Devuelve los detalles del abogado con el ID especificado.</td>
  </tr>

</table>

Capturas de interaccion:

- Visualización de los endpoints:

![alt text](../assets/imgs/endpoint-backend.png)

- Controller del bounded context Notification

![alt text](../assets/imgs/evidence-notification.png)

- Controller del bounded context Consultation

![alt text](../assets/imgs/evidence-logal-consultation.png)

- Controller del bounded context legal case

![alt text](../assets/imgs/evidence-legal-case.png)

- Controller del bounded context payment

![alt text](../assets/imgs/evidence-payment.png)

Url del repositorio: https://github.com/Open-Source-Grupo-Testigos-de-Jehova/backend-Medic-Defense

Commits relacionados: 

<table>
    <tr>
        <th colspan="2">Repository</th>
        <th colspan="2">Branch</th>
        <th colspan="2">Commit Id</th>
        <th colspan="2">Commit Message</th>
    </tr>
        <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/backend-Medic-Defense</td>
        <td colspan="2">Carlos_Avellaneda</td>
        <td colspan="2">ef480ccd255b89447523f90e8efc7a947a490001</td>
        <td colspan="2">Merge pull request</td>
    </tr>
        <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/backend-Medic-Defense</td>
        <td colspan="2">Anatoly_noriega</td>
        <td colspan="2">b268969f824061e227a7d9c98ed91b53f0b11d66</td>
        <td colspan="2">Merge pull request</td>
    </tr>
    <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/backend-Medic-Defense</td>
        <td colspan="2">Augusto_Vasquez</td>
        <td colspan="2">6e6603067d73c88a7e96dd0ecec0a71fd2f683aa</td>
        <td colspan="2">Merge pull request</td>
    </tr>
    <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/backend-Medic-Defense</td>
        <td colspan="2">Diego_Flores</td>
        <td colspan="2">4b47b3d13182b9ad5f00b1eb2603b3e9fb5c3fe1</td>
        <td colspan="2">Merge pull request</td>
    </tr>
    <tr>
        <td colspan="2">Open-Source-Grupo-Testigos-de-Jehova/backend-Medic-Defense</td>
        <td colspan="2">Gabriel_Garcia-and-Fabricio_Apaza</td>
        <td colspan="2">df35dfbd4c1b012e244eb905bb03d8cde62e29f7</td>
        <td colspan="2">Merge pull request</td>
    </tr>
</table>    

### 5.2.3.7. Software Deployment Evidence for Sprint Review
Para el desarrollo de la primera version de Web Services, hemos utilizado la plataforma Github para poder almacenar el avance realizado.

![alt text](<../assets/imgs/Evidence Backend.png>)

### 5.2.3.8. Team Collaboration Insights during Sprint
Para el desarrollo de este tercer sprint, todos los miembros del equipo desarrollaron y colaboraron de manera activa y continua. De tal modo, se muestra como evidencia los insights de cada miembro del equipo.

**Commits:**

![alt text](<../assets/imgs/Evidence Backend.png>)

**Analiticas de Colaboración:**

![alt text](<../assets/imgs/NetworkGraph Backend.png>)

## 5.3 Validation Interviews

### 5.3.1. Diseño de Entrevistas

### 5.3.2. Registro de Entrevistas

### 5.3.3. Evaluaciones según heurísticas


## 5.4 Video About-the-Product
**Captura del About-the-Product**
![alt text](../assets/imgs/about-the-product-captura.png)

**Enlace del video en Microsoft Stream**: https://upcedupe-my.sharepoint.com/:v:/g/personal/u201922146_upc_edu_pe/EZe_EhcxKgdEkprwnSB2xkYBzAVx31Rxmv5W6OdQyMIGvQ?e=gNhYwA&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

**Enlace del video en Youtube**: https://www.youtube.com/watch?v=sFzDCzFW6g4

## 5.5 Video About-the-Team

**Captura del About-the-Team**
![alt text](../assets/imgs/Captura-AbouttheTeam.png)

**Enlace del video en Microsoft Stream**: https://upcedupe-my.sharepoint.com/:v:/g/personal/u201922146_upc_edu_pe/ESa2l1PhMVlCimuVke4ecpUBFZTBIBPNwj2X8OXxeJG6AA?e=YDvz98&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

**Enlace del video en Youtube**: https://www.youtube.com/watch?v=2UWytSnFzU0

**Timelapse Total:** [Inicio:00:00, Fin: 19:36]

**Timelapse Gabriel García:** [Inicio: 00:00, Fin: 02:13]

**Timelapse Carlos Avellaneda:** [Inicio: 02:13, Fin: 04:10]

**Timelapse Diego Flores:** [Inicio: 04:10, Fin: 07:58]

**Timelapse Mathias Vasquez:** [Inicio: 07:58, Fin: 11:35]

**Timelapse Anatoly Noriega:** [Inicio: 11:35, Fin: 15:12]

**Timelapse Fabricio Apaza:** [Inicio: 15:12, Fin: 18:31]

**Timelapse Reunión + Voz en Off:** [Inicio: 18:31, Fin: 19:36]

# Conclusiones 

1. Existe una clara necesidad en el mercado médico de servicios especializados en asesoramiento legal y oportunidades laborales específicas en el campo de la anestesiología. La falta de acceso a expertos legales especializados y recursos para una defensa adecuada crea un ambiente de incertidumbre y estrés para los médicos que enfrentan desafíos legales, lo que afecta negativamente su bienestar emocional, su calidad de atención médica y la confianza del paciente. Esta necesidad presenta una oportunidad para la startup de llenar este vacío en el mercado, proporcionando una plataforma tecnológica que conecte a médicos, estudiantes y profesionales del peritaje en anestesiología con peritos, recursos educativos y oportunidades laborales.

2. La estrategia de la startup, que incluye ofrecer opciones de suscripción flexibles y asequibles, establecer asociaciones estratégicas con instituciones médicas y empresas del sector de la salud, y optimizar la experiencia de usuario, está diseñada para abordar las necesidades identificadas en el mercado y lograr el éxito comercial. Al centrarse en proporcionar un valor significativo a los usuarios a través de servicios especializados, contenido de alta calidad y una experiencia de usuario excepcional, la startup puede diferenciarse de la competencia y establecerse como líder en el mercado de servicios de anestesiología.

# Bibliografia
- Tuesta, P(2023). _Existe un déficit de 2417 médicos anestesiólogos en 20 regiones del país_. Convoca.pe. Recuperado de: https://convoca.pe/agenda-propia/existe-un-deficit-de-2417-medicos-anestesiologos-en-20-regiones-del-pais

- Conne, M(2024). _The Markdown Guide_. MarkdownGuide. Recuperado de: https://www.markdownguide.org/
