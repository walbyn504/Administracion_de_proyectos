# Historial de versiones

Este historial registra los avances realizados cada semana durante el desarrollo del proyecto.

| Versión | Semana | Fecha | Avance realizado |
| --- | --- | --- | --- |
| 0.1 | 2 | 23/09/2026 | Documentación de la propuesta inicial: problema, sistema propuesto, roles, valor esperado y objetivos. |
| 0.2 | 2 | 26/09/2026 | Análisis de interesados (registro, mapa Poder–Interés e interesados críticos) y selección del Enfoque Híbrido de desarrollo.|
| 0.3 | 3 | 01/10/2026 | Definición del Scrum Team y distribución de responsabilidades de gestión, desarrollo, diseño, arquitectura y calidad. |

---

## Tabla de Contenidos

[Semana 2](#semana-2)
- [1. Planteamiento del problema](#1-planteamiento-del-problema)
- [2. Proyecto propuesto](#2-proyecto-propuesto)
  - [2.1. Administrador](#21-administrador)
  - [2.2. Colaborador](#22-colaborador)
- [3. Valor esperado](#3-valor-esperado)
- [4. Objetivos](#4-objetivos)
  - [Objetivo general](#objetivo-general)
  - [Objetivos específicos](#objetivos-específicos)
- [5. Análisis de Interesados](#análisis-de-interesados)
  - [5.1. Identificación de los interesados](#51-identificación-de-los-interesados)
  - [5.2. Registro de interesados](#52-registro-de-interesados)
  - [5.3. Valoración del poder y el interés](#53-valoración-del-poder-y-el-interés)
  - [5.4. Mapa Poder–Interés](#54-mapa-poderinterés)
  - [5.5. Interesados críticos](#55-interesados-críticos)
- [6. Enfoque de Desarrollo del Proyecto](#6-enfoque-de-desarrollo-del-proyecto)

[Semana 3](#semana-3)

- [1. Acta de Inicio](#1-acta-de-inicio-project-charter)
  - [1.1. Justificación del Proyecto](#11-justificación-del-proyecto)
  - [1.2. Objetivos del Proyecto](#12-objetivos-del-proyecto)
  - [1.3. Alcance y Límites Generales](#13-alcance-y-límites-generales)
- [2. Definición del Scrum Team y distribución de responsabilidades](#2-definición-del-scrum-team-y-distribución-de-responsabilidades)
  - [2.1. Asignación de responsabilidades de Scrum](#21-asignación-de-responsabilidades-de-scrum)
  - [2.2. Distribución de funciones técnicas](#22-distribución-de-funciones-técnicas)
- [3. Análisis de entorno](#3-análisis-de-entorno)
  - [3.1 Factores Ambientales de la Empresa (EEFs)](#31-factores-ambientales-de-la-empresa-eefs)
  - [3.2 Canvas del Proyecto](#32-canvas-del-proyecto)



---



## Semana 2

**Tema:** Sistema de gestión y seguimiento de solicitudes de clientes para una empresa corredora de seguros.

**Estudiantes:**

- Seidy Alanis.
- Walbyn González.

## 1. Planteamiento del problema

Una empresa corredora de seguros recibe diariamente solicitudes y consultas de sus clientes relacionadas con sus pólizas y servicios por diferentes medios, como llamadas telefónicas, correos electrónicos, presencial y WhatsApp. Al utilizar varios canales, se vuelve más difícil mantener las solicitudes organizadas y darles un seguimiento adecuado, debido a que no se cuenta con un mecanismo que permita conocer fácilmente el estado de cada solicitud, quién es el responsable y cuánto tiempo lleva siendo atendida.

Esta situación puede generar dificultades para llevar un control adecuado de las solicitudes y para disponer de información clara sobre el proceso de atención al cliente. Además, puede provocar retrasos, solicitudes repetidas o que algunos casos que requieren seguimiento no sean identificados oportunamente.

Por esta razón, surge la necesidad de analizar cómo se gestionan actualmente las solicitudes de los clientes, identificar las principales dificultades del proceso y buscar una alternativa que permita mejorar su organización, seguimiento y atención, tomando en cuenta las necesidades de los clientes y de las personas involucradas en el proceso.

## 2. Proyecto propuesto

Desarrollar un sistema web para la gestión y seguimiento de solicitudes de clientes de una empresa de seguros. El sistema permitirá centralizar en un solo lugar las solicitudes que actualmente pueden recibirse por diferentes medios, facilitando su registro, organización y seguimiento.

La propuesta contemplará el registro de cada solicitud con información como los datos del cliente, tipo de consulta o solicitud, fecha de ingreso, canal por el cual fue recibida, colaborador responsable, aseguradora responsable de atender, prioridad y estado. El colaborador que registre la solicitud quedará automáticamente asignado como responsable de su gestión. Los estados podrían incluir opciones como recibido, pendiente de requisito, enviado a aseguradora y finalizado, permitiendo conocer de manera rápida en qué situación se encuentra cada caso.

El sistema contará con dos roles principales:

### 2.1. Administrador

- Gestionar usuarios.
- Consultar el estado general de los trámites.
- Registrar solicitudes.
- Gestionar los trámites registrados.
- Actualizar los estados.
- Registrar observaciones o actualizaciones del trámite.
- Consultar y filtrar solicitudes para dar seguimiento.

### 2.2. Colaborador

- Registrar solicitudes.
- Gestionar los trámites registrados.
- Actualizar los estados.
- Registrar observaciones o actualizaciones del trámite.
- Consultar y filtrar solicitudes para dar seguimiento.

Además, el sistema permitirá consultar y filtrar las solicitudes para facilitar la búsqueda de casos específicos y dar seguimiento a aquellos que aún se encuentren pendientes. También se podrán registrar observaciones o actualizaciones realizadas durante la atención, de manera que exista un historial básico de cada solicitud.

La solución estará orientada a facilitar el trabajo de las personas encargadas de la atención al cliente, proporcionando una herramienta que permita mantener la información organizada, reducir la pérdida de seguimiento y disponer de información más clara sobre las solicitudes recibidas.

## 3. Valor esperado

Se espera que el sistema permita mejorar la organización y el seguimiento de las solicitudes de los clientes, centralizando la información en una sola plataforma y facilitando el control de cada trámite.

Con la implementación del sistema se espera:

- Mantener las solicitudes organizadas y centralizadas.
- Conocer el estado actual de cada trámite.
- Identificar fácilmente al colaborador responsable de cada solicitud.
- Facilitar el seguimiento de los trámites pendientes.
- Mantener un registro de las observaciones y actualizaciones realizadas.
- Facilitar la consulta y búsqueda de solicitudes mediante filtros.
- Reducir el riesgo de que una solicitud quede sin seguimiento.
- Proporcionar al administrador información general sobre el estado de los trámites.

## 4. Objetivos

### Objetivo general

Desarrollar un sistema web para la gestión y seguimiento de solicitudes de clientes de una empresa corredora de seguros, que facilite el registro, control y consulta de los trámites recibidos por los diferentes medios de atención.

### Objetivos específicos

1. Analizar el proceso actual de recepción y seguimiento de las solicitudes de los clientes, identificando las principales dificultades del proceso.

2. Definir los requerimientos del sistema web de acuerdo con las necesidades de los administradores y colaboradores.

3. Desarrollar un sistema web para el registro, gestión y seguimiento de las solicitudes de los clientes.

4. Implementar mecanismos de búsqueda y filtrado que faciliten la localización de solicitudes según diferentes criterios.


## Análisis de Interesados

### 5.1. Identificación de los interesados

- Empresa corredora de seguros.
- Gerencia de la corredora.
- Administradores.
- Colaboradores.
- Clientes de la corredora.
- Compañías aseguradoras.
- Equipo desarrollador.
- Encargado/área de TI.

### 5.2. Registro de interesados

Las actitudes y puntuaciones son estimaciones iniciales pendientes de validar. La existencia y las atribuciones del encargado o área de TI están por confirmar.

| Interesado | Rol / relación | Necesidad | Poder (1–5) | Interés (1–5) | Actitud | Estrategia |
| --- | --- | --- | --- | --- | --- | --- |
| 1. Empresa corredora de seguros | Organización donde se implementará el sistema y principal beneficiaria. | Centralizar las solicitudes y mejorar la continuidad de la atención. | 5 | 5 | Favorable. | Gestionar de cerca: validar el beneficio y la adecuación del sistema a sus procesos mediante sus representantes. |
| 2. Gerencia de la corredora | Autoriza decisiones, alcance y recursos del proyecto. | Conocer el avance y controlar el alcance y los recursos. | 5 | 5 | Favorable. | Gestionar de cerca: acordar prioridades y revisar avances semanalmente. |
| 3. Administradores | Gestionan usuarios, definen permisos y supervisan el flujo general de los trámites. | Gestionar usuarios, configurar roles y consultar el estado general de las solicitudes. | 4 | 5 | Favorable. | Gestionar de cerca: validar permisos, estados y consultas. |
| 4. Colaboradores | Registran y gestionan diariamente las solicitudes recibidas por los diversos canales. | Registrar y dar seguimiento a los casos sin duplicar trabajo. | 3 | 5 | Mixta: valoran el seguimiento, pero podrían percibir una mayor carga de registro. | Gestionar de cerca: consultar sus requerimientos de captura, validar la facilidad de las pantallas y capacitarlos en el uso del sistema. |
| 5. Clientes de la corredora | Beneficiarios externos; consultan el avance de sus trámites por medios tradicionales (llamadas, mensajes) sin acceso al sistema. | Recibir atención y seguimiento oportunos sobre sus solicitudes. | 2 | 3 | Favorable. | Mantener informados: asegurar que el sistema brinde datos precisos y actualizados para que el colaborador les responda con rapidez. |
| 6. Compañías aseguradoras | Entidades externas; reciben las solicitudes canalizadas por la corredora mediante sus propias plataformas oficiales. | Recibir la información completa para tramitar las solicitudes en sus plataformas. | 3 | 2 | Neutral. | Monitorear y consultar sus requisitos al definir el flujo de solicitudes. |
| 7. Equipo desarrollador | Diseña, desarrolla y documenta el sistema. | Contar con requisitos claros y un alcance viable. | 3 | 5 | Favorable. | Mantener informado e involucrar continuamente en las decisiones técnicas. |
| 8. Encargado/área de TI | Apoya la implementación, operación y soporte técnico. | Garantizar funcionamiento, seguridad y soporte. | 4 | 4 | Favorable, sujeto a la viabilidad técnica. | Gestionar de cerca: consultar restricciones técnicas y validar las condiciones de operación. |

### 5.3. Valoración del poder y el interés

Se utiliza la escala **1 = muy bajo, 2 = bajo, 3 = medio, 4 = alto y 5 = muy alto**.

- **Poder:** capacidad para autorizar, detener o modificar decisiones del proyecto.
- **Interés:** grado en que el resultado del proyecto afecta o importa al interesado.

Las puntuaciones del registro se justifican de la siguiente manera:

- **Empresa corredora de seguros — Poder 5, interés 5:** es la organización beneficiaria y determina si se implementa el sistema. Su autoridad se ejerce mediante sus representantes.
- **Gerencia de la corredora — Poder 5, interés 5:** autoriza recursos y decisiones de alcance, y necesita mejorar el control de las solicitudes. Se distingue de la empresa por su función de decisión; no representa una autoridad adicional independiente.
- **Administradores — Poder 4, interés 5:** aportan criterios para definir permisos, estados y supervisión de trámites. El sistema afecta directamente sus tareas de control.
- **Colaboradores — Poder 3, interés 5:** son los usuarios operativos clave encargados de ingresar la información. Aunque no aprueban recursos, su disposición a utilizar el sistema determina su adopción y éxito operativo.
- **Clientes de la corredora — Poder 2, interés 3:** no interactúan con el sistema ni poseen usuarios en la plataforma. Su interés es medio ya que se enfoca en recibir respuestas oportunas a través de las consultas que realicen al colaborador por los canales tradicionales (llamadas, WhatsApp, correo o presencial).
- **Compañías aseguradoras — Poder 3, interés 2:** operan de forma independiente a la plataforma y reciben las solicitudes por sus propios canales oficiales, por lo que no interactúan con el software de la corredora.
- **Equipo desarrollador — Poder 3, interés 5:** propone soluciones y determina su viabilidad técnica, pero no aprueba por sí solo recursos o cambios de alcance. Su interés es muy alto porque es responsable de construir el sistema.
- **Encargado/área de TI — Poder 4, interés 4:** se supone que puede condicionar la implementación según la infraestructura y el soporte disponibles. Esta valoración debe confirmarse; si su función fuera únicamente consultiva, su poder sería menor.

### 5.4. Mapa Poder–Interés

El mapa ubica a los ocho interesados según las puntuaciones del registro. El **poder aumenta hacia arriba** y el **interés hacia la derecha**. Para formar los cuadrantes, se agrupan los valores **1 a 3 como bajos o medios** y los valores **4 a 5 como altos**. Los pares indican **(poder, interés)**.

![Mapa Poder-Interés de la empresa corredora de seguros](Imagenes/mapa_poder-interes.png)


### 5.5. Interesados críticos 

Basado en el mapa de poder-interés se determinan tres interesados críticos y cómo se involucrarán. 

#### **- Gerencia de la corredora (Alto poder y alto interés)**

Autoriza recursos, aprueba el alcance y requiere visibilidad del control de solicitudes.

**Involucramiento:** 
- Reuniones semanales de avance y demostraciones funcionales. 
- Validar el flujo de estados de solicitudes, revisar avances del cronograma y aprobar las entregas de cada etapa. 


#### **- Colaboradores (Bajo poder y alto interés)**

Son los usuarios operativos finales que ingresan las solicitudes; su adopción determina el éxito del sistema.

**Involucramiento:** 
- Sesiones bisemanales de diseño y pruebas continuas de usabilidad.
- Validar prototipos de las pantallas de registro, simplificar la actualización de estados e impartir capacitaciones del uso de la plataforma.


#### **- Encargado/área de TI (Alto poder y alto-medio interés)**

Define la factibilidad técnica, las reglas de infraestructura y la seguridad de la información.

**Involucramiento:** 
- Mesas de trabajo técnicas al inicio, a mitad del desarrollo y previo al despliegue.
- Acordar el servidor de alojamiento, definir la gestión de base de datos y respaldos, e implementar mecanismos seguros de autenticación.



## 6. Enfoque de Desarrollo del Proyecto


Debido a las características del proyecto, se requerirá un enfoque híbrido, combinando la previsibilidad y el control de la gestión predictiva con la flexibilidad e iteración de la gestión adaptativa:

**Predictivo (Control, Arquitectura y Reglas de Negocio):** Se empleará para definir formalmente la base del sistema antes del desarrollo masivo. Permitirá establecer la arquitectura de base de datos, las restricciones de infraestructura exigidas por el área de TI (seguridad, autenticación y respaldos) y la matriz formal de roles y permisos (Administrador vs. Colaborador). Esto garantizará el cumplimiento de las reglas del negocio, el control del flujo formal del trámite y la previsibilidad en alcance, tiempo y presupuesto requerida por la Gerencia.


**Adaptativo (Diseño e Implementación de Interfaces):** Se aplicará mediante ciclos iterativos (sprints) para la construcción de las páginas web, vistas y formularios. Debido a que las solicitudes ingresarán por múltiples canales (WhatsApp, correo, llamadas y atención presencial), la capa visual se validará de forma incremental con los Colaboradores. Esto permitirá ajustar filtros, botones y vistas para optimizar la usabilidad y facilitar la adopción del sistema.


En conclusión, el componente predictivo asegurará la gobernanza, la seguridad y los permisos de acceso del sistema, mientras que el componente adaptativo otorgará la flexibilidad necesaria para diseñar e iterar las pantallas web a la medida de la operación diaria de los colaboradores.

---

## Semana 3

## 1. Acta de inicio (Project Charter)

El Acta de Inicio formaliza la autorización del proyecto y consolida su justificación, metas y límites operativos.

### 1.1. Justificación del Proyecto
*(Basado en el [Planteamiento del problema](#1-planteamiento-del-problema) y el [Valor esperado](#3-valor-esperado) de la Semana 2)*

---

### 1.2. Objetivos del Proyecto
*(Para el desglose completo de las metas del proyecto, véanse la **Semana 2, Sección 4 "Objetivos"**).*

* **Objetivo General:** Desarrollar un sistema web para la gestión y seguimiento de solicitudes de clientes de una empresa corredora de seguros, que facilite el registro, control y consulta de los trámites recibidos por los diferentes medios de atención.
* **Objetivos Específicos:** El detalle de los cuatro objetivos específicos del proyecto se encuentra disponible en la sección [objetivos](#4-objetivos) de la Semana 2.


### 1.3. Alcance y Límites Generales
Con base en la descripción y roles definidos en la [semana 2 (punto 2)](#2-proyecto-propuesto), el alcance del proyecto comprende:

#### Inclusiones (Dentro del Alcance)
* **Gestión de solicitudes:** Registro de trámites ingresando datos del cliente, tipo de consulta, fecha, canal de ingreso, aseguradora responsable, prioridad y estado inicial.
* **Asignación automática:** El usuario que registra la solicitud queda asignado automáticamente como el colaborador responsable.
* **Seguimiento y bitácora:** Actualización de estados del trámite (*recibido, pendiente de requisito, enviado a aseguradora, finalizado*) y registro de observaciones/actualizaciones.
* **Búsqueda y filtrado:** Motor de búsqueda con filtros por diversos criterios para localizar casos y dar seguimiento a trámites pendientes.
* **Gestión de accesos y roles:**
  * **Colaborador:** Funciones operativas de registro, gestión de trámites, actualización de estados, observaciones y consultas con filtros.
  * **Administrador:** Acceso total a todas las funciones del sistema, consulta del estado general de las solicitudes y módulo para la gestión de usuarios.

#### Exclusiones (Fuera del Alcance)
* **Acceso a clientes finales:** El sistema es para uso exclusivo del personal interno de la corredora; no contempla usuarios ni portal de consulta para clientes externos.
* **Integraciones automáticas con aseguradoras o mensajería:** No incluye conexión API automatizada con sistemas de aseguradoras ni envío/recepción automática de mensajes (WhatsApp API, SMS, etc.).
* **Gestión financiera o de cobros:** No abarca facturación, pagos ni cobros de pólizas.

## 2. Definición del Scrum Team y distribución de responsabilidades

El Scrum Team está conformado por Seidy Alanis y Walbyn González. Durante las semanas establecidas del proyecto, ambos integrantes participarán en el desarrollo del sistema web de gestión y seguimiento de solicitudes de clientes de la empresa corredora de seguros. Debido a que el equipo cuenta con dos integrantes, cada persona combinará responsabilidades.

### 2.1. Asignación de responsabilidades de Scrum

| Responsabilidad | Integrante asignado | Funciones principales |
| --- | --- | --- |
| **Product Owner** | Seidy Alanis | Definir el objetivo del producto; mantener actualizada la lista de tareas pendientes del producto; aclarar los requisitos de registro, seguimiento y consulta de solicitudes con los interesados; revisar que las funcionalidades respondan a las necesidades del negocio. |
| **Scrum Master** | Walbyn González | ofrecerá asesoramiento sobre los procesos y metodologías al propietario del producto, a los desarrolladores y a las partes interesadas. Además, actúa como agente de cambio y facilita el desarrollo organizacional. |
| **Developers** | Seidy Alanis y Walbyn González | Planificar el trabajo de cada Sprint; analizar, diseñar, desarrollar y probar las funcionalidades; integrar los componentes del sistema y cumplir los criterios de calidad acordados en la Definición de Terminado. |

### 2.2. Distribución de funciones técnicas

Ambos integrantes participarán como desarrolladores full-stack, con una distribución inicial de funciones principales y apoyo mutuo según las necesidades de cada Sprint.

| Función técnica | Responsable principal | Actividades en el proyecto |
| --- | --- | --- |
| **Desarrollo full-stack** | Ambos | Construir e integrar las interfaces, la lógica del sistema y el acceso a la base de datos; corregir errores y entregar funcionalidades completas. |
| **Frontend** | Seidy Alanis, con apoyo de Walbyn González | Implementar las pantallas de registro, consulta y seguimiento de solicitudes, filtros y formularios; adaptar las interfaces a distintos dispositivos. |
| **Backend** | Walbyn González, con apoyo de Seidy Alanis | Implementar la lógica de solicitudes, cambios de estado, asignación de responsables, observaciones, autenticación y permisos de Administrador y Colaborador. |
| **Designer** | Seidy Alanis | Elaborar bocetos y prototipos; definir la apariencia y navegación; validar la facilidad de uso de las pantallas con los colaboradores. |
| **Architect** | Walbyn González | Proponer y documentar la estructura del sistema, los componentes, el modelo de datos y las tecnologías; acordar las decisiones técnicas con el equipo considerando las restricciones de infraestructura. |
| **QA** | Ambos | Definir criterios de aceptación; diseñar y ejecutar pruebas de registro, filtros, estados y permisos; registrar defectos y comprobar sus correcciones. |
| **Documentación técnica** | Ambos | Mantener actualizados los requisitos, las decisiones técnicas, los resultados de pruebas y las instrucciones de uso del sistema. |


## 3. Análisis de Entorno 

### 3.1. Factores Ambientales de la Empresa (EEFs)

Los Factores Ambientales de la Empresa son condiciones internas y externas que no están bajo el control directo del equipo de desarrollo, pero que influyen, condicionan y orientan las decisiones del proyecto.

#### Factores Internos
* **Cultura operacional y canales dispersos:** La corredora atiende clientes por teléfono, correo, WhatsApp y presencialmente sin un flujo estandarizado. El sistema debe adaptarse a esta realidad multi-canal para facilitar su adopción.
* **Infraestructura de TI:** La elección de tecnologías, el servidor de alojamiento (*hosting*) y la base de datos están alineados con la viabilidad técnica y condiciones fijadas por la empresa.
* **Estructura organizacional:** Definición clara de permisos y roles de trabajo (Administrador y Colaborador) según las funciones de la empresa.

#### Factores Externos
* **Normativa legal y privacidad:** Manejo de datos sensibles de clientes y pólizas sujeto a la legislación vigente de protección de datos personales (*Ley N° 8968*).
* **Entorno con Aseguradoras:** Las compañías aseguradoras operan con sus propias plataformas y tiempos. El sistema registrará el envío del trámite a la aseguradora correspondiente sin requerir integraciones API directas.
* **Expectativas de los clientes:** Los clientes no interactúan con el sistema, pero esperan respuestas rápidas cuando consultan a su colaborador por los canales tradicionales.

---


### 3.2. Canvas del Proyecto

El Canvas del Proyecto sintetiza los aspectos fundamentales de gobernanza, alcance, interesados y restricciones para el desarrollo del sistema de gestión de solicitudes de la Corredora de Seguros:

![Canvas del Proyecto](imagenes/canva.png)