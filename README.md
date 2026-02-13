# Alura Store — Análisis de Ventas (Challenge Alura Latam)

## Propósito
Este proyecto analiza el desempeño de 4 tiendas de Alura Store para recomendar cuál debería vender el Sr. Juan, utilizando métricas de ingresos, categorías más vendidas, calificación promedio de clientes, productos más/menos vendidos y costo promedio de envío.

## Estructura del proyecto
- `AluraStoreLatam.ipynb`: Notebook principal con el análisis, visualizaciones e informe final.
- `README.md`: Documentación del proyecto.

## Análisis realizados
1. **Ingreso total por tienda** (suma de `Precio`).
2. **Ventas por categoría** (conteo por `Categoría del Producto`).
3. **Calificación promedio** (promedio de `Calificación`).
4. **Productos más y menos vendidos** (conteo por `Producto`).
5. **Costo de envío promedio** (promedio de `Costo de envío`).

## Visualizaciones
Se generaron al menos 3 gráficos de diferentes tipos para apoyar la interpretación:
- Barras: ingresos por tienda.
- Barras: calificación promedio por tienda.
- Dispersión: relación entre envío promedio y calificación promedio.

## Cómo ejecutar el notebook
### Opción 1 — Google Colab
1. Abrir `AluraStoreLatam.ipynb` en Google Colab.
2. Ejecutar las celdas en orden (sin modificar el bloque de importación).
3. Revisar resultados, gráficos e informe final.

### Opción 2 — Local (opcional)
Requisitos: Python + Jupyter + pandas + matplotlib.
1. Clonar el repositorio.
2. Abrir el notebook con Jupyter.
3. Ejecutar las celdas.

## Resultado final
La recomendación final se encuentra en el notebook en la sección **Informe Final**, donde se concluye que la tienda sugerida para vender es la **Tienda 4**, principalmente por presentar la menor facturación total.
