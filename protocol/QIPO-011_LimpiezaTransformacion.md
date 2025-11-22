# QIPO-011: Limpieza y Transformación del Registro de No Conformidades

## Q
¿Cómo debe limpiarse y transformarse el archivo actual de no conformidades para obtener tablas estructuradas y listas para análisis de datos?

## I
Modelo de datos objetivo definido en QIPO-010 (tablas NC y EVENTOS_NC).  
Archivo de origen: registro de no conformidades en Excel con celdas combinadas y múltiples filas por cada NC.

## P
Se ejecuta un proceso de limpieza y transformación del archivo original para generar datasets tabulares consistentes con el modelo de datos objetivo.

### Tareas prácticas
- Importar el archivo de no conformidades desde su formato original.
- Identificar la fila de encabezados reales y descartar filas superiores usadas solo para presentación.
- Rellenar hacia abajo los campos que aplican a toda la no conformidad (ITEM, N° de NC, estado, etc.) para cada grupo de filas.
- Convertir cada fila del archivo original en un **evento** asociado a una NC (comunicación, respuesta, seguimiento, cierre).
- Construir la tabla **EVENTOS_NC** con columnas estandarizadas: id_nc, fecha_evento, remitente, tipo_comunicacion, nro_carta, descripcion_evento.
- Derivar la tabla **NC** a partir de EVENTOS_NC:
  - fecha_emision = primera fecha_evento válida por id_nc.
  - fecha_cierre = última fecha_evento asociada a cierre (si existe).
  - estado_final = estado consolidado por id_nc.
- Validar consistencia básica:
  - ausencia de filas huérfanas sin id_nc,
  - coherencia de fechas (sin cierres antes de emisión),
  - unicidad de id_nc.
- Exportar las tablas resultantes en formatos analizables (por ejemplo, `NC.csv` y `EVENTOS_NC.csv`).

### Herramientas a utilizar
- Python (pandas) para:
  - lectura del archivo,
  - relleno de datos (`ffill`),
  - construcción de tablas derivadas,
  - validaciones básicas.
- Alternativamente: Power Query (Excel/Power BI) para transformación visual si se requiere un enfoque sin código.

### Marcos que justifican las acciones
- **CRISP-DM:** fase de preparación de datos como requisito previo a cualquier análisis.
- **ETL (Extract, Transform, Load):** extracción de datos operativos, transformación a modelo analítico y carga en estructuras limpias.
- **Data Quality:** necesidad de datos completos, coherentes y estructurados para análisis confiable.
- **Gestión documental (ISO 9001):** orden y consistencia en la información documentada sobre no conformidades.

## O
Se obtienen dos tablas estructuradas (NC y EVENTOS_NC), en formato tabular y normalizado, listas para la creación de variables derivadas y la realización de análisis exploratorio e indicadores.

## E
---
## C
previous: QIPO-008
