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

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. EventStorming

![EventStorming](./assets/CandidateContextDiscovery/step7.jpg)

### 4.1.2. Candidate Context Discovery

Paso 1: <br>
![Step 1](./assets/CandidateContextDiscovery/step2.jpg)
Paso 2:<br>
![Step 2](./assets/CandidateContextDiscovery/step2.jpg)
Paso 3:<br>
![Step 3](./assets/CandidateContextDiscovery/step3.jpg)
Paso 4:<br>
![Step 4](./assets/CandidateContextDiscovery/step4.jpg)
Paso 5:<br>
![Step 5](./assets/CandidateContextDiscovery/step5.jpg)
Paso 6:<br>
![Step 6](./assets/CandidateContextDiscovery/step6.jpg)
Paso 7:<br>
![Step 7](./assets/CandidateContextDiscovery/step7.jpg)


### 4.1.3. Domain Message Flows Modeling

Escenario: Buscar Prenda <br>
![scenario 1](./assets/DomainMessageFlowsModeling/scenario1.png) <br>
Escenario: Ver Detalle Prenda <br>
![scenario 2](./assets/DomainMessageFlowsModeling/scenario2.png) <br>
Escenario: Localizar Prenda  <br>
![scenario 3](./assets/DomainMessageFlowsModeling/scenario3.png) <br>
Escenario: Reservar Prenda  <br>
![scenario 4](./assets/DomainMessageFlowsModeling/scenario4.png) <br>

### 4.1.4. Bounded Context Canvases

#### User bounded context canvas

![user context](./assets/ContextCanvases/user.png)

#### Iot device management bounded context canvas

![iot context](./assets/ContextCanvases/iot.png)

#### Inventory management bounded context canvas

![inventory context](./assets/ContextCanvases/inventory.png)

#### ERP integration bounded context canvas

![erp context](./assets/ContextCanvases/erp.png)

### 4.1.5. Context Mapping

## 4.2. Software Architecture

### 4.2.1. Software Architecture System Landscape Diagram
 El diagrama muestra el panorama general del sistema, destacando las principales entidades involucradas, como los Usuarios y las interacciones del sistema LockItem con componentes externos como AWS Iot Cloud, Store ERP y Azure Cloud. Representa las conexiones entre estos actores y cómo interactúan con el sistema para proporcionar acceso a funciones clave como la gestion de inventarios de las tiendas.
![Landscape](assets/Landscape.png)

### 4.2.2. Software Architecture Context Level Diagrams
Este diagrama desglosa el contexto a un nivel más detallado, mostrando las interacciones entre los usuarios y el sistema. Aquí, los Usuarios tienen acceso al Sistema de LockItem, pero interactúan de manera diferente.
![Context](assets/Contexto.png)

### 4.2.3. Software Architecture Container Level Diagrams
Aqui especificamos los contenedores de software que soportan la arquitectura, como la Aplicación Web, la Aplicación Móvil, el Backend y los Dispositivos IoT Gestionados. Esto proporciona un mapa claro de cómo los distintos módulos del sistema se comunican entre sí y con componentes externos.
![Contenedores](assets/Contenedores.png)

### 4.2.4. Software Architecture Deployment Diagrams
Este diagrama representa una arquitectura de software distribuida en la nube 
![Deployment](assets/Deployment.png)

# 4.2. Tactical-Level Domain-Driven Design

## 4.2.1. Bounded Context: User

Este bounded context se encarga de la gestión de los usuarios del sistema LockItem. Administra los perfiles, roles, estados y datos esenciales de cada usuario que interactúa con la plataforma, ya sea personal de tienda o clientes. La lógica cubre desde el registro y edición de usuarios hasta su autenticación y validación dentro del sistema.

### 4.2.1.1. Domain Layer

El Domain Layer define la entidad `User` junto con sus objetos de valor como `EmailAddress`, `FullName`, `UserRole` y `UserStatus`. Se encapsulan reglas de negocio como validación de correos, activación/inactivación de usuarios y verificación de permisos administrativos.

