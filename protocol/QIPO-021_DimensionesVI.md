# QIPO-021: Definición de Dimensiones de la Variable Independiente (Data Management)

## Q
¿Cuáles son las dimensiones que estructuran la Variable Independiente “Data Management”, de acuerdo con los marcos normativos internacionales aplicables a calidad de datos, modelado de datos y analítica de datos, y cómo se relacionan con las dimensiones de la Variable Dependiente?

## I
Variable Independiente (VI): **Data Management**  
Marcos normativos y técnicos:
- **ISO 8000**, **ISO 25012** — Estándares internacionales de calidad de datos  
- **DAMA-DMBOK** — Data Quality, Data Modeling & Design, DW/BI  
- **Codd** — Teoría de Normalización (1FN–3FN)  
- **ISO/IEC 11179** — Metadatos y estructura semántica  
- **ISO 9001** — Información documentada  
- **CRISP–DM** — Proceso estándar de minería de datos  
- **PMBOK** — Control de calidad y comunicaciones  
- **ISO 22400** — Estructura de KPIs industriales  

Las dimensiones deben corresponderse con:  
- VD1: Estructura documental  
- VD2: Consistencia del flujo documental  
- VD3: Capacidad analítica  

## P
Se analizan las preguntas conceptuales subyacentes a cada dimensión de la Variable Dependiente para identificar su marco normativo equivalente dentro del Data Management.  
Se seleccionan las áreas del DAMA-DMBOK, ISO y CRISP–DM que gobiernan las actividades necesarias para corregir, transformar y optimizar el dataset.  
Se establecen las tres dimensiones oficiales de la VI, garantizando su coherencia conceptual, operativa y normativa para el posterior análisis estadístico pre–post.

## O
Se definen las **tres dimensiones oficiales de la Variable Independiente (Data Management)**:

---

# 🔵 Dimensión 1 (VI): **Calidad de Datos**  
**Marcos:** ISO 8000, ISO 25012, DAMA-DMBOK (Data Quality Management)

### Justificación
Esta dimensión define qué constituye un **dato correcto**, **válido**, **organizado**, **completo**, **preciso**, **trazable** y **sin duplicidades**.  
Responde directamente a las deficiencias estructurales de la VD1 (“Estructura documental”).

### Incluye los criterios normativos:
- Organización — *ISO 25012*  
- Completitud — *ISO 8000-61*  
- Consistencia — *ISO 25012*  
- Precisión — *ISO 8000-8*  
- Integridad — *ISO 25012*  
- Normalización estructural — *DAMA-DMBOK – Data Quality Rules*  
- Unicidad — *ISO 25012*  
- Validez — *ISO 8000*  
- Trazabilidad — *DAMA-DMBOK – Lineage*  

### Resultado conceptual
Esta dimensión rige la **corrección del archivo inicial**: limpiar, normalizar, estructurar y garantizar calidad.

---

# 🔵 Dimensión 2 (VI): **Modelado y Normalización de Datos**  
**Marcos:** DAMA-DMBOK (Data Modeling & Design), Codd (1FN–3FN), ISO/IEC 11179, ISO 9001

### Justificación
Define los criterios que guían la transformación del archivo original en dos tablas relacionales (NC y EVENTOS), garantizando diseño lógico, integridad y estructura formal.  
Responde directamente a la VD2 (“Consistencia del flujo documental”).

### Incluye los criterios normativos:
- Identificación correcta de entidades — *ISO 11179*  
- Definición adecuada de atributos — *DAMA-DMBOK – Logical Design*  
- Normalización (1FN, 2FN, 3FN) — *Codd*  
- Ausencia de redundancia — *DAMA / Codd*  
- Integridad referencial — *SQL Standard / DAMA*  
- Dominio y tipología de datos — *ISO 11179 – Value Domain*  
- Cardinalidad correcta — *DAMA – Entity Relationship Rules*  
- Cohesión semántica — *ISO 11179 – Semantic Consistency*  
- Integridad lógica del flujo documental — *DAMA – Data Lifecycle Lineage*  

### Resultado conceptual
Esta dimensión rige la **reconstrucción estructural** del dataset: crear las tablas relacionales y garantizar su integridad.

---

# 🔵 Dimensión 3 (VI): **Analítica de Datos y Business Intelligence**  
**Marcos:** CRISP–DM, DAMA-DMBOK (DW/BI), PMBOK, ISO 22400

### Justificación
Define qué análisis, visualizaciones, KPIs y métricas son válidos para evaluar el proceso de no conformidades.  
Corresponde directamente a la VD3 (“Capacidad analítica”).

### Incluye los criterios normativos:
- Generación de KPIs relevantes — *PMBOK*  
- Capacidad de análisis temporal — *CRISP–DM (Data Understanding)*  
- Profundidad analítica — *DAMA – DW/BI*  
- Reducción de ambigüedad — *ISO 22400 – KPI definitions*  
- Visualizaciones normadas (histograma, Pareto, boxplot, series) — *CRISP–DM*  
- Granularidad adecuada — *DAMA – Data Warehousing*  
- Trazabilidad de cálculos — *PMBOK – Quality Assurance*  
- Eficiencia en consultas — *SQL Standard*  
- Utilidad para toma de decisiones — *ISO 22400 – KPI purpose*  

### Resultado conceptual
Esta dimensión rige la **capacidad final del dataset** para análisis, visualización, trazabilidad de métricas y toma de decisiones.

---

## E
---

## C
previous: QIPO-020
