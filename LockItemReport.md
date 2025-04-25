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

#### Profesor: 

#### Producto: LockItem

#### Ciclo: 2025-01

<h4 align="center"> Abril, 2025</h4>

___

# Registro de versiones del informe

| Versión | Fecha      | Autor             | Descripción de modificación                                                                           |
|---------|------------|-------------------|-------------------------------------------------------------------------------------------------------|
| 1.0     | 10/04/2025 | Eduardo Chero     | Creación del archivo base en Markdown para el desarrollo del Final Project                            |

---

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



---

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup



### 1.1.2. Perfiles de integrantes del equipo



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

* **Pricer:** Pricer utiliza etiquetas electrónicas de precio (ESL) para ayudar a los minoristas a actualizar precios y
  gestionar inventarios en tiempo real, mejorando la eficiencia operativa.
* **Neurolabs:** Neurolabs emplea visión artificial y aprendizaje automático para controlar inventarios en tiempo real y
  predecir el comportamiento de los consumidores sin necesidad de etiquetas físicas.

### 2.1.1. Análisis competitivo

<table border="1" cellpadding="10" cellspacing="0" style="margin-left: auto; margin-right: auto;">
  <tr>
    <th colspan="6">Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="4">El objetivo que tenemos con este análisis es conocer de mejor manera a nuestra competencia y así poder evaluar nuestras oportunidades y ventajas como empresa buscando poder destacar sobre las otras</td>
  </tr>
  <tr>
    <td colspan="4">¿Qué aporte de valor podría ofrecer nuestro producto en contraste al resto de competidores? </td>
  </tr>
  <tr>
   <td colspan="2"></td>
    <td>LockItem</td>
    <td>Pricer</td>
    <td>Neurolabs</td>
  </tr>
  <tr>
    <td rowspan="2">Perfil</td>
    <td>Overview</td>
    <td>Solución IoT para la localización de productos movidos en tiendas de ropa</td>
    <td>Ofrece etiquetas electrónicas de precios para minoristas</td>
    <td>Utiliza visión artificial para la gestión de inventarios</td>
  </tr>
  <tr>
    <td>Ventaja competitiva ¿Que valor ofrece a los clientes?</td>
    <td>Locaclización en tiempo real mediante sensores IoT en prendas</td>
    <td>Automatización de precios e inventarios, con actualizaciones en tiempo real</td>
    <td>Análisis predictivo y control sin necesidad de etiquetas físicas</td>
  </tr>
  <tr>
    <td rowspan="2">Perfil de Marketing</td>
    <td>Mercado objetivo</td>
    <td>Hombres y mujeres entre 18 y 45 años. Tiendas de ropa en Perú</td>
    <td>Minoristas globales, especialmente supermercados y tiendas grandes</td>
    <td>Minoristas que buscan automatizar la gestión de inventorios sin contacto</td>
  </tr>
  <tr>
    <td>Estrategias de marketing</td>
    <td>Enfocada en la eficiencia operativa y mejora de la experiencia del cliente</td>
    <td>Se posiciona como líder en automatización y eficiencia en minoristas </td>
    <td>Apuesta por la innovación y la automatización sin contacto </td>
  </tr>
  <tr>
    <td rowspan="3">Perfil de Producto</td>
    <td>Productos & Servicios</td>
    <td>Sensores IoT para etiquetas de prendas y app de localización en tiempo real</td>
    <td>Sensores IoT para etiquetas de prendas y app de localización en tiempo rea</td>
    <td>Visión artificial, IA para monitoreo de inventarios y comportamiento</td>
  </tr>
  <tr>
    <td>Precios & Costos</td>
    <td>Costos basados en suscripción y sensores según el tamaño de la tienda </td>
    <td>Dependiendo del tamaño de la tienda y volumen de etiquetas necesarias </td>
    <td>Costo de implementación de IA y software personalizado </td>
  </tr>
  <tr>
    <td>Canales de distribucion (Web y/o Movil)</td>
    <td>App móvil y web para tiendas minoristas </td>
    <td>Plataforma web y hardware de etiquetas electrónicas </td>
    <td>Plataforma basada en web con integración a sistemas de inventario </td>
  </tr>
  <tr>
    <td rowspan="5">Analisis SWOT</td>
    <td colspan="5">Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus
    oportunidades y contribuir a lo que ustedes definen como su posible ventaja
    competitiva. </td>
  </tr>
  <tr>
    <td>Fortalezas</td>
    <td>Integración IoT sencilla con sistema de seguridad; mejora la experiencia de compra</td>
    <td>Reducción de costos operativos, optimización de inventarios y precios en tiempo real </td>
    <td>Automatización sin necesidad de etiquetas, precisión en el monitoreo </td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td> Dependencia de hardware específico en las tiendas </td>
    <td>Costo elevado de instalación inicial de etiquetas electrónicas </td>
    <td>Necesidad de grandes volúmenes de datos para un análisis preciso </td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td>Expansión a otros sectores minoristas más allá de la ropa </td>
    <td>Ampliar el uso de la tecnología a mercados emergentes </td>
    <td>Ampliar la tecnología para otros usos, como la personalización de experiencias </td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td>Competencia en tecnologías IoT de otros mercados </td>
    <td>Nuevas soluciones de bajo costo en el mercado de etiquetas electrónicas </td>
    <td>Competidores que ofrezcan IA con mejores modelos predictivos </td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

