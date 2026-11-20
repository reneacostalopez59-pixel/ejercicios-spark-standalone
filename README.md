# Ejercicios Prácticos — Apache Spark Standalone

- **Alumno:** René Nicolas Acosta López
- **Matrícula:** 125052937
- **Entorno:** BDA Lab (Docker: Hadoop + HDFS + Spark + Jupyter Notebook)

## Índice de ejercicios

Cada ejercicio es un Jupyter Notebook autocontenido y reproducible de forma independiente:

| # | Ejercicio | Archivo |
| :-: | :--- | :--- |
| 1 | Configurar `SparkSession` personalizada (`1g` executor, `8` shuffle partitions) | [`01_configurar_sparksession.ipynb`](./01_configurar_sparksession.ipynb) |
| 2 | Operaciones básicas con RDDs (`count`, `take`, `sum`, `max`, `min`) | [`02_operaciones_basicas_rdd.ipynb`](./02_operaciones_basicas_rdd.ipynb) |
| 3 | Transformaciones `map` y `filter` | [`03_transformaciones_map_filter.ipynb`](./03_transformaciones_map_filter.ipynb) |
| 4 | Pares clave-valor y agregaciones con `reduceByKey` | [`04_pares_clave_valor.ipynb`](./04_pares_clave_valor.ipynb) |
| 5 | Lectura y procesamiento de archivo CSV (`persons.csv`) | [`05_lectura_csv.ipynb`](./05_lectura_csv.ipynb) |
| 6 | Optimización: evitar múltiples llamadas a `split()` | [`06_optimizacion_split.ipynb`](./06_optimizacion_split.ipynb) |
| 7 | Debugging: identificación y corrección de 4 errores comunes en PySpark | [`07_debugging_errores.ipynb`](./07_debugging_errores.ipynb) |

## Reproducción

1. Levantar el entorno de Spark con Jupyter Notebook (BDA Lab).
2. Abrir cualquiera de los 7 notebooks y ejecutar todas sus celdas secuencialmente (`Shift + Enter`). El dataset `DATOS/persons.csv` utilizado en los ejercicios 5, 6 y 7 ya está incluido en el repositorio.
