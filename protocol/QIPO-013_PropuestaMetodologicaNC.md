# QIPO-013: Diseño de la Propuesta Metodológica de Gestión de No Conformidades

## Q
¿Qué propuesta metodológica debe formularse, con fundamento técnico, para mejorar el proceso de gestión de no conformidades a partir del análisis de datos realizado?

## I
Resultados del análisis exploratorio (QIPO-012).  
Tablas procesadas y estructuradas (NC y EVENTOS_NC).  
Buenas prácticas de gestión documental, control de calidad y análisis de datos.

## P
Se formula una propuesta metodológica integral para la gestión de no conformidades, basada en los hallazgos obtenidos del análisis exploratorio y sustentada en buenas prácticas internacionales. La propuesta considera flujos, formatos, métricas y herramientas para mejorar la trazabilidad y efectividad del proceso.

### Tareas prácticas

#### 1. Definición del flujo metodológico de gestión de NC
- Diseñar un flujo ordenado desde la identificación de la NC hasta su cierre.  
- Incluir etapas como:
  - detección,
  - registro,
  - clasificación preliminar,
  - comunicación al responsable,
  - seguimiento,
  - verificación de corrección,
  - cierre formal,
  - análisis mensual de desempeño.
- Representar el flujo mediante diagrama (Mermaid, BPMN o similar).

#### 2. Propuesta de formato estándar para registro de NC
- Definir un formato tabular sin celdas combinadas.  
- Asegurar los campos mínimos necesarios:
  - id_nc,
  - fecha_emision,
  - remitente,
  - descripción,
  - tipo de comunicación,
  - estado_final,
  - fecha_cierre,
  - evidencias o adjuntos.
- Proponer un estándar para registrar eventos (historial por NC).

#### 3. Reglas de operación y control
- Establecer tiempos máximos recomendados para cada fase (ej. respuesta, cierre).  
- Definir roles y responsabilidades:
  - supervisor,
  - contratista,
  - residente,
  - QA/QC (si aplica).
- Establecer criterios de clasificación o severidad si son pertinentes.

#### 4. Incorporación de indicadores clave (KPIs)
Fundamentados en el análisis exploratorio:
- tiempo promedio de cierre,
- % NC cerradas dentro del plazo objetivo,
- backlog mensual,
- número promedio de eventos por NC,
- número de NC por mes o etapa,
- cumplimiento del flujo de cierre.

#### 5. Ciclo de análisis y retroalimentación
- Establecer revisiones periódicas (semanales o mensuales).  
- Proponer generación automática o semiautomática de reportes con Power BI o Python.  
- Integrar hallazgos en reuniones de coordinación.

### Herramientas a utilizar
- **Mermaid, Visio o Draw.io**: diagramación del flujo metodológico.  
- **Excel / Google Sheets**: definición del formato tabular estándar.  
- **Python / Power BI**: automatización y visualización de KPIs.  
- **Markdown**: documentación formal dentro del repositorio.

### Marcos que justifican las acciones
- **ISO 9001 (producto no conforme)**: enfoque en trazabilidad y corrección documentada.  
- **PMI (PMBOK)**:
  - gestión del conocimiento,
  - gestión de la información,
  - control de calidad,
  - comunicaciones del proyecto.
- **Ciencia de Datos / CRISP-DM**: traducción de análisis en acciones operativas.  
- **Mejora continua (PHVA / Kaizen)**: uso periódico de indicadores para retroalimentación.

## O
Se obtiene una metodología formalizada para la gestión de no conformidades, incluyendo flujos, formatos, KPIs y prácticas de seguimiento. Esta propuesta constituye el componente práctico y aplicable del trabajo de investigación.

## E
---
## C
previous: QIPO-008
