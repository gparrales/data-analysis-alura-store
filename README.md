# Análisis de Datos de Ventas de un Retail con 4 tiendas.

Proyecto de análisis de datos desarrollado con Python y Pandas, enfocado en comparar el desempeño de diferentes tiendas con el objetivo de identificar patrones de consumo, productos más vendidos, diferencias de desempeño entre sucursales y oportunidades de mejora en la toma de decisiones comerciales.

---

### Problema de negocio

Una empresa con múltiples tiendas necesita comprender:

- Qué sucursal tiene mejor desempeño en ventas
- Qué productos o categorías impulsan los ingresos
- Si existen patrones en precios, calificaciones o popularidad que influyan en el comportamiento del cliente

---

### Objetivos:

- Analizar el comportamiento de ventas
- Identificar productos con mayor demanda
- Explorar patrones de consumo
- Obtener información útil para la toma de decisiones comerciales

---

### Proceso de análisis:

1. Limpieza de datos:

- Revisión de valores nulos y tipos de datos
- Estandarización de variables categóricas

2. Análisis exploratorio (EDA):

- Comparación de ventas entre tiendas
- Distribución de precios y calificaciones
- Identificación de productos más vendidos

3. Visualización:

- Gráficos comparativos entre sucursales
- Distribuciones de precios y ratings
- Ranking de productos por ingresos

--- 

### Datasets:
Existen 4 datasets, que sumados presenta 9435 registros distribuidos en 12 variables, contienen información de ventas, incluyendo fecha, producto, categoría, vendedor, ubicación geográfica, meódo de pago, precio y cantidad.

---

### Informe:
Contiene insight's relevantes en función de los objetivos, responde preguntas como: ¿cuál es la tienda con más ventas?, ¿cuáles son los artículos más
vendidos en cada tienda?, ¿cuál es la valoración promedio de cada tienda?, ¿existe alguna relación entre los precios de los productos y las calificaciones
que los clientes asignan a dichos productos?, top de productos más vendidos. También se dan recomendaciones para afrontar los puntos débiles encontrados.

---

### Conclusiones clave:

- Ciertas categorías de productos concentran la mayor parte de las ventas.
- El precio del producto no está relacionado con la valoración atribuida por el consumidor, es decir, no significa que a mayor precio el cliente considera que es de mejor calidad o         vicecersa.
- No hay diferencia significativa en el total de ventas entre las diferentes sucursales.

---

### Estructura:

- data/: CSVs de las tiendas
- notebooks/: Jupyter Notebook (Colab)
- src/: scripts reutilizables
- docs/: informe en formato pdf

Tecnologías: Python, Pandas, Matplotlib.