* Diferenciar la oferta destacando la integración con sistemas de seguridad, para asegurar la protección de productos en
  tiendas, además de la localización en tiempo real
* Expandir el mercado objetivo más allá de tiendas de ropa, incluyendo otros sectores minoristas, para diversificar el
  riesgo y aprovechar nuevas oportunidades
* Fortalecer la experiencia del cliente mediante la mejora continua de la app móvil, asegurando que sea intuitiva y
  ofrezca funcionalidades adicionales como reportes personalizados
* Desarrollar alianzas estratégicas con proveedores de hardware y software para reducir costos de implementación y
  mejorar la escalabilidad del sistema
* Innovar en la tecnología IoT de sensores para ofrecer soluciones que requieran menos mantenimiento y sean más
  adaptables a diferentes entornos de tienda
* Optimizar la estrategia de precios para ofrecer opciones de suscripción flexible, permitiendo a las tiendas ajustar su
  inversión según el tamaño y el volumen de la tienda

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Clientes de tiendas de ropa:**

* ¿Qué desafíos enfrentas cuando buscas una prenda específica en una tienda de ropa?
* ¿Qué aspectos de la experiencia de compra te resultan más frustrantes?
* ¿Utilizas alguna aplicación o herramienta para ayudarte en las compras?
* ¿Qué funcionalidades esperas de una aplicación de tienda para mejorar tu experiencia de compra?
* ¿Qué tan importante es para ti poder localizar rápidamente las prendas en una tienda?
* ¿Cómo crees que la tecnología de localización podría mejorar tu experiencia de compra?
* ¿Qué características considerarías más valiosas en una solución de localización de prendas?
* ¿Qué tipo de información te gustaría recibir en una aplicación de tienda?
* ¿Alguna vez has usado una tecnología similar en tiendas? ¿Cómo fue tu experiencia?
* ¿Qué mejorarías en las soluciones actuales que has visto o usado?

**Trabajador de Tiendas de Ropa:**

* ¿Cómo gestionan actualmente el inventario en su tienda?
* ¿Qué desafíos enfrentan con el seguimiento de prendas y el manejo de inventarios?
* ¿Qué tipo de tecnologías utilizan para la gestión de inventarios y la experiencia del cliente?
* ¿Qué tan abiertos están a adoptar nuevas tecnologías como la localización de prendas mediante IoT?
* ¿Cómo creen que una solución de localización de prendas podría beneficiar a su tienda?
* ¿Qué funcionalidades específicas les interesan en una solución de localización?
* ¿Qué aspectos consideran cruciales para la implementación de nuevas tecnologías en su tienda?
* ¿Qué tipo de soporte esperan durante y después de la implementación?

