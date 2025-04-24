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

**SecureWave** es una empresa emergente que busca enfrentar los desafíos sociales relacionados con la inseguridad, mediante el uso de tecnologías innovadoras adaptadas al mercado peruano. La startup está conformada por estudiantes de la Facultad de Ingeniería y Ciencias de la Universidad Peruana de Ciencias Aplicadas (UPC). Su enfoque principal es el desarrollo de sistemas de vigilancia inteligentes para hogares, ofreciendo una experiencia de seguridad integral y tranquilidad a sus usuarios.

#### Misión

La misión de SafeTech Solutionses proporcionar protección y tranquilidad a las familias peruanas, asegurando la seguridad en sus hogares mediante soluciones tecnológicas de vigilancia avanzadas.

#### Visión

La visión de SafeTech Solutionses convertirse en un referente latinoamericano en soluciones de vigilancia, contribuyendo a mejorar la calidad de vida de las personas. Anhelamos un futuro donde cada familia pueda sentirse segura dentro de su hogar.

#### Valores

- **Seguridad:** Representa el eje central de nuestra labor. Nos dedicamos a ofrecer herramientas eficaces para el bienestar cotidiano de nuestros clientes.
- **Innovación:** Estamos en constante evolución tecnológica para ofrecer soluciones que respondan cada vez mejor a las necesidades del usuario.
- **Compromiso con el usuario:** Colocamos al usuario en el centro de nuestras decisiones, trabajando para superar sus expectativas y mejorar su experiencia.

