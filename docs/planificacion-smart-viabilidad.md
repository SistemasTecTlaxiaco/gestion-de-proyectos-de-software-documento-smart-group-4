# Planificación SMART y Análisis de Viabilidad del Proyecto

**Proyecto:** Sistema de Gestión Comercial para Artesanías de Olla de Barro y Canastas Tejidas a Mano  
**Institución:** Instituto Tecnológico de Tlaxiaco  
**Asignatura:** Gestión de Proyectos de Software  
**Metodología de trabajo:** eduScrum  
**Integrantes:** Edgar Axel Sandoval Hernández y Adriana Hernández Martínez

## 1. Objetivo SMART del Proyecto

### Objetivo general

Desarrollar un producto mínimo viable (MVP) de un Sistema de Gestión Comercial para Artesanías de Olla de Barro y Canastas Tejidas a Mano, dirigido a apoyar a los artesanos y productores de la región Mixteca de Oaxaca en la organización y administración de sus productos y ventas. El sistema incluirá módulos de autenticación, catálogo de productos, control de inventario, registro de ventas y generación de reportes, con el propósito de facilitar la gestión comercial y mejorar el control de la información.

### Descripción del objetivo SMART

- **S — Específico:** desarrollar un sistema que permita registrar y consultar productos artesanales, administrar existencias, registrar ventas y generar reportes básicos para apoyar las actividades comerciales de los artesanos.
- **M — Medible:** registrar al menos 50 productos artesanales de referencia y contemplar la participación de 15 talleres o productores durante las pruebas de validación. Se buscará que al menos el 98 % de las pruebas funcionales definidas se ejecuten correctamente y que las operaciones principales respondan en menos de 3 segundos en condiciones de prueba.
- **A — Alcanzable:** implementar el proyecto de manera incremental, distribuyendo las funcionalidades en módulos y priorizando las características esenciales del sistema. El desarrollo se apoyará en herramientas de software accesibles, control de versiones con GitHub y pruebas realizadas por los integrantes.
- **R — Relevante:** el sistema atenderá necesidades relacionadas con la organización de productos, el control de inventario y el registro de ventas de artesanías, considerando las condiciones de trabajo y conectividad que pueden presentarse en la región Mixteca.
- **T — Temporal:** organizar el desarrollo mediante cuatro Sprints, con actividades, responsables y entregables definidos por el equipo. Las fechas específicas se establecerán de acuerdo con el calendario académico y la planeación del proyecto.

### Resultado esperado

Al concluir los Sprints planeados, se espera contar con una versión funcional del sistema que integre los módulos principales, cuente con documentación básica y haya sido evaluada mediante pruebas funcionales. La validación permitirá identificar mejoras antes de considerar su implementación con artesanos y productores de la región.

## 2. Trazabilidad con Historias de Usuario y Costo de Calidad (CoQ)

La trazabilidad permitirá relacionar los requisitos del proyecto con las actividades de desarrollo, las pruebas y los costos asociados a la calidad. Para ello, se utilizarán las historias de usuario definidas durante la planeación y se revisará su avance en los Sprints.

### 2.1 Historias de usuario de referencia

Las siguientes historias representan una propuesta inicial para organizar las funcionalidades principales. Los puntos de referencia deberán compararse con los registrados realmente por el equipo durante el Sprint 1.

| ID | Historia de usuario | Criterio de aceptación principal | Puntos de referencia |
|---|---|---|---:|
| HU-01 | Como usuario, quiero iniciar sesión para acceder a las funciones autorizadas del sistema. | El sistema permite ingresar con credenciales válidas y rechaza las inválidas. | 5 |
| HU-02 | Como usuario, quiero registrar y consultar productos artesanales para mantener actualizado el catálogo. | Se pueden registrar, consultar y visualizar los datos principales de cada producto. | 8 |
| HU-03 | Como encargado, quiero controlar las existencias para conocer la disponibilidad de los productos. | El inventario muestra las existencias registradas y refleja los cambios correspondientes. | 8 |
| HU-04 | Como encargado, quiero registrar ventas para mantener un control de las operaciones comerciales. | El sistema registra los productos vendidos y actualiza las existencias de acuerdo con la operación. | 5 |
| HU-05 | Como usuario autorizado, quiero consultar reportes para revisar información sobre productos, inventario y ventas. | El sistema presenta información organizada y correspondiente a los registros disponibles. | 5 |

**Nota:** los puntos son estimaciones de referencia, no resultados confirmados del Sprint 1. El equipo deberá ajustarlos según su tablero y los acuerdos reales de estimación.

### 2.2 Relación con el Costo de Calidad (CoQ)