![UserDomainLayer](assets/DomainUser.png)

### 4.2.1.2. Interface Layer

El Interface Layer expone la lógica de usuario a través de un controlador REST (`UserController`). Este controlador permite registrar, actualizar, obtener o eliminar usuarios, utilizando el servicio de dominio `UserService`.

![UserInterfaceLayer](assets/InterfaceUser.png)

### 4.2.1.3. Application Layer

En esta capa se encuentran los casos de uso que orquestan la lógica del dominio. Los `CommandHandler` y `QueryHandler` permiten registrar usuarios, actualizarlos, eliminarlos y obtener información según el contexto de la solicitud.

![UserApplicationLayer](assets/ApplicationUser.png)

### 4.2.1.4. Infrastructure Layer

Esta capa contiene la implementación concreta del repositorio de usuarios usando JPA y MySQL. Se define el `JpaUserRepository`, encargado de las operaciones CRUD contra la base de datos, además de posibles integraciones externas como servicios de autenticación.

![UserInfrastructureLayer](assets/InfrastructureUser.png)


### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

![UserBoundedContext](assets/UserBoundedContextDiagram.png)

### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams

![UserBoundedContextDomainLayerClassDiagram](assets/UserFirstDiagram.png)

#### 4.2.1.6.2. Bounded Context Database Design Diagram

![UserBoundedContextDatabaseDesignDiagram](assets/UserSecondDiagram.png)

## 4.2.2. Bounded Context: IoT Device

Este bounded context gestiona los dispositivos IoT que permiten rastrear las prendas en LockItem. Cada sensor se registra con su número de serie, estado, ubicación y relación con un ítem de inventario. Se encarga de recibir señales de los dispositivos, verificar su estado y asignarlos dinámicamente.

### 4.2.2.1. Domain Layer

El Domain Layer define el agregado `Device`, que encapsula la lógica de estado del sensor, su ubicación y asociación con ítems. Los objetos de valor como `SerialNumber`, `DeviceStatus` y `DeviceLocation` ayudan a mantener la integridad del modelo.

![DeviceDomainLayer](assets/DomainDevice.png)

### 4.2.2.2. Interface Layer

El Interface Layer expone las operaciones relacionadas con los dispositivos IoT a través del `DeviceController`. Permite registrar dispositivos, actualizar su estado, consultarlos o asignarlos a un ítem del inventario.

![DeviceInterfaceLayer](assets/InterfaceDevice.png)

### 4.2.2.3. Application Layer

En esta capa se orquestan los casos de uso relacionados con dispositivos. Los handlers coordinan las operaciones de registro, actualización y consulta de estado, asegurando la persistencia y consistencia del dispositivo.

![DeviceApplicationLayer](assets/ApplicationDevice.png)

### 4.2.2.4. Infrastructure Layer

Aquí se implementa el repositorio de dispositivos utilizando JPA con MySQL. Además, se puede incluir un adaptador externo (`IoTGatewayAdapter`) para recibir eventos desde los sensores físicos a través de protocolos como MQTT o HTTP.

![DeviceInfrastructureLayer](assets/InfrastructureDevice.png)

### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams

![IoTDeviceBoundedContext](assets/IoTDeviceBoundedContext.png)

### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams

![IoTDeviceBoundedContextDomainLayerClassDiagram](assets/IoTDeviceFirstDiagram.png)

#### 4.2.2.6.2. Bounded Context Database Design Diagram

![IoTDeviceBoundedContextDatabaseDesignDiagram](assets/IotDeviceSecondDiagram.png)

## 4.2.3. Bounded Context: Inventory

El bounded context de Inventory se encarga de la gestión completa del inventario de prendas en LockItem. Permite registrar y consultar ítems, así como actualizar sus cantidades mediante movimientos de entrada o salida. También mantiene la relación con los dispositivos IoT que monitorean cada prenda en tiempo real.

