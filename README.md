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
CamGuard compite con empresas que brindan soluciones de seguridad para hogares y negocios. A continuación se presentan tres competidores directos del mercado:

- **Verisure**: Empresa internacional que ofrece soluciones de seguridad electrónica con monitoreo las 24 horas.
- **Prosegur**: Empresa global de seguridad con un portafolio que incluye transporte de valores, vigilancia y servicios de ciberseguridad.
- **Grupo Navarro**: Empresa peruana que comercializa e instala sistemas de seguridad, destacando por sus precios accesibles y cobertura nacional.
- 
### 2.1.1. Análisis competitivo
#### Competitive Analysis Landscape

**¿Por qué llevar a cabo este análisis?**  
El objetivo de este análisis es conocer mejor a los competidores y contrastar nuestra idea inicial con su verdadera propuesta de valor, identificando puntos de diferenciación que permitan a CamGuard destacar en el mercado de seguridad para hogares y pequeños negocios.

A continuación, realizamos un análisis competitivo para identificar oportunidades, amenazas, ventajas y posibles desventajas que podemos tener dentro del mercado en comparación a otras empresas que realicen actividades similares a las nuestras. De esta forma, podremos prepararnos para resaltar frente a los consumidores.

<table>
  <thead>
    <tr>
      <th colspan="7"><b>Competitive Analysis Landscape</b></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="2" align="center">¿Por qué llevar a cabo este análisis?</td>
      <td colspan="5" align="center">Identificar las fortalezas, debilidades, oportunidades y amenazas de nuestra solución, CamGuard, frente a competidores consolidados del sector de seguridad, con el fin de validar nuestra propuesta de valor, afinar nuestra estrategia de posicionamiento y asegurar una ventaja competitiva sostenible en el mercado.</td>
    </tr>
    <tr>
      <td colspan="2">PERFIL</td>
      <td><picture><p align="center"><img src="img/Verisure_logo.png" alt="Verisure Logo" height="50" width="200"></p> </picture></td>
      <td><picture><p align="center"><img src="img/Prosegur_logo.png" alt="Prosegur Logo" height="50" width="200"></p></picture></td>
      <td><picture><p align="center"><img src="img/GrupoNavarro_logo.png" alt="Grupo Navarro Logo" height="50" width="200"></p></picture></td>
      <td><picture><p align="center"><img src="img/Controltech_logo.jpeg" alt="Otros" height="50" width="200"></p></picture></td>
      <td><picture><p align="center"><img src="img/Camguard_Logo.png" alt="CamGuard Logo" height="50" width="200"></p></picture></td>
    </tr>
    <tr>
      <td rowspan="2">Perfil</td>
      <td>Overview</td>
      <td>Empresa líder en alarmas para hogar y negocio con respuesta inmediata.</td>
      <td>Multinacional de seguridad física y electrónica.</td>
      <td>Empresa peruana de seguridad privada y sistemas de alarma.</td>
      <td>Pequeños proveedores locales de alarmas.</td>
      <td>CamGuard brinda seguridad inteligente con integración IoT, notificaciones móviles y atención personalizada 24/7.</td>
    </tr>
    <tr>
      <td>Ventaja Competitiva ¿Qué valor ofrece a los clientes?</td>
      <td>Respuesta inmediata y monitoreo constante con tecnología propia.</td>
      <td>Cobertura internacional y servicios de seguridad diversificados.</td>
      <td>Precios accesibles y presencia nacional.</td>
      <td>Atención local rápida pero limitada en tecnología.</td>
      <td>Alta personalización de servicios, bajo costo de implementación y acceso vía App de monitoreo en tiempo real.</td>
    </tr>
    <tr>
      <td rowspan="2">Perfil de Marketing</td>
      <td>Mercado objetivo</td>
      <td>Familias, pymes y grandes empresas.</td>
      <td>Empresas, bancos, residenciales.</td>
      <td>Familias y negocios locales.</td>
      <td>Pequeños negocios, viviendas individuales.</td>
      <td>Hogares de clase media, emprendimientos y pequeñas empresas urbanas.</td>
    </tr>
    <tr>
      <td>Estrategias de Marketing</td>
      <td>Publicidad masiva, marketing digital, alianzas estratégicas.</td>
      <td>Marketing corporativo, presencia en eventos de seguridad.</td>
      <td>Marketing tradicional y boca a boca.</td>
      <td>Promociones locales y anuncios comunitarios.</td>
      <td>Campañas digitales geolocalizadas, marketing de contenido, recomendaciones personalizadas.</td>
    </tr>
    <tr>
      <td rowspan="3">Perfil del Producto</td>
      <td>Productos & Servicios</td>
      <td>Alarmas, sensores de movimiento, monitoreo remoto.</td>
      <td>Vigilancia física, alarmas, transporte de valores.</td>
      <td>Instalación de cámaras, alarmas y respuesta armada.</td>
      <td>Alarmas básicas y cámaras de seguridad económicas.</td>
      <td>Sistema IoT de seguridad, monitoreo vía App, asistencia inmediata y control de accesos remoto.</td>
    </tr>
    <tr>
      <td>Precios & Costos</td>
      <td>Planes desde $30/mes + costo de instalación.</td>
      <td>Precios por proyecto o servicio específico.</td>
      <td>Planes económicos desde S/ 70/mes.</td>
      <td>Pagos únicos accesibles o mensualidades bajas.</td>
      <td>Suscripción mensual flexible desde $15, sin costos de instalación inicial.</td>
    </tr>
    <tr>
      <td>Canales de Distribución (web / móvil)</td>
      <td>Web, App móvil, atención telefónica.</td>
      <td>Web, atención directa a empresas.</td>
      <td>Web y puntos físicos de atención.</td>
      <td>Tiendas locales y teléfono.</td>
      <td>Web, App móvil, Chatbots, redes sociales.</td>
    </tr>
    <tr>
      <td rowspan="4">Análisis SWOT</td>
      <td>Fortalezas</td>
      <td>Fuerte marca, rapidez en instalación, buena atención postventa.</td>
      <td>Infraestructura amplia, servicios diversificados.</td>
      <td>Cercanía y precios bajos.</td>
      <td>Atención rápida en zonas específicas.</td>
      <td>Alta flexibilidad, costos accesibles, innovación tecnológica continua.</td>
    </tr>
    <tr>
      <td>Debilidades</td>
      <td>Costos altos en comparación con otros locales.</td>
      <td>Burocracia en atención a nuevos clientes.</td>
      <td>Capacidad limitada para servicios de gran escala.</td>
      <td>Falta de innovación tecnológica.</td>
      <td>Reconocimiento de marca aún en desarrollo, dependencia de canales digitales.</td>
    </tr>
    <tr>
      <td>Oportunidades</td>
      <td>Crecimiento de la demanda de seguridad para hogares.</td>
      <td>Expansión a nuevos sectores (industrial, tecnológico).</td>
      <td>Mayor conciencia en seguridad local.</td>
      <td>Expansión en zonas urbanas vulnerables.</td>
      <td>Mercado emergente de hogares inteligentes y seguridad domiciliaria inteligente.</td>
    </tr>
    <tr>
      <td>Amenazas</td>
      <td>Competencia más económica y agresiva.</td>
      <td>Innovaciones de startups de seguridad tecnológica.</td>
      <td>Empresas globales expandiéndose en Perú.</td>
      <td>Mayor competencia tecnológica.</td>
      <td>Adopción lenta en ciertos sectores, cambios regulatorios de privacidad y datos.</td>
    </tr>
  </tbody>
