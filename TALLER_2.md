# 🌐 Taller 2 (RA2): Requisitos, Alcance y Diseño de la Solución Tecnológica

**Duración:** 1 sesión (2 horas).  
**Ciclos:** DAM · DAW · ASIR.  
**Modalidad:** Trabajo cooperativo en equipos.  
**Herramientas principales:** Draw.io · Packet Tracer · Excalidraw.

## 🎯 1. Objetivo del taller

En este taller vais a trabajar como un equipo técnico encargado de definir y diseñar una solución tecnológica para resolver un problema concreto.

El objetivo no es desarrollar todavía la solución, sino determinar **qué debe hacer, qué condiciones debe cumplir, cómo se estructurará técnicamente y qué recursos necesita para funcionar**.

Cada equipo deberá:

- Elegir un problema diferente, sin necesidad de utilizar el proyecto del Taller 1.
- Definir los requisitos funcionales y no funcionales.
- Priorizar los requisitos y delimitar el alcance de una primera versión.
- Diseñar la arquitectura o infraestructura de la solución.
- Identificar los componentes tecnológicos y sus relaciones.
- Estimar los recursos y costes necesarios.
- Analizar los riesgos y la viabilidad de la propuesta.

## 🧩 2. Punto de partida: elegid un problema tecnológico (10 min)

Formad equipos y seleccionad un problema que pueda resolverse mediante una aplicación, un sistema informático, una infraestructura tecnológica o una combinación de estos elementos.

**No es necesario continuar el proyecto del Taller 1.** Podéis elegir una situación completamente nueva.

Algunas propuestas para empezar rápidamente:

- **Gestión empresarial:** una empresa necesita gestionar pedidos, clientes y existencias.
- **Redes:** una organización necesita compartir información entre varias sedes.
- **Seguridad:** una empresa necesita mejorar la protección y disponibilidad de sus servicios.
- **Automatización:** una organización quiere reducir tareas manuales y repetitivas.
- **Desarrollo web:** un negocio necesita una plataforma para ofrecer servicios a sus clientes.
- **Gestión de datos:** una organización necesita centralizar información y facilitar la elaboración de informes.
- **Infraestructura:** una pequeña empresa necesita servidores, usuarios, copias de seguridad y controles de acceso.
- **Integración de sistemas:** una empresa necesita conectar diferentes aplicaciones mediante servicios o API.

También podéis plantear un problema propio.

### Definid brevemente la situación

Antes de comenzar el diseño, responded:

1. ¿Qué problema queremos resolver?
2. ¿Quién utilizará la solución o se beneficiará de ella?
3. ¿Qué resultado esperamos conseguir?

No dediquéis tiempo a investigar el mercado ni a comparar productos comerciales. En este taller, el objetivo es pasar rápidamente del problema al análisis y diseño técnico.

## 📋 3. Fase 1. Requisitos funcionales y no funcionales (25 min)

Antes de elegir tecnologías, debéis definir qué necesita la solución y qué condiciones deberá cumplir.

### 3.1. Requisitos funcionales

Describen **qué debe hacer el sistema**: las funcionalidades, operaciones o servicios que ofrecerá.

Ejemplos:

- Registrar y autenticar usuarios.
- Permitir la creación, modificación y consulta de pedidos.
- Generar informes a partir de los datos almacenados.
- Permitir la comunicación entre diferentes redes.
- Realizar copias de seguridad automáticas.
- Gestionar el acceso a determinados servicios según los permisos del usuario.

Cada requisito debe describir una necesidad concreta. Evitad expresiones vagas como «la aplicación tendrá muchas funcionalidades» o «el sistema será fácil de utilizar».

### 3.2. Requisitos no funcionales

Describen **cómo debe funcionar la solución y qué condiciones de calidad debe cumplir**.

| Aspecto | Qué debéis considerar |
|---|---|
| Seguridad | Autenticación, permisos, cifrado y protección de datos. |
| Rendimiento | Tiempos de respuesta y volumen de operaciones esperado. |
| Disponibilidad | Cuándo debe estar operativo el servicio y qué interrupciones puede admitir. |
| Usabilidad y accesibilidad | Facilidad de uso y acceso para las personas destinatarias. |
| Escalabilidad | Capacidad para crecer en usuarios, datos o carga de trabajo. |
| Mantenibilidad | Facilidad para actualizar, corregir y ampliar la solución. |
| Recuperación | Capacidad para recuperar datos y servicios ante fallos. |
| Compatibilidad | Sistemas, dispositivos, protocolos o plataformas con los que debe funcionar. |

