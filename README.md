# Desafío Alura Store – Análisis de Datos

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar el desempeño de las cuatro tiendas de la cadena **Alura Store**, con el fin de recomendar cuál de ellas debería vender el Sr. Juan para invertir en un nuevo emprendimiento.

El análisis fue desarrollado en **Google Colab utilizando Python**, aplicando conceptos fundamentales de análisis de datos como:

- Manipulación de datos con Pandas  
- Visualización de datos con Matplotlib  
- Uso de estructuras como listas y diccionarios  
- Aplicación de funciones y condicionales para análisis de métricas  

---

## Objetivo del Análisis

Evaluar el rendimiento de cada tienda considerando los siguientes indicadores clave:

- Ingresos totales  
- Categorías más y menos vendidas  
- Productos más y menos vendidos  
- Calificación promedio de clientes  
- Costo de envío promedio  

Con base en estos indicadores se genera una recomendación final justificada con datos y visualizaciones.

---

## Tecnologías Utilizadas

- Python 3  
- Google Colab  
- Pandas  
- Matplotlib  


## Análisis Realizados

1. Análisis de Facturación

    Se calculó el ingreso total de cada tienda sumando la columna de precios.

2. Análisis de Categorías

    Se identificaron las categorías con mayor y menor volumen de ventas mediante agrupación de datos.

3. Productos Más y Menos Vendidos

    Se utilizó value_counts() para determinar los productos con mayor y menor rotación en cada tienda.

4. Valoración Promedio

    Se calculó la media de las calificaciones para evaluar la satisfacción del cliente.

5. Costo de Envío Promedio

    Se analizó el costo promedio de envío por tienda para evaluar competitividad logística.

## Visualizaciones generales

El proyecto incluye al menos tres tipos diferentes de gráficos:

📊 Gráfico de barras – Facturación total por tienda

⭐ Gráfico de barras – Valoración promedio

🥧 Gráfico circular – Distribución de categorías

Estas visualizaciones permiten identificar patrones, comparar desempeño y respaldar la recomendación final.

## Como ejecutar el proyecto

### 1. Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/alura-store-analisis.git
```
### 2. Intalar Dependencias (si se ejecuta localmente)
```bash
pip install pandas matplotlib
```
### 3. Ejecutar el proyecto

Abrir el archivo AluraStore_Analisis.ipynb en:

- Google Colab (recomendado)

- Jupyter Notebook

- Visual Studio Code con extensión de Jupyter

Ejecutar las celdas en orden para reproducir el análisis completo.
