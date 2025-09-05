# <center>Project Report</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software - 2025-20</strong><br>
    <strong>Aplicaciones para Dispositivos Móviles - 1807</strong><br>
    <strong>Profesor: Jorge Luis Mayta Guillermo</strong><br>
    <br><strong>Informe del Trabajo Final</strong>
</p>


<p align="center">
    <strong>Startup: 
        Wapps</strong><br>
    <strong>Producto: Red Carga</strong>
</p>

<div style="text-align:center;">
    <h3 align="center">Team Members:</h3>
    <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Ariana Cecilia Agreda Sobrino</td>
            <td>u202315044</td>
        </tr>
        <tr>
            <td>Claudia Valeria Belledonne Espinoza</td>
            <td>u202210259</td>
        </tr>
        <tr>
            <td>Mauricio Daniel Elera Rodríguez</td>
            <td>u202313702</td>
        </tr>
        <tr>
            <td>María Patricia Hernández Uchuya</td>
            <td>u202311258</td>
        </tr>
        <tr>
            <td>Fabiola Del Rocio Saldaña Ayala</td>
            <td>u202313773</td>
        </tr>
    </table>
</div>

<p align="center">
    <strong>Septiembre, 2025</strong>
</p>

<br>

<div style="text-align:center;">
    <h1 align="center">Registro de versiones del Informe</h1>
    </br>
    <table align="center">
        <tr>
            <th>Versión</th>
            <th>Fecha</th>
            <th>Autor</th>
            <th>Descripción de modificaciones</th>
        </tr>
        <tr>
            <td>0</td>
            <td>3/09/2025</td>
            <td>Ariana Agreda</td>
            <td>Creación del reporte.</td>
        </tr>
    </table>
<div>

<br>

# Project Report Collaboration Insights
Link del repositorio del reporte: https://github.com/Wapps1/Project-Report

## TB1

<br>

