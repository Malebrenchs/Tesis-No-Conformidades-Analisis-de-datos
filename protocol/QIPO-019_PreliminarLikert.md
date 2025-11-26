# QIPO-019: Propuesta Preliminar de Escalas Likert para las Dimensiones de la Variable Dependiente

## Q
¿Qué escalas tipo Likert permiten evaluar, de forma válida y basada en normas internacionales, las dimensiones de la Variable Dependiente “Deficiencias en la gestión documental de las no conformidades”, antes y después de la intervención de Data Management?

## I
- Dimensiones definidas en QIPO-018:
  1. Estructura documental  
  2. Consistencia del flujo documental  
  3. Capacidad analítica  
- Variable Independiente: **Data Management**
- Marcos normativos:
  - **ISO 8000**, **ISO 25012**, **ISO 11179**
  - **DAMA–DMBOK** (Data Quality, Data Modeling, DW/BI)
  - **Codd** (Formas Normales)
  - **CRISP–DM**
  - **PMBOK**
  - **ISO 22400**
  - Estándar SQL (integridad referencial)
- Diseño estadístico: pre-test y post-test, t de Student pareada, pruebas de normalidad (Shapiro).

## P
Se formulan escalas Likert para cada dimensión de la VD, garantizando:
- Alineación directa con marcos normativos internacionales.
- Evaluación ordinal reproducible en pre-test y post-test.
- Reducción de sesgo interpretativo mediante formulaciones basadas en criterios normativos.
- Integración metodológica con el análisis estadístico del estudio.

Se definen tres escalas:
1. **Escala Likert para la Dimensión 1: Estructura Documental (Calidad de Datos)**  
2. **Escala Likert para la Dimensión 2: Consistencia del Flujo Documental (Modelado y Normalización)**  
3. **Escala Likert (opcional) para la Dimensión 3: Capacidad Analítica (CRISP–DM, BI, PMBOK)**  

Cada ítem incluye su **criterio normativo**, **norma o estándar** y **referencia conceptual**.

## O

---

# 🔵 Escala Likert — Dimensión 1: *Estructura Documental*  
**Variable Independiente asociada:** Calidad de Datos (ISO 8000, ISO 25012, DAMA-DMBOK)  
**Evalúa:** organización, completitud, consistencia, validez, trazabilidad y unicidad del registro.

**Escala de respuesta:**  
1 = Totalmente en desacuerdo  
2 = En desacuerdo  
3 = Neutral  
4 = De acuerdo  
5 = Totalmente de acuerdo  

### Ítems con su respectivo criterio normativo

1. **El archivo presenta una estructura organizada y comprensible según los principios de calidad de datos.**  
   - *Norma:* ISO 25012 (Quality Model for Data)  
   - *Criterio:* Organización estructural  

2. **Los campos contienen información completa y sin omisiones relevantes.**  
   - *Norma:* ISO 8000-61 (Data Quality — Completeness)  
   - *Criterio:* Completitud  

3. **Los valores registrados mantienen consistencia interna entre sí.**  
   - *Norma:* ISO 25012 (Consistency Requirement)  
   - *Criterio:* Consistencia  

4. **La información del archivo es precisa y representa adecuadamente los hechos documentados.**  
   - *Norma:* ISO 8000-8 (Accuracy)  
   - *Criterio:* Precisión  

5. **Los datos muestran integridad, sin rupturas ni duplicidades en el registro.**  
   - *Norma:* ISO 25012 (Integrity)  
   - *Criterio:* Integridad  

6. **El archivo cumple principios básicos de normalización, evitando mezclar categorías o atributos impropios.**  
   - *Norma:* DAMA-DMBOK (Data Quality Dimensions – Structural Rules)  
   - *Criterio:* Normalización  

7. **La información es única, sin duplicidades injustificadas entre registros.**  
   - *Norma:* ISO 25012 (Uniqueness)  
   - *Criterio:* Unicidad  

8. **El archivo permite trazabilidad adecuada entre NC, eventos, fechas y responsables.**  
   - *Norma:* DAMA-DMBOK (Data Governance – Lineage & Traceability)  
   - *Criterio:* Trazabilidad  

---

# 🔵 Escala Likert — Dimensión 2: *Consistencia del Flujo Documental*  
**Variable Independiente asociada:** Modelado y Normalización (DAMA-DMBOK, Codd, ISO 11179)  
**Evalúa:** estructura relacional, entidades, atributos, formas normales, integridad referencial, cohesión semántica y dominio de datos.

**Escala de respuesta:** 1–5 igual a la dimensión anterior.

