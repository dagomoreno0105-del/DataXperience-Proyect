# Proyecto DataXperience: Factores Determinantes del Éxito Cinematográfico (2010-2024)
**Grupo 4** 
Integrantes: David Santiago Moreno, Angie Sanabria, Catalina Romero, Juan Diego Niño.

## Descripción del Proyecto
En este proyecto aplicamos el ciclo completo de Ciencia de Datos para resolver un problema de la industria cinematográfica: **¿Qué factores comerciales y creativos (género, ingresos, volumen de votos) garantizan que una película supere una calificación de 7.5?**
A través de la limpieza de datos, análisis exploratorio y algoritmos de Machine Learning, demostramos que la interacción masiva de la audiencia supera al presupuesto como indicador de éxito.

## Estructura del Repositorio
Este repositorio contiene todos los entregables requeridos para la evaluación:
*   **INFORME_PROYECTO - Colab.pdf**: Documento detallado con el planteamiento, EDA, análisis estadístico y conclusiones.
*   **Organic_design_system_deck (1).pptx**: Diapositivas de apoyo para la exposición ejecutiva.
*   **Proyecto_Final_DataXperience_Grupal_4.ipynb**: Cuaderno de código con el pipeline completo (Limpieza, EDA y Machine Learning).
*   **enhanced_box_office_data(2000-2024)u.csv**: Base de datos cruda original.
*   **Peliculas_Limpias_Grupo4.csv**: Base de datos limpia generada por nuestro código, lista para análisis.

## Instrucciones para ejecutar el código
1. Descarga el cuaderno `Proyecto_Final_DataXperience_Grupal_4.ipynb` y el dataset original `enhanced_box_office_data(2000-2024)u.csv`.
2. Abre el cuaderno utilizando Google Colab o un entorno local como Jupyter Notebook.
3. Asegúrate de tener instaladas las dependencias ejecutando: `pip install pandas numpy matplotlib seaborn scikit-learn`.
4. Sube el dataset a tu entorno de ejecución.
5. Ejecuta las celdas de manera secuencial (Run All). El cuaderno generará automáticamente un archivo CSV con los datos limpios y desplegará todas las gráficas y métricas de evaluación.

## Conclusiones Principales
*   **Volumen de interacción sobre recaudación:** Nuestro modelo de Random Forest probó que el interés del público (Vote_Count) es un predictor inmensamente superior a los ingresos en taquilla.
*   **Segmentación por género:** Documentales y musicales tienen tasas inherentes de aclamación muy superiores a géneros comerciales de alto presupuesto como la Acción o la Comedia.
