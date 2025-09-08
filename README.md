# P1.-Regresion

Este proyecto analiza datos de la Cuenta Satèlite del turismo de Mèxico (INEGI), que reporta el PIB turìstico total y sus componentes en millones de pesos (1993-2023).
El objetivo es modelar y predecir el PIB turìstico total usando regresiòn lineal y polinòmica, aplicando soluciones a los problemas tìpicos. https://www.inegi.org.mx/app/descarga/ficha.html?tit=1627954&ag=0&f=csv 

Objetivos: 

1. Importar y describir el dataset en formato tidy.

2. Aplicar soluciones C1.5:

Huecos → interpolación y mediana.

Outliers → capado IQR.

Cualitativas → jerarquía de categorías.

Colinealidad → uso de shares y eliminación de dependencias.

Interacciones → en modelo polinómico.

3. Seleccionar variables con eliminación hacia atrás.

4. Comparar modelos lineal (OLS) y polinómico (G2).

5. Evaluar métricas (RMSE, R²) en train/test.

6. Realizar inferencia (IC/IP) y caso hipotético.


Metodologìa:

Preprocesamiento: limpieza de huecos, capado de outliers, construcción de shares.

Exploración visual: serie temporal (choque 2020), boxplots de componentes, heatmap de correlaciones.

Modelado: OLS como baseline; polinómico G2 con cuadráticos e interacciones.

Evaluación: comparación en test para medir generalización.


El proyecto va de 3 documentos:

[reporte html](P1_652911.html)

[reporte ipynb](P1_652911.ipynb)

[reporte pib_turismo.csv](pib_turismo.csv)