No es necesario incluir todos los aspectos en todos los proyectos. Seleccionad los que tengan sentido para vuestra solución.

Siempre que sea posible, definid condiciones comprobables.

Por ejemplo, en lugar de «el sistema debe ser rápido», podéis proponer que las consultas habituales respondan en menos de dos segundos bajo una carga de uso determinada.

### 3.3. Clasificación y priorización mediante MoSCoW

Clasificad los requisitos según su importancia para la primera versión.

| Prioridad | Significado |
|---|---|
| **Must** | Imprescindible para que la primera versión cumpla su objetivo. |
| **Should** | Importante, pero la solución puede funcionar inicialmente sin ello. |
| **Could** | Mejora deseable que se puede posponer. |
| **Won't** | Fuera del alcance de esta versión. |

**Tarea:** definid al menos seis requisitos, combinando requisitos funcionales y no funcionales, y asignadles una prioridad MoSCoW.

Podéis utilizar una tabla como esta:

| ID | Requisito | Tipo | Prioridad |
|---|---|---|---|
| RF01 | Permitir el registro de usuarios. | Funcional | Must |
| RF02 | Generar informes de actividad. | Funcional | Should |
| RNF01 | Restringir el acceso según los permisos asignados. | No funcional | Must |
| RNF02 | Permitir ampliar la capacidad de almacenamiento. | No funcional | Could |

Los ejemplos son orientativos. Adaptadlos a vuestro problema y justificad las prioridades cuando no resulten evidentes.

### 3.4. Delimitación del alcance

Definid qué incluirá la primera versión de la solución y qué quedará fuera.

Responded:

- ¿Qué funcionalidades o servicios estarán disponibles inicialmente?
- ¿Qué elementos técnicos serán necesarios?
- ¿Qué funcionalidades, integraciones o mejoras se pospondrán?

**Resultado de la fase:** requisitos identificados, priorizados y un alcance inicial claramente delimitado.

## 🏗️ 4. Fase 2. Diseño de la solución tecnológica (40 min)

Ahora debéis representar cómo se estructurará técnicamente la solución y cómo se relacionarán sus componentes.

El diseño dependerá de la naturaleza del problema. No todos los proyectos necesitan una aplicación web, una base de datos, una red compleja o servicios cloud.

### 4.1. Identificad los componentes

Determinad qué elementos necesita vuestra solución. Según el proyecto, pueden ser:

- Aplicaciones o módulos de software.
- Interfaces de usuario.
- Bases de datos y sistemas de almacenamiento.
- API y servicios de comunicación.
- Equipos, redes y dispositivos.
- Servidores y sistemas operativos.
- Máquinas virtuales o contenedores.
- Servicios cloud.
- Mecanismos de autenticación, seguridad y copias de seguridad.

No añadáis componentes simplemente por hacer el diseño más complejo. Cada elemento debe responder a una necesidad o requisito.

### 4.2. Elegid la representación técnica adecuada

Utilizad una o varias de las siguientes herramientas, según lo que necesitéis explicar.

#### Draw.io

Adecuado para elaborar diagramas técnicos estructurados, como:

- Arquitectura general de la solución.
- Componentes y relaciones entre módulos.
- Modelo Entidad-Relación de una base de datos.
- Diagrama de despliegue.
- Infraestructura y servicios.
- Esquemas de comunicación entre sistemas.

#### Packet Tracer

Adecuado cuando el proyecto incluye redes e infraestructura que se pueden representar y simular mediante esta herramienta:

- Topologías de red.
- Segmentación de redes.
- Routers, switches y dispositivos finales.
- Direccionamiento IP.
- Comunicación entre segmentos.
- Servicios de red y conectividad.
- Medidas básicas de segmentación y seguridad.

No es necesario utilizar Packet Tracer si el proyecto no tiene un componente de redes que justifique su uso.

#### Excalidraw

Adecuado para realizar esquemas rápidos y explicar ideas técnicas de forma visual:

- Distribución inicial de los componentes.
- Flujo de información.
- Interacción entre usuarios y sistemas.
- Procesos y decisiones.
- Diseño conceptual de una solución.
- Representaciones preliminares que posteriormente puedan detallarse.

Podéis utilizar otra representación complementaria si resulta necesaria, pero estas serán las herramientas de referencia del taller.

### 4.3. Elaborad el diseño

Cada equipo deberá producir una representación técnica que permita comprender la solución propuesta.

El diseño deberá mostrar, según corresponda:

- Los principales componentes.
- La función de cada componente.
- Las relaciones y comunicaciones entre ellos.
- La ubicación de los datos o servicios.
- Los elementos de infraestructura necesarios.
- Los principales mecanismos de seguridad.

Añadid una breve explicación de las decisiones técnicas adoptadas.

Por ejemplo, si proponéis una aplicación cliente-servidor, identificad los elementos que intervienen y cómo se comunican. Si diseñáis una infraestructura de red, representad los dispositivos, las conexiones y la organización de la red. Si la propuesta consiste en automatizar un proceso, mostrad el flujo de información y los sistemas que participan.

No es necesario desarrollar código, configurar una infraestructura completa ni implementar todos los servicios.

**Resultado de la fase:** un diseño técnico comprensible y coherente con los requisitos definidos.

## 💻 5. Fase 3. Recursos, infraestructura y presupuesto (20 min)

Una vez diseñado el sistema, identificad los recursos necesarios para desarrollarlo, implantarlo y mantenerlo.

### 5.1. Identificación de recursos

Considerad los elementos que realmente necesita vuestro proyecto:

- Hardware y equipamiento.
- Software y licencias.
- Sistemas operativos.
- Servidores y almacenamiento.
- Redes y conectividad.
- Servicios cloud.
- Herramientas de desarrollo y pruebas.
- Seguridad y copias de seguridad.
- Horas de trabajo y mantenimiento.

Distinguid entre recursos disponibles, recursos que habría que adquirir y servicios que se contratarían.

### 5.2. CAPEX y OPEX

**CAPEX (Capital Expenditure): inversión en activos.**

Son los desembolsos destinados a adquirir o mejorar activos duraderos.

Ejemplos tecnológicos:

- Comprar un servidor físico.
- Comprar switches, routers u otros equipos de red.
- Adquirir equipamiento de almacenamiento.
- Comprar ordenadores para una infraestructura de trabajo.

**OPEX (Operating Expenditure): gastos operativos.**

Son los gastos necesarios para mantener la solución en funcionamiento, normalmente recurrentes.

Ejemplos tecnológicos:

- Pagar una suscripción mensual a un servicio cloud.
- Contratar alojamiento web o capacidad de servidor.
- Pagar cuotas de mantenimiento o soporte.
- Abonar licencias mediante suscripción.
- Pagar la conectividad o los servicios de copias de seguridad.

La diferencia fundamental es que CAPEX se relaciona habitualmente con la inversión en activos duraderos y OPEX con los gastos de funcionamiento. La clasificación exacta puede depender del contrato y del tratamiento contable.

Una solución basada en servicios cloud puede reducir la necesidad de comprar equipos, pero seguir generando gastos recurrentes.

### 5.3. Estimación de costes

Completad una tabla con los recursos principales.

| Recurso | Disponibilidad o necesidad | Tipo de coste | Estimación |
|---|---|---|---|
| Servidor físico | Adquisición necesaria | CAPEX | Coste inicial |
| Servicio cloud | Contratación necesaria | OPEX | Coste mensual |
| Software libre | Disponible | Sin coste de licencia, si procede | 0 € de licencia |
| Mantenimiento | Necesario | OPEX, si se contrata recurrentemente | Coste estimado |

Los conceptos y costes deben adaptarse a vuestra propuesta. No es obligatorio que todos los proyectos tengan gastos CAPEX y OPEX.

Indicad también qué recursos podrían condicionar el proyecto por su coste, disponibilidad o dificultad de configuración.

**Resultado de la fase:** inventario de recursos y estimación inicial de los costes relevantes.

## ⚠️ 6. Fase 4. Riesgos y viabilidad técnica (15 min)

