# Trabajo Práctico Integrador – Organización Empresarial

**Estudiante:** Germán Caballero

**Modalidad:** Trabajo individual

**Institución:** Universidad Tecnológica Nacional (UTN)

**Empresa analizada:** YPF Américo Stuyck SRL  

**Proyecto:** Sistema informático de apoyo a la gestión empresarial

## 1. Descripción del proyecto

El presente Trabajo Práctico Integrador tiene como objetivo analizar la organización y proponer una solución informática que contribuya a mejorar la gestión de determinados procesos de YPF Américo Stuyck SRL.

El proyecto integra conceptos de estructura organizacional, procesos empresariales, diseño de datos, trabajo colaborativo y mecanismos de control.

## 2. Objetivo del sistema

Proponer un sistema informático que permita organizar y consultar información relevante para las actividades de la empresa, facilitando el acceso a los datos y apoyando las tareas del personal.

## 3. Proceso de negocio modelado mediante BPMN

Para la cuarta entrega se seleccionó el proceso **Consulta de promociones**.

Este proceso representa cómo un cliente solicita información sobre una promoción y cómo el personal de Playa y FULL utiliza el sistema informático propuesto para responder a esa consulta.

### Participantes

- **Cliente:** solicita y recibe información sobre las promociones.
- **Personal de Playa y FULL:** atiende la consulta y comunica el resultado.
- **Sistema informático:** consulta las promociones registradas y determina su disponibilidad.

### Descripción del proceso

1. El cliente solicita información sobre una promoción.
2. El personal recibe la consulta y busca la promoción en el sistema.
3. El sistema consulta las promociones registradas.
4. Se verifica si la promoción está disponible.
5. Si está disponible, el sistema muestra la promoción y sus condiciones.
6. Si no está disponible, informa esa situación.
7. El personal comunica el resultado al cliente.
8. El cliente recibe la información y finaliza la consulta.

### Diagrama BPMN

![Diagrama BPMN de consulta de promociones](BPMN_Consulta_Promociones_YPF.drawio.png)

[Consultar archivo editable del BPMN](BPMN_Consulta_Promociones_YPF.drawio)

## 4. Herramientas utilizadas

- **diagrams.net:** elaboración del diagrama BPMN 2.0.
- **Git:** control de versiones del proyecto.
- **GitHub:** almacenamiento y seguimiento de la documentación.
- **GitHub Projects:** organización de tareas y seguimiento del avance del proyecto.

## 5. Trabajo colaborativo y control de versiones

El proyecto utiliza un repositorio público de GitHub para conservar su documentación y registrar las modificaciones realizadas.

Se emplean ramas de trabajo, commits descriptivos y Pull Requests para organizar e integrar los cambios.

## 6. Estado del proyecto

El proyecto se encuentra en la etapa de documentación y organización correspondiente a la cuarta entrega del Trabajo Práctico Integrador.

El sistema informático constituye una propuesta académica y no una aplicación implementada.

## 7. Validación del proceso BPMN

El proceso de consulta de promociones contempla dos escenarios:

- **Promoción disponible:** el sistema muestra la promoción y sus condiciones para que el personal informe al cliente.
- **Promoción no disponible:** el sistema informa que la promoción consultada no se encuentra disponible.

En ambos casos, el personal comunica el resultado al cliente, quien recibe la información y finaliza la consulta.

Esta descripción se incorpora para facilitar la revisión del diagrama BPMN 2.0 y comprobar la coherencia entre las actividades, las decisiones y los flujos de comunicación.

## 8. Historias de usuario y tablero Kanban

Para organizar el desarrollo del sistema informático propuesto para YPF Américo Stuyck SRL, se utilizó GitHub Projects como herramienta de planificación y seguimiento de actividades.

Se definieron tres historias de usuario vinculadas al repositorio:

- **HU01 - Consultar promociones disponibles:** permite al personal de Playa y FULL consultar las promociones vigentes para informar correctamente a los clientes.
- **HU02 - Consultar condiciones de promociones:** permite consultar los requisitos, las condiciones y las fechas de vigencia de los beneficios.
- **HU03 - Gestionar promociones:** permite al personal autorizado registrar y actualizar las promociones disponibles.

Las historias se encuentran registradas como incidencias de GitHub y organizadas en un tablero Kanban mediante diferentes estados de seguimiento.

**Estado actual de las actividades:**

