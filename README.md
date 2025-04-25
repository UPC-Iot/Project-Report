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
#### Competitive Analysis Landscape

**¿Por qué llevar a cabo este análisis?**  
El objetivo de este análisis es conocer mejor a los competidores y contrastar nuestra idea inicial con su verdadera propuesta de valor, identificando puntos de diferenciación que permitan a CamGuard destacar en el mercado de seguridad para hogares y pequeños negocios.

| **Aspecto** | ![CamGuard Logo](URL) **CamGuard** | ![Verisure Logo](URL) **Verisure** | ![Prosegur Logo](URL) **Prosegur** | ![Grupo Navarro Logo](URL) **Grupo Navarro** |
|---|---|---|---|---|
| **Overview**<br>Perfil | Startup peruana de seguridad inteligente que protege hogares mediante sistemas de vigilancia con IA, cámaras inteligentes y conexión remota. | Multinacional especializada en seguridad electrónica para hogares y negocios con presencia en más de 15 países. | Empresa global con servicios integrales de seguridad física, electrónica y ciberseguridad. | Empresa nacional que vende, instala y mantiene sistemas de seguridad accesibles a nivel nacional. |
| **Ventaja competitiva**<br>¿Qué valor ofrece al cliente? | Monitoreo 24/7 con inteligencia artificial, cámaras con activación automática, respuesta inmediata, conexión global y enfoque en hogares. | Tecnología de última generación, fuerte presencia de marca, monitoreo profesional. | Diversificación, experiencia global, enfoque integral en seguridad física y digital. | Variedad de productos a precios accesibles, cobertura nacional, atención personalizada. |
| **Mercado objetivo** | Familias y pequeños negocios en Lima Metropolitana interesados en seguridad avanzada. | Propietarios de viviendas y pymes preocupados por la seguridad. | Grandes empresas, gobiernos y entidades financieras. | Hogares e instituciones medianas que buscan soluciones económicas. |
| **Estrategias de marketing** | Presencia en redes sociales, landing page, colaboraciones con influencers en tecnología y seguridad, alianzas estratégicas. | Campañas televisivas, redes sociales, marketing boca a boca, referidos. | Participación en ferias, marketing institucional, estrategia B2B. | Publicidad local, ventas directas, redes sociales, eventos feriales. |
| **Productos y Servicios** | Cámaras con IA, app de control remoto, sistema de alertas automatizadas, emisión de humo disuasorio, conexión directa con seguridad. | Alarmas inteligentes, sensores de movimiento, cámaras, panel de control, control desde app. | Vigilancia física, monitoreo electrónico, transporte de valores, ciberseguridad. | Cámaras IP, cercos eléctricos, alarmas, intercomunicadores y videoporteros. |
| **Precios & Costos** | Equipos: S/800–1200<br>Mensual: S/100–150 | Equipos: S/1600–2000<br>Mensual: S/170–220 | Equipos: S/1000–1800<br>Mensual: S/120–180 | Equipos: S/1000–1600<br>Mensual: S/100–150 |
| **Canales de distribución**<br>(Web y/o Móvil) | Página web, aplicación móvil, contacto directo por WhatsApp. | Página web, app móvil, call center. | Web corporativa, canales empresariales. | Página web, contacto por WhatsApp, ventas telefónicas. |
| **Fortalezas** | Tecnología con IA, enfoque especializado, experiencia digital, sistema de respuesta automática. | Marca reconocida, amplia cobertura, sistema probado. | Servicios variados, experiencia global, reputación consolidada. | Precios bajos, atención local, instalación rápida. |
| **Debilidades** | Falta de posicionamiento, startup nueva, dependencia tecnológica. | Alto costo, menor personalización. | Costos elevados, falta de enfoque en hogares. | Bajo reconocimiento de marca, limitada innovación tecnológica. |
| **Oportunidades** | Expansión en Lima, alianzas locales, hogares más digitalizados, hogares con mayor percepción de inseguridad. | Crecimiento del mercado latinoamericano, nuevos productos inteligentes. | Demanda creciente de ciberseguridad, nuevas tecnologías aplicadas a vigilancia. | Crecimiento de clases medias, interés en protección de hogares. |
### 2.1.2. Estrategias y tácticas frente a competidores
## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas
## 2.3. Needfinding
### 2.3.1. User Personas

<img src="img/User Persona.png" alt="User Persona" >
### 2.3.2. User Task Matrix

| User Task                                                                 | Frecuencia     | Importancia |
|---------------------------------------------------------------------------|----------------|-------------|
| Revisar regularmente si el sistema de seguridad cubre las necesidades actuales del hogar. | Siempre        | Alta        |
| Observar comportamientos sospechosos o inusuales cerca de su vivienda.   | Casi Siempre   | Alta        |
| Definir cuánto puede gastar mensualmente en soluciones de seguridad.     | Siempre        | Alta        |
| Consultar a expertos en tecnología para conocer nuevas herramientas de protección. | Casi Siempre   | Media       |
| Analizar diferentes alternativas de monitoreo y alarmas domésticas.      | Siempre        | Alta        |
| Leer experiencias de otros usuarios sobre dispositivos de seguridad.     | Casi Siempre   | Alta        |
| Evaluar el costo-beneficio de sistemas de vigilancia antes de comprarlos.| Siempre        | Alta        |
### 2.3.3. User Journey Mapping

<img src="img/User Journey Mapping.jpeg" alt="User Journey Mapping" >
### 2.3.4. Empathy Mapping

<img src="img/Empathy Mapping.png" alt="Empathy Mapping" >
### 2.3.5. As-is Scenario Mapping

