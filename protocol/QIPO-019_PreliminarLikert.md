# QIPO-019: Propuesta Preliminar de Escalas Likert e Instrumentos de Medición

## Q
¿Qué tipo de escalas e instrumentos de medición deben emplearse para evaluar las dimensiones de la variable dependiente, asegurando validez metodológica, comparabilidad pre–post y cumplimiento de los requisitos para la aplicación de pruebas estadísticas como la t de Student?

## I
Dimensiones de la Variable Dependiente (VD):  
1. Estructura documental  
2. Consistencia del flujo documental  
3. Capacidad analítica  

Naturaleza del proyecto: transformación del archivo original mediante principios de Data Management.  
Necesidad metodológica: comparar el nivel de cumplimiento documental antes y después de la intervención (pre–post).  
Justificación: la evaluación no recae sobre el dataset como dato, sino sobre el **proceso documental**, por lo cual es válido usar instrumentos tipo checklist y escalas Likert.

## P
Se analiza la naturaleza de cada dimensión para determinar:  
- si requiere medición cualitativa ordinal (Likert) o cuantitativa,  
- número recomendado de ítems,  
- escala óptima para permitir sensibilidad estadística,  
- condiciones mínimas para aplicar t de Student en diseño pre–post,  
- coherencia con el enfoque de Data Management y con la estructura de transformación documental.

Se establece que dos dimensiones poseen naturaleza evaluativa perceptual (estructura y flujo), mientras que la tercera es inherentemente cuantitativa (capacidad analítica), por lo que se estructura un instrumento mixto con secciones diferenciadas.

## O
Se define un instrumento preliminar compuesto por dos secciones tipo Likert y una sección cuantitativa:

---

### **1. Dimensión 1: Estructura documental**  
**Tipo de medición:** Escala Likert 1–5  
**N° de ítems sugeridos:** 6–8  
**Orientación:** Evaluar claridad, normalización y capacidad estructural del archivo.

**Ejemplos de ítems (1 = totalmente insuficiente, 5 = totalmente adecuado):**
1. El archivo presenta una estructura clara y comprensible.  
2. Los encabezados están normalizados y permiten análisis tabular.  
3. La información está organizada sin celdas combinadas.  
4. Las filas presentan homogeneidad en sus atributos principales.  
5. Los campos mantienen coherencia entre sí.  
6. El formato facilita el filtrado, ordenamiento y agrupamiento.

---

### **2. Dimensión 2: Consistencia del flujo documental**  
**Tipo de medición:** Escala Likert 1–5  
**N° de ítems sugeridos:** 6–8  
**Orientación:** Evaluar la trazabilidad y coherencia del flujo de información.

**Ejemplos de ítems (1 = totalmente insuficiente, 5 = totalmente adecuado):**
1. El archivo permite seguir el flujo documental de cada NC.  
2. La trazabilidad entre eventos y su NC es clara.  
3. Las fechas de emisión, respuesta y cierre presentan coherencia.  
4. La estructura respeta principios básicos de integridad relacional.  
5. El registro permite identificar responsables sin ambigüedad.  
6. El conjunto de datos evita duplicidades en los eventos.

---

### **3. Dimensión 3: Capacidad analítica**  
**Tipo de medición:** Indicadores cuantitativos (no Likert)  
**Método:** Comparación pre–post intervención  
**Justificación:** La capacidad analítica es un producto directo de la estructura y normalización del archivo; por tanto, su medición debe basarse en variables numéricas, no percepciones.

**Indicadores recomendados (comparados pre vs post):**
- Número de KPIs posibles  
- Número de variables derivadas  
- Profundidad temporal recuperable  
- Proporción de consultas analíticas posibles  
- Cantidad de estadísticas disponibles en Power BI  
- Grado de detalle recuperable por NC  

Todos estos indicadores permiten la aplicación de pruebas estadísticas (incluyendo t de Student).

---

## E
---

## C
previous: QIPO-018
