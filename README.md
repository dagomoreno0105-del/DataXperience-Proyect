# 🎬 Proyecto DataXperience: Factores Determinantes del Éxito Cinematográfico (2010-2024)
**Grupo 4** 
Integrantes: Catalina Romero, Angie Sanabria, David Santiago Moreno, Juan Diego Niño.

## 📌 Descripción del Proyecto
En este proyecto aplicamos el ciclo completo de Ciencia de Datos para resolver un problema de la industria cinematográfica: **¿Qué factores comerciales y creativos (género, ingresos, volumen de votos) garantizan que una película supere una calificación de 7.5?**
A través de la limpieza de datos, análisis exploratorio y algoritmos de Machine Learning, demostramos que la interacción masiva de la audiencia supera al presupuesto como indicador de éxito.

## 📂 Estructura del Repositorio
Este repositorio contiene todos los entregables requeridos para la evaluación:
*   [📄 Informe Final del Proyecto](LINK_AQUI_AL_PDF_DEL_INFORME): Documento detallado con el planteamiento, EDA, análisis estadístico y conclusiones.
*   [📊 Presentación de Sustentación](LINK_AQUI_A_LA_PRESENTACION): Diapositivas de apoyo para la exposición ejecutiva.
*   [💻 Cuaderno de Colab (Código Completo)](LINK_AQUI_AL_IPYNB): Archivo `.ipynb` con el pipeline completo (Limpieza, EDA y Machine Learning con validación cruzada).

## ⚙️ Instrucciones para ejecutar el código
1. Descarga el cuaderno `Proyecto_Final_DataXperience_Completo_v3.ipynb` y el dataset original.
2. Abre el cuaderno utilizando Google Colab o un entorno local como Jupyter Notebook/VS Code.
3. Asegúrate de tener instaladas las dependencias ejecutando: `pip install pandas numpy matplotlib seaborn scikit-learn`.
4. Sube el dataset a tu entorno de ejecución.
5. Ejecuta las celdas de manera secuencial (Run All). El cuaderno generará automáticamente un archivo CSV con los datos limpios y desplegará todas las gráficas y métricas de evaluación.

## 🚀 Conclusiones Principales
*   **Volumen de interacción sobre recaudación:** Nuestro modelo de Random Forest y la matriz de correlación probaron que el interés del público (Vote_Count) es un predictor inmensamente superior a los ingresos en taquilla ($Worldwide).
*   **Segmentación por género:** El género cinematográfico es un diferenciador base crítico. Documentales y musicales tienen tasas inherentes de aclamación del doble o triple que géneros comerciales de alto presupuesto como la Acción o la Comedia.
