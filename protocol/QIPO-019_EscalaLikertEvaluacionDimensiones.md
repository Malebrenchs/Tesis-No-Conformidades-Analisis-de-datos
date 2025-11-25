# QIPO-019: Definir el Sistema de Evaluación Likert para las Dimensiones de la Variable Dependiente

La evaluación utiliza una escala Likert diseñada para medir objetivamente el grado de mejora entre el dataset original y el dataset transformado.  
Cada puntaje se asigna exclusivamente en base a **evidencias observables y verificables** en los archivos Excel.

## Q
¿Cómo se asigna objetivamente el puntaje de la escala Likert a cada ítem de las dimensiones de la variable dependiente?

## I
Variable dependiente: Gestión documental de las no conformidades  
Dimensiones definidas en QIPO-018  
Reglas de evaluación basadas en:
- porcentaje de filas afectadas  
- presencia o ausencia de problemas estructurales  
- claridad y trazabilidad de datos  
- facilidad de uso para análisis  

## P
Se establecen criterios cuantitativos y cualitativos específicos para asignar puntajes entre 1 y 5 a cada ítem.  
Los criterios están diseñados para minimizar la subjetividad y permitir que distintos evaluadores obtengan resultados equivalentes al analizar el mismo dataset.

## O
### ⭐ ESCALA LIKERT (criterio general)
- **1 = Muy pobre** → el criterio casi no se cumple; múltiples defectos críticos.  
- **2 = Deficiente** → el criterio se cumple parcialmente, pero con problemas frecuentes.  
- **3 = Aceptable** → el criterio se cumple en un grado moderado; aún hay deficiencias claras.  
- **4 = Bueno** → el criterio se cumple casi en totalidad, con detalles menores.  
- **5 = Excelente** → cumplimiento completo, sin inconsistencias.

---

# DIMENSIÓN 1 — Estructuración formal (IEID)

### Ítem 1 — *Formato tabular uniforme*
**Criterio objetivo:** medir cuántas filas presentan problemas estructurales (celdas combinadas, texto repetido, mezcla de conceptos, saltos irregulares).

| Puntaje | Evidencia observada en el archivo |
|--------|-----------------------------------|
| **1** | >70% de filas presentan problemas estructurales. |
| **2** | 40–70% de filas presentan problemas estructurales. |
| **3** | Al menos 50% del archivo es tabular, pero 20–40% sigue desorganizado. |
| **4** | 80–90% de filas son uniformes; 10–20% tienen errores menores. |
| **5** | 100% de las filas están estructuradas una por una; sin celdas combinadas ni mezclas. |

---

### Ítem 2 — *Ausencia de celdas combinadas*
**Criterio objetivo:** contar celdas combinadas en encabezados y cuerpo.

| Puntaje | Evidencia |
|--------|-----------|
| **1** | Celdas combinadas en encabezados y cuerpo; afectan la lectura. |
| **2** | Muchas combinadas en bloques completos. |
| **3** | Solo en encabezados, pero no en los datos. |
| **4** | 1–2 celdas combinadas irrelevantes. |
| **5** | Cero celdas combinadas en todo el documento. |

---

### Ítem 3 — *Unidad conceptual por fila*
**Criterio objetivo:** verificar si cada fila contiene un solo concepto (NC, evento, estado, etc.).

| Puntaje | Evidencia |
|--------|-----------|
| **1** | Fila contiene 3 o más conceptos mezclados. |
| **2** | 2 conceptos mezclados en más del 50% de filas. |
| **3** | Mezcla ocasional; 20–40% de filas afectadas. |
| **4** | 1–2 filas presentan mezcla menor. |
| **5** | Cada fila representa exactamente un concepto. |

---

### Ítem 4 — *Claridad de encabezados*
**Criterio objetivo:** evaluar si los encabezados son claros, únicos y coherentes.

| Puntaje | Evidencia |
|--------|-----------|
| **1** | Encabezados ausentes, ambiguos o repetidos. |
| **2** | Inconsistentes o poco claros. |
| **3** | Correctos pero con imprecisiones en 2–3 columnas. |
| **4** | Claros excepto por 1 detalle menor. |
| **5** | Total claridad y coherencia en todos los encabezados. |

