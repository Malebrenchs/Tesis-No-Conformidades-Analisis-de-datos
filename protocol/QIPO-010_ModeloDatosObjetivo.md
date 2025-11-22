# QIPO-010: Diseño del Modelo de Datos Objetivo

## Q
¿Qué estructura de datos es necesaria para transformar el registro de no conformidades en un formato adecuado para análisis, trazabilidad y generación de indicadores?

## I
Diagnóstico del registro actual de no conformidades (QIPO-009), identificando que el archivo contiene múltiples eventos por NC, celdas combinadas y ausencia de estructura relacional.

## P
Se diseña un modelo de datos objetivo que permita análisis eficiente, trazabilidad completa y normalización de la información sobre no conformidades.

### Tareas prácticas
- Definir un **modelo relacional básico** adecuado para análisis:
  - Tabla **NC (maestra)**: una fila por no conformidad.
  - Tabla **EVENTOS_NC (historial)**: una fila por comunicación o evento asociado.
- Establecer claves y relaciones:
  - `id_nc` como identificador único.
  - `id_evento` para cada comunicación.
  - Relación 1:N entre NC y EVENTOS_NC.
- Definir columnas necesarias:
  - Para NC: id_nc, fecha_emision, fecha_cierre, estado_final, atributos generales.
  - Para EVENTOS_NC: fecha_evento, remitente, tipo de comunicación, descripción, nro_carta.
- Documentar reglas básicas de integridad:
  - Cada evento debe asociarse a una sola NC.
  - Cada NC debe tener un estado final identificable.
  - Fechas deben ser consistentes (cierre ≥ emisión).

### Herramientas a utilizar
- Diagramación del modelo:
  - Mermaid / Draw.io / Lucidchart.
- Validación del modelo:
  - Python (pandas) para pruebas de estructura.
  - PowerQuery para previsualizar tablas resultantes.

### Marcos que justifican las acciones
- **Modelado de datos relacionales:** normalización y separación de entidades.
- **Ciencia de Datos / CRISP-DM:** preparación de datos como requisito para análisis.
- **ISO 9001:** estructuración coherente de información documentada.
- **PMI (PMBOK):** gestión del conocimiento y trazabilidad documental.

## O
Se obtiene un modelo de datos claro, coherente y preparado para soportar limpieza, transformación y análisis. Este modelo constituye la base estructural para procesar el registro actual de no conformidades.

## E
---
## C
previous: QIPO-008
previous: QIPO-009