### Ítems con su criterio normativo

1. **Las entidades principales del proceso (NC y eventos) están correctamente identificadas.**  
   - *Norma:* ISO 11179 (Metadata Registry – Entity Definitions)  
   - *Criterio:* Identificación de entidades  

2. **Cada atributo pertenece claramente a su entidad correspondiente.**  
   - *Norma:* DAMA-DMBOK (Logical Modeling Rules)  
   - *Criterio:* Definición correcta de atributos  

3. **La estructura del archivo se ajusta a las formas normales básicas (1FN, 2FN, 3FN).**  
   - *Norma:* Codd (Forms of Normalization)  
   - *Criterio:* Normalización  

4. **El registro evita redundancias injustificadas entre filas o columnas.**  
   - *Norma:* Codd / DAMA (Non-Redundancy Principle)  
   - *Criterio:* Ausencia de redundancia  

5. **Las relaciones del proceso permiten integridad referencial adecuada.**  
   - *Norma:* SQL Standard (PK/FK Constraints) / DAMA  
   - *Criterio:* Integridad referencial  

6. **Los valores de cada campo se ajustan a dominios coherentes (fecha, texto, identificador, estado, etc.).**  
   - *Norma:* ISO 11179 (Value Domain)  
   - *Criterio:* Dominio de datos  

7. **La secuencia del flujo documental (emisión–respuesta–cierre) está representada de manera lógica y sin rupturas.**  
   - *Norma:* DAMA-DMBOK (Data Lifecycle / Lineage)  
   - *Criterio:* Integridad lógica del flujo  

8. **Los datos registrados mantienen cohesión semántica dentro de sus categorías.**  
   - *Norma:* ISO 11179 (Semantic Consistency)  
   - *Criterio:* Cohesión semántica  

---

# 🔵 Escala Likert (Opcional) — Dimensión 3: *Capacidad Analítica*  
**Variable Independiente asociada:** Analítica de Datos y BI (CRISP–DM, DAMA, PMBOK, ISO 22400)

Evalúa la capacidad del archivo para generar métricas, KPIs, análisis temporal, visualizaciones y trazabilidad analítica.

### Ítems con su referencia normativa

1. **El archivo permite calcular indicadores clave del proceso de no conformidades.**  
   - *Norma:* PMBOK (Project Monitoring & Control)  
   - *Criterio:* Indicadores clave (KPIs)  

2. **La información facilita análisis temporales (emisión, respuesta, cierre).**  
   - *Norma:* CRISP–DM (Data Understanding – Temporal Analysis)  
   - *Criterio:* Análisis temporal  

3. **El registro ofrece suficiente detalle para análisis por categoría, responsable o estado.**  
   - *Norma:* DAMA (DW/BI – Level of Detail)  
   - *Criterio:* Profundidad analítica  

4. **Los datos permiten generar visualizaciones significativas como histogramas, Pareto y series de tiempo.**  
   - *Norma:* CRISP–DM (Data Visualization Standards)  
   - *Criterio:* Capacidad de visualización  

5. **El nivel de granularidad es adecuado para análisis operativos.**  
   - *Norma:* DAMA-DMBOK (Granularity Principle)  
   - *Criterio:* Granularidad  

6. **Los indicadores derivados son verificables y auditables.**  
   - *Norma:* PMBOK (Quality Assurance & Auditability)  
   - *Criterio:* Trazabilidad de cálculos  

7. **El archivo permite consultas complejas sin pérdida de información.**  
   - *Norma:* SQL Standard / DAMA (Query Efficiency)  
   - *Criterio:* Eficiencia en consultas  

8. **La información generada es útil para apoyar la toma de decisiones operativas.**  
   - *Norma:* ISO 22400 (Operational KPI Usefulness)  
   - *Criterio:* Soporte a la decisión  

---

# 🟩 Indicadores Numéricos (Recomendados para la Dimensión 3)
Comparación pre vs post:

1. Número de KPIs posibles (ISO 22400)  
2. Número de variables derivadas (CRISP–DM Modeling)  
3. Número de visualizaciones posibles (CRISP–DM Visualization)  
4. KPIs temporales (duraciones, backlog, cierres)  
5. Profundidad de trazabilidad (DAMA Lineage)  
6. Consultas analíticas permitidas (SQL Standard)  
7. Filtros operativos útiles (DAMA – DW/BI)  
8. Estadísticas generables sin transformación adicional (CRISP–DM)  

---

## E
---

## C
previous: QIPO-018
previous: QIPO-020