---

# DIMENSIÓN 2 — Trazabilidad operativa del ciclo (ITC-NC)

### Ítem 1 — *Reconstrucción del ciclo completo de la NC*
**Criterio:** verificar si puede seguirse la secuencia (emisión → actividades → cierre).

| Puntaje | Evidencia |
|--------|-----------|
| **1** | No hay orden ni relación visible. |
| **2** | Solo se identifican eventos aislados. |
| **3** | Secuencia incompleta pero parcialmente inferible. |
| **4** | Secuencia casi completa; 1 dato faltante o confuso. |
| **5** | Secuencia completa, clara y lógica. |

---

### Ítem 2 — *Asociación evento–NC*
**Criterio:** verificar si cada evento pertenece inequívocamente a una NC.

| Puntaje | Evidencia |
|--------|-----------|
| **1** | Eventos mezclados; imposible asignación. |
| **2** | Asociación débil; requiere interpretación manual. |
| **3** | Mayoría clara; algunos casos ambiguos. |
| **4** | Asociación clara excepto 1–2 casos. |
| **5** | Identificación perfecta de cada evento. |

---

### Ítem 3 — *Claridad de fechas clave*
**Criterio:** evaluar integridad, formato y orden temporal.

| Puntaje | Evidencia |
|--------|-----------|
| **1** | Fechas incorrectas o ausentes. |
| **2** | Fechas inconsistentes o mezcladas. |
| **3** | Fechas claras en su mayoría; errores menores. |
| **4** | Formato uniforme con 1–2 detalles irrelevantes. |
| **5** | Todas correctas, consistentes y ordenadas. |

---

### Ítem 4 — *Separación entre descripción y eventos*
**Criterio:** medir mezcla de narrativa inicial con seguimientos.

| Puntaje | Evidencia |
|--------|-----------|
| **1** | Todo mezclado. |
| **2** | Mezclas frecuentes. |
| **3** | Separación parcial. |
| **4** | Separación casi perfecta. |
| **5** | Separación total y profesional. |

---

# DIMENSIÓN 3 — Capacidad analítica (ICAR)

### Ítem 1 — *Importación a Power BI / Python*
**Criterio:** medir facilidad de carga.

| Puntaje | Evidencia |
|--------|-----------|
| **1** | Imposible cargar sin rehacer el archivo. |
| **2** | Carga parcial; requiere limpieza pesada. |
| **3** | Carga correcta tras limpieza moderada. |
| **4** | Carga casi perfecta. |
| **5** | Carga inmediata sin modificaciones. |

---

### Ítem 2 — *Generación de indicadores*
**Criterio:** evaluar si pueden calcularse KPIs básicos sin transformaciones complejas.

| Puntaje | Evidencia |
|--------|-----------|
| **1** | Ningún KPI puede calcularse. |
| **2** | Solo algunos indicadores básicos con dificultad. |
| **3** | La mayoría tras una limpieza razonable. |
| **4** | KPIs fáciles de generar. |
| **5** | KPIs disponibles de inmediato. |

---

### Ítem 3 — *Facilidad para generar gráficos*
**Criterio:** capacidad del archivo para análisis visual.

| Puntaje | Evidencia |
|--------|-----------|
| **1** | Gráficos imposibles. |
| **2** | Requiere transformación extensa. |
| **3** | Gráficos posibles tras limpieza intermedia. |
| **4** | Gráficos fáciles. |
| **5** | Gráficos instantáneos. |

---

### Ítem 4 — *Tiempo necesario para preparación de datos*
**Criterio:** medir esfuerzo previo al análisis.

| Puntaje | Evidencia |
|--------|-----------|
| **1** | Horas de trabajo manual. |
| **2** | Más de 1 hora para limpieza básica. |
| **3** | Minutos de preparación. |
| **4** | 1–2 minutos. |
| **5** | Cero preparación. |

---

## E
none

## C
previous: QIPO-018
