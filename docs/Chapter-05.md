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

4. **C#**: 
- "C# Coding Conventions"
- "Microsoft ASP.NET Core Coding Guidelines".

5. **Gherkin**:
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

## 5.2. Landing Page, Services & Applications Implementation
En esta sección se explicará y evidenciará el proceso de implementación, pruebas,
documentación y despliegue del Landing Page.

### 5.2.1. Sprint 1

### 5.2.1.1. Sprint Planning 1

Para este primer sprint nos enfocaremos en los tasks para la
elaboración de la Landing Page. Nos dividiremos entre nosotros cada
una de las tareas identificadas para el sprint.

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
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="3"></td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
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
        <td colspan="2">
fix(User): correct implementation details in user.entity</td>
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
        <td colspan="2"></td>
        <td colspan="2"></td>
        <td colspan="2">-</td>
        <td colspan="2"></td>
    </tr>
</table>

### 5.2.2.4. Testing Suite Evidence for Sprint Review

**Unit Tests**

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
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Open-Source-Grupo-Testigos-de-Jehova/Landing-page-MedicDefense</td>
      <td>develop</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>


### 5.2.2.5. Execution Evidence for Sprint Review

Para esta segunda entrega, nuestro equipo a conseguido elaborar la primera versión de Frontend Web Application del proyecto "MedicDefense". De tal modo, se podrá visualizar la información necesaria de lo que ofrece nuestro proyecto.


### 5.2.2.6. Services Documentation Evidence for Sprint Review


### 5.2.2.7. Software Deployment Evidence for Sprint Review


### 5.2.2.8. Team Collaboration Insights during Sprint

Para el desarrollo de este segundo sprint, todos los miembros del equipo desarrollaron y colaboraron de manera activa y continua. De tal modo, se muestra como evidencia los insights de cada miembro del equipo.

Commits:


Analiticas de Colaboración:




## 5.3. Conclusiones 

1. Existe una clara necesidad en el mercado médico de servicios especializados en asesoramiento legal y oportunidades laborales específicas en el campo de la anestesiología. La falta de acceso a expertos legales especializados y recursos para una defensa adecuada crea un ambiente de incertidumbre y estrés para los médicos que enfrentan desafíos legales, lo que afecta negativamente su bienestar emocional, su calidad de atención médica y la confianza del paciente. Esta necesidad presenta una oportunidad para la startup de llenar este vacío en el mercado, proporcionando una plataforma tecnológica que conecte a médicos, estudiantes y profesionales del peritaje en anestesiología con peritos, recursos educativos y oportunidades laborales.

2. La estrategia de la startup, que incluye ofrecer opciones de suscripción flexibles y asequibles, establecer asociaciones estratégicas con instituciones médicas y empresas del sector de la salud, y optimizar la experiencia de usuario, está diseñada para abordar las necesidades identificadas en el mercado y lograr el éxito comercial. Al centrarse en proporcionar un valor significativo a los usuarios a través de servicios especializados, contenido de alta calidad y una experiencia de usuario excepcional, la startup puede diferenciarse de la competencia y establecerse como líder en el mercado de servicios de anestesiología.

## 5.4 Bibliografia
- Existe un déficit de 2417 médicos anestesiólogos en 20 regiones del país. (n.d.). Convoca.pe - Agenda Propia. Retrieved April 11, 2024, from https://convoca.pe/agenda-propia/existe-un-deficit-de-2417-medicos-anestesiologos-en-20-regiones-del-pais

- The Markdown Guide-MarkdownGuide from https://www.markdownguide.org/