| Phases| Preparación para salir de la casa                                                                 | Salir de casa                                                                                          | Volver a casa                                                                                           |
|---------------------------|----------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|
| **Doing**                 | - Revisar que las ventanas estén bien cerradas y sin daños.                                       | - Asegurarme de cerrar con llave todas las entradas.                                                   | - Observar si hay algo fuera de lo habitual al entrar.                                                  |
|                           | - Desconectar electrodomésticos innecesarios para evitar accidentes eléctricos.                   | - Confirmar que todo está bien colocado y que no hay objetos fuera de lugar.                          | - Comprobar que las cerraduras y ventanas siguen intactas.                                              |
|                           |                                                                                                    | - Hacer un chequeo rápido general antes de partir.                                                     |                                                                                                          |
| **Thinking**              | - Espero que con estas acciones mi hogar permanezca protegido en mi ausencia.                     | - Deseo que mi jornada transcurra sin contratiempos y que mi casa siga intacta.                        | - Me gustaría encontrar mi hogar tal como lo dejé.                                                       |
|                           | - Confío en que no suceda ningún percance mientras estoy fuera.                                   | - Confío en que los cuidados que tomé antes de salir hayan sido útiles.                               | - Sería ideal contar con tecnología que ayude a vigilar la casa de forma remota.                        |
| **Feeling**               | - Inquietud por si olvidé cerrar algo importante.                                                  | - Nervios por lo que pueda pasar mientras no estoy.                                                    | - Alivio de regresar y ver que todo sigue igual.                                                         |
|                           | - Temor por la seguridad de mis pertenencias valiosas.                                            | - Cierta calma por haber hecho lo que estaba a mi alcance.                                             | - Paz mental al notar que no hubo incidentes.                                                            |

## 2.4. Ubiquitous Language

Para el desarrollo de nuestro proyecto en **SecureWave**, es fundamental establecer un lenguaje común que facilite la comunicación entre los desarrolladores, diseñadores, usuarios finales y demás actores involucrados. Este lenguaje refleja las necesidades y preocupaciones de los usuarios respecto a la seguridad del hogar, y nos permite diseñar soluciones efectivas y centradas en el usuario. A continuación, presentamos los términos clave que forman parte del lenguaje ubicuo de nuestro sistema:

## Términos Clave

- **Home Security System**  
  Conjunto de dispositivos y tecnologías interconectadas que permiten proteger una vivienda ante posibles intrusos o situaciones de riesgo.

- **Smart Monitoring**  
  Vigilancia automatizada mediante cámaras inteligentes, sensores y dispositivos conectados que detectan actividad inusual y envían alertas en tiempo real.

- **Access Control**  
  Tecnología que permite gestionar quién puede entrar a la vivienda mediante cerraduras electrónicas, tarjetas inteligentes, reconocimiento facial, entre otros.

- **Motion Detection**  
  Sistema capaz de detectar movimientos no esperados dentro o alrededor del hogar, activando alarmas o notificaciones instantáneas.

- **Real-Time Alerts**  
  Notificaciones inmediatas enviadas al usuario cuando se detecta una anomalía o intento de acceso no autorizado.

- **User Dashboard**  
  Interfaz personalizada desde la cual los usuarios pueden revisar el estado de su hogar, ver las cámaras en tiempo real y configurar sus preferencias de seguridad.

- **Remote Access**  
  Capacidad del usuario de controlar el sistema de seguridad desde cualquier lugar mediante una app móvil o plataforma web.

- **Threat Recognition**  
  Algoritmos que analizan patrones y comportamientos para identificar posibles amenazas con mayor precisión y reducir falsas alarmas.

- **Secure Entry Log**  
  Registro detallado de todas las entradas y salidas del hogar, permitiendo al usuario hacer seguimiento de la actividad.

- **Automated Locking**  
  Funcionalidad que permite cerrar puertas o ventanas de forma automática si se detecta una situación sospechosa o si el usuario lo programa.

- **Energy-Safe Mode**  
  Modo del sistema que apaga o reduce el consumo energético de ciertos dispositivos cuando no se detecta presencia en casa.

- **Emergency Protocol**  
  Conjunto de acciones automáticas que el sistema activa en caso de detectar una emergencia, como avisar a la policía, activar sirenas, y enviar alertas a contactos de confianza.

- **Safe Zones**  
  Áreas específicas del hogar que cuentan con sensores reforzados y monitoreo más estricto por tratarse de espacios sensibles (como habitaciones o salas con objetos de valor).

- **Privacy Control**  
  Opciones para desactivar temporalmente cámaras o sensores en zonas determinadas del hogar cuando se desee mayor privacidad.

- **System Health Check**  
  Diagnóstico automatizado del funcionamiento del sistema, que notifica al usuario si un dispositivo está fallando o necesita mantenimiento.

- **Intrusion Detection**  
  Sistema especializado en identificar entradas forzadas, manipulación de puertas/ventanas o presencias no autorizadas.

- **User Roles**  
  Configuración de distintos niveles de acceso al sistema para familiares, invitados o empleados del hogar, asegurando el control de permisos.

- **24/7 Surveillance**  
  Monitoreo constante del hogar sin interrupciones, con respaldo en la nube y almacenamiento seguro de video.

- **Security Patterns**  
  Análisis del comportamiento habitual del usuario (como horas de entrada y salida) para detectar desviaciones que puedan indicar un riesgo.

- **Panic Mode**  
  Botón o comando de emergencia que activa todos los sistemas de defensa del hogar de inmediato en caso de una amenaza inminente.

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