### 2.2.2. Registro de entrevistas

**Clientes de tiendas de ropa:**

|                        | **Descripcion**                                                                                                                                                                                                        |
|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nombre y apellidos** | Brad Segovia                                                                                                                                                                                                      |
| **Edad**               | 22                                                                                                                                                                                                                     |
| **Evidencia**          | ![Cliente 1](assets/chapter2/entrevista_franco.png)                                                                                                                                                                |
| **Duracion del video** | 07:59                                                                                                                                                                                                                   |
| **Timing del video**   |                                                                                                                                                                                                                        |
| **Entrevistador**      | Franco Surco Reyes                                                                                                                                                                                                |
| **Resumen**            | Brad Segovia, comprador habitual en tiendas de ropa, comparte sus experiencias de compra y los desafíos que ha enfrentado, como la desorganización en el diseño de las tiendas y la falta de precisión en los precios. Considera que el proceso puede ser frustrante y consumir demasiado tiempo. Por ello, sugiere mejoras en una aplicación de compras, como la ubicación precisa de los artículos según su color y tamaño dentro de la tienda. Además, destaca la importancia de una aplicación basada en la ubicación para optimizar las compras y, finalmente, propone la incorporación de mapas interactivos que muestren la ubicación exacta de los productos. |

|                        | **Descripcion**                                                                                                                                                                                                        |
|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nombre y apellidos** | Alessandra Alvarado                                                                                                                                                                                                      |
| **Edad**               | 21                                                                                                                                                                                                                     |
| **Evidencia**          | ![Cliente 2](assets/chapter2/Entrevista_Nicolas.png)                                                                                                                                                                |
| **Duracion del video** | 07:59                                                                                                                                                                                                                   |
| **Timing del video**   |                                                                                                                                                                                                                        |
| **Entrevistador**      | Nicolás Cortés Hidalgo                                                                                                                                                                                                |
| **Resumen**            | Alessandra Alvarado es una estudiante de 21 años de la carrera de Derecho en la Pontificia Universidad Católica del Perú. A pesar de que cuando quiere comprarse algún tipo de prenda, lo suele realizar de manera online, cuando suele salir a algún sitio, no pierde la oportunidad de entrar a alguna tienda departamental y revisar ciertas prendas que le llaman la atención. Uno de los aspectos que mas le molesta de comprar en las mismas tiendas es el tiempo que le tarda encontrar una ropa en particular, por lo que valoraría la implementación de una solución que le ayude a reducir el tiempo que empeña en buscar y comprar prendas. |


|                        | **Descripcion**                                                                                                                                                                                                      |
|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nombre y apellidos** | Angelo Arevalo                                                                                                                                                                                                    |
| **Edad**               | 22                                                                                                                                                                                                                   |
| **Evidencia**          | ![Cliente 3](assets/chapter2/ESant.jpg)                                                                                                                                                                |
| **Duracion del video** | 05 : 37                                                                                                                                                                                                               |
| **Timing del video**   |                                                                                                                                                                                                                      |
| **Entrevistador**      | Santiago Mickelle Olivera Gueera                                                                                                                                                                                     |
| **Resumen**            | Angelo es un cliente conservador que suele ir en presencial a cada una de las tiendas de ropa o de bienes. Este en la entrevista nos relata que lo que resaltaría de una solución es la facilidad de encontrar cada producto dentro de una tienda gigante con exactitud, con numero de pasillo y que se muestre su ubicación reflejada en el mapa, incluso si es solo un producto el que quede en las estanterías, a él le gustaría poder encontrarlo si es de su agrado. La razón de esto es simple, las aplicaciones indican en qué pasillo se encuentran los productos, pero en verdad te indican solamente la estantería, no el producto, en caso de que quede solo unas unidades y no se encuentren, el cliente no podría encontrarlo, este tema es el eje principal de la entrevista con Angelo. |


