# Bitácora de cambios: Mall Customers (S6)

| Fecha | Cambio | Motivo | Evidencia |
| --- | --- | --- | --- |
| 2026-11-24 | Carga del dataset original (200 registros, 7 columnas) | Punto de partida; el archivo raw no se modifica | Notebook, sección 1.1 |
| 2026-11-24 | Verificación de unicidad de CustomerID y exclusión del conjunto procesado | Privacidad: reducir riesgo de reidentificación | Notebook, sección 1.4 |
| 2026-11-24 | Corrección del nombre de columna `Education ` (espacio final) | Evitar errores de referencia | Tabla antes y después |
| 2026-11-24 | Conservación de `Unknown` como categoría propia (26 en Education, 15 en Marital Status) | Imputar introduciría información no observada; eliminar perdería hasta 19,5 % de los registros | Notebook, sección 2.2 |
| 2026-11-24 | Conservación de 2 atípicos de ingreso (137 miles de USD) | Valores plausibles, sin evidencia de error, apenas sobre el límite IQR (132,75) | Notebook, sección 2.1 |
| 2026-11-24 | Conversión de variables de texto a categóricas | Validación de valores y menor uso de memoria | Tabla antes y después |
| 2026-11-25 | Generación de dos visualizaciones y tres hallazgos del EDA | Responder el criterio de análisis exploratorio | Notebook, sección 3 |
| 2026-11-25 | Organización del repositorio y subida de archivos en commits separados | Trazabilidad | Historial de commits |
