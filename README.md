# Dashboard de Utilidad y Márgenes – Power BI

Este proyecto presenta un dashboard profesional desarrollado en Power BI, donde se analizan métricas clave de utilidad, márgenes, ingresos y desempeño por continente, país y categoría de producto.
Incluye modelado de datos, medidas DAX, segmentadores avanzados y visualizaciones interactivas.

# Vista general del Dashboard

Incluye:

- KPIs principales (Ingresos, Gastos, Utilidad, Margen)

- Gráfico de anillo por continente

- Utilidad y margen por año

- Mapa interactivo por país y continente

- Series temporales por trimestre

# Modelo de Datos

El modelo está compuesto por:

- Tabla de Datos: Año, Continente, País, Trimestre, Ingresos, Gastos

- Tabla de Productos: Categoría y Tipo de Producto

- Tabla de Medidas: Métricas calculadas en DAX

- Relación 1→* entre Productos y Datos

# Principales métricas DAX

Algunas de las medidas incluidas:
```python
Margen = DIVIDE([Utilidad], [Ingresos])
Utilidad = [Ingresos] - [Gastos]
```
# Habilidades demostradas

- Modelado de datos relacional

- Limpieza y transformación con Power Query

- Creación de medidas avanzadas en DAX

- Construcción de KPIs

- Visualizaciones profesionales

- Diseño responsable y storytelling con datos

# 📁 Estructura del repositorio
```python
PowerBI-Dashboards-Portfolio/
│── README.md
│── dashboards/
│     └── appol.pbix
│── images/
│     ├── dashboard_general.png
│     └── modelo_datos.png
```