**Trabajador de tiendas de ropa:**

|                        | **Descripcion**                                                                                                                                                                                                        |
|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nombre y apellidos** | Sebastian Cordova                                                                                                                                                                                                      |
| **Edad**               | 21                                                                                                                                                                                                                     |
| **Evidencia**          | ![Trabajador 1](assets/chapter2/entrevista_eduardo.png)                                                                                                                                                                |
| **Duracion del video** | 03:41                                                                                                                                                                                                                  |
| **Timing del video**   |                                                                                                                                                                                                                        |
| **Entrevistador**      | Eduardo André Chero Emé                                                                                                                                                                                                |
| **Resumen**            | Sebastián, trabajador de una tienda de ropa, identifica como principal problema la dificultad de encontrar prendas fuera de lugar durante el orden y control de inventario, ya que el proceso actual es manual y poco eficiente. Ve con interés la incorporación de tecnología IoT para localizar prendas, destacando que podría ahorrar tiempo, mejorar la precisión del inventario y optimizar la reposición. Considera clave que la solución permita ubicar prendas rápidamente, detectar ubicaciones incorrectas y generar reportes. También enfatiza la importancia de una implementación simple, capacitación adecuada y soporte técnico continuo. |


|                        | **Descripcion**                                                                                                                                                                                                      |
|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nombre y apellidos** | María Cabrejos                                                                                                                                                                                                       |
| **Edad**               | 21                                                                                                                                                                                                                   |
| **Evidencia**          | ![Trabajador 2](assets/chapter2/entrevista_josue.png)                                                                                                                                                                |
| **Duracion del video** | 03:45                                                                                                                                                                                                                |
| **Timing del video**   |                                                                                                                                                                                                                      |
| **Entrevistador**      | Josué David Arrunátegui Aguilar                                                                                                                                                                                      |
| **Resumen**            | María trabaja en una tienda de ropa y conoce bien el problema que representa encontrar prendas fuera de su lugar. Cada día, especialmente en horarios con gran afluencia de clientes, se enfrenta al desafío de reorganizar constantemente artículos que han sido dejados en estantes incorrectos o abandonados en los probadores. Esta tarea no solo le consume tiempo valioso que podría dedicar a asesorar mejor a los compradores, sino que también complica el control del inventario y afecta la imagen general del local. Por eso, cuando escuchó sobre una solución que permite ubicar rápidamente las prendas mediante sensores conectados a una app móvil, le pareció una idea innovadora y muy útil para facilitar su trabajo diario y mejorar la experiencia del cliente. Por eso, le pareció muy atractiva la idea de contar con un dispositivo que le ayude a identificar y reorganizar la ropa de forma más eficiente. |

|                        | **Descripcion**                                                                                                                                                                                                      |
|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nombre y apellidos** | Abel Montoya                                                                                                                                                                                                       |
| **Edad**               | 23                                                                                                                                                                                                                   |
| **Evidencia**          | ![Trabajador 3](assets/chapter2/entrevista_Abel.PNG)                                                                                                                                                                |
| **Duracion del video** | 06:07                                                                                                                                                                                                                |
| **Timing del video**   |                                                                                                                                                                                                                      |
| **Entrevistador**      | Piero Stefano Márquez                                                                                                                                                                                      |
| **Resumen**            | Abel es un joven universitario que hace part-time en una tienda de ropa, nos habla con un poco de como es el como persona y dentro de su trabajo. Al proponerle la idea de LockItem le parecio interesante y una solución a una problematica que sufren en su tienda hace mucho que es el robo de prendas, abel piensa que nuestro solución agilizaria algunos procesos pero añadio que se le podria poner una alarma extra al dispositivo iot para que cuando el sensor sienta cruzo la puerta la alarma se active y se pueda detener al ladron. Tambien nos compartio que como herramienta podria ser bastante util en tema de retail ya que la empresa se ahorraria los gastos operatvios. Cree que si se lo propone a su gerente pueda aceptar la implementación, nos menciona que vendria genial una capacitación para el manejo del dispositivo y software y mantenimiento constante tambien. |




