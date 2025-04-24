<p align="center">
  <img src="img/upc.png" alt="Logo de UPC" width="100%">
</p>

<div align="center">
  <h1>Universidad Peruana de Ciencias Aplicadas</h1>
  <p><strong>Carrera:</strong> Ingenieria de Software</p>
  <p><strong>Ciclo:</strong> 2025 - 1</p>
  <p><strong>Curso:</strong> Desarrollo de Soluciones IOT</p>
  <p><strong>Sección:</strong> 1ASI0572</p>
  <p><strong>Profesor:</strong> David Carlos Vera</p>
  <p><strong>"Informe de Trabajo Final"</strong></p>
  <p><strong>Startup:</strong> xxx</p>
  <p><strong>Producto:</strong> xxx</p>
</div>


<table align="center">
  <tr>
    <th>Integrantes</th>
    <th>Código</th>
  </tr>
  <tr>
    <td>Adrianzen Flores, Carlos Arturo</td>
    <td>U202215705</td>
  </tr>
  <tr>
    <td>Dam Rubianes, Frida Sofia</td>
    <td>U202218352</td>
  </tr>
  <tr>
    <td>Matos Fernandez, Christian Andre</td>
    <td>U202214162</td>
  </tr>
  <tr>
    <td>Ortiz Fajardo, Tomás</td>
    <td>U201910146</td>
  </tr>
  <tr>
    <td>Ramos Ramirez, Renzo Manuel</td>
    <td>U202113745</td>
  </tr>
</table>

<p align="center"><b>Abril 2025</b></p>

# Registro de Versiones

<table>
  <thead>
    <tr>
        <th>Versión</th>
        <th>Fecha</th>
        <th>Autor</th>
        <th>Descripción de modificación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>1.0</strong></td>
      <td>23 de abril de 2025</td>
      <td>
        <ul>
          <li></li>
        </ul>
      </td>
      <td>
        Creación del repositorio
      </td>
    </tr>
  </tbody>
</table>

# Project Report Collaboration Insights

# Tabla de Contenido

