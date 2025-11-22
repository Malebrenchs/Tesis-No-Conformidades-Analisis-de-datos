# QIPO-009: Diagnóstico del Registro Actual de No Conformidades

## Q
¿Cuál es el diagnóstico del formato y la estructura del registro actual de no conformidades, y cuáles son las limitaciones que presenta para su análisis mediante técnicas de gestión y análisis de datos?

## I
Archivo Excel “BPE-ATE-EJ-CAL-FOR-000-006 CONTROL NC Definitiv.xlsx”, que contiene el registro operativo de no conformidades de la obra.  
El archivo presenta celdas combinadas, múltiples eventos asociados a una misma no conformidad, encabezados ampliados y estructura orientada a presentación visual.

## P
Se realiza la evaluación del documento empleado en obra para el registro de no conformidades, identificando su estructura, características documentales y limitaciones técnicas para su posterior procesamiento analítico. Las acciones principales consideradas en este diagnóstico son:

### 1. Identificación de la estructura actual del archivo
- Inspección del encabezado real utilizado para describir cada registro.  
- Revisión de las columnas presentes: ITEM, N° DE NO CONFORMIDAD, FECHA DE INGRESO / FECHA DE ENVÍO, N° DE CARTA, REMITENTE, TIPO DE COMUNICACIÓN, DESCRIPCIÓN, ESTADO, entre otras.  
- Identificación de que una misma no conformidad se extiende en múltiples filas debido a comunicaciones sucesivas.

### 2. Evaluación de aspectos estructurales que afectan el análisis
- Presencia de celdas combinadas que impiden filtrar y transformar la información.  
- Campos repetidos solo en la primera fila de cada grupo de comunicaciones, dejando las filas siguientes con datos incompletos visualmente.  
- Estructura del archivo optimizada para reporte visual y no para análisis tabular.

### 3. Identificación de limitaciones técnicas para análisis de datos
- Dificultad para identificar correctamente la clave única de cada no conformidad.  
- Falta de separación entre entidad “No Conformidad” y entidad “Evento asociado”.  
- Ausencia de un formato rectangular estricto que permita lectura directa por herramientas como Python, Power BI o Power Query.  
- Complejidad para medir duración, número de eventos, tiempos de respuesta o generación de indicadores temporales.

### 4. Elaboración del diagnóstico general
- El formato actual permite lectura humana y seguimiento narrativo, pero no soporte analítico.  
- La estructura debe reconvertirse a un modelo tabular normalizado para permitir cálculos, visualizaciones e indicadores.  
- Se determina la necesidad de diseñar un modelo de datos y realizar un proceso de limpieza para su uso analítico.

## O
Se obtiene un diagnóstico claro del registro actual, identificando sus limitaciones para el análisis de datos y estableciendo la necesidad de transformar el archivo hacia un formato tabular y normalizado. Este diagnóstico servirá como base directa para la siguiente fase del procedimiento práctico.

## E
---
## C
previous: QIPO-008