### 2.2.3. Análisis de entrevistas

**Clientes de tiendas de ropa:**

Este segmento está compuesto por personas que, aunque pueden realizar compras en línea, aún mantienen el hábito de visitar tiendas físicas para adquirir prendas de vestir. A través de las entrevistas realizadas, se identificaron patrones comunes relacionados con las dificultades en la experiencia de compra presencial, así como sugerencias sobre cómo una solución digital podría mejorar dicha experiencia. La mayor parte de los entrevistados señaló la necesidad de herramientas que reduzcan el tiempo de búsqueda dentro de la tienda y aumenten la precisión al ubicar productos específicos.

### Características objetivas:
- El **100%** de los entrevistados (3 de 3) ha realizado compras en tiendas físicas, aunque uno de ellos (**33%**) también compra en línea ocasionalmente.
- El **33%** (1 de 3) pertenece al grupo universitario joven (21 años), mientras que los otros dos representan perfiles adultos con hábitos de consumo más establecidos.
- El **100%** (3 de 3) manifestó conocer y usar aplicaciones móviles para complementar su experiencia de compra.

### Características subjetivas:
- El **100%** (3 de 3) expresó frustración con la falta de organización en las tiendas físicas, especialmente al intentar encontrar productos específicos.
- El **100%** (3 de 3) valoraría una solución tecnológica que reduzca el tiempo de búsqueda de prendas dentro de una tienda.
- El **66%** (2 de 3) mencionó específicamente la importancia de mapas interactivos o ubicación precisa de productos en la tienda.
- Un **33%** (1 de 3) destacó como crítica la falta de precisión entre lo que indica la app y lo que realmente se encuentra en tienda, especialmente cuando hay pocas unidades disponibles.

### Relación con entrevistas:
- **Brad Segovia** relató problemas de desorganización y confusión de precios, sugiriendo mapas interactivos que ayuden a localizar productos por color y talla.
- **Alessandra Alvarado**, universitaria, mencionó que aunque compra online, le resulta molesto el tiempo que consume buscar ropa específica en tienda física.
- **Angelo** enfatizó que las aplicaciones actuales no permiten encontrar productos exactos cuando quedan pocas unidades, lo que puede hacer que el cliente pierda tiempo o abandone la compra.


**Trabajador de tiendas de ropa:**

Este segmento está compuesto por empleados que trabajan directamente en tiendas físicas de ropa, enfrentándose a los retos diarios de la organización de productos, control de inventario y atención al cliente. Las entrevistas muestran que existen desafíos importantes como el desorden generado por los clientes, la dificultad de ubicar prendas fuera de lugar y los riesgos de robo. Todos los entrevistados coinciden en que una solución tecnológica basada en IoT podría mejorar significativamente su desempeño laboral, optimizando tareas rutinarias y elevando la experiencia general en tienda.

### Características objetivas:
- El **100%** de los entrevistados (3 de 3) trabaja actualmente en tiendas de ropa.
- El **66%** (2 de 3) realiza funciones de orden, inventario y reposición diaria como parte fundamental de su trabajo.
- El **33%** (1 de 3) está contratado como part-time y también es estudiante universitario.
- El **100%** (3 de 3) mostró apertura a soluciones tecnológicas que integren sensores IoT y aplicaciones móviles.