[Registro de Versiones](#registro-de-versiones)

[Project Report Collaboration Insights](#project-report-collaboration-insights)

[Tabla de contenidos](#tabla-de-contenidos)

[Student Outcome](#student-outcome)

[Capítulo I: Introducción](#capítulo-i-introducción)
- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2. Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

[Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
- [2.1. Competidores](#21-competidores)
  - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
  - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
  - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
  - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
  - [2.3.1. User Personas](#231-user-personas)
  - [2.3.2. User Task Matrix](#232-user-task-matrix)
  - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
  - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#24-ubiquitous-language)

[Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

[Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
- [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
  - [4.1.1. EventStorming](#411-eventstorming)
    - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
    - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
    - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
  - [4.1.2. Context Mapping](#412-context-mapping)
  - [4.1.3. Software Architecture](#413-software-architecture)
    - [4.1.3.1. System Landscape Diagram](#4131-system-landscape-diagram)
    - [4.1.3.2. Context Level Diagrams](#4132-context-level-diagrams)
    - [4.1.3.3. Container Level Diagrams](#4133-container-level-diagrams)
    - [4.1.3.4. Deployment Diagrams](#4134-deployment-diagrams)
- [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
  - [4.2.X. Bounded Context: &lt;Bounded Context Name&gt;](#42x-bounded-context)
    - [4.2.X.1. Domain Layer](#42x1-domain-layer)
    - [4.2.X.2. Interface Layer](#42x2-interface-layer)
    - [4.2.X.3. Application Layer](#42x3-application-layer)
    - [4.2.X.4. Infrastructure Layer](#42x4-infrastructure-layer)
    - [4.2.X.5. Component Level Diagrams](#42x5-component-level-diagrams)
    - [4.2.X.6. Code Level Diagrams](#42x6-code-level-diagrams)
      - [4.2.X.6.1. Class Diagrams](#42x61-class-diagrams)
      - [4.2.X.6.2. Database Design Diagram](#42x62-database-design-diagram)


# Student Outcome

ABET – EAC - Student Outcome 5: La capacidad de funcionar efectivamente en un
equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de
colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.

<table>
  <thead>
    <tr>
      <th>Criterio específico</th>
      <th>Acciones realizadas</th>
      <th>Conclusiones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Trabaja en equipo para proporcionar liderazgo en forma conjunta</strong></td>
      <td>
        <strong>Renzo Manuel Ramos Ramirez</strong><br><strong>TB1</strong><br><br>
        <strong>Christian Andre Matos Fernandez</strong><br><strong>TB1</strong><br><br>
        <strong>Frida Sofia Dam Rubianes</strong><br><strong>TB1</strong><br><br>
        <strong>Carlos Arturo Adrianzen Flores</strong><br><strong>TB1</strong><br><br>
        <strong>Tomás Ortiz Fajardo</strong><br><strong>TB1</strong><br>
      </td>
      <td>…</td>
    </tr>
    <tr>
      <td><strong>Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos</strong></td>
      <td>
        <strong>Renzo Manuel Ramos Ramirez</strong><br><strong>TB1</strong><br><br>
        <strong>Christian Andre Matos Fernandez</strong><br><strong>TB1</strong><br><br>
        <strong>Frida Sofia Dam Rubianes</strong><br><strong>TB1</strong><br><br>
        <strong>Carlos Arturo Adrianzen Flores</strong><br><strong>TB1</strong><br><br>
        <strong>Tomás Ortiz Fajardo</strong><br><strong>TB1</strong><br>
      </td>
      <td>…</td>
    </tr>
  </tbody>
</table>



# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
### 1.1.2. Perfiles de integrantes del equipo
## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
#### 1.2.2.2. Lean UX Assumptions
#### 1.2.2.3. Lean UX Hypothesis Statements
#### 1.2.2.4. Lean UX Canvas
## 1.3. Segmentos objetivo

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores
## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas
## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
### 2.3.5. As-is Scenario Mapping
## 2.4. Ubiquitous Language

# Capítulo III: Requirements Specification
# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping

**Segmento #1**: Personas que residan en zonas urbanas dentro del distrito de Lima.

<img src="img/to-be_scenario_mapping.png" alt="To-Be Scenario Mapping">

## 3.2. User Stories


Epics

- **Gestión de usuarios**

---

**EP01:** Como usuario quiero poder registrarme en la aplicación para acceder a mis funciones personalizadas, editar mi perfil, iniciar sesión de forma segura, cambiar mi contraseña y cerrar sesión cuando sea necesario, para poder tener el control de mi cuenta y de mis datos.

| User Story ID | Título                             |
|---------------|------------------------------------|
| US-01         | Registro de usuario               |
| US-02         | Editar perfil de usuario          |
| US-03         | Iniciar sesión en la aplicación   |
| US-04         | Cambiar contraseña                |
| US-05         | Cerrar sesión                     |

- **Seguridad y visualización**

---

**EP02:** Como usuario quiero ver las cámaras de seguridad en tiempo real, para estar al tanto de lo que sucede en mi hogar.

| User Story ID | Título                              |
|---------------|-------------------------------------|
| US-06         | Visualización en tiempo real de cámaras de seguridad |
| US-07         | Notificaciones de alerta           |
| US-08         | Historial de eventos               |

- **Configuración y ajustes**

---

**EP03:** Como usuario, quiero modificar mi experiencia en la aplicación para poder tener una experiencia única y acorde a mis gustos personales.

| User Story ID | Título                                       |
|---------------|----------------------------------------------|
| US-09         | Ajustes de notificaciones                    |
| US-10         | Configuración de alarmas personalizadas      |
| US-11         | Configurar video de la cámara               |

- **Gestión de reconocimiento facial**

---

**EP04:** Como usuario, quiero gestionar perfiles de reconocimiento facial para mejorar la seguridad de la aplicación.

| User Story ID | Título                              |
|---------------|-------------------------------------|
| US-12         | Crear perfiles de reconocimiento    |
| US-13         | Actualizar perfiles de reconocimiento |
| US-14         | Eliminación de perfiles de reconocimiento |
| US-15         | Reconocimiento facial               |

- **Compartir y colaboración**

---

**EP05:** Como usuario, quiero poder compartir y colaborar conmigo mismo y con personas de confianza, para poder darle una colaboratividad a mi experiencia y no ser el único responsable de la seguridad de mi hogar.

| User Story ID | Título                                   |
|---------------|------------------------------------------|
| US-16         | Compartir acceso con invitados          |
| US-17         | Registro de eventos en calendario       |
| US-18         | Informe de seguridad semanal           |

| **Soporte y emergencias**

---

**EP006:** Como usuario, quiero tener la capacidad de contactar al centro de seguridad en caso de emergencia y acceder a información de contacto de emergencia relevante para mantener la seguridad y la asistencia en situaciones críticas.

| User Story ID | Título                              |
|---------------|-------------------------------------|
| US-19         | Contactar al centro de seguridad    |
| US-20         | Información de contacto de emergencia |

- **Página Web**
---

**EP007:** Como usuario, quiero explorar de manera interactiva la página web, participando activamente en sus funcionalidades para obtener información detallada sobre la aplicación y, finalmente, tener la posibilidad de descargarla.

| User Story ID | Título                                    |
|---------------|-------------------------------------------|
| US-21         | Envío de Mensaje a la Empresa para Consultas |
| US-22         | Visualización de contenido en Redes Sociales |
| US-23         | Exploración selectiva con la barra de navegación |


---


|**User Story ID**|**Título**|**Descripción**|**Criterio de aceptación**|**Relación (EPIC ID)**|
| :- | :- | :- | :- | :- |
|**US-01**|Registro de usuario|<p>Como nuevo usuario, quiero registrarme en la aplicación para poder tener mi cuenta.</p><p></p>|<p>**Escenario 1:** Acceso del usuario a la página de registro</p><p></p><p>Dado que el usuario haya descargado la aplicación y abra la aplicación</p><p>Cuando el usuario se encuentra en la página de "Inicio de sesión"</p><p>Y haga clic en el botón "Registrarse",</p><p>Entonces, la aplicación mostrará la página de registro.</p><p></p><p>**Escenario 2:** Registro exitoso del usuario </p><p></p><p>Dado que el usuario se encuentra en la página de registro</p><p>Cuando el usuario ingrese sus datos </p><p>Y el usuario haga clic en el botón "Registrarse”</p><p>Entonces la aplicación registrará al usuario y guardará su cuenta.</p><p></p><p>**Escenario 3:** Registro del usuario con datos inválidos</p><p></p><p>Dado que el usuario se encuentra en la página de registro,</p><p>Cuando el usuario ingrese sus datos de manera incompleta o con datos no válidos</p><p>Y el usuario haga clic en el botón "Registrarse"</p><p>Entonces la aplicación mostrará un mensaje de error</p><p>Y borrará los datos ingresados. </p>|**EP01**|
|**US-02**|<p>Editar perfil del usuario</p><p></p>|Como usuario registrado, quiero modificar mi perfil para tener mi información actualizada en el sistema.|<p>**Escenario 1:** Acceso del usuario a "Mi perfil"</p><p></p><p>Dado que el usuario está registrado en la aplicación</p><p>Cuando el usuario seleccione su perfil, Entonces el sistema presentará la página "Mi perfil”</p><p></p><p>**Escenario 2:** El usuario elige  editar su perfil</p><p></p><p>Dado que el usuario se encuentra en la página "Mi perfil" con los datos personales visibles</p><p>Cuando el usuario haga clic en el botón "Editar perfil"</p><p>Entonces, el sistema mostrará la página de edición de perfil.</p><p></p><p>**Escenario 3:** Actualización exitosa de los datos del perfil del usuario</p><p>Dado que el usuario se encuentra en la página de edición de perfil con los datos personales visibles</p><p>Cuando el usuario introduzca sus nuevos datos</p><p>Y el usuario haga clic en el botón "Cambiar"</p><p>Entonces el sistema actualizará la información del perfil del usuario con los nuevos datos ingresados.</p><p>**Escenario 4:** Actualización de los datos del perfil del usuario con información inválida o incompleta</p><p>Dado que el usuario se encuentra en la página de edición de perfil con los datos personales visibles</p><p>Cuando el usuario ingrese datos incompletos o inválidos</p><p>Y el usuario haga clic en el botón "Actualizar"</p><p>Entonces la aplicación mostrará un mensaje de "Error"</p><p>Y borrará los datos ingresados.</p>|**EP01**|
|**US-03**|Iniciar sesión en la aplicación|Como usuario registrado, quiero iniciar sesión en la aplicación para acceder dentro de ella.|<p>**Escenario 1:** Acceso del usuario a la página de inicio de sesión</p><p>Dado que el usuario inicia la aplicación</p><p>Y el usuario no ha iniciado sesión previamente o se ha desconectado</p><p>Cuando el usuario seleccione el botón "Iniciar Sesión"</p><p>Entonces, la aplicación exhibirá la página de inicio de sesión.</p><p>**Escenario 2:** Inicio de sesión exitoso del usuario</p><p>Dado que el usuario se encuentra en la página de inicio de sesión</p><p>Cuando el usuario ingrese sus credenciales válidas</p><p>Y el usuario haga clic en el botón "Iniciar Sesión"</p><p>Entonces, el usuario será autenticado</p><p>Y redirigido a la página principal de la aplicación.</p><p>**Escenario 3:** Intento de inicio de sesión fallido </p><p>Dado que el usuario se encuentra en la página de inicio de sesión</p><p>Cuando el usuario introduzca credenciales inválidas</p><p>Y el usuario haga clic en el botón "Iniciar Sesión"</p><p>Entonces la aplicación mostrará un mensaje de error que indica que las credenciales son incorrectas.</p>|**EP01**|
|**US-04**|Cambiar Contraseña|<p>Como usuario registrado, quiero cambiar mi contraseña para tener una mayor seguridad.</p><p></p>|<p>**Escenario 1:** Acceso del usuario a la configuración de la cuenta</p><p>Dado que el usuario ha iniciado sesión en la aplicación</p><p>Cuando el usuario se dirija a la sección de configuración de la cuenta</p><p>Entonces la aplicación mostrará la opción para modificar la contraseña.</p><p>**Escenario 2:** Cambio exitoso de la contraseña </p><p>Dado que el usuario se encuentra en la página de cambio de contraseña</p><p>Cuando el usuario introduzca su contraseña actual y la nueva contraseña en dos ocasiones</p><p>Y después haga clic en el botón "Cambiar Contraseña"</p><p>Entonces la aplicación realizará el cambio de contraseña</p><p>Y mostrará un mensaje de confirmación.</p><p>**Escenario 3:** Intento de cambio de contraseña fallido </p><p>Dado que el usuario se halla en la página de cambio de contraseña</p><p>Cuando el usuario introduzca una contraseña actual incorrecta o incompleta, luego ingrese la nueva contraseña dos veces</p><p>Y seleccione el botón "Cambiar Contraseña" </p><p>Entonces la aplicación desplegará un mensaje de error que señala que la contraseña actual es incorrecta.</p>|**EP01**|
|**US-05**|<p>Cerrar Sesión</p><p></p>|<p>Como usuario registrado, quiero cerrar sesión en la aplicación para que mi cuenta no quede guardada en mi móvil.</p><p></p>|<p>**Escenario 1:** Acceso del usuario a la configuración de la cuenta</p><p>Dado que el usuario ha iniciado sesión en la aplicación</p><p>Cuando el usuario acceda a la sección de configuración de la cuenta</p><p>Entonces la aplicación mostrará la opción para cerrar sesión.</p><p>**Escenario 2:** Cierre de sesión exitoso por parte del usuario</p><p>Dado que el usuario se encuentra en la página de cierre de sesión</p><p>Cuando el usuario seleccione el botón "Cerrar Sesión"</p><p>Entonces, la aplicación concluirá la sesión del usuario y lo redirigirá a la página de inicio de sesión.</p>|**EP01**|
|**US-06**|<p>Visualización en tiempo real de cámaras de seguridad</p><p></p>|<p>Como usuario, quiero acceder a la visualización en tiempo real de todas mis cámaras de seguridad para poder monitorear mi hogar en cualquier momento.</p><p></p>|<p>**Escenario 1**: Usuario accede a la visualización en tiempo real</p><p>Dado que el usuario ha iniciado sesión en la aplicación CamGuard</p><p>Cuando el usuario seleccione la opción "Ver cámaras en tiempo real"</p><p>Entonces, la aplicación mostrará una vista en tiempo real de todas las cámaras de seguridad registradas en su cuenta.</p><p></p><p>**Escenario 2:** Usuario cambia la vista de la cámara</p><p>Dado que el usuario está viendo las imágenes en tiempo real de sus cámaras de seguridad</p><p>Cuando el usuario toque una cámara específica en la vista en tiempo real</p><p>Entonces, la aplicación cambiará la vista para mostrar solo la imagen en tiempo real de la cámara seleccionada.</p><p></p><p>**Escenario 3:** Usuario activa el audio de la cámara</p><p>Dado que el usuario está viendo las imágenes en tiempo real de una cámara de seguridad</p><p>Cuando el usuario active la opción de "Audio" en la cámara seleccionada</p><p>Entonces, la aplicación permitirá al usuario escuchar el sonido ambiente capturado por esa cámara.</p>|**EP02**|
|**US-07**|<p>Notificaciones de alerta</p><p></p>|<p>Como usuario, quiero recibir notificaciones en tiempo real cuando una persona desconocida sea detectada por las cámaras de seguridad para estar al tanto de posibles amenazas en mi propiedad.</p><p></p>|<p>**Escenario 1:** Usuario recibe una notificación de alerta</p><p>Dado que la cámara de seguridad detecta a una persona desconocida</p><p>Cuando la aplicación identifica al individuo como desconocido</p><p>Entonces, la aplicación enviará una notificación instantánea al propietario con información sobre la persona detectada y la opción de marcarla como ladrón o no.</p><p></p><p>**Escenario 2:** Usuario marca a una persona como ladrón</p><p>Dado que el usuario ha recibido una notificación de alerta sobre una persona desconocida</p><p>Cuando el usuario seleccione la opción "Marcar como ladrón"</p><p>Entonces, la aplicación registrará a la persona como un ladrón en el historial de eventos y activará el dispositivo de seguridad.</p><p></p><p>**Escenario 3:** Usuario desactiva las notificaciones de alerta temporalmente</p><p>Dado que el usuario ha recibido varias notificaciones de alerta y desea un breve período de tranquilidad</p><p>Cuando el usuario seleccione la opción "Desactivar notificaciones por 1 hora"</p><p>Entonces, la aplicación dejará de enviar notificaciones de alerta durante el período especificado y luego las reanudará automáticamente.</p>|**EP02**|
|**US-08**|<p>Historial de eventos</p><p></p>|<p>Como usuario, quiero acceder al historial de eventos para revisar y mantener un registro de todas las detecciones de personas desconocidas y las acciones tomadas en mi propiedad.</p><p></p>|<p>**Escenario 1:** Usuario accede al historial de eventos</p><p>Dado que el usuario está autenticado en la aplicación CamGuard</p><p>Cuando el usuario seleccione la opción "Historial de eventos"</p><p>Entonces, la aplicación mostrará una lista cronológica de todas las detecciones de personas desconocidas, indicando si fueron marcadas como ladrones o no y si se activó el dispositivo de seguridad.</p><p></p><p>**Escenario 2:** Usuario filtra el historial por fecha</p><p>Dado que el usuario está viendo el historial de eventos</p><p>Cuando el usuario seleccione una fecha específica en la que ocurrieron eventos</p><p>Entonces, la aplicación mostrará solo los eventos que ocurrieron en la fecha seleccionada en el historial.</p><p></p><p>**Escenario 3:** Usuario borra un evento del historial</p><p>Dado que el usuario está viendo el historial de eventos</p><p>Cuando el usuario seleccione un evento específico en el historial</p><p>Y el usuario seleccione la opción "Borrar evento"</p><p>Entonces, la aplicación eliminará ese evento del historial de eventos.</p>|**EP02**|
|**US-09**|<p>Ajustes de notificaciones</p><p></p>|<p>Como usuario, quiero personalizar mis preferencias de notificación para recibir alertas de acuerdo a mis necesidades y establecer momentos de tranquilidad cuando lo requiera.</p><p></p>|<p>**Escenario 1:** Usuario accede a las preferencias de notificación</p><p>Dado que el usuario ha iniciado sesión en la aplicación CamGuard</p><p>Cuando el usuario vaya a la sección de "Ajustes de notificaciones"</p><p>Entonces, la aplicación permitirá al usuario personalizar la configuración de notificaciones, incluyendo el tipo de alertas que desea recibir y la forma en que desea recibirlas.</p><p></p><p>**Escenario 2:** Usuario desactiva las notificaciones de sonido</p><p>Dado que el usuario está en la sección de "Ajustes de notificaciones"</p><p>Cuando el usuario desactive la opción de "Notificaciones de sonido"</p><p>Entonces, la aplicación dejará de enviar notificaciones auditivas al dispositivo del usuario, pero seguirá enviando notificaciones visuales.</p><p></p><p>**Escenario 3:** Usuario programa un horario de notificaciones silenciosas</p><p>Dado que el usuario está en la sección de "Ajustes de notificaciones"</p><p>Cuando el usuario configure un horario de notificaciones silenciosas, por ejemplo, durante las horas de sueño</p><p>Entonces, la aplicación dejará de enviar notificaciones de sonido durante el período especificado.</p>|**EP03**|
|**US-10**|<p>Configuración de alarmas personalizadas</p><p></p>|Como usuario, deseo configurar alarmas personalizadas, como sirenas o notificaciones específicas, en caso de intrusión, para estar informado de manera efectiva en situaciones de seguridad.|<p>**Escenario 1:** Acceso a la configuración de alarmas personalizadas.</p><p>Dado que, el usuario se encuentra en la ventana de configuración de alarmas personalizadas.</p><p>Cuando, el usuario selecciona la opción para configurar una alarma personalizada.</p><p>Entonces, se mostrará un formulario de configuración de alarma.</p><p></p><p>**Escenario 2:** Elección del tipo de alarma y modo de ser notificado en caso de intrusión.</p><p>Dado que, el usuario ha completado el formulario de configuración de alarma personalizada.</p><p>Cuando, el usuario guarda la configuración de la alarma personalizada.</p><p>Entonces, la alarma se configurará según las preferencias del usuario, y se notificará al usuario de acuerdo con las opciones seleccionadas.</p>|**EP03**|
|**US-11**|Configurar video de la cámara|Como usuario quiero modificar el video de la cámara para poder visualizar cómodamente los videos.|<p>**Escenario 1:** Usuario entra a la seccion configuracion de video</p><p>Dado que el usuario está en la página principal y quiere cambiar lo colores del video</p><p>Cuando el usuario da click en configuracion/video</p><p>Entonces, se abre la sección de ajustes de video.</p><p>**Escenario 2:** Usuario cambia valores en las sección ajustes de video</p><p>Dado que el usuario está en la sección ajustes de video</p><p>Cuando el usuario realiza algún cambio en los valores</p><p>Entonces se guardarán los cambios en la visualización de los videos.</p><p></p>|**EP03**|
|**US-12**|Crear perfiles de reconocimiento|Como usuario quiero crear perfiles de reconocimiento para que las cámaras reconozcan a las personas recurrentes en mi domicilio.|<p>**Escenario 1:** Entrar a la sección perfiles</p><p>Dado que el usuario está en la página principal y quiere registrar un nuevo perfil</p><p>Cuando el usuario haga click en Perfiles/Registrar perfil</p><p>Entonces se abrirá la ventana de registro de perfiles.</p><p>**Escenario 2:** Crear un nuevo perfil</p><p>Dado que el usuario se encuentra en la ventana de registro de perfiles</p><p>Cuando el usuario llene todo los requerimientos ( nombre, apellido, celular, relación) y le de al click guardar</p><p>Entonces se almacenará el nuevo usuario en la base de datos y se mostrará un mensaje de operación exitosa.</p>|**EP04**|
|**US-13**|Actualizar perfiles de reconocimiento|Como usuario quiero poder actualizar los perfiles de reconocimiento para tener noción de las personas incluidas en la lista.|<p>**Escenario 1:** Entrar a la lista de perfiles</p><p>Dado que el usuario está en la página principal</p><p>Cuando el usuario haga click en Perfiles</p><p>Entonces se abrirá una ventana con todos los perfiles registrados en la base de datos</p><p>**Escenario 2:** Actualizar información de perfiles</p><p>Dado que el usuario está en la página de Perfiles</p><p>Cuando el usuario seleccione un perfil y elija la opción ‘Actualizar información’</p><p>Entonces se abrirá una ventana para el registro de los nuevo datos</p><p>**Escenario 3:** Confirmar actualización</p><p>Dado que el usuario está en la ventana ‘Actualización de perfil’</p><p>Cuando llene todos los atributos  (nombre, apellido, celular, relación)</p><p>Y de click en confirmar</p><p>Entonces se actualizará la información de dicho perfil en la base de datos</p><p>Y se mostrará un mensaje de operación exitosa.</p>|**EP04**|
|**US-14**|Eliminación de perfiles de reconocimiento|Como usuario quiero eliminar perfiles de reconocimiento para tener actualizado mis invitados permitidos.|<p>**Escenario 1:** Eliminar el perfil seleccionado</p><p>Dado que el usuario se encuentra en la página de Perfiles</p><p>Cuando el usuario selecciona un usuario</p><p>Y elige la opción eliminar perfil</p><p>Entonces el perfil se eliminará de la lista de Perfiles</p><p>Y se mostrará un mensaje de operación exitosa.</p>|**EP04**|
|**US-15**|Reconocimiento facial|Como usuario quiero realizar un reconocimiento facial, para tener guardado mi perfil.|<p>**Escenario 1:**Entrar a reconocimiento facial</p><p>Dado que el usuario está en la ventana de Perfiles</p><p>Cuando el usuario seleccione un perfil y haga clic en añadir reconocimiento facial.</p><p>Entonces se abrirá una ventana dedicada al reconocimiento facial.</p><p>**Escenario 2:**Registras reconocimiento facial</p><p>Dado que el usuario se encuentra en la ventana Registro Facial</p><p>Cuando el usuario está realizando el proceso de registro facial y logra realizar todos los movimientos correctamente.</p><p>Entonces se mostrará un mensaje de registro de exitoso</p><p>**Escenario 3:** Error en medio reconocimiento facial</p><p>Dado que el usuario se encuentra realizando el reconocimiento facial</p><p>Cuando el usuario realiza un mal movimiento en el proceso</p><p>Entonces se muestra un mensaje de alinear correctamente la postura</p>|**EP04**|
|**US-16**|Compartir acceso con invitados|Como usuario, deseo poder compartir acceso a mis cámaras con invitados temporales, como familiares que visitan mi hogar, para que puedan ver las cámaras durante su estadía.|<p>**Escenario 1:** Acceder a la configuración de acceso compartido.</p><p>Dado que, el usuario se encuentra en la ventana de configuración de acceso compartido.</p><p>Cuando, el usuario selecciona la opción para agregar un nuevo invitado.</p><p>Entonces, se mostrará un formulario para ingresar los detalles del invitado.</p><p></p><p>**Escenario 2:** Invitación a un invitado.</p><p>Dado que, el usuario ha ingresado los detalles del invitado en el formulario.</p><p>Cuando el usuario selecciona la opción para enviar la invitación.</p><p>Entonces, se generará un enlace de invitación que se enviará al invitado.</p><p>Y, el usuario podrá establecer un período de acceso temporal para el invitado.</p><p>Y, se mostrará un mensaje de confirmación de la invitación enviada con éxito.</p>|**EP05**|
|**US-17**|Registro de eventos en calendario|<p>Como usuario, deseo poder registrar eventos importantes en un calendario integrado en la aplicación, para mantener un registro de eventos relevantes relacionados con la seguridad de mi hogar.</p><p></p>|<p>**Escenario 1:** Usuario accede al calendario dentro de la aplicación.</p><p>Dado que, el usuario se encuentra en la ventana de calendario.</p><p>Cuando el usuario selecciona la opción para agregar un nuevo evento.</p><p>Entonces, se abrirá un formulario para ingresar los detalles del evento.</p><p></p><p>**Escenario 2:** Usuario registra eventos y recibe notificaciones previas.</p><p>Dado que, el usuario ha ingresado los detalles del evento en el formulario.</p><p>Cuando el usuario selecciona la opción para guardar el evento en el calendario.</p><p>Entonces, el evento se registrará en el calendario de la aplicación.</p><p>Y, el usuario recibirá notificaciones previas al evento en las fechas programadas.</p>|**EP05**|
|**US-18**|Informe de seguridad semanal|Como usuario, deseo recibir un informe semanal de seguridad que resuma la actividad de las cámaras en mi hogar, para estar al tanto de lo que ha sucedido durante la semana.|<p>**Escenario 1:** Informe semanal por correo electrónico.</p><p>Dado que, el usuario ha configurado la opción de recibir un informe semanal.</p><p>Cuando llega el día programado para el envío del informe semanal.</p><p>Entonces, la aplicación enviará un correo electrónico al usuario con el informe adjunto.</p><p></p><p>**Escenario 2:** El informe contiene estadísticas de detección de movimiento y reconocimiento facial.</p><p>Dado que, el usuario ha recibido el informe semanal por correo electrónico.</p><p>Cuando el usuario abre el informe adjunto.</p><p>Entonces, el informe contendrá estadísticas detalladas sobre la detección de movimiento y el reconocimiento facial registrados durante la semana.</p>|**EP05**|
|**US-19**|Contactar al centro de seguridad|Como usuario, quiero tener la capacidad de comunicarme rápidamente con el centro de seguridad más cercano en caso de emergencia para obtener ayuda inmediata y proteger mi seguridad y la de mi familia.|<p>**Escenario 1:** Usuario solicita ayuda al centro de seguridad</p><p>Dado que el usuario se encuentra en una situación de emergencia y necesita asistencia inmediata</p><p>Cuando el usuario seleccione la opción "Contactar al centro de seguridad"</p><p>Entonces, la aplicación enviará una alerta automática al centro de seguridad más cercano junto con la ubicación del usuario y otra información relevante para solicitar ayuda.</p><p></p><p>**Escenario 2:** Usuario cancela la solicitud de ayuda</p><p>Dado que el usuario ha solicitado ayuda al centro de seguridad</p><p>Cuando el usuario seleccione la opción "Cancelar solicitud de ayuda"</p><p>Entonces, la aplicación detendrá la alerta automática y notificará al usuario que la solicitud ha sido cancelada con éxito.</p><p></p><p>**Escenario 3:** Centro de seguridad responde a la solicitud</p><p>Dado que el centro de seguridad ha recibido una solicitud de ayuda</p><p>Cuando el centro de seguridad envíe una respuesta al usuario o tome medidas apropiadas</p><p>Entonces, la aplicación notificará al usuario sobre la respuesta o acciones tomadas por el centro de seguridad.</p>|**EP06**|
|**US-20**|<p>Información de contacto de emergencia</p><p></p>|Como usuario, deseo proporcionar información de contacto de emergencia a la aplicación, como números de teléfono de familiares o amigos en caso de alerta, para garantizar una respuesta rápida en situaciones de emergencia.|<p>**Escenario 1:** Acceso a la configuración de información de contacto de emergencia.</p><p>Dado que, el usuario se encuentra en la ventana de configuración de información de contacto de emergencia.</p><p>Cuando, el usuario selecciona la opción para agregar información de contacto de emergencia.</p><p>Entonces, se mostrará un formulario para ingresar los detalles de contacto de emergencia.</p><p></p><p>**Escenario 2:** Información de contacto almacenada.</p><p>Dado que, el usuario ha ingresado la información de contacto de emergencia en el formulario.</p><p>Cuando, el usuario guarda la información de contacto de emergencia.</p><p>Entonces, la información de contacto se almacenará en la</p>|**EP06**|
|**US-21**|<p>Envío de Mensaje a la Empresa para Consultas</p><p></p>|Como usuario, quiero establecer contacto con la empresa para enviar un mensaje detallado con el objetivo de resolver algunas dudas que puedan surgir durante mi experiencia en la plataforma.|<p>**Escenario 1**: Envío Exitoso de Mensaje</p><p>Dado que el usuario tiene dudas sobre la página y se encuentra en el pie de página,</p><p>cuando completa correctamente los campos: nombre, correo y mensaje,</p><p>y luego presiona "Enviar",</p><p>Entonces se envía el mensaje exitosamente, mostrando el mensaje "Mensaje enviado con éxito".</p><p></p><p>**Escenario 2:** Datos Incorrectos en el Envío de Mensaje</p><p>Dado que el usuario tiene dudas sobre la página y se encuentra en el pie de página,</p><p>cuando completa incorrectamente los campos: nombre, correo y mensaje,</p><p>y luego presiona "Enviar",</p><p>Entonces se muestra el mensaje "Datos incorrectos".</p><p></p><p>**Escenario 3:** Datos Incompletos en el Envío de Mensaje</p><p>Dado que el usuario tiene dudas sobre la página y se encuentra en el pie de página,</p><p>cuando completa incorrectamente los campos: nombre, correo y mensaje,</p><p>y luego presiona "Enviar",</p><p>Entonces se muestra el mensaje "Datos incompletos".</p><p></p>|**EP07**|
|**US-22**|<p>Visualización de contenido en Redes Sociales</p><p></p>|<p>Como usuario, quiero explorar y visualizar la información de la empresa a través de las redes sociales para obtener detalles adicionales y tener una comprensión más completa de la misma.</p><p></p>|<p>**Escenario 1:** Acceso a Redes Sociales desde el Pie de Página</p><p>Dado que el usuario está navegando en la página y se encuentra en el pie de página,</p><p>cuando presiona uno de los iconos de las redes sociales: Instagram, Facebook, Twitter o Youtube,</p><p>Entonces la página lo redirige a otra ventana con enlace a la red social seleccionada.</p><p></p>|**EP07**|
|**US-23**|Exploración selectiva con la barra de navegación|<p>Como usuario, quiero explorar la página web utilizando los botones de la barra de navegación superior para dirigirme a la sección de mi elección.</p><p></p>|<p>**Escenario 1:** Navegación con Botones de la Barra</p><p>Dado que el usuario está navegando en la página web,</p><p>cuando selecciona un botón de la barra de navegación: "Contáctanos", "Acerca de", "Descarga" o "Inicio",</p><p>Entonces la página lo redireccionará a la sección elegida por el usuario.</p><p></p>|**EP07**|

## 3.3. Impact Mapping

<img src="img/impact_mapping.png" alt="Impact Mapping">

## 3.4. Product Backlog

Para analizar el nivel de dificultad de las tareas, utilizamos la secuencia de Fibonacci (1,2,3,5,8) para crear nuestro Product Backlog.

<table>
  <thead>
    <tr>
      <th># Orden</th>
      <th>User Story ID</th>
      <th>Descripción</th>
      <th>Story Points<br>(1/2/3/5/8)</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>1</td><td>US-01</td><td>Como nuevo usuario, quiero registrarme en la aplicación para poder tener mi cuenta.</td><td>2</td></tr>
    <tr><td>2</td><td>US-03</td><td>Como usuario registrado, quiero iniciar sesión en la aplicación para acceder dentro de ella.</td><td>3</td></tr>
    <tr><td>3</td><td>US-02</td><td>Como usuario registrado, quiero modificar mi perfil para tener mi información actualizada en el sistema.</td><td>2</td></tr>
    <tr><td>4</td><td>US-04</td><td>Como usuario registrado, quiero cambiar mi contraseña para tener una mayor seguridad.</td><td>2</td></tr>
    <tr><td>5</td><td>US-05</td><td>Como usuario registrado, quiero cerrar sesión en la aplicación para que mi cuenta no quede guardada en mi móvil.</td><td>2</td></tr>
    <tr><td>6</td><td>US-11</td><td>Como usuario quiero modificar el video de la cámara para poder visualizar cómodamente los videos.</td><td>3</td></tr>
    <tr><td>7</td><td>US-15</td><td>Como usuario quiero realizar un reconocimiento facial, para tener guardado mi perfil.</td><td>5</td></tr>
    <tr><td>8</td><td>US-12</td><td>Como usuario quiero crear perfiles de reconocimiento para que las cámaras reconozcan a las personas recurrentes en mi domicilio.</td><td>5</td></tr>
    <tr><td>9</td><td>US-13</td><td>Como usuario quiero poder actualizar los perfiles de reconocimiento para tener noción de las personas incluidas en la lista.</td><td>3</td></tr>
    <tr><td>10</td><td>US-14</td><td>Como usuario quiero eliminar perfiles de reconocimiento para tener actualizado mis invitados permitidos.</td><td>3</td></tr>
    <tr><td>11</td><td>US-16</td><td>Como usuario, deseo poder compartir acceso a mis cámaras con invitados temporales, como familiares que visitan mi hogar, para que puedan ver las cámaras durante su estadía.</td><td>5</td></tr>
    <tr><td>12</td><td>US-17</td><td>Como usuario, deseo poder registrar eventos importantes en un calendario integrado en la aplicación, para mantener un registro de eventos relevantes relacionados con la seguridad de mi hogar.</td><td>3</td></tr>
    <tr><td>13</td><td>US-06</td><td>Como usuario, quiero acceder a la visualización en tiempo real de todas mis cámaras de seguridad para poder monitorear mi hogar en cualquier momento.</td><td>8</td></tr>
    <tr><td>14</td><td>US-09</td><td>Como usuario, quiero personalizar mis preferencias de notificación para recibir alertas de acuerdo a mis necesidades y establecer momentos de tranquilidad cuando lo requiera.</td><td>3</td></tr>
    <tr><td>15</td><td>US-07</td><td>Como usuario, quiero recibir notificaciones en tiempo real cuando una persona desconocida sea detectada por las cámaras de seguridad para estar al tanto de posibles amenazas en mi propiedad.</td><td>5</td></tr>
    <tr><td>16</td><td>US-10</td><td>Como usuario, deseo configurar alarmas personalizadas, como sirenas o notificaciones específicas, en caso de intrusión, para estar informado de manera efectiva en situaciones de seguridad.</td><td>3</td></tr>
    <tr><td>17</td><td>US-08</td><td>Como usuario, quiero acceder al historial de eventos para revisar y mantener un registro de todas las detecciones de personas desconocidas y las acciones tomadas en mi propiedad.</td><td>3</td></tr>
    <tr><td>18</td><td>US-20</td><td>Como usuario, deseo proporcionar información de contacto de emergencia a la aplicación, como números de teléfono de familiares o amigos en caso de alerta, para garantizar una respuesta rápida en situaciones de emergencia.</td><td>3</td></tr>
    <tr><td>19</td><td>US-19</td><td>Como usuario, quiero tener la capacidad de comunicarme rápidamente con el centro de seguridad más cercano en caso de emergencia para obtener ayuda inmediata y proteger mi seguridad y la de mi familia.</td><td>3</td></tr>
    <tr><td>20</td><td>US-18</td><td>Como usuario, deseo recibir un informe semanal de seguridad que resuma la actividad de las cámaras en mi hogar, para estar al tanto de lo que ha sucedido durante la semana.</td><td>3</td></tr>
    <tr><td>21</td><td>US-21</td><td>Como usuario, quiero visualizar el video del producto que se muestra en la página web para obtener información más detallada y completa sobre sus características y funcionalidades.</td><td>3</td></tr>
    <tr><td>22</td><td>US-22</td><td>Como usuario, quiero establecer contacto con la empresa para enviar un mensaje detallado con el objetivo de resolver algunas dudas que puedan surgir durante mi experiencia en la plataforma.</td><td>3</td></tr>
    <tr><td>23</td><td>US-23</td><td>Como usuario, quiero explorar y visualizar la información de la empresa a través de las redes sociales para obtener detalles adicionales y tener una comprensión más completa de la misma.</td><td>2</td></tr>
    <tr><td>24</td><td>US-24</td><td>Como usuario, quiero explorar la página web utilizando los botones de la barra de navegación superior para dirigirme a la sección de mi elección.</td><td>5</td></tr>
  </tbody>
</table>

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design
### 4.1.1. EventStorming
#### 4.1.1.1. Candidate Context Discovery
#### 4.1.1.2. Domain Message Flows Modeling
#### 4.1.1.3. Bounded Context Canvases
### 4.1.2. Context Mapping
### 4.1.3. Software Architecture
#### 4.1.3.1. System Landscape Diagram
#### 4.1.3.2. Context Level Diagrams
#### 4.1.3.3. Container Level Diagrams
#### 4.1.3.4. Deployment Diagrams
## 4.2. Tactical-Level Domain-Driven Design
### 4.2.X. Bounded Context: <Bounded Context Name>
#### 4.2.X.1. Domain Layer
#### 4.2.X.2. Interface Layer
#### 4.2.X.3. Application Layer
#### 4.2.X.4. Infrastructure Layer
#### 4.2.X.5. Component Level Diagrams
#### 4.2.X.6. Code Level Diagrams
##### 4.2.X.6.1. Class Diagrams
##### 4.2.X.6.2. Database Design Diagram