- **Reserva:** HU03 - Gestionar promociones.
- **En curso:** HU02 - Consultar condiciones de promociones.
- **En revisión:** HU01 - Consultar promociones disponibles.
- **Hecho:** documentación del proceso de consulta de promociones mediante BPMN 2.0.

Estos estados representan el avance del análisis, la documentación y la planificación del proyecto. No implican que las funcionalidades del sistema informático ya estén implementadas.

**Enlace al tablero Kanban:**

https://github.com/users/gercab88-cyber/projects/1

**Enlaces a las historias de usuario:**

- HU01: https://github.com/gercab88-cyber/TPI-Organizacion-Empresarial-YPF/issues/4
- HU02: https://github.com/gercab88-cyber/TPI-Organizacion-Empresarial-YPF/issues/5
- HU03: https://github.com/gercab88-cyber/TPI-Organizacion-Empresarial-YPF/issues/6

## 9. Indicadores de control y estándares de desempeño

Para evaluar el funcionamiento del sistema informático propuesto, se establecen indicadores de control relacionados con la eficiencia de las consultas, la exactitud de la información y la actualización de las promociones.

Estos indicadores permitirían identificar desviaciones respecto de los objetivos establecidos y aplicar acciones correctivas.

### Indicador 1. Tiempo promedio de consulta de promociones

- **Objetivo:** evaluar la rapidez con la que el personal obtiene información sobre las promociones.
- **Medición:** suma de los tiempos de consulta dividida por la cantidad de consultas realizadas.
- **Estándar propuesto:** tiempo promedio igual o inferior a 30 segundos.
- **Acción correctiva:** revisar el procedimiento de búsqueda y mejorar la organización de la información si se supera el tiempo establecido.

### Indicador 2. Exactitud de la información

- **Objetivo:** verificar que las promociones y sus condiciones se informen correctamente.
- **Medición:** (consultas con información correcta / total de consultas verificadas) × 100.
- **Estándar propuesto:** exactitud igual o superior al 98 %.
- **Acción correctiva:** revisar los registros de promociones, corregir inconsistencias y reforzar la capacitación del personal.

### Indicador 3. Tiempo de actualización de promociones

- **Objetivo:** asegurar que los cambios en las promociones se reflejen oportunamente en el sistema.
- **Medición:** tiempo transcurrido entre la comunicación oficial de un cambio y su actualización en el sistema.
- **Estándar propuesto:** actualización dentro de las 24 horas posteriores a la comunicación del cambio, sin superar la fecha de entrada en vigencia.
- **Acción correctiva:** establecer responsables de actualización y mejorar el procedimiento de comunicación interna.

### Consideraciones

Los estándares definidos son valores de referencia propuestos para el proyecto académico. No representan mediciones reales de YPF Américo Stuyck SRL.

Su aplicación requeriría implementar el sistema, registrar los datos necesarios y evaluar periódicamente los resultados obtenidos.

## 10. Declaración de uso de inteligencia artificial

Durante la elaboración del Trabajo Práctico Integrador de Organización Empresarial se utilizó ChatGPT, una herramienta de inteligencia artificial generativa, como apoyo para el análisis, la organización y la documentación del proyecto.

### Aplicaciones de la herramienta

- Orientación para estructurar la documentación del repositorio de GitHub.
- Asistencia en la descripción y revisión del proceso de consulta de promociones modelado mediante BPMN 2.0.
- Apoyo para redactar historias de usuario y criterios de aceptación.
- Orientación en el uso de GitHub, ramas, commits, Pull Requests y GitHub Projects.
- Propuesta de indicadores de control, estándares de desempeño y acciones correctivas.
- Revisión de la ortografía, la coherencia y la claridad de los textos.

### Revisión crítica de los resultados

Las respuestas generadas por la inteligencia artificial se utilizaron como propuestas de trabajo y no como información automáticamente validada.

Se revisó su coherencia con la organización analizada, el proceso BPMN y los contenidos de la asignatura. También se distinguieron las funcionalidades propuestas de aquellas efectivamente implementadas.

Los estándares de desempeño incluidos en el proyecto son objetivos académicos sugeridos y no representan mediciones reales de la empresa.

### Responsabilidad académica

La selección de la empresa, la definición del proceso analizado y las decisiones finales sobre el contenido del trabajo corresponden al estudiante.

La inteligencia artificial se utilizó como herramienta de apoyo y no reemplaza la responsabilidad de comprender, revisar y justificar las decisiones presentadas.
