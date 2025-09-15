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

- [Project Report](#project-report)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
  - [TB1](#tb1)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Objetivos SMART](#objetivos-smart)
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
    - [🎯 Segmento Objetivo #1: Personas o empresas que quieren transportar carga de forma interprovincial](#-segmento-objetivo-1-personas-o-empresas-que-quieren-transportar-carga-de-forma-interprovincial)
      - [📊 Aspectos Demográficos](#-aspectos-demográficos)
      - [🌍 Aspectos Geográficos](#-aspectos-geográficos)
      - [🧠 Aspectos Psicográficos](#-aspectos-psicográficos)
    - [🚛 Segmento Objetivo #2: Administradores de empresas que se encargan del transporte interprovincial de carga](#-segmento-objetivo-2-administradores-de-empresas-que-se-encargan-del-transporte-interprovincial-de-carga)
      - [📊 Aspectos Demográficos](#-aspectos-demográficos-1)
      - [🌍 Aspectos Geográficos](#-aspectos-geográficos-1)
      - [🧠 Aspectos Psicográficos](#-aspectos-psicográficos-1)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
      - [**Segmento 1: Personas o empresas que quieren transportar carga de forma interprovincial**](#segmento-1-personas-o-empresas-que-quieren-transportar-carga-de-forma-interprovincial)
      - [**Segmento 2: Administradores de empresas que se encargan del transporte interprovincial de carga**](#segmento-2-administradores-de-empresas-que-se-encargan-del-transporte-interprovincial-de-carga)
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

### 🎯 Segmento Objetivo #1: Personas o empresas que quieren transportar carga de forma interprovincial

#### 📊 Aspectos Demográficos
- **Sexo:** Masculino y Femenino
- **Edades:** 18 a 65+ años (personas naturales) y responsables de logística/administración en empresas
- **Nivel socioeconómico:** Clases A, B, C, D y E

#### 🌍 Aspectos Geográficos
- **Nacionalidad:** Peruana
- **Zona geográfica:** Urbana y rural
- **Departamento:** Todos los departamentos del Perú (incluida Lima Metropolitana y Callao)

#### 🧠 Aspectos Psicográficos
- Valoran comparar precios y tiempos de entrega para optimizar costo/beneficio
- Buscan formalidad (emisión de guía de remisión cuando corresponda) y trazabilidad en tiempo real
- Prefieren procesos simples desde el móvil: solicitud → cotización → trato → pago en la app
- Confían en proveedores con buena reputación, soporte en chat y políticas claras de cambios
- **Perfil de uso:** envíos puntuales (personas) y recurrentes (pymes/empresas), con necesidades de plantilla para ítems frecuentes

---

### 🚛 Segmento Objetivo #2: Administradores de empresas que se encargan del transporte interprovincial de carga

#### 📊 Aspectos Demográficos
- **Sexo:** Masculino y Femenino
- **Edades:** 21 a 65+ años (conductores y administradores/operadores de flota)
- **Nivel socioeconómico:** Clases A, B, C, D y E (predominio de micro, pequeñas y medianas empresas; compatible con grandes flotas)

#### 🌍 Aspectos Geográficos
- **Nacionalidad:** Peruana
- **Zona geográfica:** Urbana y rural
- **Departamento:** Todos los departamentos del Perú (incluida Lima Metropolitana y Callao)

#### 🧠 Aspectos Psicográficos
- Quieren captar demanda formal y estable para mejorar ocupación y flujo de caja
- Valoran una app que facilite cotizar rápido, chatear con el cliente y gestionar documentos (guía de transportista)
- Necesitan activar geolocalización para generar confianza y cumplir con hitos operativos (recogido/en ruta/entregado)
- Prefieren liquidaciones claras en la plataforma (99% al proveedor, 1% fee) y visibilidad de pagos
- **Perfil operativo:** flotas pequeñas y medianas como núcleo, con soporte para grandes operadores y subcontratación controlada

<br>
<br>

<!-- Capítulo II: Requirements Elicitation & Analysis -->
<h1>2.1. Competidores</h1>
<h2>2.1.1. Análisis competitivo</h2>

<table border="1" cellspacing="0" cellpadding="6" width="100%">
  <tr>
    <th colspan="6">Competitive Analysis Landscape</th>
  </tr>

  <tr>
    <td align="center"><b>¿Por qué llevar a cabo este análisis?</b></td>
    <td colspan="5" align="center">
      Identificar cómo <b>RedCarga</b> puede diferenciarse en el mercado peruano de carga interprovincial frente a jugadores existentes,
      qué funcionalidades y tácticas priorizar, y qué riesgos/amenazas debemos mitigar.
    </td>
  </tr>

  <tr>
    <th colspan="2" align="center">Nombre y logo</th>
    <th align="center">Su startup: <b>RedCarga</b></th>
    <th align="center">Competidor 1: <b>Efletex (Perú)</b></th>
    <th align="center">Competidor 2: <b>DeltaX (LatAm)</b></th>
    <th align="center">Competidor 3: <b>MiCarga (Tracklink, Perú)</b></th>
  </tr>

  <!-- PERFIL -->
  <tr>
    <th rowspan="2" align="center">Perfil</th>
    <td align="center"><b>Overview</b></td>
    <td>
      <p align="justify">
        <b>RedCarga</b> es una app móvil que conecta empresas/usuarios que envían <b>carga pesada interprovincial</b> con transportistas,
        con experiencia en tiempo real: solicitud con fotos (IA estima medidas), cotizaciones instantáneas, negociación por chat,
        pago in-app, <b>documentos automáticos</b> y <b>tracking GPS obligatorio</b> tras el pago.
      </p>
    </td>
    <td>
      <p align="justify">
        Plataforma peruana de transporte de carga pesada (2018). Conecta generadores de carga con transportistas vía web/móvil,
        modernizando la logística con comunidades de transporte. Empezó B2B y se amplió a pymes/usuarios.
      </p>
    </td>
    <td>
      <p align="justify">
        Plataforma digital B2B (2020) conocida como “Uber de camiones” andino. Ofrece software integral para gestionar logística
        end-to-end y opera en varios países con marketplace regional unificado y respaldo de inversión.
      </p>
    </td>
    <td>
      <p align="justify">
        Plataforma peruana creada por <b>Tracklink</b> (GPS vehicular) para conectar clientes y transportistas a nivel nacional.
        Comunidad online + app móvil; los transportistas ofertan/aceptan servicios “de A a B”.
      </p>
    </td>
  </tr>

  <tr>
    <td align="center"><b>Ventaja competitiva<br/>¿Qué valor ofrece?</b></td>
    <td>
      <ul>
        <li><b>1% de comisión</b> (solo si el pago es in-app) → mejores tarifas netas y retención en la plataforma.</li>
        <li><b>Documentos obligatorios automáticos</b> (guía de remisión y de transportista) tras el pago.</li>
        <li><b>IA</b> para estimar medidas desde fotos + plantillas reutilizables.</li>
        <li>Enfoque <b>Perú</b> (adaptación rápida a normativa local).</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Pionero local; conocimiento del mercado peruano.</li>
        <li>Ahorro de tiempo/costos; comparación de ofertas.</li>
        <li>Seguimiento GPS 24/7; verificación y reputación.</li>
        <li>Soporte con asesores; menos viajes en vacío.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Digitaliza procesos end-to-end (licitaciones, planificación, tracking).</li>
        <li>Homologación/seguridad; alertas y documentación digital.</li>
        <li>Gran red regional; cargas de retorno.</li>
        <li>Fintech: anticipos de pago y beneficios.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Matching con <b>cotización y cierre</b> en línea.</li>
        <li><b>Seguimiento GPS</b> con el stack Tracklink.</li>
        <li>App móvil nativa para transportistas (Android/iOS).</li>
      </ul>
    </td>
  </tr>

  <!-- PERFIL DE MARKETING -->
  <tr>
    <th rowspan="2" align="center">Perfil de marketing</th>
    <td align="center"><b>Mercado objetivo</b></td>
    <td>
      <ul>
        <li><b>Perú</b>, rutas interprovinciales.</li>
        <li>Empresas medianas/grandes y transportistas verificados (heavy cargo).</li>
        <li>Pymes con envíos recurrentes y usuarios con envíos puntuales de alto volumen.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Perú; carga pesada interprovincial (≥1 t).</li>
        <li>Corporativos (minería, consumo, logística) → pymes/mudanzas.</li>
        <li>No última milla/paquetería ligera.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Medianas y grandes empresas (bebidas, puertos, agro, construcción).</li>
        <li>Región andina + México; oferta: empresas y choferes independientes.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Perú; cargas ligeras-medianas-pesadas (foco operativo nacional).</li>
        <li>Transportistas con GPS Tracklink y clientes que requieren visibilidad.</li>
      </ul>
    </td>
  </tr>

  <tr>
    <td align="center"><b>Estrategias de marketing</b></td>
    <td>
      <ul>
        <li>Lanzamiento por <b>corredores</b> (Lima–Arequipa, Lima–Piura) con clientes ancla.</li>
        <li><b>Onboarding asistido</b> a transportistas (WhatsApp/llamadas) + verificación rápida.</li>
        <li>Incentivos a <b>pago in-app</b> (documentos + tracking solo tras pagar).</li>
        <li>Narrativa “<b>hecho en Perú</b>”, casos de uso locales y PR sectorial.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>PR y estudios de mercado; prensa local.</li>
        <li>RR. SS. (comunidad “amigos ruteros”, tutoriales, promos).</li>
        <li>Activaciones B2B y testimonios de ahorros.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Ventas consultivas y demos; casos de éxito y logos.</li>
        <li>PR en ecosistema startup; redes para captar transportistas.</li>
        <li>Incentivos (anticipos/beneficios) y oficinas locales.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Uso de canales Tracklink (base instalada GPS) y prensa logística.</li>
        <li>Redes sociales para captar oferta y demanda.</li>
        <li>Promesa de seguridad/visibilidad 24/7.</li>
      </ul>
    </td>
  </tr>

  <!-- PERFIL DEL PRODUCTO -->
  <tr>
    <th rowspan="3" align="center">Perfil del producto</th>
    <td align="center"><b>Productos &amp; Servicios</b></td>
    <td>
      <ul>
        <li>Marketplace móvil: solicitud por ítem (fotos→<b>IA</b>→medidas), ruta con puntos intermedios.</li>
        <li><b>Cotizaciones en tiempo real</b>, chat, estado <i>trato</i> y <i>trato formal</i> tras pagar.</li>
        <li><b>Documentos</b> automáticos (cliente/proveedor) y <b>tracking</b> obligatorio.</li>
        <li>Ajustes post-pago: top-ups, reembolsos, y recálculo del 1%.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Marketplace: órdenes, chat/alertas, calificaciones.</li>
        <li>Tracking en vivo.</li>
        <li>GPS/fleet propio (reportes, cumplimiento SUTRAN/OSINERGMIN).</li>
        <li>Vertical de mudanzas.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li><b>SaaS TMS</b> configurable (roles, dashboards, KPIs; ML para matching).</li>
        <li>Marketplace por invitación; compartir cargas/rutas entre clientes.</li>
        <li>APIs/integraciones; <b>fintech</b> (anticipos/factoring).</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Marketplace: clientes publican; transportistas ofertan y cierran en línea.</li>
        <li>Tracking en tiempo real con GPS de Tracklink.</li>
      </ul>
    </td>
  </tr>

  <tr>
    <td align="center"><b>Precios &amp; Costos</b></td>
    <td>
      <ul>
        <li><b>1% de comisión</b> solo si el pago se realiza en la app.</li>
        <li>Con top-ups o reembolsos, el 1% se <b>recalcula</b> sobre el monto final.</li>
        <li>Documentos/tracking se habilitan <b>solo tras el pago</b> (incentivo anti “cerrar por fuera”).</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Registro/uso básico gratis.</li>
        <li>Comisión al transportista por flete (rango de mercado ~5–10%).</li>
        <li>Ahorros reportados para clientes; GPS con precio adicional.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>SaaS: suscripción/licenciamiento según tamaño/uso.</li>
        <li>Marketplace: comisión por transacción.</li>
        <li>Ingresos fintech (descuentos/intereses de anticipos).</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>No publica comisión/estructura de precios en canales abiertos.</li>
      </ul>
    </td>
  </tr>

  <tr>
    <td align="center"><b>Canales de distribución<br/>(Web y/o Móvil)</b></td>
    <td>
      <ul>
        <li><b>Móvil (Android)</b> como canal principal.</li>
        <li>Panel web para empresas (posterior/roadmap).</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Web + apps Android/iOS (&gt;5k descargas Android).</li>
        <li>24/7; notificaciones en tiempo real.</li>
        <li>Soporte telefónico y oficina en Lima; números MX/CO/AR.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Web SaaS (empresas) + apps Android/iOS (&gt;10k descargas).</li>
        <li>Tracking resiliente; equipos locales por país.</li>
        <li>Integraciones vía API con ERPs.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Web (captación) + <b>MiCarga Transportista</b> en Android/iOS.</li>
      </ul>
    </td>
  </tr>

  <!-- SWOT -->
  <tr>
    <th rowspan="4" align="center">Análisis SWOT</th>
    <td align="center"><b>Fortalezas</b></td>
    <td>
      <ul>
        <li><b>Costos</b>: 1% → propuesta agresiva para atraer oferta/demanda.</li>
        <li><b>Compliance</b>: documentos automáticos + tracking obligatorio.</li>
        <li><b>UX</b> simple y móvil-first; IA en captura de medidas.</li>
        <li><b>Local</b>: velocidad para adaptar normativa peruana.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>First mover en Perú; red local validada.</li>
        <li>Funcionalidades adaptadas a normativa local.</li>
        <li>Seguridad: verificación + GPS + reputación.</li>
        <li>Soporte personalizado y servicios complementarios (GPS).</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Solución integral TMS + Marketplace.</li>
        <li>&gt;200 empresas; 42k transportistas, 240k viajes monitoreados.</li>
        <li>Seguridad/homologación y analítica avanzada.</li>
        <li>Respaldo VC; beneficios y fintech.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Respaldo Tracklink (confianza + infraestructura GPS).</li>
        <li>Matching con cotización/cierre en app.</li>
        <li>Apps móviles nativas para operación en campo.</li>
      </ul>
    </td>
  </tr>

  <tr>
    <td align="center"><b>Debilidades</b></td>
    <td>
      <ul>
        <li><b>Efecto red</b> inicial limitado (liquidez por corredor).</li>
        <li>Riesgo de <b>desintermediación</b> si no se incentiva pago in-app.</li>
        <li>Necesidad de soporte 24/7 y verificación robusta.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Menor escala vs actores regionales.</li>
        <li>Menor financiación; posible menor sofisticación analítica.</li>
        <li>Foco amplio (B2B + mudanzas) diluye esfuerzos.</li>
        <li>Presencia internacional limitada.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Menos accesible para pequeños/espóradicos.</li>
        <li>Plataforma compleja; curva de aprendizaje.</li>
        <li>Marketplace por invitación limita crecimiento.</li>
        <li>Riesgos de adopción digital multi-país.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Información pública limitada sobre comisiones/precios.</li>
        <li>Foco mixto (ligera-mediana-pesada) puede diluir heavy cargo.</li>
        <li>Dependencia del ecosistema GPS Tracklink.</li>
      </ul>
    </td>
  </tr>

  <tr>
    <td align="center"><b>Oportunidades</b></td>
    <td>
      <ul>
        <li>Formalización (guías electrónicas) y digitalización del sector.</li>
        <li>Nichos de heavy cargo especializado y pymes regionales.</li>
        <li>Alianzas con gremios, terminales, aseguradoras.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Digitalización/guías electrónicas; captar independientes.</li>
        <li>Verticales clave: minería, agro, retail.</li>
        <li>Expansión andina y alianzas (seguros, combustible, MTC).</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Mercado LatAm grande; nuevos países/industrias.</li>
        <li>Profundizar fintech (seguros, leasing, puntos).</li>
        <li>Alianzas gobierno/gremios; monetizar insights.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Integrar documentación electrónica para diferenciarse.</li>
        <li>Captar pymes y regiones poco digitalizadas.</li>
        <li>Aprovechar base Tracklink para escalar oferta.</li>
      </ul>
    </td>
  </tr>

  <tr>
    <td align="center"><b>Amenazas</b></td>
    <td>
      <ul>
        <li>Efletex/DeltaX/MiCarga con base instalada o escala.</li>
        <li>Cambios regulatorios/seguros que eleven barreras.</li>
        <li>Desintermediación cliente-transportista.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Competidores tecnológicos y nuevos entrantes.</li>
        <li>Actores tradicionales/soluciones internas.</li>
        <li>Cambios regulatorios; resistencia de transportistas.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Competencia local ágil y jugadores globales.</li>
        <li>Entornos regulatorios diversos.</li>
        <li>Preferencia por soluciones locales; incidentes de seguridad.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>DeltaX (escala) y Efletex (arraigo local).</li>
        <li>Nuevos entrantes móviles con UX simple y costos bajos.</li>
      </ul>
    </td>
  </tr>
</table>



### 2.1.2. Estrategias y tácticas frente a competidores

<h4>1) Palancas de diferenciación (Producto, Precio, Plaza, Promoción)</h4>
<ul>
  <li><b>Producto:</b>
    <ul>
      <li><b>Documentos automáticos</b> (guía de remisión/transportista) <u>solo</u> al pagar en-app → reduce fricción y asegura uso del pago in-app.</li>
      <li><b>IA en captura</b> (fotos → medidas sugeridas) + <b>plantillas reutilizables</b> por ítem/ruta para acelerar nuevas solicitudes.</li>
      <li><b>Tracking obligatorio</b> pospago con alertas (salida, llegada a hitos, ETA) y tableros móviles simples para el cliente.</li>
      <li><b>Antidesintermediación:</b> ocultar teléfono/email hasta pago; chat con detección de intento de compartir contacto; <i>beneficios</i> (docs, tracking, soporte) solo si pagan en la app.</li>
    </ul>
  </li>
  <li><b>Precio:</b>
    <ul>
      <li><b>Comisión plana 1%</b> (solo in-app). Mensaje: “Mejor tarifa neta para ambos”.</li>
      <li><b>Incentivos</b>: cantidad limitada de cotizaciones gratuitas de bienvenida para los clientes.</li>
    </ul>
  </li>
  <li><b>Plaza (canales):</b>
    <ul>
      <li><b>Móvil-first</b> (Android). Panel web ligero para empresas (seguimiento y reportes) en fase 2.</li>
      <li><b>Alianzas</b>: gremios/terminales, patios logísticos, cámaras regionales, aseguradoras (seguro básico ligado al pago in-app), pasarela local de bajo costo.</li>
    </ul>
  </li>
  <li><b>Promoción:</b>
    <ul>
      <li><b>Hecho en Perú</b> + cumplimiento local (documentos automáticos) como narrativa central.</li>
      <li><b>Onboarding asistido</b> a transportistas (WhatsApp/llamadas) + jornadas presenciales en terminales.</li>
      <li>Contenido simple: “cómo cotizar”, “cómo activar GPS”, “cómo emitir guías en 1 toque”.</li>
    </ul>
  </li>
</ul>

<br>

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas

#### **Segmento 1: Personas o empresas que quieren transportar carga de forma interprovincial**

**Dirigido a:** Personas o representantes de empresas que desean enviar carga interprovincial y buscan seleccionar entre distintas propuestas el servicio más adecuado.<br>
**Objetivo:** Conocer las necesidades, prioridades y problemas de quienes desean transportar carga interprovincialmente, identificando los procesos más complicados o lentos, así como sus expectativas frente a una herramienta digital como Red Carga.<br>
**Preguntas:**<br>
**Preguntas:**  
1. ¿Cuál es su nombre completo?  
2. ¿Qué edad tiene?  
3. ¿En qué provincia reside actualmente?  
4. ¿A qué se dedica (ocupación/empresa)?  
5. ¿Con qué frecuencia realiza envíos interprovinciales y qué tipo de carga envía normalmente?  
6. ¿Cómo busca y selecciona actualmente una empresa de transporte? (canales, criterios).  
7. ¿Cuánto tiempo le toma en promedio encontrar una empresa que se ajuste a sus necesidades?  
8. ¿Qué canales utiliza para contactar a la empresa (teléfono, redes sociales, página web, presencial, etc.)?  
9. ¿Cuántas cotizaciones suele solicitar antes de decidirse por una empresa?  
10. ¿Qué tan fácil o difícil le resulta obtener una cotización adecuada?  
11. ¿Qué documentos o requisitos legales suele solicitarle la empresa de transporte y qué tan complicados le resultan?  
12. ¿Qué medio de pago utiliza normalmente y qué problemas ha tenido en este proceso?  
13. ¿Qué tan importante es para usted la seguridad, el precio, la rapidez y la atención al cliente en este servicio?  
14. ¿Qué experiencias negativas ha tenido en el pasado (demoras, pérdidas, mal servicio, etc.)?  
15. Si existiera una aplicación que centralice cotizaciones, contratos, pagos y seguimiento, ¿qué funcionalidades consideraría imprescindibles?  



#### **Segmento 2: Administradores de empresas que se encargan del transporte interprovincial de carga**

**Dirigido a:** Personas que administran una empresa de transporte interprovincial y desean agilizar sus procesos de conexión con clientes y cotizaciones.<br>
**Objetivo:** Comprender los procesos internos que siguen los administradores desde el primer contacto con el cliente hasta la entrega final, identificando fallas, tiempos, impacto en la calidad del servicio, así como sus expectativas frente a una herramienta digital como Red Carga.<br>
**Preguntas:**<br>
1. ¿Cuál es su nombre completo?  
2. ¿Qué edad tiene?  
3. ¿En qué provincia opera principalmente su empresa?  
4. ¿Cuál es su cargo u ocupación dentro de la empresa?  
5. ¿Qué tipo de carga gestionan con mayor frecuencia y qué volumen promedio manejan en sus envíos?  
6. ¿Cómo es actualmente el proceso desde que un cliente solicita información hasta la confirmación de un envío?  
7. ¿Cuánto suele demorar este proceso y qué pasos generan más retrasos?  
8. ¿Qué canales utilizan para captar clientes y cuáles resultan más efectivos?  
9. ¿Qué factores influyen más en la decisión de un cliente al contratarlos (precio, tiempo, seguridad, reputación)?  
10. ¿Qué problemas o dificultades se presentan con mayor frecuencia al coordinar un envío?  
11. ¿Qué tipo de documentos o trámites legales deben gestionarse en cada envío y qué dificultades enfrentan con ellos?  
12. ¿Qué dificultades han tenido en el manejo de contratos, comprobantes de pago o facturación?  
13. ¿Qué aspectos considera más débiles en la comunicación actual con los clientes?  
14. ¿Cómo gestionan actualmente el seguimiento de la carga y qué tan importante es la trazabilidad en tiempo real?  
15. Si existiera una aplicación que le permita centralizar en un solo lugar la gestión de cotizaciones, contratos, pagos y seguimiento de envíos, ¿qué funcionalidades le resultarían más valiosas para su empresa?



<br>

### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

En el siguiente apartado, analizaremos a nuestros segmentos objetivos para identificar sus necesidades y en base a esto ofrecerles soluciones óptimas a sus problemas.

<br>

### 2.3.1. User Personas
**Segmento 1: Personas o empresas que quieren transportar carga de forma interprovincial**
<img src="img/Chapter-2/UserPersona1.png" alt="User persona - segmento 1" width="700"/>



**Segmento 2: Administradores de empresas que se encargan del transporte interprovincial de carga**
<img src="img/Chapter-2/UserPersona2.png" alt="User persona - segmento 2" width="700"/>



### 2.3.2. User Task Matrix

**Segmento 1: Personas o empresas que quieren transportar carga de forma interprovincial**

| **Task Matrix**                                                                | **Frecuencia** | **Importancia** |
| ------------------------------------------------------------------------------ | -------------- | --------------- |
| Solicitar transporte para enviar electrodomésticos a provincias                | Alta           | Alta            |
| Comparar precios y tiempos de entrega entre diferentes proveedores             | Alta           | Alta            |
| Coordinar entregas con clientes finales                                        | Alta           | Alta            |
| Empacar y preparar los electrodomésticos para el transporte                    | Media          | Alta            |
| Hacer seguimiento de los envíos en tiempo real                                 | Alta           | Alta            |
| Registrar ventas y costos en hojas de cálculo o aplicaciones simples           | Media          | Alta            |
| Responder consultas y coordinar ventas en Facebook, WhatsApp e Instagram       | Alta           | Media           |
| Negociar precios con clientes y proveedores de transporte                      | Alta           | Alta            |
| Gestionar pagos y reembolsos a través de apps bancarias o billeteras digitales | Alta           | Alta            |
| Resolver problemas con entregas dañadas, retrasos o pérdidas                   | Media          | Alta            |
| Capacitarse en nuevas herramientas digitales para mejorar la gestión           | Baja           | Media           |

<br>

**Segmento 2: Administradores de empresas que se encargan del transporte interprovincial de carga**

| **Task Matrix**                                                              | **Frecuencia** | **Importancia** |
| ---------------------------------------------------------------------------- | -------------- | --------------- |
| Coordinar y asignar rutas a los camiones                                     | Alta           | Alta            |
| Cotizar precios y responder solicitudes de transporte                        | Alta           | Alta            |
| Gestionar la documentación de envío (guías de remisión, contratos, facturas) | Alta           | Alta            |
| Supervisar el estado y mantenimiento de los camiones                         | Media          | Alta            |
| Contactar y negociar con nuevos clientes                                     | Alta           | Alta            |
| Hacer seguimiento del transporte y ubicación de las unidades en tiempo real  | Alta           | Alta            |
| Controlar pagos, ingresos y liquidaciones con clientes y transportistas      | Alta           | Alta            |
| Publicar y responder mensajes en Facebook, WhatsApp y otras plataformas      | Alta           | Media           |
| Registrar datos de viajes, pagos y clientes en hojas de cálculo o cuadernos  | Media          | Alta            |
| Capacitarse en nuevas herramientas tecnológicas para optimizar procesos      | Baja           | Alta            |



### 2.3.3. User Journey Mapping
**Segmento 1: Personas o empresas que quieren transportar carga de forma interprovincial**
<img src="img/Chapter-2/JourneyMap1.png" alt="Journey Map - segmento 1" width="750"/>

<br>

**Segmento 2: Administradores de empresas que se encargan del transporte interprovincial de carga**
<img src="img/Chapter-2/JourneyMap2.png" alt="Journey Map - segmento 2" width="750"/>


### 2.3.4. Empathy Mapping
**Segmento 1: Personas o empresas que quieren transportar carga de forma interprovincial**
<img src="img/Chapter-2/EmpathyMap1.png" alt="Empathy Map - segmento 1" width="700"/>

<br>

**Segmento 2: Administradores de empresas que se encargan del transporte interprovincial de carga**
<img src="img/Chapter-2/EmpathyMap2.png" alt="Empathy Map - segmento 2" width="700"/>

### 2.3.5. As-is Scenario Mapping
**Segmento 1: Personas o empresas que quieren transportar carga de forma interprovincial**
<br>

**Segmento 2: Administradores de empresas que se encargan del transporte interprovincial de carga**

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