Un diseño puede ser correcto sobre el papel y, aun así, presentar dificultades durante su desarrollo o implantación.

Identificad al menos tres riesgos que puedan afectar a vuestra solución.

### 6.1. Matriz de riesgos

| Riesgo | Probabilidad | Impacto | Medida preventiva o contingencia |
|---|---|---|---|
| Pérdida de información | Baja, media o alta | Bajo, medio o alto | Definir copias de seguridad y procedimientos de recuperación. |
| Fallo de un componente crítico | Baja, media o alta | Bajo, medio o alto | Identificar dependencias y valorar alternativas de recuperación. |
| Costes superiores a los previstos | Baja, media o alta | Bajo, medio o alto | Estimar consumos y revisar periódicamente los costes. |

Son ejemplos orientativos. Identificad riesgos específicos del diseño de vuestro equipo.

La **prevención** busca reducir la probabilidad de que ocurra un problema. La **contingencia** establece qué hacer si finalmente sucede.

### 6.2. Valoración de la viabilidad

Responded brevemente a las siguientes preguntas:

- **Técnica:** ¿disponemos de tecnologías, conocimientos e infraestructura suficientes?
- **Económica:** ¿son asumibles los costes iniciales y recurrentes?
- **Temporal:** ¿puede desarrollarse o implantarse en el plazo disponible?
- **Legal y de seguridad:** ¿se han tenido en cuenta las licencias, la protección de datos y los controles de seguridad que correspondan?

Concluid si la propuesta es viable, viable con condiciones o necesita modificaciones.

No se trata de realizar un estudio exhaustivo, sino de identificar los principales condicionantes y justificar vuestra decisión.

## ✅ 7. Fase 5. Revisión del diseño y cierre (10 min)

Antes de finalizar, revisad el trabajo con una perspectiva técnica.

Comprobad que:

- El problema está claramente identificado.
- Los requisitos funcionales y no funcionales están diferenciados.
- Las prioridades MoSCoW tienen sentido.
- El alcance de la primera versión está delimitado.
- El diseño responde a los requisitos.
- Los componentes y sus relaciones se entienden.
- Las tecnologías y la infraestructura están justificadas.
- Los recursos y costes se han estimado de forma razonable.
- Los riesgos principales están identificados.
- La conclusión sobre la viabilidad es coherente con el diseño.

Si encontráis contradicciones, corregidlas antes de finalizar.

## ⏱️ 8. Distribución del tiempo

| Fase | Actividad | Tiempo |
|---|---|---:|
| 1 | Elección del problema y definición inicial | 10 min |
| 2 | Requisitos, prioridades y alcance | 25 min |
| 3 | Diseño de la solución tecnológica | 40 min |
| 4 | Recursos, infraestructura y presupuesto | 20 min |
| 5 | Riesgos y viabilidad | 15 min |
| 6 | Revisión y cierre | 10 min |
| **Total** | | **120 min** |

## 🏁 Reto final

Imaginad que otro equipo debe implementar vuestra propuesta sin haber participado en su diseño.

¿Podría entender qué debe hacer el sistema, qué requisitos debe cumplir, cómo se relacionan sus componentes y qué recursos necesita?

El objetivo es transformar un problema en una **propuesta técnica inicial, estructurada, justificada y viable**.

## 🎤 9. Puesta en común y exposición final

**Duración:** Máximo 5 minutos por equipo.

Cada equipo expondrá brevemente el trabajo realizado, explicando las principales decisiones tomadas durante el taller.

La exposición debe incluir:

- **Problema y solución propuesta:** qué necesidad se pretende resolver y cuál es la solución planteada.
- **Requisitos y alcance:** qué funcionalidades o características se consideran prioritarias y qué queda fuera del alcance.
- **Diseño técnico:** explicación de los diagramas, esquemas o prototipos realizados con las herramientas utilizadas.
- **Recursos y viabilidad:** qué recursos serían necesarios, qué costes principales tendría la solución y qué riesgos habría que tener en cuenta.

No es necesario preparar una presentación adicional ni entregar documentación. El equipo puede utilizar directamente los diagramas, esquemas y anotaciones elaborados durante la sesión.

**Importante:** todos los miembros del equipo deben participar en la exposición y ser capaces de justificar las decisiones técnicas adoptadas.