### 4.2.3.1. Domain Layer

El Domain Layer contiene el agregado `InventoryItem`, que representa a cada ítem en stock. Incorpora reglas para validar el mínimo de stock (`threshold`), registrar movimientos y asociarse a dispositivos. Los objetos de valor `Quantity` y `StorageLocation` encapsulan la lógica de cantidades y ubicación física.

![InventoryDomainLayer](assets/DomainInventory.png)

### 4.2.3.2. Interface Layer

El Interface Layer permite acceder a la funcionalidad del inventario desde el exterior. El `InventoryController` proporciona endpoints REST para consultar ítems, registrar movimientos de stock y asignar dispositivos IoT.

![InventoryInterfaceLayer](assets/InterfaceInventory.png)

### 4.2.3.3. Application Layer

Aquí se implementan los casos de uso que gestionan el stock. Los command handlers permiten registrar movimientos o asignar sensores a ítems, mientras que los query handlers exponen funcionalidades de consulta y monitoreo de estado.

![InventoryApplicationLayer](assets/ApplicationInventory.png)

### 4.2.3.4. Infrastructure Layer

Esta capa contiene la implementación del repositorio usando JPA con MySQL (`JpaInventoryRepository`). También incluye adaptadores opcionales como `ERPInventorySyncAdapter` para sincronizar datos con sistemas ERP externos.

![InventoryInfrastructureLayer](assets/InfrastructureInventory.png)


### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams

![InventoryBoundedContext](assets/BoundedContextInventory.png)

### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams

![InventoryBoundedContextDomainLayerClassDiagram](assets/InventoryFirstDiagram.jpg)

#### 4.2.3.6.2. Bounded Context Database Design Diagram

![InventoryBoundedContextDatabaseDesignDiagram](assets/InventorySecondDiagram.jpg)

## 4.2.4. Bounded Context: ERP

Este bounded context se encarga de la integración del sistema LockItem con sistemas ERP externos. Permite sincronizar los datos de inventario con plataformas de gestión empresarial, manteniendo consistencia en los niveles de stock y el estado de los productos tanto dentro como fuera de LockItem.

### 4.2.4.1. Domain Layer

El Domain Layer define el agregado `ERPInventorySync`, que vincula ítems locales con sus equivalentes en el ERP externo. Incluye la lógica para determinar cuándo es necesario sincronizar y aplicar cambios de stock.

![ERPDomanLayer](assets/DomainERP.png)

### 4.2.4.2. Interface Layer

Esta capa expone los endpoints necesarios para iniciar procesos de sincronización, consultar el estado de los ítems sincronizados o traer información desde el ERP. Todo esto se maneja desde el `ERPSyncController`.

![ERPInterfaceLayer](assets/InterfaceERP.png)

### 4.2.4.3. Application Layer

En el Application Layer se orquestan los casos de uso de sincronización. Handlers como `SyncItemWithERPCommandHandler` y `FetchExternalInventoryQueryHandler` gestionan las interacciones entre los repositorios internos y los servicios externos del ERP.

![ERPApplicationLayer](assets/ApplicationERP.png)

### 4.2.4.4. Infrastructure Layer

Esta capa contiene la implementación del repositorio de sincronización (`JpaERPInventoryRepository`) y el adaptador HTTP que conecta con el sistema ERP externo. Este adaptador maneja la transformación de datos y la comunicación con APIs REST externas.

![ERPInfrastructureLayer](assets/InfrastructureERP.png)


### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams

![ERPBoundedContext](assets/ERPBoundedContext.png)

### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams

#### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams

![ERPBoundedContextDomainLayerClassDiagram](assets/ERPFirstDiagram.png)

#### 4.2.4.6.2. Bounded Context Database Design Diagram

![ERPBoundedContextDatabaseDesignDiagram](assets/ERPSecondDiagram.png)

# Conclusiones