</table>



### 2.1.2. Estrategias y tácticas frente a competidores
A continuación, se detallan las estrategias y tácticas preliminares que aplicará **SwiftPort** para afrontar las fortalezas de los competidores, aprovechar sus debilidades, y responder al contexto de oportunidades y amenazas identificadas en el análisis competitivo.

## Estrategias

- **Diferenciación mediante integración tecnológica**:  
  Aprovechar la integración de **IoT, RFID, QR** y **dashboards colaborativos** como propuesta de valor única frente a plataformas tradicionales que no combinan múltiples tecnologías.

- **Enfoque en la facilidad de adopción**:  
  Reducir la barrera de entrada ofreciendo capacitaciones gratuitas, onboarding personalizado y una interfaz intuitiva, aprovechando las debilidades de los competidores que presentan curvas de aprendizaje elevadas o costos de implementación altos.

- **Penetración de mercado en sectores subatendidos**:  
  Atacar segmentos como minería, agroindustria y distribución regional, sectores que aún no han sido prioritarios para competidores como Flexport o WiseTech.

- **Modelo de precios flexible**:  
  Ofrecer un esquema de **suscripción mensual escalable** que se ajuste a diferentes tamaños de empresa, frente a los modelos de licenciamiento costoso y de alta inversión inicial que presentan competidores.

- **Alianzas estratégicas locales**:  
  Formar alianzas con operadores logísticos medianos y grandes a nivel regional para fortalecer la adopción de SwiftPort y superar la ventaja de redes globales de actores como Flexport.

