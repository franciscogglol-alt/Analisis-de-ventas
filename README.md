# Análisis de ventas – Caso de negocio

Proyecto de análisis exploratorio de un dataset de ventas con pedidos realizados por clientes de distintos países y regiones a lo largo de varios años. El enfoque es mostrar el proceso y las habilidades de un analista de datos.

## Rol y objetivo

Como analista de datos, el objetivo es ayudar al área comercial a entender:
- Qué líneas de producto generan más ingresos.
- Qué países y territorios son más rentables.
- Cómo se comportan las ventas por año y por estado del pedido.


Con estos insights, el negocio puede tomar decisiones sobre qué productos impulsar, en qué mercados enfocarse y cómo priorizar clientes.

## Preguntas de negocio

Algunas preguntas que se responden en el análisis:

- ¿Cuáles son las 3 líneas de producto con mayores ventas totales?
- ¿Qué países aportan más ingresos al año?
- ¿Cómo cambia el volumen de ventas entre 2003, 2004 y 2005?


## Datos

- Archivo: data/Ventas_Analisis.csv.
- Cada fila representa una línea de pedido con:
  - Número de orden, fecha, estado del pedido.
  - Línea de producto (`PRODUCTLINE`) y código de producto.
  - Ventas (`SALES`), cantidad, precio unitario.


## Proceso de análisis

El notebook sigue un flujo típico de analista de datos:

1. **Carga y comprensión de los datos**: vista general de columnas, tipos y valores faltantes.
2. **Limpieza básica**: ajuste de tipos de datos de fecha, revisión de duplicados y nulos.
3. **Análisis exploratorio**: métricas de ventas por línea de producto, país, año y tamaño de trato.
4. **Visualización**: gráficos simples para comunicar hallazgos a negocio.
5. **Conclusiones**: resumen corto de oportunidades detectadas.

## Herramientas

- Python
- pandas
- Jupyter Notebook
- matplotlib / seaborn para gráficos

## Contenido del repositorio

- `data/Ventas_Analisis.csv`: dataset de ventas.
- `notebooks/sales_eda.ipynb`: análisis exploratorio con enfoque de negocio.
