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
- La mayoría de los pedidos contienen un número reducido de productos  
- Existen productos básicos con tasas de reorden muy altas  
- El comportamiento de reorden varía significativamente entre usuarios  
- Un conjunto reducido de productos aparece frecuentemente como el primer artículo agregado al carrito  

Autor: Valeria — Analista de Datos Jr.