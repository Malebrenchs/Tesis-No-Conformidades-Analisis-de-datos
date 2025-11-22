# QIPO-012: Análisis Exploratorio y Generación de Indicadores

## Q
¿Qué análisis exploratorio debe realizarse sobre las tablas resultantes para obtener indicadores relevantes y comprender los patrones principales de las no conformidades registradas?

## I
Tablas resultantes de la transformación realizada en QIPO-011:
- **NC.csv** (una fila por no conformidad)
- **EVENTOS_NC.csv** (una fila por comunicación o evento asociado)

## P
Se ejecuta un análisis exploratorio (EDA) sobre ambas tablas para identificar comportamientos, tendencias, volúmenes, tiempos y características operativas del proceso de no conformidades.

### Tareas prácticas

#### 1. Análisis sobre la tabla NC
- Calcular métricas de volumetría:
  - número total de NC,
  - NC por mes / semana,
  - NC por fase (si aplica).
- Evaluar tiempos:
  - duración de cierre (`fecha_cierre - fecha_emision`),
  - edad de NC abiertas,
  - distribución de tiempos (mínimo, máximo, mediana, percentiles).
- Evaluar estados:
  - proporción de NC abiertas vs cerradas,
  - backlog acumulado.
- Identificar NC fuera de control (casos atípicos por duración o estado).

#### 2. Análisis sobre la tabla EVENTOS_NC
- Contar número de eventos por cada NC.
- Determinar proporción de tipos de comunicación (emisión, respuesta, seguimiento, cierre).
- Analizar tiempos entre eventos (si corresponde).
- Verificar patrones de interacción:
  - ¿cuántas idas y vueltas son habituales?
  - ¿hay NC con exceso de eventos?

#### 3. Construcción de indicadores clave (KPIs)
- Tiempo promedio de cierre.  
- Tiempo mediano de cierre.  
- % de NC cerradas dentro de un umbral definido.  
- Promedio de eventos por NC.  
- NC por período (mensual, semanal).  
- Distribución de tipos de comunicación.

#### 4. Visualizaciones recomendadas
- Histogramas de duración de NC.  
- Barras por mes de emisión o cierre.  
- Gráficos de Pareto (si luego existen tipos de NC).  
- Líneas de backlog acumulado.  
- Gráficos de barras para tipos de comunicación.

### Herramientas a utilizar
- **Python (pandas, matplotlib / seaborn)** para crear métricas y visualizaciones.  
- **Power BI** para dashboards interactivos y visualizaciones dinámicas.  
- **Excel** para análisis rápido o validación de cálculos iniciales.

### Marcos que justifican las acciones
- **Estadística descriptiva:** base para análisis exploratorio.  
- **Ciencia de datos / CRISP-DM:** fase de *Data Understanding* y *Data Exploration*.  
- **Control de calidad:** uso de indicadores para evaluar la gestión de no conformidades.  
- **Business Intelligence:** construcción de KPIs y visualizaciones para toma de decisiones.

## O
Se obtiene un conjunto de indicadores y visualizaciones que permiten comprender el comportamiento de las no conformidades, destacando patrones de duración, volumen, backlog e interacción. Esta información constituye la base para la formulación metodológica posterior.

## E
---
## C
previous: QIPO-008