## Tácticas

- **Pilotos y demos gratuitas en sectores clave**:  
  Lanzar programas piloto de 30-60 días para demostrar el valor de la plataforma en campo, con especial enfoque en industrias de alta demanda logística.

- **Eventos y ferias sectoriales**:  
  Participar en eventos de logística, agroindustria y minería para aumentar la visibilidad y generar leads cualificados.

- **Marketing de contenido técnico**:  
  Crear artículos, whitepapers y casos de éxito orientados a mostrar la facilidad de integración de SwiftPort con ERP/CRM/WMS, resaltando nuestra ventaja competitiva.

- **Campañas de adopción digital para PYMEs**:  
  Lanzar campañas enfocadas en concientizar a pequeñas y medianas empresas sobre los beneficios de adoptar tecnología logística, para combatir la resistencia al cambio detectada como amenaza.

- **Soporte técnico especializado 24/7**:  
  Implementar soporte técnico con rápida atención para usuarios, reforzando la percepción de bajo riesgo al momento de adoptar nuestra solución.
## 2.2. Entrevistas


En esta sección se aborda la investigación tomando como base la recolección de información a través de entrevistas a representantes de los segmentos objetivo.

## 2.2.1. Diseño de Entrevistas

Esta sección incluye la relación de preguntas principales y complementarias para entrevistas, dirigidas a cada uno de los segmentos. Es importante aplicar buenas prácticas en el diseño de entrevistas. También se debe considerar qué tipo de información principal y complementaria se necesita recolectar para construir los arquetipos, tales como características demográficas (género, edad, distrito de residencia, estado civil, familia, ocupación), así como otras características como personalidad, habilidades, marcas e influencias, dispositivos de preferencia, canales digitales de interacción, objetivos, frustraciones, biografía o background.

### Preguntas Principales:
1. ¿Cuáles son las principales preocupaciones respecto a la seguridad de tu hogar?
2. ¿Has tenido alguna experiencia previa de robo o situaciones de inseguridad?
3. ¿Utilizas actualmente algún sistema de seguridad en tu hogar? Si es así, ¿Qué tipo de seguridad empleas?
4. ¿Cómo te sientes respecto a la tecnología de vigilancia existente?
5. ¿Qué características consideras más importantes en un sistema de seguridad para tu hogar?
6. ¿Cómo prefieres recibir notificaciones en caso de situaciones sospechosas?
7. ¿Cuánto estarías dispuesto a gastar en un sistema de vigilancia para tu hogar?
8. ¿Qué características adicionales te gustaría ver en un sistema de vigilancia?

### Preguntas Complementarias:
1. ¿Qué dispositivos prefieres usar para monitorear tu hogar (teléfono móvil, computadora)?
2. ¿Qué marcas o tecnologías usas actualmente en tu vida cotidiana y qué tan satisfecho estás con ellas?
3. ¿Cuál es tu principal frustración con los sistemas de seguridad actuales?
4. ¿Estarías dispuesto a cambiar tu sistema de seguridad si ofreciera características innovadoras que mejoren tu experiencia?

---

### 2.2.2. Registro de Entrevistas

A continuación se presentan las entrevistas realizadas, donde se especifican los detalles de cada entrevistado, su video y el resumen de la entrevista con sus características objetivas y subjetivas.

### Segmento: Personas que residan en zonas urbanas dentro del distrito de Lima

### Entrevistado #1: Nicolle Gonzales
![Entrevista 1](img/Entrevista 1.png)


- **Sexo:** Femenino
- **Edad:** 20
- **Distrito:** San Juan de Lurigancho
- **Nivel socioeconómico:** Clase B

