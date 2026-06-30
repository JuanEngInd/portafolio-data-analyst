# Análisis exploratorio de datos — Retail Sales

Análisis exploratorio completo de un dataset de ventas retail con 9,800 transacciones, usando Python, Pandas y visualización de datos.

## Objetivo

Identificar patrones de ventas por categoría, región, segmento de cliente y temporalidad para generar recomendaciones de negocio accionables.

## Herramientas utilizadas

- Python (Pandas, NumPy)
- Matplotlib y Seaborn
- Jupyter Notebook (Google Colab)

## Hallazgos principales

- **Technology** es la categoría más rentable con $827,455 en ventas totales
- La distribución de ventas está fuertemente sesgada — la media ($230) es 4 veces mayor que la mediana ($54)
- **West** y **East** concentran el 54% de las ventas totales; **South** es la región más débil
- La combinación **Technology + East** representa el mayor volumen de ventas combinado ($263,116)
- Existe estacionalidad clara — noviembre y diciembre son los meses pico, febrero es el más débil
- El 1.25% de las transacciones (outliers) concentra el 22.3% de los ingresos totales

## Dataset

Dataset público de Kaggle: [Sales Forecasting](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting)

## Archivo principal

[`EDA_retail_sales.ipynb`](./EDA_retail_sales.ipynb) — notebook completo con limpieza de datos, análisis univariado, bivariado y conclusiones.