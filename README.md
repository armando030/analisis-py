# Análisis de Tiendas – Alura Store Latam

Proyecto de análisis de datos desarrollado en Python para evaluar el desempeño de cuatro tiendas y recomendar cuál debería vender el Sr. Juan, basándose en métricas de negocio y visualización de datos.

## Objetivo del proyecto

El propósito de este análisis es comparar el rendimiento de las tiendas de Alura Store Latam mediante técnicas de análisis exploratorio de datos (EDA) y visualización, con el fin de tomar una decisión estratégica:

**Determinar qué tienda debería vender el Sr. Juan.**

### Indicadores claves analizados:

* Ingresos totales por tienda

* Categorías de productos más y menos vendidas

* Calificaciones promedio de clientes

* Productos más y menos vendidos

* Coste de envío promedio

## Tecnologías utilizadas

* Python
  * Pandas → Manipulación y análisis de datos
  * Matplotlib → Visualización de datos
* Google Colab / Jupyter Notebook

## Estructura del proyecto

📦 analisis-py

 ┣ 📜 AluraStoreLatam.ipynb

 ┗ 📄 README.md

El notebook contiene todo el flujo del análisis:

1. Importación de datos
2. Limpieza y preparación
3. Análisis exploratorio
4. Visualización de resultados
5. Conclusiones y recomendación final

## Análisis realizado
### 1. Ingresos totales por tienda

Se compararon los ingresos generados por cada tienda para identificar cuál aporta mayor rentabilidad al negocio.

**Hallazgo:**

* La Tienda 4 registra los ingresos más bajos.

### 2. Categorías de productos vendidos

Se analizaron las categorías de productos para entender el comportamiento de compra de los clientes.

**Hallazgo:**

* La Tienda 2 presenta menor volumen de ventas en las categorías principales.

### 3. Calificación promedio de clientes

La satisfacción del cliente se evaluó a partir de las valoraciones de los compradores.

**Hallazgos:**

* Las Tiendas 1 y 4 no superan los 4 puntos de calificación.

### 4. Productos más y menos vendidos

Se identificaron productos con mayor rotación y productos con baja demanda.

**Hallazgos:**

* Cada tienda tiene diferencias en los productos mas vendidos

### 5. Coste de envío promedio

El costo de envío influye directamente en la decisión de compra del cliente.

**Hallazgo:**

* La Tienda 4 presenta el menor coste de envio

## Conclusión del análisis

Después de evaluar todos los indicadores, se concluye que:

**La tienda que el Sr. Juan debería vender es la Tienda 4**

### Justificación

La Tienda 4 presenta el peor desempeño global:

* Menores ingresos
* Peor calificación de clientes

A pesar de destacar en la cantidad vendida de productos, no se refleja en las ventas obtenidas. Por lo tanto, mantener esta tienda implicaría continuar invirtiendo recursos en una unidad con bajo rendimiento.

## Autor

Proyecto desarrollado como parte del programa de ONE | TECH FOUNDATION - Especialización Data Science de Alura Latam.