### Características subjetivas:
- El **100%** (3 de 3) señaló como problemática central la dificultad para ubicar prendas fuera de lugar.
- El **66%** (2 de 3) enfatizó que reorganizar constantemente productos mal ubicados interfiere con su atención al cliente.
- El **66%** (2 de 3) considera crucial que la solución permita localizar rápidamente las prendas y generar reportes de ubicación.
- Un **33%** (1 de 3) identificó como principal problema el robo de prendas, proponiendo mejoras a nivel de seguridad como alarmas en los sensores.
- El **100%** (3 de 3) valoraría una solución que incluya capacitación para su uso y soporte técnico constante.

### Relación con entrevistas:
- **Sebastián** resaltó que el inventario manual es poco eficiente, y que una solución IoT ayudaría a detectar prendas fuera de lugar, optimizando el orden y la reposición. Enfatizó la necesidad de una implementación simple y buen soporte técnico.
- **María** vive el problema de desorden en horarios con alta afluencia. Le pareció muy útil una app con sensores para ubicar prendas, ya que le permitiría dedicar más tiempo a los clientes y mantener mejor imagen de la tienda.
- **Abel**, trabajador part-time y estudiante, destacó el problema del robo y propuso integrar una alarma a la solución. Considera que la herramienta reduciría costos operativos y apoya su implementación, siempre que haya capacitación y mantenimiento.


## 2.3. Needfinding

### 2.3.1. User Personas

**Clientes de tiendas de ropa**

![user_persona_cliente](assets/chapter2/user_persona_cliente.png)

**Dueños de tiendas de ropa**

![user_persona_dueño](assets/chapter2/user_persona_dueño.png)

### 2.3.2. User Task Matrix

<table>
  <tr>
    <th colspan="3">User Persona 1: Clientes de tiendas de ropa </th>
  </tr>
  <tr>
    <td>Descripción</td>
    <td>Frecuencia</td>
    <td>Importancia</td>
  </tr>
  <tr>
    <td>Buscar prendas específicas en la tienda</td>
    <td>Often</td>
    <td>High</td>
  </tr>
  <tr>
    <td>Recibir alertas de promociones</td>
    <td>Sometime</td>
    <td>Medium</td>
  </tr>
  <tr>
    <td>Obtener información de stock</td>
    <td>Often</td>
    <td>High</td>
  </tr>
</table>

<table>
  <tr>
    <th colspan="3">User Persona 2: Trabajdor de Tiendas de Ropa</th>
  </tr>
  <tr>
    <td>Descripción</td>
    <td>Frecuencia</td>
    <td>Importancia</td>
  </tr>
  <tr>
    <td>Gestionar el inventario de la tienda</td>
    <td>Often</td>
    <td>High</td>
  </tr>
  <tr>
    <td>Monitorear la ubicación de las prendas</td>
    <td>Often</td>
    <td>High</td>
  </tr>
  <tr>
    <td>Analizar las preferencias de los clientes</td>
    <td>Sometime</td>
    <td>Medium</td>
  </tr>
</table>

### 2.3.3. User Journey Mapping

**User Persona Cliente**: El segmento de clientes se caracteriza por tener la necesidad de encontrar una solucion a la perdida excesiva de tiempo que estos sufren al momento de buscar ropa en tiendas departamentales. Es un segmento que, ante la falta de soluciones que combatan directamente la problematica, no confian del todo en una solucion que ataque directamente a dicho problema. Creemos que, una vez probado correctamente por los propios usuarios, estos se acostumbraran rapidamente al mismo una vez comprueben que este es altamente efectivo, y compartiran con sus conocidos y familiares su experiencia con el sistema.

![user_journey_map_cliente](assets/chapter2/UserJourneyMapCliente.png)


**User Persona Gerente**: El segmento de gerentes se caracteriza por tener la necesidad de beneficiar a sus clientes incentivandolos a encontrar prendas que estos podrian encontrar en otras tiendas de un tipo similar, pero ofrenciendoles la posibilidad de ahorrar la mayor cantidad de tiempo posibles brindandoles una solucion que los distinga del resto. Ante la propuesta de implementar esta solucion, este segmento debe considerar diversos factores y costos operativos ante la posibilidad de diferenciarse de su competencia de una manera efectiva. Creemos que una vez que los gerentes implementen esta solucion y, noten su efectividad, podran implementarlo a gran escala en diversas tiendas, en casos de tratarse de franquicias.

