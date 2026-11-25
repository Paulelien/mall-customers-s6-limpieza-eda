# Mall Customers: calidad, limpieza y EDA (GDT2202, Semana 6)

Proyecto individual de ciencia de datos sobre un conjunto de 200 clientes de un centro comercial: diagnóstico de calidad, limpieza y transformación documentadas, y análisis exploratorio.

**Autor:** Ricardo Delannoy · Duoc UC, Ingeniería en Ciencia de Datos

## Estructura del repositorio

| Carpeta | Contenido |
| --- | --- |
| `Data/Raw` | Dataset original (`Mall Customers.xlsx`), sin modificaciones |
| `Data/Processed` | Dataset limpio (`mall_customers_limpio.csv`) |
| `Notebooks` | Notebook de calidad, limpieza y EDA |
| `Docs` | Diccionario de datos, registro de validaciones y bitácora de cambios |
| `Figuras` | Visualizaciones generadas en el EDA |

## Resumen del proceso

1. **Comprensión de los datos:** 200 registros y 7 variables; `CustomerID` verificado como único y excluido del conjunto procesado por privacidad.
2. **Limpieza:** corrección de nombres de columnas, conversión a tipos categóricos, `Unknown` conservado como categoría propia (26 en Education, 15 en Marital Status), 2 atípicos de ingreso conservados con justificación.
3. **EDA:** 3 hallazgos y 2 visualizaciones (ingreso vs gasto, edad vs gasto).

## Reproducibilidad

Ejecutar el notebook en `Notebooks/` sobre el archivo de `Data/Raw`. Los cambios y sus motivos están en `Docs/bitacora_cambios.md`.
