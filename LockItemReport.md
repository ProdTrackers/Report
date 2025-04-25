<p align="center">
  <img src="assets/upc_logo.png" alt="Logo" width="200"/>
</p>

<h3 align="center"> Universidad Peruana de Ciencias Aplicadas</h3>
<h4 align="center"> Ingeniería de Software  </h4>
<h4 align="center"> Arquitectura de Foftware Emergentes </h4>
<h4 align="center"> Informe de Trabajo Final </h4>

### Startup: 

#### Team Members

- Arrunátegui Aguilar, Josué David
- Chero Eme, Eduardo Andre
- Cortes Hidalgo, Nicolas Andres
- Olivera Guerra, Santiago Mickelle
- Stefano Máquez, Piero 
- Surco Reyes, Franco

#### Sección: SI728

#### Profesor: Marco Antonio León Baca

#### Producto: LockItem

#### Ciclo: 2025-01

<h4 align="center"> Abril, 2025</h4>

___

# Registro de versiones del informe

| Versión | Fecha      | Autor             | Descripción de modificación                                                                           |
|---------|------------|-------------------|-------------------------------------------------------------------------------------------------------|
| 1.0     | 10/04/2025 | Eduardo Chero     | Creación del archivo base en Markdown para el desarrollo del Final Project                            |

---
Project Report Collaboration Insights
# Project Report Collaboration Insights

<img src="assets\insights-tb1.PNG">

## Project Report
<img src="assets/images/report.PNG">

Link: https://github.com/ProdTrackers/Report

TB1: El equipo ha cumplido con éxito los puntos solicitados para la entrega. Durante el proceso de adaptación al entorno documental, enfrentamos algunos desafíos al planear correctamente el proyecto al inicio pero al final logramos encontrar nuestro enfoque. Como equipos nos sentimos satisfechos de haber alcanzado los objetivos propuestos.

### Analiticos para el TB1

<img src="assets/images/Analiticos TB1.PNG">



# Contenido