### 1.1.2. Perfiles de integrantes del equipo
| Integrante            | Foto                |
|-----------------|-----------------|
|  **Frida Sofia Dam Rubianes (u202218352)**   
Soy Frida Dam estoy en el 7mo ciclo de la carrera de ingeniería de software. Me apasiona el trabajo en equipo y encontrar soluciones mediante la tecnologia. Me apasiona el trabajo en equipo y encontrar soluciones mediante la tecnologia. Aportaré en el trabajo con mis conocimientos adquiridos en cursos previos sobre IoT.        |    ![image](https://github.com/user-attachments/assets/75e31180-9705-45e0-b3d0-35ec1f1bc135)
       |
|       |                 |
|       |                 |
|       |                 |




## 1.2. Solution Profile

Nuestra propuesta se centra en **Protectify**, un sistema de seguridad doméstica basado en inteligencia artificial. Este sistema utiliza cámaras de alta resolución que capturan imágenes con gran claridad, permitiendo una vigilancia efectiva del hogar. Cada vez que detecta movimiento, el sistema consulta una base de datos local con tecnología de reconocimiento facial para distinguir entre residentes habituales y personas desconocidas. Si identifica a alguien no reconocido, el sistema envía una alerta al propietario mediante la aplicación móvil de Protectify. El usuario podrá entonces decidir si se trata de un visitante o de un posible intruso. Si se confirma que es un ladrón, se activa un mecanismo que libera humo para obstruir la visibilidad del intruso y se notifica automáticamente a las autoridades más cercanas. Además, el usuario puede crear perfiles personalizados para visitantes frecuentes, acelerando así el proceso de identificación.

### 1.2.1. Antecedentes y problemática

En el contexto actual de creciente urbanización y digitalización, la vigilancia se ha vuelto esencial para garantizar la seguridad ciudadana. Las cámaras de seguridad han evolucionado notablemente, pasando de simples grabaciones a sistemas inteligentes capaces de actuar en tiempo real. Este desarrollo representa una oportunidad importante para incrementar la seguridad en ciudades como Lima, la capital peruana.

Lima enfrenta serios desafíos en materia de seguridad. Aunque se han adoptado estrategias convencionales como el patrullaje policial, persisten deficiencias en la prevención y respuesta efectiva frente a delitos. Según el INEI, en 2020 se registraron 189,656 denuncias por delitos contra el patrimonio. Aunque estas cifras bajaron a 50,776 en el primer semestre de 2021, los robos en viviendas siguen siendo comunes. Datos de Verisure revelan un incremento del 82% en robos a hogares y negocios en 2022 en ciudades como Lima, Callao, Trujillo, Chiclayo, Piura, Cusco, Ica y Arequipa.

Para analizar esta problemática de manera detallada, utilizamos la metodología **5Ws & 2Hs**:

#### What (¿Qué?)
- **Problema:** El incremento de robos en viviendas representa una de las mayores preocupaciones en el país.
- **Relación con la solución:** Protectify permite monitorear el hogar a distancia y reaccionar ante la presencia de intrusos no identificados.

#### When (¿Cuándo?)
- El problema ocurre cuando las viviendas no cuentan con sistemas de seguridad, quedando vulnerables durante la ausencia de sus dueños.

#### Where (¿Dónde?)
- **Uso del producto:** Desde cualquier ubicación, mediante la app Protectify.
- **Público objetivo:** Personas en zonas urbanas de Lima sin sistemas de seguridad instalados.
- **Ubicación del problema:** Principalmente en zonas con alto índice de delincuencia en Lima.

#### Who (¿Quiénes?)
- **Involucrados:** Ladrones, víctimas (dueños y habitantes de las casas), autoridades y vecinos.
- **Afectados:** Personas que pasan muchas horas fuera de casa y no cuentan con vigilancia.
- **Usuarios potenciales:** Personas que ya fueron víctimas, están fuera por viajes, o buscan proteger su hogar.

#### Why (¿Por qué?)
- La inseguridad y la alta tasa de robos motivan la creación de Protectify, con el objetivo de reducir incidentes y ayudar a capturar delincuentes.

#### How (¿Cómo?)
- **Condiciones de uso:** Usuarios que suelen dejar su vivienda desatendida.
- **Medios de difusión:** Publicidad en TikTok, Instagram y Facebook.
- **Acceso al contenido:** A través de la aplicación Protectify, donde se puede revisar cámaras, recibir alertas y activar el mecanismo de defensa.
- **Motivación para la compra:** El crecimiento continuo de la criminalidad en Lima.

#### How much (¿Cuánto?)
- **Presupuesto estimado:** S/. 1000 para el desarrollo e implementación del sistema.

### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements

**Problem Statement 1:** 
Actualmente, hemos notado que la tasa de criminalidad en el Perú es elevada, por lo tanto nuestra solución desea mejorar la tranquilidad y seguridad ciudadana.
Hemos podido identificar que un factor determinante que pone en riesgo la seguridad y economía de los ciudadanos, son los delitos que ocurren en nuestro país, tales como los robos a domicilios, que cuando se producen, los ladrones se llevan dinero u objetos de valor que luego las personas tienen que volver a adquirir.
¿Cómo facilitar nuevas herramientas para luchar contra la delincuencia?

**Problem Statement 2:**
Nuestro entorno demanda información importante para reducir la cantidad de robos a domicilios en Lima. Por medio de esta información, nuestros clientes podrán tener una mayor seguridad y protección dentro de sus domicilios.
Hemos identificado un factor crítico que afecta a la integridad física y mental de la población, el cual se manifiesta en la inseguridad al momento en el que las personas salen de sus viviendas, debido a que al no saber si su domicilio estará lo suficientemente protegida para evitar un robo, les afecta mental y emocionalmente.
¿Cómo podemos mejorar la seguridad de las viviendas de los ciudadanos que residen en Lima?

**Problem Statement 3:**
En la actualidad, podemos ver que cuando un ladrón ingresa a una vivienda en la que no están los dueños, y esta no cuenta con alguna seguridad, los propietarios no pueden hacer nada para evitar el robo, por lo que nuestro producto quiere ofrecer una medida de defensa para frustrar estos intentos de robo.
Logramos identificar que un factor crítico que pone en riesgo la seguridad de los domicilios, es la falta de una acción defensiva en caso un ladrón logre ingresar.
¿Cómo implementar una herramienta en la que se pueda frustrar el robo sin que algún propietario se encuentre presente?

---
#### 1.2.2.2. Lean UX Assumptions

#### Business Outcomes

- Nuestros usuarios necesitan sentirse seguros cuando no están en sus casas.
- Estas necesidades se pueden resolver con un sistema de videovigilancia con IA que alerte al dueño si alguien entra al domicilio.
- Nuestros clientes iniciales son personas entre 20 y 60 años que viven en zonas urbanas de Lima.
- El valor #1 que un cliente quiere de nuestro servicio es poder usar el sistema en todo momento y contar con medidas de autodefensa efectivas.
- El cliente también puede obtener beneficios como el historial de personas que ingresaron, su tiempo dentro y grabaciones en alta definición.
- Vamos a adquirir la mayoría de nuestros clientes a través de campañas en redes sociales y recomendaciones.
- Haremos dinero a través de la venta del producto y el alquiler de servicios.
- Nuestras competencias principales en el mercado son Verisure y Prosegur.
- Los venceremos debido a ventajas como cámaras de alta resolución, mecanismos de autodefensa y registros detallados de ingreso.
- El mayor riesgo que puede enfrentar nuestro producto es que el sistema no detecte ingresos no autorizados o no active las defensas.
- Resolveremos esto a través del mantenimiento regular y simulacros de robo.

#### User Outcomes

- **¿Quién es el usuario?**  
  Personas con viviendas en Lima.

- **¿Dónde encaja nuestro servicio? ¿En su trabajo o vida?**  
  En su vida diaria, protegiendo su hogar cuando no están presentes.

- **¿Cómo y cuándo es usado nuestro producto?**  
  Cada vez que el usuario se ausenta de casa. La app le informa de cualquier ingreso y le permite activar defensas.

- **¿Qué problemas tiene nuestro servicio?**  
  El reto principal es identificar correctamente a quien ingresa a la casa.

- **¿Qué características son importantes?**  
  Identificación precisa, alta resolución de video, y ejecución efectiva de medidas defensivas.

- **¿Cómo debe verse nuestro producto y cómo debe comportarse?**  
  Debe operar 24/7 y notificar de inmediato cualquier actividad sospechosa dentro del hogar.

---
#### 1.2.2.3. Lean UX Hypothesis Statements

- Creemos que proporcionar a los usuarios un sistema de seguridad personal inteligente y adaptable mejorará su sensación diaria de seguridad y bienestar.
Sabremos que esto es cierto cuando al menos el 50% de los usuarios que utilizan nuestros sistemas digan que se sienten más seguros y han reducido sus niveles de estrés en situaciones de seguridad.

- Creemos que la  personalización de nuestro sistema permitirá a los usuarios adaptar las medidas de seguridad a sus necesidades individuales, aumentando así su confianza en la eficacia del sistema.
Sabemos que esto es cierto cuando el 60% de los usuarios utilizan las funciones de personalización de nuestro sistema para adaptarlo a sus necesidades específicas.

#### 1.2.2.4. Lean UX Canvas
![image](https://github.com/user-attachments/assets/f5e27911-b081-4dc5-b6fa-03628aa33355)

## 1.3. Segmentos objetivo

Dado que ofrecemos cámaras de seguridad con tecnología avanzada, es fundamental definir cuidadosamente a quién nos dirigimos para maximizar la eficacia de nuestra estrategia comercial. Por ello, hemos identificado un grupo específico con alto potencial de adopción de nuestra solución.

### Aspectos Demográficos

- **Sexo:** Hombres y mujeres.
- **Edad:** Entre 20 y 60 años.
- **Nivel socioeconómico:** A, B y C (alta, media-alta y media).  
  Nos enfocamos en personas con la capacidad económica para invertir en tecnología de seguridad avanzada, lo cual incrementa las probabilidades de adopción y fidelización de nuestros clientes.
- **Propiedad de vivienda:** Propietarios de casas o departamentos.  
  Al contar con una inversión significativa en bienes inmuebles, este grupo muestra un mayor interés en proteger su patrimonio, convirtiéndose en potenciales usuarios interesados en soluciones efectivas de seguridad.

### Aspectos Geográficos

- **Ubicación:** Lima Metropolitana, Perú.  
  Esta zona, con alta densidad poblacional y preocupaciones constantes por la seguridad, representa un mercado ideal para nuestros servicios, además de permitirnos brindar soporte técnico de forma más eficiente.
- **Zona de residencia:** Urbana.  
  En zonas urbanas, la concentración de viviendas en espacios reducidos incrementa la necesidad de herramientas que garanticen la seguridad del hogar.

### Aspectos Psicográficos

- Personas preocupadas por la protección de su hogar y el bienestar de sus familias.  
  Nuestro producto ofrece una solución proactiva al enviar alertas en tiempo real ante cualquier intrusión, brindando mayor tranquilidad a los usuarios.
- Usuarios con afinidad por la tecnología que buscan mejorar su estilo de vida.  
  Las cámaras inteligentes encajan perfectamente con quienes valoran el control, la comodidad y la innovación en la gestión de la seguridad personal.

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
## 3.1. To-Be Scenario Mapping
## 3.2. User Stories
## 3.3. Impact Mapping
## 3.4. Product Backlog

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



