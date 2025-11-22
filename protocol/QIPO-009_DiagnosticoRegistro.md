# QIPO-009: Diagnóstico del Registro Actual de No Conformidades

## Q
¿Cuál es el diagnóstico del registro actual de no conformidades y qué limitaciones presenta para aplicar análisis de datos?

## I
Archivo Excel “BPE-ATE-EJ-CAL-FOR-000-006 CONTROL NC Definitiv.xlsx”, estructurado mediante celdas combinadas y múltiples filas por cada no conformidad.

## P
Se realiza un diagnóstico inicial del archivo para determinar su estructura operativa, sus limitaciones analíticas y los requisitos para su posterior transformación.

### Tareas prácticas
- Inspeccionar el encabezado real y las columnas utilizadas en el registro.  
- Identificar la estructura agrupada por no conformidad (una NC → varias filas).  
- Detectar celdas combinadas y campos incompletos que impiden análisis tabular.  
- Evaluar capacidad del formato actual para:  
  - filtrar, ordenar y agrupar,  
  - calcular tiempos de cierre,  
  - contar comunicaciones por NC,  
  - generar indicadores.  
- Elaborar un diagnóstico general que determine la necesidad de transformar el archivo a un formato limpio y normalizado.

### Herramientas a utilizar
- Excel / PowerQuery → inspección y detección de estructuras problemáticas.  
- Python (pandas) → análisis preliminar, lectura del archivo y detección de inconsistencias.  

### Marcos que justifican las acciones
- **ISO 9001:** control adecuado de la información documentada.  
- **PMI / PMBOK:** gestión de información y comunicación del proyecto.  
- **Ciencia de Datos / CRISP-DM:** etapas de comprensión del negocio y comprensión de los datos.  
- **Data Governance:** necesidad de estructuras consistentes y trazables para análisis.

## O
Se obtiene un diagnóstico claro que demuestra que el formato actual dificulta el análisis de datos y debe ser transformado para permitir mediciones, indicadores y trazabilidad efectiva.

## E
---
## C
previous: QIPO-008
