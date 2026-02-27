# Instacart — Análisis Exploratorio de Datos (EDA)

## Descripción
Este proyecto analiza el comportamiento de compra de los clientes en la plataforma Instacart utilizando datos transaccionales.  
El objetivo es identificar patrones relacionados con la frecuencia de pedidos, popularidad de productos y comportamiento de reorden.

## Objetivos
- Analizar cuántos productos suelen incluir los usuarios en sus pedidos  
- Identificar los productos con mayor frecuencia de reorden  
- Analizar la proporción de reorden por producto y por usuario  
- Encontrar los productos que con mayor frecuencia se agregan primero al carrito  

## Dataset
El dataset fue proporcionado por TripleTen como parte de un proyecto de análisis de datos.  
Debido a su tamaño, los archivos de datos no se incluyen en este repositorio.

## Estructura del Proyecto
instacart_project/  
├── notebooks/  
│   └── instacart_project.ipynb  
├── data/   (solo local, ignorado por git)  
├── README.md  
├── requirements.txt  
└── .gitignore  

## Herramientas y Librerías
- Python  
- pandas  
- numpy  
- matplotlib   

## Cómo Ejecutar el Proyecto

1. Clonar el repositorio  
2. Instalar dependencias:

pip install -r requirements.txt  

3. Iniciar Jupyter Notebook o VS Code:


4. Abrir el archivo:

notebooks/instacart_project.ipynb  

## Principales Hallazgos
- La mayoría de los pedidos contienen entre 3 y 10 productos, lo que indica cestas de compra de tamaño pequeño a mediano.

- La actividad de pedidos alcanza su punto máximo los fines de semana y entre las 10:00 y las 16:00 horas, lo que sugiere un comportamiento de compra planificado durante los periodos de alta disponibilidad.

- Se observan picos significativos en los días entre pedidos a los 7 y 30 días, lo que indica ciclos de compra semanales y mensuales.

- Los plátanos son el primer artículo que se añade con más frecuencia al carrito y aparecen constantemente entre los productos más comprados y con mayor número de pedidos repetidos, lo que refuerza su papel como producto básico.

- Las tasas de reordenamiento son altas tanto a nivel de producto como de usuario, lo que indica rutinas de compra consistentes y un comportamiento de compra habitual.

Autor: Valeria — Analista de Datos Jr.