#### Entrevista:
- **Link:** [https://youtu.be/SW0SmZon-fE](https://youtu.be/SW0SmZon-fE)
- **Momento en el que inicia:** 0:00
- **Duración:** 3:30

#### Resumen:
La entrevistada, Nicolle González Bolaños, de 20 años, expresó su preocupación por la posibilidad de contratar un servicio de seguridad que no cumpla con las expectativas, enfatizando la importancia de que el servicio funcione de manera confiable. Aunque no ha tenido experiencias previas de robos o situaciones de seguridad, actualmente utiliza cámaras de vigilancia en el exterior de su casa. Además, se siente positiva acerca de la tecnología de vigilancia actual, destacando la variedad de opciones avanzadas disponibles que brindan mayor seguridad y tranquilidad. 
En cuanto a las características esenciales de un sistema de seguridad en el hogar, considera fundamental la detección de movimiento, especialmente durante ciertas horas del día. Para recibir notificaciones sobre situaciones sospechosas, prefiere alertas con un sonido distintivo que la mantenga informada sobre la fuente de la alerta. Respecto al presupuesto, está dispuesta a gastar entre 500 y 600 soles en un sistema de vigilancia.
Finalmente, ella sugiere que una buena resolución de la cámara, la capacidad de identificar personas, una amplia cobertura visual y un almacenamiento eficiente de datos serían aspectos adicionales valiosos para un sistema de vigilancia.

---

### Entrevistado #2: Yasmin Calderón
![Entrevista 2](img/Entrevista 2.png)

- **Sexo:** Femenino
- **Edad:** 50
- **Distrito:** San Juan de Lurigancho
- **Nivel socioeconómico:** Clase B

#### Entrevista:
- **Link:** [https://youtu.be/Ma6YkZ45ZNs](https://youtu.be/Ma6YkZ45ZNs)
- **Momento en el que inicia:** 0:00
- **Duración:** 4:05

#### Resumen:
La entrevistada, Yasmin Calderón, de 50 años, mencionó que su principal preocupación es evitar que personas desconocidas ingresen a su casa y valora la vigilancia constante para identificar cualquier actividad sospechosa en su puerta. Aunque no ha tenido experiencias previas de robos en su casa, está considerando instalar cámaras de seguridad para mejorar la seguridad. Además, expresó una actitud positiva hacia la tecnología de vigilancia actual y la considera una excelente herramienta para brindar apoyo a los propietarios de viviendas.
Las características más importantes para un sistema de seguridad en su hogar, según ella, incluyen una buena visibilidad, instalación confiable, capacidad de monitoreo en tiempo real desde dispositivos móviles o computadoras, y alertas audibles para situaciones sospechosas. 

Prefiere recibir notificaciones de situaciones sospechosas a través de una alarma en su celular para que pueda ser informada de inmediato. En cuanto al presupuesto, Yasmin está dispuesta a gastar entre 500 y 700 soles en un sistema de vigilancia, siempre que demuestre su eficacia.

Finalmente, sugiere que sería beneficioso tener alarmas o sonidos que alerten sobre actividades sospechosas, como personas que permanecen mucho tiempo en el área de entrada de su casa.

---

### Entrevistado #3: Ian Sanchez
![Entrevista 3](img/Entrevista 3.png)

- **Sexo:** Masculino
- **Edad:** 20
- **Distrito:** Lince
- **Nivel socioeconómico:** Clase B

#### Entrevista:
- **Link:** [https://youtu.be/fRC5i__QzLM](https://youtu.be/fRC5i__QzLM)
- **Momento en el que inicia:** 0:00
- **Duración:** 2:38

#### Resumen:
El entrevistado, Ian, tiene varias preocupaciones principales en cuanto a la seguridad de su hogar, que incluyen el robo, la intrusión de personas no autorizadas, la protección de su familia y sus bienes, así como la seguridad contra incendios y desastres naturales. Afortunadamente, no ha tenido experiencias previas de robo o situaciones de seguridad que lo hayan afectado directamente, pero es consciente de los problemas de delincuencia en su área.
Actualmente, Ian utiliza un sistema de alarma básico con sensores en puertas y ventanas, además de cerraduras de seguridad en las puertas principales. Se siente positivo acerca de la tecnología de vigilancia actual y considera que puede ser una herramienta eficaz para mejorar la seguridad en su hogar.
Para Ian, las características más importantes de un sistema de seguridad en el hogar incluyen la capacidad de monitoreo remoto a través de una aplicación móvil, notificaciones en tiempo real, sensores de movimiento, cámaras de alta resolución y una respuesta rápida de las autoridades en caso de una emergencia. Prefiere recibir notificaciones a través de su teléfono móvil y correo electrónico en caso de situaciones sospechosas.
Ian está dispuesto a gastar hasta $1,000 en un sistema de vigilancia para su hogar, ya que considera que la seguridad de su familia y sus bienes es una inversión importante. Además, valora la facilidad de instalación y mantenimiento del sistema, así como la posibilidad de integrarlo con otros dispositivos inteligentes en su hogar para mayor comodidad y eficiencia.

### 2.2.3. Análisis de entrevistas
En esta sección se presenta el análisis de las entrevistas realizadas a los entrevistados del segmento objetivo. Cada característica se analiza con base en los hallazgos de las entrevistas registradas y los resúmenes de las mismas, proporcionando porcentajes representativos de los aspectos comunes de este segmento.

## Segmento #1: Personas que residen en zonas urbanas dentro del distrito de Lima

### Hallazgos Clave:

#### 1. Preocupación Principal: Eficacia de los Servicios de Seguridad
- **Porcentaje**: 100% (de los entrevistados)
- **Descripción**: Todos los entrevistados comparten la preocupación sobre la eficacia de los servicios de seguridad contratados y la posibilidad de que no cumplan con lo prometido en caso de una emergencia. Esta preocupación resalta la importancia de la confiabilidad de los sistemas de seguridad en el hogar, como lo reflejan las respuestas en sus entrevistas. 
  - **Fuente**: Nicolle, Yasmin, Ian.

#### 2. Intrusión y Robo como Preocupaciones Comunes
- **Porcentaje**: 100% (de los entrevistados)
- **Descripción**: La intrusión y el robo son preocupaciones frecuentes. Todos los entrevistados expresaron el deseo de proteger sus hogares y bienes de personas no autorizadas. La seguridad del hogar es una prioridad común entre ellos.
  - **Fuente**: Nicolle, Yasmin, Ian.

#### 3. Falta de Experiencia Directa con Robos
- **Porcentaje**: 100% (de los entrevistados)
- **Descripción**: Ninguno de los entrevistados ha tenido experiencias previas de robo o situaciones de seguridad que los hayan afectado directamente en sus hogares. Sin embargo, mencionaron ser conscientes de la delincuencia en su entorno, lo que refuerza su deseo de contar con medidas preventivas.
  - **Fuente**: Nicolle, Yasmin, Ian.

#### 4. Uso Actual de Sistemas de Seguridad
- **Porcentaje**: 66.7% (2 de 3 entrevistados)
- **Descripción**: Dos de los entrevistados utilizan actualmente sistemas de seguridad en sus hogares, como cámaras de vigilancia. Esto refleja un interés por adoptar medidas preventivas. El tercer entrevistado está considerando implementarlos en el futuro.
  - **Fuente**: Nicolle, Yasmin.

#### 5. Percepción Positiva de la Tecnología de Vigilancia
- **Porcentaje**: 100% (de los entrevistados)
- **Descripción**: Todos los entrevistados tienen una percepción positiva de la tecnología de vigilancia actual, considerando que las opciones disponibles son eficaces y avanzadas en brindar seguridad. Ven la tecnología como una herramienta valiosa para mejorar la seguridad de sus hogares.
  - **Fuente**: Nicolle, Yasmin, Ian.

#### 6. Características Más Valoradas en un Sistema de Seguridad
- **Porcentaje de entrevistados que valoran la Detección de Movimiento**: 100% (de los entrevistados)
- **Porcentaje de entrevistados que valoran las Notificaciones en Tiempo Real**: 100% (de los entrevistados)
- **Porcentaje de entrevistados que valoran el Monitoreo Remoto por Aplicación Móvil**: 66.7% (2 de 3 entrevistados)
- **Descripción**: Los entrevistados coinciden en la importancia de características como la detección de movimiento y las notificaciones en tiempo real. Además, valoran el monitoreo remoto a través de aplicaciones móviles, ya que consideran estas características como fundamentales para la seguridad y la tranquilidad.
  - **Fuente**: Nicolle, Yasmin, Ian.

---

## Conclusión General

A través del análisis de las entrevistas, se pueden identificar varias características comunes entre los entrevistados de este segmento:

- **Preocupación central sobre la confiabilidad** de los sistemas de seguridad, ya que todos los entrevistados temen que estos no cumplan con lo prometido en situaciones críticas.
- **Preocupación por la intrusión y el robo**, que es una prioridad para la mayoría de los entrevistados, aunque no han experimentado robos directos en sus hogares, sino en su entorno.
- **Interés en la tecnología de seguridad**, con un énfasis particular en la **detección de movimiento**, las **notificaciones en tiempo real** y el **monitoreo remoto** a través de aplicaciones móviles.
- A pesar de no haber tenido experiencias directas con robos, los entrevistados están conscientes de la situación de inseguridad en su entorno y están tomando medidas preventivas como el uso de cámaras de vigilancia.

Este análisis permite construir arquetipos de usuarios basados en las preocupaciones y necesidades comunes del segmento, destacando la importancia de contar con sistemas de seguridad confiables, accesibles y avanzados tecnológicamente.

## 2.3. Needfinding
Con el fin de desarrollar un producto que satisfaga las necesidades de un cliente en particular, SecureWave identificará los User persona, User Task Matrix, User Journey Maps y Empathy Mapping.

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