# Contenido
[Student Outcome](#student-outcome)

- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo I: Presentación](#capítulo-i-presentación)
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
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    - [4.1.1. EventStorming](#411-eventstorming)
      - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
      - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping](#412-context-mapping)
    - [4.1.3. Software Architecture](#413-software-architecture)
      - [4.1.3.1. Software Architecture Context Level Diagrams](#4131-software-architecture-context-level-diagrams)
      - [4.1.3.2. Software Architecture Container Level Diagrams](#4132-software-architecture-container-level-diagrams)
      - [4.1.3.3. Software Architecture Deployment Diagrams](#4133-software-architecture-deployment-diagrams)
  - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    - [4.2.X. Bounded Context: Nombre](#42x-bounded-context-nombre)
      - [4.2.X.1. Domain Layer](#42x1-domain-layer)
      - [4.2.X.2. Interface Layer](#42x2-interface-layer)
      - [4.2.X.3. Application Layer](#42x3-application-layer)
      - [4.2.X.4. Infrastructure Layer](#42x4-infrastructure-layer)
      - [4.2.X.5. Bounded Context Software Architecture Component Level Diagrams](#42x5-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.X.6. Bounded Context Software Architecture Code Level Diagrams](#42x6-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.X.6.1. Bounded Context Domain Layer Class Diagrams](#42x61-bounded-context-domain-layer-class-diagrams)
        - [4.2.X.6.2. Bounded Context Database Design Diagram](#42x62-bounded-context-database-design-diagram)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

  
<br>
<br>

# Student Outcome

<br>
<br>

# Objetivos SMART


# Capítulo I: Presentación

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
### 1.1.2. Perfiles de integrantes del equipo

<table align="center" border="1" cellspacing="0" cellpadding="8" style="width: 90%; border-collapse: collapse;">
  <tr>
    <td style="width: 150px; text-align: center;">
      <img src="img/profile-photos/ari.jpg"  width="520"></img>
    </td>
      <td>
          <p align="center"><strong>Ariana Agreda - u202315044</strong></p>
          <p align="justify">
            Mi nombre es Ariana Agreda, tengo 19 años y soy estudiante del 6to ciclo de Ingeniería de Software en la UPC. Me considero una persona creativa, responsable y comprometida con cada tarea. Por ello, estoy dispuesta a dedicar un gran esfuerzo y apoyo para que logremos los mejores resultados para el proyecto.
          </p>
    </td>
  </tr>
</table>

<table align="center" border="1" cellspacing="0" cellpadding="8" style="width: 90%; border-collapse: collapse;">
  <tr>
    <td style="width: 150px; text-align: center;">
      <img src="img/profile-photos/ClaudiaBelledonne.jpg"  width="520"></img>
    </td>
      <td>
          <p align="center"><strong>Claudia Belledonne - u202210259</strong></p>
          <p align="justify">
            Mi nombre es Claudia Belledonne, tengo 20 años y me encuentro en mi tercer año de Ingeniería de Software en la UPC.
            En general, soy alguien creativa, responsable, dedicada y manejo bien el hacer muchas tareas a la vez.
            Para este trabajo, me comprometo a brindar mi máximo esfuerzo y dedicación.
          </p>
    </td>
  </tr>
</table>

<table align="center" border="1" cellspacing="0" cellpadding="8" style="width: 90%; border-collapse: collapse;">
  <tr>
    <td style="width: 150px; text-align: center;">
      <img src="img/profile-photos/mau.jpg"  width="520"></img>
    </td>
      <td>
          <p align="center"><strong>Mauricio Elera - u202313702</strong></p>
          <p align="justify">
            Mi nombre es Mauricio Elera, tengo 19 años y soy estudiante del 6to ciclo de Ingeniería de Software en la UPC. Me considero una persona proactiva, organizada y con muchas ganas de aprender. Estoy comprometido con el trabajo en equipo y dispuesto a aportar todo lo necesario para que nuestro proyecto sea exitoso.
          </p>
    </td>
  </tr>
</table>

<table align="center" border="1" cellspacing="0" cellpadding="8" style="width: 90%; border-collapse: collapse;">
  <tr>
    <td style="width: 150px; text-align: center;">
      <img src="img/profile-photos/maria-hernandez.jpeg"  width="520"></img>
    </td>
      <td>
          <p align="center"><strong>María Hernández - u202311258</strong></p>
          <p align="justify">
             Estudio la carrera de Ingeniería de Software, tengo 19 años y actualmente me encuentro cursando el sexto ciclo de dicha carrera. Tengo conocimientos en C++, C#, Python, Java, HTML, CSS, JavaScript y Vue. Me considero una persona con responsabilidad, optimismo y honestidad, cualidades que considero fundamentales para una colaboración efectiva en equipo y un buen desarrollo en este proyecto.
          </p>
    </td>
  </tr>
</table>
<table align="center" border="1" cellspacing="0" cellpadding="8" style="width: 90%; border-collapse: collapse;">
  <tr>
    <td style="width: 150px; text-align: center;">
      <img src="img/profile-photos/fabiola.jpeg"  width="520"></img>
    </td>
      <td>
          <p align="center"><strong>Fabiola Saldaña - u202313773</strong></p>
          <p align="justify">
             Mi nombre es Fabiola Saldaña, tengo 19 años y actualmente curso el 6to ciclo de la carrera de Ingeniería de Software. En lo personal busco aprender constantemente y me considero alguien responsable, proactiva y dedicada con mis trabajos. Es por ello que me comprometo apoyar al equipo con mis habilidades y conocimientos para alcanzar los mejores resultados.
          </p>
    </td>
  </tr>
</table>

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
#### 1.2.2.2. Lean UX Assumptions
#### 1.2.2.3. Lean UX Hypothesis Statements
#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

<br>
<br>

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas

#### **Segmento 1: Personas o empresas que quieres transportar carga de forma interprovincial**

**Dirigido a:** Personas o representantes de empresas que desean enviar carga interprovincial y buscan seleccionar entre distintas propuestas el servicio más adecuado.<br>
**Objetivo:** Conocer las necesidades, prioridades y problemas de quienes desean transportar carga interprovincialmente, identificando los procesos más complicados o lentos, así como sus expectativas frente a una herramienta digital como Red Carga.<br>
**Preguntas:**<br>
1. ¿Cuál es su nombre completo?  
2. ¿Qué edad tiene?  
3. ¿En qué provincia reside actualmente?  
4. ¿A qué se dedica (ocupación/empresa)?  
5. ¿Con qué frecuencia realiza envíos interprovinciales de carga?  
6. ¿Qué tipo de carga suele enviar con mayor frecuencia?  
7. ¿Cómo se informa o busca actualmente las empresas de transporte disponibles?  
8. ¿Qué criterios utiliza para seleccionar una empresa de transporte (precio, rapidez, seguridad, reputación, etc.)?  
9. ¿Cuánto tiempo le toma en promedio encontrar una empresa que se ajuste a sus necesidades?  
10. ¿Qué canales utiliza para contactar a la empresa (teléfono, redes sociales, página web, presencial, etc.)?  
11. ¿Con qué problemas se ha encontrado al buscar una empresa de transporte confiable?  
12. ¿Qué tan fácil o difícil le resulta obtener una cotización?  
13. ¿Qué aspectos del proceso le generan mayor frustración o demora?  
14. ¿Ha tenido experiencias negativas con el servicio de transporte? Si es así, ¿cuáles?  
15. ¿Qué documentos o requisitos legales suele solicitarle la empresa de transporte?  
16. ¿Qué tan cómodo se siente con los procesos legales y contractuales de los envíos?  
17. ¿Qué importancia le da al seguimiento en tiempo real de la carga?  
18. ¿Qué medio de pago prefiere o utiliza habitualmente para contratar un servicio de transporte?  
19. ¿Le ha resultado complicado el proceso de pago o facturación?  
20. ¿Qué tan importante es para usted la atención al cliente en este tipo de servicios?  
21. ¿Qué considera más valioso: rapidez, seguridad o precio? ¿Por qué?  
22. ¿Qué le gustaría que fuera diferente en la experiencia actual de enviar carga interprovincial?  
23. Si existiera una aplicación que centralice cotizaciones, contratos y seguimiento, ¿qué funcionalidades le gustaría que incluyera?  
24. ¿Estaría dispuesto(a) a utilizar una plataforma digital como Red Carga para simplificar este proceso?  


#### **Segmento 2: Administradores de empresas que se encargan del transporte interprovincial de carga**

**Dirigido a:** Personas que administran una empresa de transporte interprovincial y desean agilizar sus procesos de conexión con clientes y cotizaciones.<br>
**Objetivo:** Comprender los procesos internos que siguen los administradores desde el primer contacto con el cliente hasta la entrega final, identificando fallas, tiempos, impacto en la calidad del servicio, así como sus expectativas frente a una herramienta digital como Red Carga.<br>
**Preguntas:**<br>
1. ¿Cuál es su nombre completo?
2. ¿Qué edad tiene?
3. ¿En qué provincia opera principalmente su empresa?
4. ¿Cuál es su cargo u ocupación dentro de la empresa?
5. ¿Qué tipo de cargas suelen transportar con mayor frecuencia?
6. ¿Cuál es el proceso actual desde que un cliente solicita información hasta que se concreta un envío?
7. ¿Cuánto tiempo puede tardar en promedio ese proceso?
8. ¿Qué canales utiliza su empresa para recibir solicitudes (teléfono, WhatsApp, correo, oficina física, etc.)?
9. ¿Qué medio considera más eficiente para captar clientes?
10. ¿Qué tan frecuente es que un cliente pida varias cotizaciones antes de decidirse?
11. ¿Qué factores considera más decisivos para que un cliente elija su empresa (precio, tiempo, seguridad, reputación)?
12. ¿Cuáles son los principales problemas que enfrenta al coordinar un envío con un cliente?
13. ¿Qué pasos considera más engorrosos o que más retrasan el proceso?
14. ¿Qué tipo de documentos o trámites legales se deben gestionar en cada envío?
15. ¿Cómo se asegura de que la información y documentación de los clientes esté completa?
16. ¿Qué dificultades ha tenido con el manejo de contratos y comprobantes de pago?
17. ¿Qué herramientas digitales utiliza actualmente su empresa para la gestión de clientes y envíos?
18. ¿Qué tan satisfecho está con estas herramientas?
19. ¿Qué aspectos considera más débiles en la comunicación actual con los clientes?
20. ¿De qué manera realiza actualmente el seguimiento y control de las cargas en tránsito?
21. ¿Qué tan importante es para su empresa ofrecer trazabilidad en tiempo real a los clientes?
22. ¿Qué problemas ha tenido con el cumplimiento de plazos o pérdidas de carga?
23. ¿Qué estrategias utilizan para fidelizar clientes?
24. ¿Qué expectativas tendría de una aplicación como Red Carga para mejorar la comunicación, cotizaciones y procesos legales?
25. ¿Qué funcionalidades imprescindibles debería incluir esta herramienta para que su empresa la utilice activamente?


<br>

### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
### 2.3.5. As-is Scenario Mapping

## 2.4. Ubiquitous Language

<br>
<br>

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping
## 3.2. User Stories
## 3.3. Impact Mapping
## 3.4. Product Backlog

<br>
<br>

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design
### 4.1.1. EventStorming
#### 4.1.1.1. Candidate Context Discovery
#### 4.1.1.2. Domain Message Flows Modeling
#### 4.1.1.3. Bounded Context Canvases
### 4.1.2. Context Mapping
### 4.1.3. Software Architecture
#### 4.1.3.1. Software Architecture Context Level Diagrams
#### 4.1.3.2. Software Architecture Container Level Diagrams
#### 4.1.3.3. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design
### 4.2.X. Bounded Context: Nombre
#### 4.2.X.1. Domain Layer
#### 4.2.X.2. Interface Layer
#### 4.2.X.3. Application Layer
#### 4.2.X.4. Infrastructure Layer
#### 4.2.X.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.X.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.X.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.X.6.2. Bounded Context Database Design Diagram


<br>
<br>

# Conclusiones

## Conclusiones y recomendaciones


<br>
<br>

# Bibliografía


<br>
<br>

# Anexos

Link del Repositorio del Informe: https://github.com/Wapps1/Project-Report <br>
Link del Repositorio del Proyecto: <br>
Link del Repositorio del Backend: <br>