El Costo de Calidad (CoQ, por sus siglas en inglés) permite identificar el esfuerzo destinado a prevenir errores y el esfuerzo utilizado para corregir problemas detectados durante el desarrollo.

Para esta planeación se toma como referencia una tarifa estimada de $150 MXN por hora.

| Categoría | Actividades consideradas | Horas estimadas | Costo estimado | Porcentaje |
|---|---|---:|---:|---:|
| Prevención | Planeación, revisión de requisitos, diseño, documentación y preparación de pruebas. | 18.5 h | $2,775 MXN | 56.06 % |
| Corrección | Corrección de errores, ajustes de funcionalidades y solución de problemas detectados en las pruebas. | 14.5 h | $2,175 MXN | 43.94 % |
| **Total** | **Esfuerzo de calidad estimado.** | **33 h** | **$4,950 MXN** | **100 %** |

Estos valores constituyen una estimación de referencia y deberán actualizarse con las horas reales registradas durante el Sprint 2.

### 2.3 Interpretación del CoQ

La estimación muestra que se destinarían 18.5 horas a actividades preventivas y 14.5 horas a correcciones. La prevención representa una parte importante del esfuerzo de calidad, ya que revisar los requisitos, definir criterios de aceptación y preparar las pruebas puede ayudar a detectar problemas antes de que afecten otras funcionalidades.

El equipo deberá registrar el tiempo empleado en cada actividad para comparar el esfuerzo planeado con el real y reconocer qué prácticas contribuyen a reducir errores y retrabajos.

### 2.4 Acciones de seguimiento

- Relacionar cada historia de usuario con sus tareas de desarrollo y pruebas.
- Definir criterios de aceptación antes de considerar terminada una funcionalidad.
- Registrar los errores encontrados y las correcciones realizadas.
- Actualizar las horas de prevención y corrección al finalizar cada Sprint.
- Revisar si los cambios de alcance afectan el tiempo, el costo o la calidad del sistema.

## 3. Análisis de Viabilidad Técnica y Operativa

### 3.1 Viabilidad técnica

El proyecto se considera técnicamente viable si el equipo dispone de los recursos necesarios para desarrollar, probar y mantener una primera versión funcional del sistema.

Los principales aspectos técnicos que deberán considerarse son los siguientes:

- **Herramientas de desarrollo:** utilizar herramientas accesibles para la programación, documentación y pruebas del sistema.
- **Control de versiones:** emplear Git y GitHub para conservar el historial de cambios, trabajar mediante ramas y revisar las modificaciones antes de integrarlas.
- **Modularidad:** separar las funcionalidades de catálogo, inventario, ventas, autenticación y reportes para facilitar el mantenimiento y la detección de errores.
- **Seguridad:** proteger las credenciales, validar los datos de entrada y limitar el acceso a las funciones según los permisos definidos.
- **Rendimiento:** evaluar el tiempo de respuesta de las operaciones principales mediante pruebas en condiciones conocidas.
- **Pruebas funcionales:** comprobar que cada módulo cumpla con sus criterios de aceptación y que la integración entre módulos funcione correctamente.
- **Documentación:** mantener instrucciones básicas de instalación, configuración y uso del sistema.

La viabilidad técnica deberá confirmarse conforme avance el desarrollo y se verifique que las herramientas seleccionadas sean compatibles con los requisitos del proyecto.

### 3.2 Viabilidad operativa

La viabilidad operativa considera si el sistema puede utilizarse en las actividades comerciales de los artesanos y si su funcionamiento se adapta a las condiciones reales de la región Mixteca.

Para ello, se tomarán en cuenta los siguientes factores:

- **Conectividad:** algunas comunidades pueden tener acceso limitado o inestable a Internet. Por esta razón, se deberá evaluar la conectividad disponible antes de decidir si el sistema requiere operar localmente, funcionar parcialmente sin conexión o depender de servicios en línea.
- **Facilidad de uso:** la interfaz deberá ser clara y sencilla, con formularios comprensibles y opciones fáciles de identificar.
- **Administración de productos:** el registro de las artesanías deberá contemplar información útil, como nombre, descripción, precio y existencias.
- **Control de ventas:** el registro de las operaciones deberá ser claro y permitir consultar la información necesaria para la administración comercial.
- **Capacitación:** será necesario proporcionar instrucciones básicas para que los usuarios puedan familiarizarse con el sistema.
- **Validación con usuarios:** cuando sea posible, se buscará obtener comentarios de artesanos o productores para identificar necesidades y oportunidades de mejora.

Antes de establecer un requisito de funcionamiento sin conexión, el equipo deberá confirmar su viabilidad técnica. Si esta característica no puede implementarse en la primera versión, se documentará como una posible mejora futura.

### 3.3 Aplicación de eduScrum

