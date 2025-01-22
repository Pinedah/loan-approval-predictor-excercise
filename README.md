# Predictor de Aprobación de Tarjetas de Crédito

Este proyecto colaborativo consiste en desarrollar un modelo de Machine Learning capaz de predecir la aprobación de solicitudes de tarjetas de crédito. Utilizamos dos datasets complementarios y aplicamos diversas técnicas de análisis y procesamiento de datos.

## Objetivos del Proyecto
- **Predecir la aprobación de tarjetas de crédito:** Crear un modelo robusto capaz de identificar solicitudes aprobadas y rechazadas.
- **Manejo de datos desbalanceados:** Implementar estrategias para abordar el desbalance de clases en los datos.
- **Validación de datos:** Asegurar la calidad de los datos a través de análisis exploratorio, limpieza y validación.

## Pasos del Proyecto
1. **Carga y exploración de datos**
   - Utilización de dos datasets relacionados con solicitudes de tarjetas de crédito.
   - Análisis estadístico y visualización para comprender la distribución y las características de los datos.

2. **Limpieza de datos**
   - Manejo de valores nulos o faltantes.
   - Transformación y estandarización de las variables.

3. **Manejo del desbalance de clases**
   - Imputación de datos sintéticos mediante técnicas como **SMOTE** para equilibrar las clases.

4. **Análisis exploratorio de datos (EDA)**
   - Generación de gráficos y resúmenes estadísticos para detectar patrones y relaciones importantes.

5. **Modelado de Machine Learning**
   - Entrenamiento de algoritmos como:
     - **Random Forest**
     - **Gradient Boosting**
     - **Árboles de decisión**
   - Comparación de métricas de rendimiento entre los modelos.

6. **Visualización de resultados**
   - Gráficos que ilustran el rendimiento de los modelos y los resultados del análisis.

## Herramientas Utilizadas
- **Librerías de Python:**
  - `pandas` para la manipulación de datos.
  - `numpy` para cálculos numéricos.
  - `matplotlib` y `seaborn` para visualización.
  - `scikit-learn` para el modelado de Machine Learning.
- **Técnicas de validación:** Validación cruzada y división del dataset en conjuntos de entrenamiento y prueba.

## Resultados
- El modelo más eficiente fue Random Forest con una precisión de 0.76.
- La imputación de datos sintéticos ayudó significativamente a mejorar la capacidad predictiva de los modelos.
- Las gráficas generadas ilustran los patrones encontrados y el desempeño del modelo final.

## Cómo Reproducir el Proyecto
1. Clona este repositorio:  
   ```bash
   git clone https://github.com/Pinedah/loan-approval-predictor-excercise.git

## Instala las dependencias
1. pip install -r requirements.txt

## Contacto
Si tienes preguntas o sugerencias sobre este proyecto, no dudes en contactar a github.com/Pinedah o github.com/Rod0225 a través de @pinedah_11 en Ig.

### Aclaración
© 2025 Pinedah. Este proyecto es de código abierto, y fue realizado como proyecto para la asignatura de Desarrollo de Aplicaciones para Análisis de Datos en la Escuela Superior de Cómputo del IPN.