![user_journey_map_gerente](assets/chapter2/UserJourneyMapGerente.png)

### 2.3.4. Empathy Mapping

**Clientes de tiendas de ropa**

![empathy_map_cliente](assets/chapter2/emphaty-map_cliente.png)

**Trabajador de tiendas de ropa**

![empathy_map_dueño](assets/chapter2/emphaty-map_dueño.png)

### 2.3.5. As-is Scenario Mapping

**Clientes de tiendas de ropa**

<table>
  <tr>
    <th>Steps</th>
    <th>Buscando una prenda específica en la tienda</th>
    <th>Solicitando ayuda al personal</th>
    <th>Completando la compra o desistiendo</th>
  </tr>
  <tr>
    <td>Doing</td>
    <td>Recorre diferentes áreas de la tienda, deteniéndose a buscar entre varias prendas</td>
    <td>Le pide a un empleado de la tienda que le ayude a localizar el producto específico</td>
    <td>Analiza si el producto encontrado es lo que busca y si su experiencia fue satisfactoria</td>
  </tr>
  <tr>
    <td>Thinking</td>
    <td>Espero que esté disponible</td>
    <td>¿Por qué es tan difícil encontrar lo que necesito?</td>
    <td>¿Debería seguir buscando?</td>
  </tr>
  <tr>
    <td>Feeling</td>
    <td>Frustración</td>
    <td>Esperanza</td>
    <td>Satisfacción o decepción</td>
  </tr>
</table>

**Trabajador de tiendas de ropa**

<table>
  <tr>
    <th>Steps</th>
    <th>Supervisando el inventario</th>
    <th>Recibiendo quejas o solicitudes de los clientes</th>
    <th>Evaluando mejoras operativas</th>
  </tr>
  <tr>
    <td>Doing</td>
    <td>Se asegura de que las prendas estén bien distribuidas y visibles en las diferentes secciones</td>
    <td>Responde a los empleados que reportan quejas o problemas con la ubicación de productos</td>
    <td>Observa cómo la falta de organización afecta las ventas y el rendimiento general de la tienda</td>
  </tr>
  <tr>
    <td>Thinking</td>
    <td>¿Cómo puedo mejorar la experiencia de compra?</td>
    <td>Esta situación podría costarnos ventas</td>
    <td>¿Debo invertir en una solución tecnológica?</td>
  </tr>
  <tr>
    <td>Feeling</td>
    <td>Frustración</td>
    <td>Motivación</td>
    <td>Alivio o ansiedad</td>
  </tr>
</table>

## 2.4. Ubiquitous Language

En el contexto de la startup LockItem, se ha definido un lenguaje compartido que permite una mejor comunicación entre
desarrolladores, diseñadores, clientes, y usuarios. Estos son algunos de los términos clave:

* **Prenda:** Hace referencia a cualquier tipo de vestimenta disponible en la tienda. Las prendas pueden ser localizadas
  a través del sistema.
* **Cliente:** Persona que ingresa a la tienda y busca una prenda específica. El cliente puede solicitar ayuda para
  encontrar el producto que desea.
* **Inventario:** Conjunto de todas las prendas disponibles en la tienda. La gestión del inventario es esencial para
  asegurar que los productos estén localizados y disponibles para los clientes.
* **Localizador de Prendas:** Sistema que permite a los usuarios, ya sea el personal de la tienda o los clientes,
  encontrar la ubicación exacta de una prenda en tiempo real dentro de la tienda.
* **Sensor IoT:** Dispositivos instalados en las prendas que permiten el rastreo en tiempo real, ayudando a determinar
  la ubicación precisa de cada artículo en el inventario.

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

