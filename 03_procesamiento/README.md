# 03_procesamiento

Módulo de procesamiento de los datos de expresión génica (RNA-Seq).

## Contenido

- `normalizacion.py`: normaliza los conteos de expresión para que las muestras sean comparables.
- `filtrado_genes.py`: elimina los genes con expresión muy baja o nula.

## Entrada y salida

- Entrada: datos de `01_datos/` ya revisados en `02_control_calidad/`.
- Salida: datos normalizados y filtrados para el análisis de `04_analisis/`.