La metodología eduScrum permitirá organizar el trabajo en periodos de desarrollo, revisar los resultados y adaptar las actividades según las necesidades detectadas.

Se aplicarán las siguientes prácticas:

- **Planeación del Sprint:** definir las historias de usuario, las tareas y los resultados esperados.
- **Distribución del trabajo:** asignar responsabilidades de acuerdo con las capacidades y los acuerdos de los integrantes.
- **Seguimiento:** mantener actualizado el tablero para conocer las tareas pendientes, en proceso y terminadas.
- **Revisión del Sprint:** verificar las funcionalidades desarrolladas y comprobar si cumplen con los criterios de aceptación.
- **Retrospectiva:** analizar qué funcionó, qué dificultades surgieron y qué cambios pueden mejorar el siguiente Sprint.

Estas prácticas ayudarán a mantener la organización del proyecto, mejorar la comunicación y detectar retrasos o problemas de calidad de manera oportuna.

## 4. Viabilidad Financiera y Estrategia Web3

### 4.1 Estimación inicial de costos

Para evaluar la viabilidad financiera, se presenta una estimación de referencia de los recursos que podrían requerirse para desarrollar y validar el sistema.

| Concepto | Descripción | Costo estimado |
|---|---|---:|
| Desarrollo y calidad | Planeación, programación, pruebas, documentación y correcciones. | $18,000 MXN |
| Servicios de alojamiento | Estimación para servicios de alojamiento o infraestructura durante una etapa inicial. | $3,600 MXN |
| Materiales de validación | Materiales de apoyo y actividades de validación con usuarios. | $5,500 MXN |
| **Total estimado** | **Costo inicial de referencia.** | **$27,100 MXN** |

Los importes anteriores son estimaciones para el análisis de viabilidad, no cotizaciones ni gastos comprobados. Deberán ajustarse según el alcance final, las herramientas elegidas, la duración del proyecto y los recursos disponibles.

Para una comparación internacional se puede utilizar un tipo de cambio de referencia de $18.95 MXN por dólar estadounidense. Con ese supuesto, el costo estimado de $27,100 MXN equivale aproximadamente a **1,430 USD**. El tipo de cambio real puede variar.

### 4.2 Posibles fuentes de financiamiento Web3

El proyecto podría explorar alternativas de financiamiento comunitario para apoyar su desarrollo o futuras mejoras. Sin embargo, la posibilidad de recibir fondos depende de los requisitos, las convocatorias vigentes, la evaluación de la propuesta y la aprobación de cada programa.

**Stellar Community Fund (SCF)**

El Stellar Community Fund es una iniciativa relacionada con el ecosistema Stellar que ha apoyado proyectos que construyen soluciones sobre su red. El equipo podría investigar sus convocatorias y requisitos para determinar si una futura versión del sistema tiene una justificación adecuada para incorporar funcionalidades basadas en Stellar.

Para considerar esta alternativa, sería necesario definir con claridad el problema que resolvería una integración blockchain, su beneficio para los artesanos y los costos de implementación y mantenimiento. La integración no forma parte de los requisitos confirmados de la versión inicial.

**Drips Protocol**

Drips Protocol está relacionado con mecanismos de financiamiento y distribución de recursos dentro del ecosistema Web3. El equipo podría investigar sus posibilidades de uso para apoyar actividades de desarrollo de código abierto, mantenimiento o colaboración comunitaria, siempre que la propuesta cumpla con las condiciones aplicables.

Antes de incluirlo en la estrategia financiera, será necesario verificar la disponibilidad, las reglas y la compatibilidad de sus mecanismos con las necesidades del proyecto.

### 4.3 Consideraciones financieras

- La versión inicial deberá priorizar herramientas accesibles y reducir los gastos innecesarios.
- Las estimaciones deberán actualizarse con los costos reales conforme avance el proyecto.
- Las posibles fuentes Web3 se tratarán como alternativas por investigar, no como ingresos garantizados.
- Cualquier integración blockchain deberá justificarse por su utilidad real para los usuarios.
- Si se considera recibir o administrar fondos digitales, deberán evaluarse los riesgos técnicos, financieros, operativos y regulatorios correspondientes.

### 4.4 Decisión Go/No-Go

**Decisión inicial: GO condicionado.**

Se recomienda continuar con el desarrollo del MVP porque el proyecto presenta un alcance que puede organizarse por módulos y evaluarse mediante historias de usuario y pruebas funcionales.

La decisión está condicionada a los siguientes puntos:

1. Confirmar y priorizar los requisitos esenciales del sistema.
2. Verificar que las herramientas seleccionadas permitan implementar las funcionalidades previstas.
3. Mantener un control del tiempo, los costos y los errores encontrados.
4. Validar que el sistema resulte comprensible y útil para los usuarios a quienes está dirigido.
5. No depender de una subvención o financiamiento Web3 para completar las funciones esenciales de la primera versión.