- [Registro de versiones del informe](#registro-de-versiones-del-informe)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
	    - [4.1.1.2. Domain Message Flows Modeling](#4212-domain-message-flows-modeling)
	    - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
	      - [User bounded context canvas](#user-bounded-context-canvas)
	      - [Iot device management bounded context canvas](#iot-device-management-bounded-context-canvas)
	      - [Inventory management bounded context canvas](#inventory-management-bounded-context-canvas)
	      - [ERP integration bounded context canvas](#erp-integration-bounded-context-canvas)
    - [4.1.2. Context Mapping](#412-context-mapping)
    - [4.1.3. Software Architecture](#413-software-architecture)
	    - [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
	    - [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
	    - [4.1.3.3. Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
	    - [4.1.3.4. Software Architecture Deployment Diagrams](#4134-software-architecture-deployment-diagrams)
  - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
	- [4.2.1. Bounded Context: User](#421-bounded-context:-user)
	    - [4.2.1.1. Domain Layer](#4211-domain-layer)
	    - [4.2.1.2. Interface Layer](4212-interface-layer)
	    - [4.2.1.3. Application Layer](4213-application-layer)
	    - [4.2.1.4. Infrastructure Layer](4214-infrastructure-layer)
	    - [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](4215-bounded-context-software-architecture-component-level-diagrams)
	    - [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](4216-bounded-context-software-architecture-code-level-diagrams)
	        - [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams](42161-bounded-context-domain-layer-class-diagrams)
	        - [4.2.1.6.2. Bounded Context Database Design Diagram](42162-bounded-context-database-design-diagram)
	- [4.2.2. Bounded Context: IoT Device](#422-bounded-context-iot-device)
		 - [4.2.2.1. Domain Layer](#4221-domain-layer)
		 - [4.2.2.2. Interface Layer](#4222-interface-layer)
		 - [4.2.2.3. Application Layer](#4223-application-layer)
		 - [4.2.2.4. Infrastructure Layer](#4224-infrastructure-layer)
		 - [4.2.2.5. Bounded Context Software Architecture Component Level Diagrams](#4225-bounded-context-software-architecture-component-level-diagrams)
		 - [4.2.2.6. Bounded Context Software Architecture Code Level Diagrams](#4226-bounded-context-software-architecture-code-level-diagrams)
			 - [4.2.2.6.1. Bounded Context Domain Layer Class Diagrams](#42261-bounded-context-domain-layer-class-diagrams)
			 - [4.2.2.6.2. Bounded Context Database Design Diagram](#42262-bounded-context-database-design-diagram)
	 - [4.2.3. Bounded Context: Inventory](#423-bounded-context-inventory)
		 - [4.2.3.1. Domain Layer](#4231-domain-layer)
		 - [4.2.3.2. Interface Layer](#4232-interface-layer)
		 - [4.2.3.3. Application Layer](#4233-application-layer)
		 - [4.2.3.4. Infrastructure Layer](#4234-infrastructure-layer)
		 - [4.2.3.5. Bounded Context Software Architecture Component Level Diagrams](#4235-bounded-context-software-architecture-component-level-diagrams)
		 - [4.2.3.6. Bounded Context Software Architecture Code Level Diagrams](#4236-bounded-context-software-architecture-code-level-diagrams)
			 - [4.2.3.6.1. Bounded Context Domain Layer Class Diagrams](#42361-bounded-context-domain-layer-class-diagrams)
			 - [4.2.3.6.2. Bounded Context Database Design Diagram](#42362-bounded-context-database-design-diagram)
	 - [4.2.4. Bounded Context: ERP](#424-bounded-context-erp)
		 - [4.2.4.1. Domain Layer](#4241-domain-layer)
		 - [4.2.4.2. Interface Layer](#4242-interface-layer)
		 - [4.2.4.3. Application Layer](#4243-application-layer)
		 - [4.2.4.4. Infrastructure Layer](#4244-infrastructure-layer)
		 - [4.2.4.5. Bounded Context Software Architecture Component Level Diagrams](#4245-bounded-context-software-architecture-component-level-diagrams)
		 - [4.2.4.6. Bounded Context Software Architecture Code Level Diagrams](#4246-bounded-context-software-architecture-code-level-diagrams)
			 - [4.2.4.6.1. Bounded Context Domain Layer Class Diagrams](#42461-bounded-context-domain-layer-class-diagrams)
			 - [4.2.4.6.2. Bounded Context Database Design Diagram](#42462-bounded-context-database-design-diagram)
[Conclusiones](#conclusiones)
[Bibliografía](#bibliografia)

---

# Student Outcome
<table border="1">
  <tr>
    <th>Criterio específico</th>
    <th>Acciones realizadas</th>
    <th>Conclusiones</th>
  </tr>
  <tr>
    <td>Trabaja en equipo para 
proporcionar liderazgo en 
forma conjunta </td>
    <td>
      <p>Márquez, Piero Stefano <br> 
      TB1:<br> 
      Organicé y gestioné los documentos clave, incluyendo la publicación del video de las entrevistas y su analisis. Además, desarrollé estrategias y tácticas competitivas para posicionarnos frente a los competidores, y participé activamente en el diseño, análisis y registro de entrevistas. También trabajé en la creación y priorización del product backlog, asegurando que todas las tareas estuvieran alineadas con los objetivos del proyecto. Por último, colaboré en los capítulos 3 y 4 del proyecto, contribuyendo de manera significativa a su desarrollo y asegurando el avance según lo planificado.<br>
      </p>
      <p>Arrunátegui Aguilar, Josué David<br> 
      TB1:<br>
	  Aca escribe 
      <br>
      </p>
      <p>Chero Eme, Eduardo Andre<br> 
      TB1:<br> 
      Aca escribe<br>
      </p>
      <p>Cortes Hidalgo, Nicolas Andres <br> 
      TB1:<br> 
      Aca escribe<br>
      </p>
      <p>Olivera Guerra, Santiago Mickelle <br> 
      TB1:<br> 
      Aca escribe<br>
      </p>
      <p>Surco Reyes, Franco<br> 
      TB1:<br> 
      Aca escribe<br>
      </p>
    </td>
    <td>En conclusión, un enfoque colaborativo y multidisciplinario es clave en el desarrollo de soluciones de ingeniería de software. Los estudiantes han destacado la importancia de integrar diversas disciplinas y conocimientos para mejorar cada fase del proceso, desde el diseño inicial y el análisis competitivo hasta la interacción con los usuarios y la arquitectura de software. Este enfoque no solo garantiza que los productos finales sean técnicamente robustos y alineados con las necesidades del mercado, sino que también resalta la importancia de la colaboración y la comunicación efectiva entre áreas especializadas para superar desafíos complejos y alcanzar soluciones innovadoras. Este modelo interdisciplinario no solo eleva la calidad del desarrollo de productos, sino que también prepara a los futuros ingenieros para liderar proyectos en entornos más integrados y tecnológicamente avanzados. Liderazgo Colaborativo en Equipo: El equipo adopta un liderazgo compartido, donde cada miembro asume roles de liderazgo según sus habilidades y el momento del proyecto, fomentando la toma de decisiones conjunta y el compromiso. Este enfoque dinámico permite que todos contribuyan a la coordinación y ejecución de tareas clave.</td>
  </tr>
  <tr>
    <td>Crea un entorno colaborativo e 
inclusivo, establece metas, 
planifica tareas y cumple 
objetivos.</td>
    <td>
      <p>Márquez, Piero Stefano <br> 
      TB1:<br> 
      Durante la primera entrega, organicé y gestioné documentos clave, como el video de entrevistas y analisis de la mismas. También participé en el diseño y priorización del product backlog, asegurando que todas las tareas estuvieran alineadas con los objetivos. Gracias a una planificación clara, el equipo avanzó de manera colaborativa en los capítulos 3 y 4, cumpliendo con los plazos establecidos.<br>
      </p>
      <p>Arrunátegui Aguilar, Josué David<br> 
      TB1:<br> 
      Aca escribe<br>
      </p>
      <p>Chero Eme, Eduardo Andre<br> 
      TB1:<br> 
   	  Aca escribe<br>
      </p>
      <p>Cortes Hidalgo, Nicolas Andres <br> 
      TB1:<br> 
      Aca escribe<br>
      </p>
      <p>Olivera Guerra, Santiago Mickelle <br> 
      TB1:<br> 
      Durante la primera entrega, me encargué de los layers para los principales Bounded Context: User, Inventory, Device y ERP, para planificar unn correcto desarrollo de Backend siguiendo respetando el core del negocio y aplicando ddd correctamente. <br>
      </p>
      <p>Surco Reyes, Franco <br> 
      TB1:<br> 
	  Aca escribe<br>
      </p>
    </td>
    <td>El equipo consolidó un entorno altamente colaborativo e inclusivo. Se reforzó la comunicación efectiva mediante herramientas como WhatsApp y Discord, manteniendo reuniones interdiarias que facilitaron la coordinación y resolución de dudas. Cada miembro del equipo contribuyó activamente, estableciendo metas concretas y organizando las tareas de manera precisa, lo que permitió un trabajo fluido y alineado con los objetivos del proyecto. Además, la mejora en la planificación y distribución de responsabilidades, sumada al apoyo mutuo, fue clave para cumplir con los plazos y lograr los resultados esperados. El equipo mostró una notable capacidad para trabajar en conjunto, corregir errores y cumplir los objetivos establecidos de manera eficiente. Entorno Inclusivo y Cumplimiento de Objetivos: El equipo promueve un ambiente inclusivo y abierto a diversas ideas, planificando metas claras en un tablero Kanban en Trello. Esta herramienta organiza y prioriza tareas, facilita el seguimiento del progreso y asegura el cumplimiento de objetivos mediante la responsabilidad compartida.</td>
  </tr>
</table>


---

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup



### 1.1.2. Perfiles de integrantes del equipo

| Integrante                                                                                                                                                                                                                                                                                                                               | Chero Eme, Eduardo Andre                                    |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| **Código:** U20201F282 <br> **Carrera:** Ingeniería de software <br> **Acerca de mí:** Me gustan los videojuegos y las series, quiero especializarme en ciberseguridad para tener una ganancia estable mientras creo videojuegos aparte por pasión. Con experiencia en backend y en frontend con tecnologias como Spring Boot y Angular. | ![Eduardo Perfil](assets/chapter1/members/eduardo.jpg) |

| Integrante                                                                                                                                                                                                                                                                                                                               | Arrunátegui Aguilar, Josué David                   |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------|
| **Código:** U202111033 <br> **Carrera:** Ingeniería de Software <br> **Acerca de mí:** Me gusta dibujar, tocar guitarra y jugar videojuegos. Tengo conocimiento en el desarrollo frontend con lenguajes como angular y vue.js, así como desarrollo móvil con flutter. Planeo especializarme en desarrollo web o como Analista de Datos.  | ![Josue Perfil](assets/chapter1/members/josue.jpg) |

| Integrante                                                                                                                                                                                                                                                                                                                               | Márquez, Piero Stefano                   |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------|
| **Código:** U201816402 <br> **Carrera:** Ingeniería de Software <br> **Acerca de mí:** Me gusta leer manga, salir a comer a nuevos lugares los videojuegos y la musica. Tengo conocimiento en el desarrollo frontend con angular y backend con node.js para mi trabajo utilizo bastante el stack MEAN(MongoDb, Express, Anulgar, Node.js) y moviles manejo flutter. Acabando la carrera me gustaria desenvolver como Analista de Datos.  | <img src="assets/chapter1/members/Piero.jpeg" alt="Piero Perfil" width="600" height="200"/>|

| Integrante                                                                                                                                                                                                                                                                                                                               | Surco Reyes, Franco                   |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------|
| **Código:** U202015132 <br> **Carrera:** Ingeniería de Software <br> **Acerca de mí:** Soy estudiante de la carrera de ingeniería de Software en la universidad Peruana de Ciencias Aplicadas, elegí esta carrera por mi pasión por la programación e interés por la tecnología. Me considero una persona responsable y colaborativa, por lo que apoyaré al grupo en lo que se necesite. Además, tengo conocimientos de programación en C++, Python, HTML, CSS, JavaScript y modelado de base de datos en SQL Server. | ![Franco Perfil](assets/chapter1/members/franco.jpg) |


| Integrante                                                                                                                                                                                                                                                                                                                               | SSantiago Mickelle, Olivera Guerra                   |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------|
| **Código:** U20201a821 <br> **Carrera:** Ingeniería de Software <br> **Acerca de mí:** Me considero un estudiante comprometido con el trabajo y desenvolvimiento en el campo profesional con mucho foco para cada uno de los proyectos en los cuales participo y detallisata con los temas a arreglar. Domino tecnologías como Java para Backend como sus frameworks tales como Spring para el desarrollo de APIs , en Front con Angular y Android Studio, por ultimo, SQL a nivel avanzado para inserción y extracción de datos específicos. | ![Santiago Perfil](assets/Santiago.jpg) |


## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática



### 1.2.2 Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements



#### 1.2.2.2. Lean UX Assumptions



#### 1.2.2.3. Lean UX Hypothesis Statements



#### 1.2.2.4. Lean UX Canvas



## 1.3. Segmentos objetivo

**1. Clientes de tiendas de ropa**



**2. Dueños de tiendas de ropa:**



# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores



### 2.1.1. Análisis competitivo


### 2.1.2. Estrategias y tácticas frente a competidores


## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Clientes de tiendas de ropa:**


**Dueños de Tiendas de Ropa:**


### 2.2.2. Registro de entrevistas

**Clientes de tiendas de ropa:**

**Dueños de tiendas de ropa:**

### 2.2.3. Análisis de entrevistas

**Clientes de tiendas de ropa:**


**Dueños de tiendas de ropa:**


## 2.3. Needfinding

### 2.3.1. User Personas

**Clientes de tiendas de ropa**



**Dueños de tiendas de ropa**



### 2.3.2. User Task Matrix



### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

**Clientes de tiendas de ropa**


**Dueños de tiendas de ropa**


### 2.3.5. As-is Scenario Mapping

**Clientes de tiendas de ropa**



**Dueños de tiendas de ropa**


## 2.4. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping


## 3.2. User Stories



## 3.3. Impact Mapping



## 3.4. Product Backlog



# Capítulo IV: Strategic-Level Software Design

## 4.1. Strategic-Level Attribute-Driven Design


### 4.1.1. Design Purpose



### 4.1.2. Attribute-Driven Design Inputs



#### 4.1.2.1. Primary Functionality (Primary User Stories)


#### 4.1.2.2. Quality attribute Scenarios



#### 4.1.2.3. Constraints



### 4.1.3. Architectural Drivers Backlog



### 4.1.4. Architectural Design Decisions


### 4.1.5. Quality Attribute Scenario Refinements

## 4.2. Strategic-Level Domain-Driven Design

### 4.2.1. EventStorming



### 4.2.2. Candidate Context Discovery



### 4.2.3. Domain Message Flows Modeling


### 4.2.4. Bounded Context Canvases

#### User bounded context canvas



#### Iot device management bounded context canvas



#### Inventory management bounded context canvas



#### ERP integration bounded context canvas



### 4.2.5. Context Mapping

## 4.3. Software Architecture

### 4.3.1. Software Architecture System Landscape Diagram



### 4.3.2. Software Architecture Context Level Diagrams



### 4.3.3. Software Architecture Container Level Diagrams



### 4.3.4. Software Architecture Deployment Diagrams



# Capítulo V: Tactical-Level Software Design

## 5.1. Bounded Context: User

### 5.1.1. Domain Layer


### 5.1.2. Interface Layer



### 5.1.3. Application Layer


### 5.1.4. Infrastructure Layer


### 5.1.5. Bounded Context Software Architecture Component Level Diagrams



### 5.1.6. Bounded Context Software Architecture Code Level Diagrams

#### 5.1.6.1. Bounded Context Domain Layer Class Diagrams



#### 5.1.6.2. Bounded Context Database Design Diagram


## 4.2.2. Bounded Context: IoT Device

### 4.2.2.1. Domain Layer

### 4.2.2.2. Interface Layer

### 4.2.2.3. Application Layer

### 4.2.2.4. Infrastructure Layer

### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams

### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams

#### 4.2.2.6.2. Bounded Context Database Design Diagram


## 4.2.3. Bounded Context: Inventory

### 4.2.3.1. Domain Layer

### 4.2.3.2. Interface Layer

### 4.2.3.3. Application Layer

### 4.2.3.4. Infrastructure Layer

### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams

### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams

#### 4.2.3.6.2. Bounded Context Database Design Diagram

## 4.2.4. Bounded Context: ERP

### 4.2.4.1. Domain Layer

### 4.2.4.2. Interface Layer

### 4.2.4.3. Application Layer

### 4.2.4.4. Infrastructure Layer

### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams

### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams

#### 4.2.4.6.2. Bounded Context Database Design Diagram



# Conclusiones