Si durante el desarrollo se identifican limitaciones técnicas importantes, costos fuera del alcance o dificultades operativas que no puedan resolverse, el equipo deberá revisar la decisión y ajustar el alcance antes de continuar.

## 5. Gestión del Equipo y Gobernanza eduScrum

La organización del trabajo permitirá coordinar las actividades, dar seguimiento a las entregas y mantener la trazabilidad entre las necesidades del proyecto y las funcionalidades desarrolladas.

### A. Organización del equipo

- **Integrantes:** Edgar Axel Sandoval Hernández y Adriana Hernández Martínez.
- **Responsabilidades:** deberán distribuirse entre análisis, diseño, desarrollo, pruebas y documentación, de acuerdo con las capacidades y los acuerdos del equipo.
- **Coordinación:** ambos integrantes darán seguimiento a las actividades y mantendrán actualizado el tablero de trabajo.
- **Validación de requisitos:** se revisarán las historias de usuario y los criterios de aceptación para asegurar que las funcionalidades respondan a las necesidades de los artesanos de la región Mixteca.

### B. Seguimiento y control del proyecto

- **Gestión del tablero:** las tareas se organizarán mediante los estados definidos por el equipo, desde la propuesta hasta su finalización.
- **Control de versiones:** GitHub permitirá registrar los cambios en el código y la documentación, trabajar mediante ramas y revisar las modificaciones a través de Pull Requests.
- **Aseguramiento de calidad:** se realizarán pruebas funcionales para comprobar el funcionamiento del catálogo de productos, el inventario, las ventas, la autenticación y los reportes.
- **Revisión de los Sprints:** al finalizar cada Sprint, ambos integrantes evaluarán los resultados, identificarán problemas y propondrán mejoras.
- **Toma de decisiones:** las propuestas de modificación o incorporación de funcionalidades se revisarán y aprobarán de común acuerdo antes de integrarse al proyecto.

### C. Autogestión y mejora continua

- **Compromiso del equipo:** cada integrante será responsable de cumplir las tareas acordadas y comunicar cualquier dificultad que afecte su avance.
- **Colaboración:** se promoverá la comunicación constante, la revisión entre compañeros y el apoyo mutuo para resolver problemas técnicos.
- **Documentación:** los avances, las decisiones y los cambios relevantes se registrarán en el repositorio de GitHub.
- **Mejora continua:** las revisiones permitirán identificar oportunidades de mejora en la organización, la distribución del trabajo y la calidad del sistema.

La aplicación de estas prácticas permitirá mantener una organización clara, mejorar el seguimiento de las actividades y favorecer el desarrollo progresivo del Sistema de Gestión Comercial para Artesanías de Olla de Barro y Canastas Tejidas a Mano.

## 6. Conclusión

La planificación SMART y el análisis de viabilidad permiten establecer una dirección clara para el desarrollo del Sistema de Gestión Comercial para Artesanías de Olla de Barro y Canastas Tejidas a Mano. La definición de un MVP facilita priorizar las funcionalidades principales y organizar su implementación mediante historias de usuario y Sprints.

El análisis técnico y operativo destaca la importancia de considerar la conectividad, la facilidad de uso, la seguridad y la validación de los requisitos. Por otra parte, la estimación del Costo de Calidad permite identificar el esfuerzo destinado a prevenir y corregir errores, mientras que el análisis financiero proporciona una referencia inicial para valorar los recursos necesarios.

Las alternativas Stellar Community Fund y Drips Protocol podrán investigarse como posibles fuentes de apoyo, sin asumir que el proyecto recibirá financiamiento ni que necesita incorporar blockchain en su primera versión.

Finalmente, la aplicación de eduScrum, el seguimiento en GitHub y la colaboración entre Edgar Axel Sandoval Hernández y Adriana Hernández Martínez contribuirán a organizar las actividades, mantener la trazabilidad y mejorar progresivamente la calidad del sistema.

## 7. Referencias

- eduScrum. (s. f.). *The eduScrum method*. https://eduscrum.org/
- GitHub. (s. f.). *GitHub Docs*. https://docs.github.com/
- Stellar Development Foundation. (s. f.). *Stellar Community Fund*. https://communityfund.stellar.org/
- Drips Protocol. (s. f.). *Drips*. https://www.drips.network/

**Nota para la entrega:** antes de presentar el documento, verifica que las cifras de historias de usuario, horas de CoQ y costos coincidan con los registros reales de los Sprints y con las instrucciones del docente. También conviene revisar la vigencia y los requisitos de los programas de financiamiento antes de afirmar que son opciones disponibles para el proyecto.
